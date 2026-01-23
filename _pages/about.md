---
permalink: /
title: "Zeeshan Nadir"
author_profile: false
layout: single
classes: wide

redirect_from: 
  - /about/
  - /about.html
---

<!-- THIS is the front page of a website (which I will edit) that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. Incidentally, these same features make it a great template for anyone that needs to show off a professional template!

 You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and Markdown files, add your own PDFs and other content, and have your own site for free, with no ads! -->


<!-- I am an imaging scientist with 10+ years of experience in deep learning, generative models, and numerical optimization for real-time imaging systems. Proven track record of designing, training, and deploying neural models under strict latency and performance constraints, and shipping AI-driven features used by millions of users. Deep expertise in neural rendering–adjacent pipelines, image/video generation, and performance-critical PyTorch/C++ systems, with strong cross-functional collaboration across hardware, systems, and product team -->



<div class="research-item">
  <div class="research-thumb">
      <img src="../images/Thumbnail.jpg" alt="Thumbnail" style="width:200px">
  </div>

  <div class="research-content">
    <p>
   I am an computational imaging scientist with <b>10+ years of experience </b> in computational photography, inverse problems, mathematical & statistical modelling, and deep learning. I am currently a staff engineer at Samsung Research America working on <b> night mode photography</b>. 
   <!-- I have a proven track record of developing commercial grade algorithms for smartphone cameras and have been involved in numerous projects collaborating with many prestigious institutions including Argonne national laboratory, and air force research labs (AFRL).  -->
   Recently I have been involved in leading projects on <b> generative AI </b> focusing on physics consistent and identity consistent content generation.
   I have hands on experience in developing performance critical Pytorch/Tensorflow/C++ systems with strong cross-functional collaboration across hardware, systems, and product teams.
  <br><br><br>
  <a href="/assets/Zeeshan_Resume_Dec-25-2025.pdf" target="_blank" rel="noopener"> <strong>CV</strong></a> / 
  <a href="https://www.linkedin.com/in/zeeshan-nadir/"><strong>LinkedIn</strong></a> / 
  <a href="https://scholar.google.com/citations?view_op=list_works&hl=en&hl=en&user=lHj-_TkAAAAJ&sortby=pubdate/"><strong>Google Scholar</strong></a>.
    </p>
  </div>
</div>

<hr style="border: none; height: 2px; background-color: #000; margin: 40px 0;">

Research
======

<!-- <img src="../images/outdoor.jpg" alt="A cat" width="200" height="200"> -->

## *Generative Models*


### SeeU: Seeing the Unseen World via 4D Dynamics-aware Generation
<div class="research-item">
  <!-- <div class="research-thumb">
    <img src="../images/research/SeeU/replace.gif" alt="Tomographic Reconstruction" style="width:600px">
  </div> -->

  <div class="research-content">
    <p>
    <img src="../images/research/SeeU/replace.gif" alt="Tomographic Reconstruction" style="width:800px"> 
    <p class="caption" style="margin-top:-20px; text-align:center;"> <b>Replacing object in the video using SeeU</b></p>
      <i> A novel 2D→4D→2D framework that reconstructs a continuous 4D world from sparse monocular video and learns its dynamics under low-rank and physical constraints.
      By modeling motion in continuous 4D space-time, SeeU generates physically consistent unseen views and unobserved time frames.
      </i><br>
      <a href="https://arxiv.org/abs/2512.03350">[arXiv]</a> / 
      <a href="https://huggingface.co/datasets/pandaphd/SeeU45"> [Dataset]</a> / 
      <a href="https://github.com/pandayuanyu/SeeU"> [Code]</a>.</p>
  </div>
</div>

<hr style="border: none; height: 1px; background-color: #000; margin: 40px 0;">

### NewtonGen: Physics-Consistent and Controllable Text-to-Video Generation via Neural Newtonian Dynamics
<div class="research-item">
  <!-- <div class="research-thumb">
    <img src="../images/research/SeeU/replace.gif" alt="Tomographic Reconstruction" style="width:600px">
  </div> -->

  <div class="research-content">
    <p>
    <img src="../images/research/NewtonGen/teaser_a.gif" alt="Tomographic Reconstruction" style="width:800px"> 
    <p class="caption" style="margin-top:-20px;"> Replacing object in the video using SeeU.</p>
      <i> A novel 2D→4D→2D framework that reconstructs a continuous 4D world from sparse monocular video and learns its dynamics under low-rank and physical constraints.
      By modeling motion in continuous 4D space-time, SeeU generates physically consistent unseen views and unobserved time frames.
      </i><br>
      <a href="https://arxiv.org/abs/2509.21309">[arXiv]</a> / 
      <a href="https://github.com/pandayuanyu/NewtonGen"> [Code]</a>. </p>
  </div>  
</div>

