---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Nuclear Engineering, UC Berkeley, 2019
    * Thesis: Free-moving Omnidirectional 3D Gamma-ray Imaging and Localization
    * Advisor: Prof. Kai Vetter
* M.S. in Nuclear Engineering, Texas A&M University, 2015
    * Thesis: Feasibility of Nuclear Reactor Antineutrino Directionality via Elastic Electron Scattering in the WATer CHerenkov Monitor of ANtineutrinos (WATCHMAN)
    * Advisor: Prof. Craig Marianno
* B.S. in Physics, UC Santa Barbara, 2013


Work experience
======
* Senior Scientific Engineering Associate (Aug 2019 - Present)\
Applied Nuclear Physics Group, Lawrence Berkeley National Laboratory, Berkeley CA
    * Real-time quantitative 3D gamma-ray imaging and scene data fusion.
* Research Fellow (Nov 2014 - Jul 2019)\
Nuclear Science and Security Consortium, UC Berkeley, Berkeley, CA
    * Modeling and imaging algorithm development for free-moving hand-held and UAS-mounted gamma-ray imagers (proximity, coded aperture, Compton).
    * Experimental demonstration of omnidirectional 3D active coded mask imaging in real-time.
    * Fusion of contextual sensors (e.g., LiDAR, RGB camera, IMU) and computer vision techniques (e.g., SLAM) with gamma-ray image reconstruction.
* Physics Intern (Jun - Aug 2015/2014)\
Rare Event Detection Group, Lawrence Livermore National Laboratory, Livermore, CA
    * Monte Carlo simulations and data analysis for a water Cherenkov antineutrino detector.
    * Study on the feasibility of remote clandestine nuclear reactor directionality with antineutrino-electron elastic scattering.
    * Investigation of potential electron scattering background sources in water and the impact of overburden, fiducial volume, and radon contamination on directionality.
* Graduate Research Assistant (Sep 2013 - Nov 2014)\
Department of Nuclear Engineering, Texas A&M University, College Station, TX
    * Design, construction and characterization of a vehicle-mounted scintillator detector array for wide area radiological search in urban environments.
    * Review on the use of solid-state photodiodes and photomultipliers in improving scintillation detection systems.


Skills
======
Languages: Python, C/C++, bash\
Computing Environments: IPython, Mathematica, Matlab\
Data/Statistical Analysis: ROOT, R\
Monte Carlo Transport: Geant4, MCNP5/X, Serpent\
Build Systems: make, CMake\
Operating Systems: macOS, Linux, Windows\
Robotics: ROS\
Databases: HDF5, SQL\
Documentation: Doxygen, Sphinx\
Markup: Markdown, XML, HTML\
Version Control: git (hub, lab)\
Other Software: LaTeX, MS Office


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
