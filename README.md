# About MIMBCD-UI Project

<a href="https://github.com/MIMBCD-UI/" title="Meta" target="_blank">
  <img src="https://github.com/MIMBCD-UI/meta/blob/master/headers/breast_cancer_women.png" alt="header" />
</a>

Medical Imaging Multimodality Breast Cancer Diagnosis User Interface (MIMBCD-UI) Project involves the collaborative effort of two Portuguese Research Institutions: [INESC-ID](http://www.inesc-id.pt/) and [ISR](http://welcome.isr.tecnico.ulisboa.pt/) both are [Associate Laboratories](https://tecnico.ulisboa.pt/en/research-and-innovation/rd/associate-laboratories/) of [IST](http://tecnico.ulisboa.pt/) from [ULisboa](https://www.ulisboa.pt/) - [Portugal](https://www.portugal.gov.pt/) ([EU](https://europa.eu/)). The project was created through the [Master Thesis](https://fenix.tecnico.ulisboa.pt/cursos/meic-a/dissertacao/1409728525632244) of [Francisco Maria Calisto](http://web.tecnico.ulisboa.pt/francisco.calisto/).

## Citing Master Thesis

We kindly ask **scientific works and studies** that make use of Master Thesis to cite Master Thesis in their associated publications. Similarly, we ask **open-source** and **closed-source** works that make use of Master Thesis to warn us about this use. You can cite our work using the following BibTeX entry:

```
@mastersthesis{calisto2017mimbcdui,
  author       = {Francisco Maria Calisto},
  title        = {Medical Imaging Multimodality Breast Cancer Diagnosis User Interface},
  school       = {Instituto Superior T\'{e}cnico},
  year         = 2017,
  address      = {Avenida Rovisco Pais 1, 1049-001 Lisboa - Portugal (EU)},
  month        = 10,
  note         = {A Medical Imaging for Multimodality of Breast Cancer Diagnosis by an User Interface.}
}
```

## Introduction

The project is being developed by the Associate Laboratory - [Institute for Systems and Robotics (ISR-Lisboa)](http://welcome.isr.tecnico.ulisboa.pt/). This project proposes the development of a methodology for breast detection and cancer targeting using multi-modality of medical imaging and textual information.

More Specifically, this project deals with the use of a recently proposed technique in literature: [Deep Convolutional Neural Networks (CNNs)](https://en.wikipedia.org/wiki/Convolutional_neural_network). These deep networks will incorporate information from several different modes: magnetic resonance imaging volumes (MRI), ultrasound images, mammographic images (both views [CC](http://radiopaedia.org/articles/craniocaudal-view) and [MLO](http://radiopaedia.org/articles/mediolateral-oblique-view)) and text. The proposed algorithm, called for multimodality CNNs (MMCNNs) will have the ability to process multimodal information at an unified and sustained manner. This methodology needs to "learn" what are the masses and calcifications.

So that is necessary to collect the [ground truth](https://en.wikipedia.org/wiki/Ground_truth), or notes of the masses and calcifications provided by medical experts. For the collection of these notes, the design and development of an interface is necessary allows the user (in this case, the medical specialist) to display various types of image (i.e., ultrasound, MRI and mammography), and that also allows for user interaction, particularly in providing the notes of the masses and calcifications. For these reasons, it is crucial for the development of this project, cooperation with experts providing the above notes.

## Goals

Development of the User Interface for Diagnosis of Breast Cancer in Medical Imaging Multimodality. MIMBCD-UI is aiming for an intuitive User Interface, a user-friendly interface that allows users to rapidly diagnosis several image modalities.

It is intended to develop an User Interface for monitoring and diagnosis of breast lesions in various medical imaging modalities. Responses of these imaging modalities are containing plenty of useful information that are extracted and analyzed by the clinicians for the purpose of analysis, detection and the diagnosis of breast lesions.

The imaging modalities to include in the work are:

* [Mammography](https://en.wikipedia.org/wiki/Mammography) (including the views caudal-skull and oblique);
* [Ultrasound](https://en.wikipedia.org/wiki/Ultrasound);
* [MRI](https://en.wikipedia.org/wiki/Magnetic_resonance_imaging) volumes;

With protocol already signed with the [Hospital Fernando Fonseca](http://www.hff.min-saude.pt/), it is intended that this interface has two features:

**(i)** - Build a database with annotations in multimodality mammography image.

Provide the user (doctor) facility to draw / write down masses and calcifications, as well as the corresponding [BI-RADS](https://en.wikipedia.org/wiki/BI-RADS) for each imaging modality. This annotation process can be built during the examination, and thus it is possible to build a database of medical notes.

**(ii)** - Follow-up of the patient. With this feature is to allow the doctor automate a multimodality inspection for the patient.

Based on the patient's identification (eg, via a query on the ID), and for a given type of mammography imaging, the system must return all images of this patient over a period of time (eg. Two or more years) entered by the doctor, and show these images (pre-recorded). This feature is critical for diagnosis because it allows, through information visualization, observing not only the calcifications density and the morphological evolution of the masses in that time period.

## Requirements

* [HTML](http://www.w3schools.com/html/);
* [CSS](http://www.w3schools.com/css/);
* [Javascript](http://www.w3schools.com/js/);
* [Python](https://www.python.org/);
* [MATLAB](http://www.mathworks.com/);

## Media

* [MIMBCD-UI Site](https://mimbcd-ui.github.io/)

* [ResearchGate](https://www.researchgate.net/project/MIMBCD-UI)

* [GitHub](https://github.com/MIMBCD-UI)

* [MIMBCD-UI Youtube Channel](https://www.youtube.com/channel/UCPz4aTIVHekHXTxHTUOLmXw)

* [MIMBCD-UI Youtube Playlist](https://www.youtube.com/playlist?list=PLSTwZNTQNGC5pdYGWmUwwV8jsckozx6U9)

## Advisorship

#### Advisor

Professor [Jacinto Peixoto do Nascimento](http://users.isr.ist.utl.pt/~jan/) ([ISR](http://welcome.isr.tecnico.ulisboa.pt/author/jacintocarlosmarquespeixotodo/)/[IST](https://fenix.tecnico.ulisboa.pt/homepage/ist33543))

#### Co-Advisor

Professor [Daniel Gonçalves](http://danielgoncalves.info/) ([INESC-ID](http://www.inesc-id.pt/member.php?pid=317)/[IST](https://fenix.tecnico.ulisboa.pt/homepage/ist13898))

### Acknowledgements

A special thanks to [Chris Hafey](https://www.linkedin.com/in/chafey/), the propelling person of [CornerstoneJS](https://cornerstonejs.org/), who also developed the [cornerstoneDemo](https://github.com/chafey/cornerstoneDemo). Not forgetting the three supporters of the [CornerstoneJS](https://cornerstonejs.org/) library, [Aloïs Dreyfus](https://www.linkedin.com/in/alois-dreyfus), [Danny Brown](http://dannyrb.com/) and [Erik Ziegler](https://www.npmjs.com/~swederik). We also would like to give a special thanks to [Erik Ziegler](https://www.npmjs.com/~swederik) who support several [issues](https://groups.google.com/forum/#!forum/cornerstone-platform) during this path. Thanks also [Pedro Miraldo](https://github.com/pmiraldo), [Carlos Santiago](https://github.com/cajosantiago), [Bruno Cardoso](https://github.com/bdcardoso) and [Bruno Oliveira](https://github.com/bruno-oliveira) for the help given.

## Sponsors

<span class="image">
  <a href="http://www.fct.pt/" title="FCT" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/fct_footer.png" alt="fct" width="20%" />
  </a>
</span>
<span class="image">
  <a href="https://www.fccn.pt/en/" title="FCCN" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/fccn_footer.png" alt="fccn" width="20%" />
  </a>
</span>
<span class="image">
  <a href="https://www.ulisboa.pt/en/" title="ULisboa" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/ulisboa_footer.png" alt="ulisboa" width="20%" />
  </a>
</span>
<span class="image">
  <a href="http://tecnico.ulisboa.pt/" title="IST" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/ist_footer.png" alt="ist" width="20%" />
  </a>
</span>
<span class="image">
  <a href="http://hff.min-saude.pt/" title="HFF" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/hff_footer.png" alt="hff" width="20%" />
  </a>
</span>

## Departments

<span class="image">
  <a href="http://dei.tecnico.ulisboa.pt" title="DEI" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/dei_footer.png" alt="dei" width="20%" />
  </a>
</span>
<span class="image">
  <a href="http://deec.tecnico.ulisboa.pt" title="DEEC" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/deec_footer.png" alt="dei" width="20%" />
  </a>
</span>

## Laboratories

<span class="image">
  <a href="http://sipg.isr.tecnico.ulisboa.pt/" title="SIPG" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/sipg_footer.png" alt="sipg" width="20%" />
  </a>
</span>
<span class="image">
  <a href="http://welcome.isr.tecnico.ulisboa.pt/" title="ISR" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/isr-lisboa_footer.png" alt="isr" width="20%" />
  </a>
</span>
<span class="image">
  <a href="http://larsys.pt/" title="LARSys" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/larsys_footer.png" alt="larsys" width="20%" />
  </a>
</span>
<span class="image">
  <a href="http://www.inesc-id.pt/" title="INESC-ID" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/inesc-id_footer.png" alt="inesc-id" width="20%" />
  </a>
</span>

## Domain

<span class="image">
  <a href="https://europa.eu/" title="EU" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/eu_footer.png" alt="eu" width="20%" />
  </a>
</span>
<span class="image">
  <a href="https://www.portugal.gov.pt/" title="Portugal" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/pt_footer.png" alt="pt" width="20%" />
  </a>
</span>