<hr style="border: none; height: 2px; background-color: #000; margin: 40px 0;">
## *Inverse Problems*
### Tomographic Reconstruction of Gaseous Media using Bayesian Modelling

<div class="research-item">
  <!-- <div class="research-thumb">
    <img src="../images/research/TDLAT/Gas_Temp.jpg" alt="Tomographic Reconstruction" style="width:200px">
  </div> -->

  <div class="research-content">
    <p>
        <img src="../images/research/TDLAT/Gas_Temp.jpg" alt="Tomographic Reconstruction" style="width:400px;display:block; margin:0 auto;"> 
      <i>Developed a model-based iterative reconstruction (MBIR) framework for imaging gasesous media using Tunable Diode Laser Absorption Tomography (TDLAT). 
      First, I developed a nonlinear statistical measurement model of spectroscopic measurements and regularize the sparase nature of measurements, I proposed a Gaussian mixture model using a 
      small basis set that accomodates complex flow structures.</i><br>
      <a href="/projects/tdlat/">[Read more →]</a> / 
      <a href="https://media.proquest.com/media/hms/ORIG/2/xZodI?_s=wDQEqAzJI9KeqT1uXbXOWYk8p8c%3D">[Thesis]</a> / 
      <a href="https://ieeexplore.ieee.org/abstract/document/7025347"> [Paper]</a> / 
      <a href="https://ieeexplore.ieee.org/abstract/document/7418251"> [Paper]</a> / 
      <a href="https://arc.aiaa.org/doi/abs/10.2514/6.2018-1361"> [Paper]</a> / 
      <a href="https://ieeexplore.ieee.org/abstract/document/8451063"> [Paper]</a> /
      <a href="https://library.imaging.org/ei/articles/33/15/art00008"> [Paper]</a>. </p>
  </div>
</div>


<hr style="border: none; height: 2px; background-color: #000; margin: 40px 0;">
## *Synthetic Data for Deep Learning*

### Sensor-Realistic Synthetic Data Engine for Multi-Frame HDR Photography
<div class="research-item">
  <div class="research-thumb">
    <img src="../images/research/synthetic_data/syn_data.jpg" alt="Tomographic Reconstruction" style="width:200px; margin-top:50px; margin-left:0px;">
  </div>

  <div class="research-content">
    <p>
        <!-- <br> <img src="../images/research/synthetic_data/syn_data.jpg" alt="Tomographic Reconstruction" style="width:700px;display:block; margin:0 auto;"> <br> -->
        <i>This work addresses the lack of realistic training data for deep learning–based multi-frame HDR imaging by introducing a sensor-realistic synthetic data engine. The proposed pipeline augments synthetic multi-exposure images with device-specific sensor characteristics, including noise and color response, to better match real camera behavior. Experiments using a Samsung Galaxy S10 Plus sensor model show that HDR networks fine-tuned with sensor-realistic synthetic data generalize better to real captures than those trained on purely synthetic data. This approach enables scalable, device-aware training data generation for practical HDR imaging systems.</i> <br>
        <a href="https://openaccess.thecvf.com/content_CVPRW_2020/papers/w31/Hu_Sensor-Realistic_Synthetic_Data_Engine_for_Multi-Frame_High_Dynamic_Range_Photography_CVPRW_2020_paper.pdf"> [Paper]</a> / 
        <a href="https://github.com/nadir-zeeshan/sensor-realistic-synthetic-data"> [Code]</a>.
    </p>
  </div>
</div>

<hr style="border: none; height: 1px; background-color: #000; margin: 40px 0;">

### Synthetic Data Generation using Dead Leaves
<div class="research-item">
  <div class="research-thumb">
    <img src="../images/research/dead_leaves/DL.jpg" alt="Tomographic Reconstruction" style="width:200px; margin-top:10px">
  </div>

  <div class="research-content">
    <p>
        <i>
            Presented a method for generating realistic synthetic training data using dead leaves images to support AI-based camera applications where ground truth is difficult or impossible to obtain.
            Starting from a natural raw image in the Bayer domain, we analyze the underlying color distribution and variation statistics and use this information to guide an iterative synthesis process directly in the same raw domain.
            We iteratively synthesize dead leaves by with controlled geometry until the image is filled. Object textures are blended using color statistics from source images.
            Optional localized blurring models optical and sensor effects. 
            The result is a physically plausible raw-domain dead leaves image suitable for scalable, ground-truth–free training of low-level camera AI models.
        </i> <br>
        <a href="https://patentimages.storage.googleapis.com/6c/1c/97/2a855a4a911de1/US12347110B2.pdf"> [Patent]</a>.
    </p>
  </div>
</div>

<hr style="border: none; height: 1px; background-color: #000; margin: 40px 0;">

