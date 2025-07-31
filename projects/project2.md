---
title: Project2
---

# {% include icon.html icon="fa-solid fa-microscope" %} Testing insights from models with brain data

We develop neural network models whose underlying hypotheses provide a good explanation for an ensemble of experimental results available in the literature.

To go further, we look for robust and testable predictions that distinguish different plausible models. We then collaborate with colleagues who collect brain and behavioral data to test these hypotheses.

{% capture text %}

For instance, [we have recently reviewed](https://academic.oup.com/book/55212/chapter-abstract/427110505?redirectedFrom=fulltext&login=false) different models of how two different brain regions — the motor thalamus and the motor cortex — interact. Different contemporary models make distinct predictions that can be tested by analyzing and/or perturbing the activity of neurons in these two regions during specific behaviors.

{%
  include button.html
  link="https://youtu.be/6Z366GTSkY0?si=BUf73HcoJx-O-_8X"
  text="See a video about this review"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}


{%
  include feature.html
  image="images/chapterGraph.png"
  link="https://youtu.be/6Z366GTSkY0?si=BUf73HcoJx-O-_8X"
  title=""
  text=text
%}

{% capture text %}

Notably, a thalamocortical model we recently developed makes unique predictions about the involvement of specific thalamic populations of neurons — which are associated with different dynamical regimes in the thalamocortical network — at different phases of hierarchical movement sequences.

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
  image="images/thalamocortical_proj2_v2.png"
  link="https://www.cell.com/cell-reports/fulltext/S2211-1247(21)00424-1"
  flip=true
  title=""
  text=text
%}


{% capture text %}

We are collaborating with [Adam Hantman and Stefan Lemke](https://www.med.unc.edu/neuroscience/hantmanlab/directory/), who train mice, record from their brains, and perform brain stimulation experiments. To test predictions of our model, we are analyzing data recorded in the motor cortex and thalamus of mice performing a motor sequence during which they reach for, grasp, and finally retract and eat a pellet.

{% endcapture %}

{%
  include feature.html
  image="images/DataAnalysis_proj2_v3.png"
  link=""
  flip=false
  title=""
  text=text
%}