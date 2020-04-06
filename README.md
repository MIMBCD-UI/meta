# About MIMBCD-UI Project

<a href="https://github.com/MIMBCD-UI/" title="Meta" target="_blank">
  <img src="https://github.com/MIMBCD-UI/meta/blob/master/headers/breast_cancer_women.png" alt="header" />
</a>

The [Medical Imaging Multimodality Breast Cancer Diagnosis User Interface (MIMBCD-UI)](https://mimbcd-ui.github.io/) Project involves the collaborative effort of three Portuguese Research Institutions: [ISR](http://welcome.isr.tecnico.ulisboa.pt/), [ITI](http://iti.larsys.pt/) and [INESC-ID](http://www.inesc-id.pt/). The three labpratories are [Associate Laboratories](https://tecnico.ulisboa.pt/en/research-and-innovation/rd/associate-laboratories/) of [IST](http://tecnico.ulisboa.pt/) from [ULisboa](https://www.ulisboa.pt/) - [Portugal](https://www.portugal.gov.pt/) ([EU](https://europa.eu/)). The project was created through the [Master Thesis](https://fenix.tecnico.ulisboa.pt/cursos/meic-a/dissertacao/1409728525632244) of [Francisco Maria Calisto](http://web.tecnico.ulisboa.pt/francisco.calisto/). The [MIMBCD-UI](https://github.com/MIMBCD-UI) Project is the precursor of both [MIDA](https://github.com/mida-project) and [BreastScreening](https://github.com/BreastScreening) projects. For further information, follow the project [Wiki](https://github.com/MIMBCD-UI/meta/wiki).

## Research

Like the fact that these projects are research projects, we underline and ask for the support of our noble scientific community to help us across the path. With this project, we hope to provide valuable information regarding our research topics and theories. Also, you can follow and support our project on [ResearchGate](https://www.researchgate.net/project/Medical-Imaging-Multimodality-Breast-Cancer-Diagnosis-User-Interface).

### Citing Master Thesis

We kindly ask **scientific works and studies** that make use of Master Thesis to cite Master Thesis in their associated publications. Similarly, we ask **open-source** and **closed-source** works that make use of Master Thesis to warn us about this use. You can cite our work using the following BibTeX entry:

```
@mastersthesis{calisto2017mimbcdui,
  doi = {10.13140/RG.2.2.15187.02084},
  url = {http://rgdoi.net/10.13140/RG.2.2.15187.02084},
  author = {Francisco Maria Calisto},
  title = {Medical Imaging Multimodality Breast Cancer Diagnosis User Interface},
  school = {Instituto Superior T\'{e}cnico},
  year = 2017,
  address = {Avenida Rovisco Pais 1, 1049-001 Lisboa - Portugal (EU)},
  month = 10,
  note = {A Medical Imaging Tool for a Multimodality use of Breast Cancer Diagnosis on an User Interface.}
}
```

### Publications

We have several publications made on research conferences and journals. In this section, we provide a short list of our main samples. To see a more complete list, please follow [this link](https://github.com/MIMBCD-UI/meta/wiki/Publications).

***

[Towards Touch-Based Medical Image Diagnosis Annotation](https://dl.acm.org/citation.cfm?id=3134111&CFID=841794082&CFTOKEN=36707834)

[Francisco M. Calisto](https://dl.acm.org/author_page.cfm?id=99659211441&CFID=841794082&CFTOKEN=36707834), [Alfredo Ferreira](https://dl.acm.org/author_page.cfm?id=81448599037&CFID=841794082&CFTOKEN=36707834), [Jacinto C. Nascimento](https://dl.acm.org/author_page.cfm?id=99659210241&CFID=841794082&CFTOKEN=36707834) and [Daniel Gonçalves](https://dl.acm.org/author_page.cfm?id=81100240223&CFID=841794082&CFTOKEN=36707834)

In [Proceedings](http://st.sigchi.org/publications/toc/iss-2017.html) of the [2017 ACM International Conference on Interactive Surfaces and Spaces (ISS '17)](https://iss2017.acm.org/)

ACM, New York, NY, USA, 390-395.

DOI: [10.1145/3132272.3134111](https://doi.org/10.1145/3132272.3134111)

***

[Automated Analysis of Unregistered Multi-View Mammograms With Deep Learning](http://ieeexplore.ieee.org/abstract/document/8032490/)

[Gustavo Carneiro](http://ieeexplore.ieee.org/search/searchresult.jsp?searchWithin=%22Authors%22:.QT.Gustavo%20Carneiro.QT.&newsearch=true), [Jacinto Nascimento](http://ieeexplore.ieee.org/search/searchresult.jsp?searchWithin=%22Authors%22:.QT.Jacinto%20Nascimento.QT.&newsearch=true) and [Andrew P. Bradley](http://ieeexplore.ieee.org/search/searchresult.jsp?searchWithin=%22Authors%22:.QT.Andrew%20P.%20Bradley.QT.&newsearch=true)

Published in: [IEEE Transactions on Medical Imaging](http://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=42) ( Volume: 36, [Issue: 11](http://ieeexplore.ieee.org/xpl/tocresult.jsp?isnumber=8087860), Nov. 2017 )

Page(s): 2355 - 2365

Date of Publication: 12 September 2017

DOI: [10.1109/TMI.2017.2751523](https://doi.org/10.1109/TMI.2017.2751523)

***

## Introduction

The project is being developed by the Associate Laboratory - [Institute for Systems and Robotics (ISR-Lisboa)](http://welcome.isr.tecnico.ulisboa.pt/). This [project proposes](https://www.researchgate.net/project/Medical-Imaging-Multimodality-Breast-Cancer-Diagnosis-User-Interface) the development of [visualizations and interaction techniques](https://dl.acm.org/citation.cfm?id=3134111) for the detection of cancer targeting among breast using [Multi-Modality](https://www.researchgate.net/publication/331686858_BreastScreening_A_Multimodality_Diagnostic_Assistant) medical imaging and textual information.

More specifically, this project deals with the use of a recently proposed Machine Learning (ML) method in literature: [Deep Convolutional Neural Networks (CNNs)](https://en.wikipedia.org/wiki/Convolutional_neural_network). These Deep Networks will incorporate information from several different modes: Magnetic Resonance Imaging (MRI) volumes, UltraSound (US) images, MammoGraphic (MG) images (both views [CC](http://radiopaedia.org/articles/craniocaudal-view) and [MLO](http://radiopaedia.org/articles/mediolateral-oblique-view)) and text. The proposed algorithm, called for Multi-Modality CNN (MMCNNs) will have the ability to process multimodal information at a unified and sustained manner. This methodology needs to "learn" what are the masses and calcifications. Therefore, it is of chief importance to create and improve several visualization and interaction techniques to promote and generate data (i.e., our datasets) for the purpose.

So that is necessary to collect the [ground truth](https://en.wikipedia.org/wiki/Ground_truth), or notes of the masses and calcifications provided by medical experts. For the collection of these notes, the design and development of several User Interfaces (UI) is necessary, allowing the user (in this case, the medical specialist) to display various types of image (*i.e.*, MG, US and MRI), and that also allows for user interaction, particularly in providing the notes of the masses and calcifications. For these reasons, it is crucial for the development of this project, cooperation with experts providing the above notes.

## Goals

Development of the UI for diagnosis of breast cancer in Medical Imaging (MI) Multi-Modality. MIMBCD-UI is aiming for an intuitive UI, a user-friendly interface that allows users to rapidly diagnose several image modalities.

It is intended to develop an UI for monitoring and diagnosis of breast lesions in various medical imaging modalities. Responses of these imaging modalities are containing plenty of useful information that are extracted and analyzed by the clinicians for the purpose of analysis, detection and the diagnosis of breast lesions.

The imaging modalities to include in the work are:

* [MG](https://en.wikipedia.org/wiki/Mammography) (including the views CC and MLO);
* [US](https://en.wikipedia.org/wiki/Ultrasound);
* [MRI](https://en.wikipedia.org/wiki/Magnetic_resonance_imaging) volumes;

Having a protocol already signed with the [Hospital Fernando Fonseca](http://www.hff.min-saude.pt/), it is intended that this interface has two features:

**(i)** - Build a database with annotations in Multi-Modality of breast images.

Provide the user (doctor) facility to draw / write down masses and calcifications, as well as the corresponding [BIRADS](https://en.wikipedia.org/wiki/BI-RADS) for each imaging modality. This annotation process can be built during the examination, and thus it is possible to build a database of medical notes.

**(ii)** - Follow-up of the patient. With this feature is to allow the doctor automate a Multi-Modality inspection for the patient.

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

Our projects provide comprehensive academic advising and research opportunities. Together the projects enable students, fellows and researchers to chart their own educational journey and make the best research experience.

#### Advisor

Professor [Jacinto Peixoto do Nascimento](http://users.isr.ist.utl.pt/~jan/) ([ISR](http://welcome.isr.tecnico.ulisboa.pt/author/jacintocarlosmarquespeixotodo/)/[IST](https://fenix.tecnico.ulisboa.pt/homepage/ist33543))

#### Co-Advisors

Professor [Daniel Gonçalves](http://danielgoncalves.info/) ([INESC-ID](http://www.inesc-id.pt/member.php?pid=317)/[IST](https://fenix.tecnico.ulisboa.pt/homepage/ist13898))

[Francisco Maria Calisto](https://web.tecnico.ulisboa.pt/francisco.calisto/) ([ITI](https://iti.larsys.pt/)/[IST](https://fenix.tecnico.ulisboa.pt/homepage/ist170916))

## Information

The following information shows our resources and acknowledgements across the project development. It is in this section, where we link our [datasets](https://github.com/MIMBCD-UI/meta/wiki/Datasets) and important people, as well as projects to our research. The [MIMBCD-UI](https://mimbcd-ui.github.io/) will serve as base research of both [MIDA](https://mida-project.github.io/) and [BreastScreening](https://breastscreening.github.io/) projects.

### Dataset Resources

During the development of this project we generated a combination of interesting [datasets](https://www.kaggle.com/MIMBCD-UI/datasets). To publish our related [datasets](https://www.kaggle.com/MIMBCD-UI/datasets) we used a well known platform called [Kaggle](https://www.kaggle.com/MIMBCD-UI). To access our project's [Profile Page](https://www.kaggle.com/MIMBCD-UI) just follow the [link](https://www.kaggle.com/MIMBCD-UI).

### Acknowledgements

A special thanks to [Chris Hafey](https://www.linkedin.com/in/chafey/), the propelling person of [CornerstoneJS](https://cornerstonejs.org/), who also developed the [cornerstoneDemo](https://github.com/chafey/cornerstoneDemo). Not forgetting the three supporters of the [CornerstoneJS](https://cornerstonejs.org/) library, [Aloïs Dreyfus](https://www.linkedin.com/in/alois-dreyfus), [Danny Brown](http://dannyrb.com/) and [Erik Ziegler](https://www.npmjs.com/~swederik). We also would like to give a special thanks to [Erik Ziegler](https://www.npmjs.com/~swederik) who support several [issues](https://groups.google.com/forum/#!forum/cornerstone-platform) during this path. Thanks also [Pedro Miraldo](https://github.com/pmiraldo), [Carlos Santiago](https://github.com/cajosantiago), [Bruno Cardoso](https://github.com/bdcardoso) and [Bruno Oliveira](https://github.com/bruno-oliveira) for the technical help given. In the end, a great thank to all [Orthanc](https://www.orthanc-server.com/) project team, but especially to [Sébastien Jodogne](https://www.linkedin.com/in/jodogne/).

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