### Generating multi-exposure frames from single input
<div class="research-item">
  <!-- <div class="research-thumb">
    <img src="../images/research/synthetic_data/syn_data.jpg" alt="Tomographic Reconstruction" style="width:200px; margin-top:50px">
  </div> -->

  <div class="research-content">
    <p>
        <i>Developed a method and system for generating multiple simulated exposure images from a single input image using a machine-learning model, then combining those exposures into a high-quality final image.
         Instead of capturing multiple photos at different exposure levels (which can cause blur or artifacts when camera or objects move), the system uses an input image from a camera sensor and applies a convolutional neural network to create several synthetic images that mimic under-exposed, normal-exposed, and over-exposed frames.
         These generated frames are aligned by design with each other and with the original image, and then blended together to form a final high-dynamic-range (HDR) or enhanced image.
         The approach improves image capture on devices like smartphones, enabling a single shot to produce image quality similar to multi-shot HDR without motion artifacts, and can be implemented in the device’s processor using software instructions.</i> <br>
        <a href="https://patentimages.storage.googleapis.com/39/21/4d/6b1e4e01cfcbd9/US10944914.pdf"> [Patent]</a>.
    </p>
  </div>
</div>

<hr style="border: none; height: 1px; background-color: #000; margin: 40px 0;">

### Multi-sensor, multi-view, multi-frame, multi-task synthetic image fusion engine for mobile imaging systems
<div class="research-item">
  <!-- <div class="research-thumb">
    <img src="../images/research/synthetic_data/syn_data.jpg" alt="Tomographic Reconstruction" style="width:200px; margin-top:50px">
  </div> -->

  <div class="research-content">
    <p>
        <i> Developed a deep learing framework for generating synthetic images under different capture conditions from limited input data, enabling advanced image reconstruction without requiring multiple physical captures. 
        A neural network is trained to learn mappings between input images, their associated meta-data and the desired target images corresponding to different kinds of imaging and computer vision tasks.
        Once trained, the model can synthesize realistic images that approximate what a camera would have captured under alternative settings, such as different exposures or processing pipelines.</i> <br>
        <a href="https://patentimages.storage.googleapis.com/f1/c3/7d/0a00101e17b704/US11720782.pdf"> [Patent]</a>.
    </p>
  </div>
</div>

<hr style="border: none; height: 2px; background-color: #000; margin: 40px 0;">
## *Deep Learning Based Computational Photography*

### Mobile Aware Denoiser Network (MADNet) for Quad Bayer Images
<div class="research-item">
  <div class="research-thumb">
    <img src="../images/research/madnet/madnet.jpg" alt="Tomographic Reconstruction" style="width:200px; margin-top:50px">
  </div>

  <div class="research-content">
    <p>
        <i> Introduced MADNet, a deep-learning denoising framework specifically designed for Quad Bayer image sensors used in high-resolution smartphone cameras, where traditional denoising methods struggle due to the unique raw pixel layout and large data volume. We propose an efficient way to group Quad Bayer pixels into four channels for input to a denoising network, balancing image quality and inference speed, and  introduce a novel inter-channel loss function that helps train the model without overfitting. The approach operates on raw Quad Bayer data prior to demosaicing, preserving fine detail while reducing noise, and yields better denoised images than conventional techniques. Extensive experiments and ablation studies demonstrate that the proposed pixel grouping and loss regularization improve both visual quality and objective metrics, making MADNet well-suited for mobile imaging application where real-time performance and high visual fidelity are critical.</i> <br>
        <a href="https://openaccess.thecvf.com/content/CVPR2024W/UG2/papers/Madhusudana_Mobile_Aware_Denoiser_Network_MADNet_for_Quad_Bayer_Images_CVPRW_2024_paper.pdf"> [Paper]</a> / 
        <a href="https://patentimages.storage.googleapis.com/e7/d3/ee/055023be076cdc/US20250200720A1.pdf"> [Patent]</a>.
    </p>
  </div>
</div>

<hr style="border: none; height: 2px; background-color: #000; margin: 40px 0;">
## *Computer Vision*

### Enhancing human subjects in smartphone images
<div class="research-item">
  <div class="research-thumb">
    <img src="../images/research/face_enhancement/face_enhance.jpg" alt="Tomographic Reconstruction" style="width:200px; margin-top:50px">
  </div>
  <div class="research-content">
    <p>
        <i> 
            Introduce an AI based framework that automatically enhances human faces in smartphone images. The system is based on training a deep learning model first to segment out human subject from the images followed by finding pixels corresponding to facial regions using color processing. 
            Based on the segmentation map and facial pixels, the face region is enhanced by changing contrast and brightness. 
        </i><br> 
        <a href="https://patentimages.storage.googleapis.com/01/a0/e3/c4f7729f3a28f6/US12230053.pdf"> [Paper]</a>. 
    </p>
  </div>
</div>

<!-- 
Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
2. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
3. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
4. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
5. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
6. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
