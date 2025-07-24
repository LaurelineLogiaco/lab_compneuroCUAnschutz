---
title: Project1
---

# {% include icon.html icon="fa-solid fa-microscope" %} Building structured neural network models of the motor regions of the mammalian brain


While largely interconnected and integrated, the mammalian brain is composed of distinct anatomical regions that have different development programs and different architectures. Notably, the neurons - the cells that compose each brain region - are organized according to different connectivity patterns in these different brain regions. If one of these areas is damaged - for instance because of trauma or stroke - this leads to [specific deficits](https://www.youtube.com/shorts/yri-cHlQYIg).

{% include section.html size="full" %}

{% include figure.html image="images/general_multiRegionNN_brain_schematic.png" width="40%" %}

{% include section.html %}

For instance, if the cerebellum - the bottom green region in the highly schematized diagram above - is impaired, leads to specific motor deficits, [such as unstable and uncoordinated movements, and issues with maintaining stable posture and balance](https://youtu.be/1SIpRuUipxc?si=SQM50doF95Lg2q_9&t=4).

In contrast, if the primary motor cortex - the red area in the above diagram - is lesioned, [this mostly results in difficulty voluntarily contracting and/or relaxing some muscles](https://youtu.be/XvnbtLLoPqE?si=a7ZwyTGl7ibqrvrK&t=611).

Understanding why and how this specialization of different parts of the brain occurs has proven challenging as these different regions dynamically interact.

To overcome this difficulty, we leverage recent advances in machine learning to build structured neural network models that implement hypotheses about how different parts of the brain distincly contribute to shaping behavior from sensory input.
This allows us to verify whether our hypotheses are sufficient to explain experimental observations about these brain regions during behavior.
In addition, the model can be probed a lot more easily than the actual brain which can allow us to better understand how the different model regions collaborate to perform computations.
Finally, analysis of the model can guide new experiments that aim at more precisely probing its underlying hypotheses.


{% capture text %}

For instance, we have focused on the interactions between the motor thalamus (a small brain region with no excitation between its neurons) and the motor cortex


{%
  include button.html
  link="https://www.cell.com/cell-reports/fulltext/S2211-1247(21)00424-1"
  text="See related publication"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/general_multiRegionNN_brain_schematic.png"
  link="projects/project1"
  title=""
  text=text
%}

