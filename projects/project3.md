---
title: Project3
---

# {% include icon.html icon="fa-solid fa-microscope" %} Mathematical & computational analysis of the dynamics of structured neural network models

Recent advances in machine learning now allow us to construct complex artificial neural network models that have the potential to be more realistic and more capable than ever. However, it is typically very hard to dissect how the design choices made when building such models impact their performance or neural activity.

To overcome these difficulties, we develop theoretical approaches that strike a balance between maintaining key features of how the neural networks of interest perform their function while simplifying these models enough to permit mathematical tractability.

{% capture text %}

For instance, we have mathematically analyzed the dynamics of a recurrent (cortical) network modulated by a few loops. We constrained the neural response function to stay either in a linear or rectified regime, which both facilitates the mathematical analysis and is consistent with [the dynamics that fit motor cortical activity well](https://www.biorxiv.org/content/10.1101/2022.12.16.520768v1). However, even though it complicates the mathematical analysis, we preserved the expressivity of the network by accounting for task-optimized connections and allowing high-dimensional dynamics. Our ongoing work demonstrates that this framework can inform the design of robust, fully non-linear networks compatible with modern machine learning applications (see a related [presentation](https://icerm.brown.edu/video_archive/3359), [preprint](https://arxiv.org/abs/2006.13332), and [use of a similar approach in Large Language Models](https://arxiv.org/abs/2106.09685)).



{%
  include button.html
  link="https://video.ictp.it/WEB/2024/2024_06_03-smr3943/2024_06_05-14_15-smr3943.mp4"
  text="Watch a video with a chalk talk (given at ICTP) on the topic"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}


{%
  include feature.html
  image="images/TheoryIllutr_figF.png"
  link="https://video.ictp.it/WEB/2024/2024_06_03-smr3943/2024_06_05-14_15-smr3943.mp4"
  title=""
  text=text
%}

&nbsp;

{% capture text %}

In another line of research, we ask how to relate biological neurons to the simplified, smoothly varying artificial "units" used in the vast majority of modern neural network models on both the machine learning and theoretical fronts. Indeed, most mammalian biological neurons do not respond continuously to their inputs: instead, they emit a series of stereotypical signals called "spikes". A line of work has related the average spike rate in a population of biological neurons to the continuous activity of model units. However, there remain challenges to account for the heterogeneity of connections among neurons of a population, as well as for dynamic properties of biological neurons - such as adaptation. We are making progress on these questions by deriving interpretable population rate equations that reflect key features of biological neurons while revealing the emergence of continuous state variables akin to those of artificial units.

{%
  include button.html
  link="https://www.youtube.com/watch?v=GgYeKNkCov8&t=551s"
  text="See a presentation on this topic"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/pic_Wulfram_project_v2.png"
  link="https://www.youtube.com/watch?v=GgYeKNkCov8&t=551s"
  flip=true
  title=""
  text=text
%}