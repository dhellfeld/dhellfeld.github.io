---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- <button name="button" onclick="https://github.com/dhellfeld/CV/raw/master/pdfs/cv.pdf">Download PDF</button> -->
[Download PDF](https://github.com/dhellfeld/CV/raw/master/pdfs/cv.pdf){: .btn}

Education
======
- **Doctor of Philosophy (Ph.D.)** &#124; Nuclear Engineering &#124;  University of California, Berkeley &#124; Jul 2019
    - Thesis: *Free-moving Omnidirectional 3D Gamma-ray Imaging and Localization*
    - Advisor: Prof. Kai Vetter
- **Master of Science (M.S.)** &#124; Nuclear Engineering &#124; Texas A&M University &#124; May 2015
    - Thesis: *Feasibility of Nuclear Reactor Antineutrino Directionality via Elastic Electron Scattering in the WATer CHerenkov Monitor of ANtineutrinos (WATCHMAN)*
    - Advisor: Prof. Craig Marianno
- **Bachelor of Science (B.S.)** &#124; Physics &#124; University of California, Santa Barbara &#124; Jun 2013


Research experience
======
- **Senior Scientific Engineering Associate** &#124; Aug 2019 - Present <br> Applied Nuclear Physics Group &#124; Lawrence Berkeley National Laboratory &#124; Berkeley, CA
	- Real-time quantitative 3D gamma-ray mapping and contextual scene data fusion.
	- Technical software lead of online and offline image reconstruction algorithms and data pipelines.
	- 3D object detection and tracking in LiDAR point clouds using sparse convolution neural networks for improved radiological source detection and attribution.
	- Detection and tracking algorithm development for a city-scale network of multi-sensor systems.
- **Research Fellow** &#124; Nov 2014 - Jul 2019 <br> Nuclear Science and Security Consortium &#124; UC Berkeley &#124; Berkeley, CA
	- Modeling and imaging algorithm development for free-moving multi-platform (e.g., hand-held,
	ground robot/vehicles, UAS) gamma-ray imagers.
	- Fusion of contextual sensors (e.g., LiDAR, RGBD camera, IMU) and computer vision techniques (e.g., SLAM, photogrammetry) with gamma-ray image reconstruction.
	- Experimental demonstration of omnidirectional 3D active coded mask imaging in real-time.
- **Physics Intern** &#124; Jun - Aug 2015/2014 <br> Rare Event Detection Group &#124; Lawrence Livermore National Laboratory &#124; Livermore, CA
	- Monte Carlo simulations and statistical data analysis for a proposed antineutrino detector.
	- Study on the feasibility of remote clandestine nuclear reactor directionality.
	- Investigation of electron scattering background sources in water and the impact of overburden,
	fiducial volume, and radon contamination on directionality.

<!-- - **Graduate Research Assistant** &#124; Sep 2013 - Nov 2014 <br> Department of Nuclear Engineering &#124; Texas A&M University &#124; College Station, TX
    - Design, construction and characterization of a vehicle-mounted scintillator detector array for wide area radiological search in urban environments.
    - Review on the use of solid-state photodiodes and photomultipliers in improving scintillation detection systems. -->

Teaching experience
======
- **Lecturer** &#124; Jan - May / Sep - Nov 2018 <br> Department of Nuclear Engineering &#124; UC Berkeley &#124; Berkeley, CA
	- Undergraduate radiation detection (NE 104): semiconductor and scintillator detector operation, manufacturing, signal generation, readout techniques, applications and limitations.
	- Undergraduate imaging (NE 107): X-ray detection, image formation, computed tomography,
	and phase contrast imaging.


Skills
======
- **Languages**: Python, C++, bash
- **Data/Statistical Analysis**: ROOT, R
- **Machine Learning**: PyTorch, TensorFlow
- **Build Systems**: make, CMake, ninja
- **Operating Systems**: macOS, Linux, Windows
- **Resource Management**: SLURM
- **Robotics**: ROS
- **GPU**: OpenCL, OpenGL, CUDA
- **Databases**: HDF5, SQL
- **CI/CD**: TravisCI, Docker
- **Documentation**: Doxygen, Sphinx
- **Markup**: Markdown, XML, HTML
- **Version Control**: git
- **Other Software**: LaTeX

Awards
======
- **R&D 100 Award Winner** &#124; R&D World Magazine, WTWH Media &#124; Nov 2019
- **Best Paper Award** &#124; UC Berkeley NE Dept. &#124; Dec 2018
- **Runner-up Student Paper Competition** &#124; IEEE NSS-MIC &#124; Oct 2017
- **Best Oral Presentation** &#124; University Program Review Meeting &#124; Jun 2017
- **Best Poster Award** &#124; INMM Annual Meeting &#124; Jul 2015
- **Nuclear Science and Security Consortium Fellowship** &#124; UC Berkeley &#124; Nov 2014
- **Graduate Enhancement Fellowship** &#124; Texas A&M University &#124; Aug 2013
- **Highest Academic Honor Award** &#124; UC Santa Barbara, Physics Dept. &#124; May 2013
- **Highest Honors** &#124; UC Santa Barbara &#124; May 2013


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Posters
======
  <ul>{% for post in site.posters reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->

<!-- Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
