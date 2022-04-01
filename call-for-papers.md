---
title: Call for papers 
layout: services 
description: Call for papers 
intro_image: "images/illustrations/reading.svg"
intro_image_absolute: true 
intro_image_hide_on_mobile: true
---

# Call for papers

Colorectal cancer is the third most common cause of cancer death all over the world, with almost two million new cases in 2020,
worldwide. Early detection is of paramount importance in detecting cancer at an early stage, due to a 5-year survival
rate close to 100% at stage I, and below 10%, at stage IV. Traditional colonoscopy remains the gold standard procedure
because of its dual capability to optically inspect the colonic mucosa and to remove polyps, because they may eventually
become cancer. In the last decades, new technologies have supported clinical decisions with AI and ML algorithms playing
an important role in this process.

This workshop focuses on novel scientific contributions to vision systems, imaging algorithms as well as the autonomous
system for endorobot for GI endoscopy. This includes lesion and lumen detection, as well as 3D reconstruction of the GI
tract and hand-eye coordination. Applications include but are not limited to wireless capsule endoscopy, standard
optical colonoscopy, as well as endorobots for endoscopy. Contributions should demonstrate potential clinical benefits
describing current stage, development path and challenges to overcome before translation into clinical practice.

Localising interesting features such as the lumen, lesions, or polyps to be removed requires their detection in the
images of the video stream. Deep learning-based approaches to this task have become very successful in recent years,
with annotated datasets publicly available to train them. Challenges remain, especially concerning the robustness to
illumination because of the reflective surface. Potential solutions to these issues will be discussed in this workshop.

Another important aspect in endoscopy is the level of autonomy of a medical device to support the clinical workforce in
performing the procedure. This autonomous behaviour can benefit from 3D information such as the localisation of the
target, lumen or lesion, and the position of an endorobot with respect to the wall of the gastrointestinal (GI) tract.
Traditionally this information can be obtained from a monocular video system by using methods such as SLAM,
shape-from-template, and non-rigid structure-from-motion. More recently, methods based on deep learning monocular depth
estimation have also emerged. This workshop will discuss progresses made with those approaches and limitation remaining
to successfully move an endorobot autonomously as well as achieving autonomous surgical tasks.

The workshop will have six selected papers, 10 poster presentations, and two invited speakers covering both clinical and
technical aspects. Topics include but are not limited to

<div class="intro2" style="color:#000000; font-size:1.2rem">
<ul>
    <li>Image processing
        <ul>
            <li>Lesion detection and classification</li>
            <li>Polyp segmentation and detection</li>
            <li>Haustral folds detection</li>
            <li>Real-time lumen detection</li>
        </ul>
    </li>
    <li>3D vision for endoscopy
        <ul>
            <li>3D reconstruction of the colon</li>
            <li>CT (Virtual) colonoscopy</li>
            <li>3D camera systems</li>
            <li>Navigation systems</li>
        </ul>
    </li>
    <li>Imaging technology
        <ul>
            <li>Capsule endoscopy</li>
            <li>Imaging in surgical robots</li>
            <li>Imaging for soft robotics</li>
            <li>Imaging for self-assembling robots</li>
        </ul>
    </li>
    <li>Translational aspects
        <ul>
            <li>Clinical trials and lessons learnt</li>
            <li>Validation of endoscopic systems</li>
            <li>Explainability and acceptability of technology by patients and clinicians</li>
        </ul>
    </li>
</ul>
</div>

<div class="intro2">
  <div class="container">
  <div class="call">
    <div class="call-box-top">
    <div class="call-phone"><strong>Registration </strong> opens soon </div>
    </div>
    <div class="call-box-bottom">
        {% if site.data.contact.disable_button %}
            <a href="" onclick="return false;" class="button-disable">Submit</a>
        {% else %}
            <a href="{{ site.data.contact.contact_button_link }}" class="button">Submit</a>
        {% endif %}
    </div>
  </div>
  </div>
</div>

Workshop proceedings are published as part of Springer Nature's Lecture Notes in Computer Science (LNCS) series.
Manuscripts will be reviewed in double-blinded peer-review. Please prepare your workshop papers according to
the [MICCAI submission guidelines](https://conferences.miccai.org/2022/en/PAPER-SUBMISSION-AND-REBUTTAL-GUIDELINES.html#manuscriptpreparation)
(LNCS template, 8 pages maximum). Supplementary material: PDF documents or mp4 videos, 10 MB maximum file size.