---
title: Project3
---

# {% include icon.html icon="fa-solid fa-microscope" %} Using computational neural network models of mammalian brain regions to design smart neuroprostheses

It is an exciting time for the field of computational neuroscience: neural network models can now be adjusted to quantitatively match the activity of neurons recorded in a particular brain region. Importantly, these quantitative models can also be leveraged to find stimulation patterns that will push neural activity towards a desired state.

This technology could have wide-ranging applications, notably in the domain of neuroprostheses. Neuroprostheses are devices that aim to restore the function of a part of the nervous system that has been lesioned. In the context of the motor system, a neuroprosthesis would read out relevant brain signals (such as an intended movement) and perform appropriate sensorimotor computations that the lesioned brain region is now unable to carry out. Depending on the nature of the lesion, the results of these computations would be communicated to relevant motor and/or sensory spared circuits. If the limb or peripheral motor nerves are themselves damaged, the neuroprosthesis could also simultaneously control an artificial limb.

{% include section.html size="full" %}

{% include figure.html image="images/showSmartBMI_stimulation_vPleaseBig.png" width="40%" %}

{% include section.html %}

However, challenges remain for applying this approach to restore the functions of motor brain regions such as the motor cortex or the cerebellum. Most notably, neurons in these motor regions continuously adjust their connections to adapt our movements to the constant variations imposed by the external world. These plastic connectivity changes are currently not accounted for in the networks adjusted to quantitatively match neural activity, as this approach has so far been largely focused on visual brain regions that are less adaptive than motor ones.

With collaborators [Lakshmi Govindarajan](https://scholar.google.com/citations?user=-1k4MtgAAAAJ&hl=en) and [Christopher Cueva](https://scholar.google.com/citations?user=BxLgolsAAAAJ&hl=en), as well as a broader support team at Brown University and CU Anschutz, we are developing an approach that aims at filling this gap. To do so, we are leveraging [multi-region neural network models](https://abstracts.g-node.org/abstracts/28eb2234-df0e-4964-ab51-96da248986ae) of the sensorimotor brain systems that we have built to emulate the multiple interacting plasticity phenomena at play.