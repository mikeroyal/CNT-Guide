<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/153960848-375170b9-91f1-4332-8464-bb0ef8f6f63f.png">
  <br />
  Carbon nanotubes (CNTs) Guide
</h1>

#### A guide covering Carbon nanotubes (CNTs) including the applications and tools that will make you a better and more efficient with Carbon nanotubes (CNTs) development.

**Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/153960883-a6a2e8d5-2d5c-4de6-93f3-0cd6af37a722.png">
<br />
</p>


# Table of Contents

1. [Getting Started with CNTs](https://github.com/mikeroyal/CNT-Guide#getting-started-with-cnts)

2. [Electric charge, field, and potential](https://github.com/mikeroyal/CNT-Guide#electric-charge-field-and-potential)

     - Charge and electric force (Coulomb's law): Electric charge, field, and potential
     - Electric field: Electric charge, field, and potential
     - Electric potential energy, electric potential, and voltage: Electric charge, field, and potential

3. [Circuits](https://github.com/mikeroyal/CNT-Guide#Circuits)

    - Ohm's law and circuits with resistors: Circuits
    - Circuits with capacitors: Circuits

4. [Magnetic forces, magnetic fields, and Faraday's law](https://github.com/mikeroyal/CNT-Guide#magnetic-forces-magnetic-fields-and-Faradays-law)

    - Magnets and Magnetic Force: Magnetic forces, magnetic fields, and Faraday's law
    - Magnetic field created by a current: Magnetic forces, magnetic fields, and Faraday's law
    - Electric motors: Magnetic forces, magnetic fields, and Faraday's law
    - Magnetic flux and Faraday's law

5. [Electromagnetic waves and interference](https://github.com/mikeroyal/CNT-Guide#electromagnetic-waves-and-interference)

    - Introduction to electromagnetic waves: Electromagnetic waves and interference
    - Interference of electromagnetic waves
    
6. [Geometric optics](https://github.com/mikeroyal/CNT-Guide#Geometric-optics)

    - Reflection and refraction: Geometric optics
    - Mirrors: Geometric optics
    - Lenses

7. [Quantum Physics](https://github.com/mikeroyal/CNT-Guide#Quantum-Physics)

   - Photons: Quantum Physics
   - Atoms and electrons: Quantum Physics
   - Quantum numbers and orbitals: Quantum Physics
   - Nuclei

8. [MATLAB Development](https://github.com/mikeroyal/CNT-Guide#MATLAB-Development)

9. [CUDA Development](https://github.com/mikeroyal/CNT-Guide#CUDA-Development)

10. [Bioinformatics](https://github.com/mikeroyal/CNT-Guide#bioinformatics)


# Getting Started with CNTs
[Back to the Top](https://github.com/mikeroyal/CNT-Guide#table-of-contents)

[Carbon nanotubes (CNTs)](https://www.sciencedirect.com/topics/materials-science/carbon-nanotubes) are sp^2 nanocarbon materials with tubular structures composed of rolled-up [graphene sheets](https://www.mcmaster.com/graphene-sheets). In addition to unique nanostructures, they exhibit remarkable properties, some derived from the similar properties of [graphite](https://mineralseducationcoalition.org/minerals-database/graphite/) and some from their one-dimensional aspects. CNTs are chemically stable and resist virtually any chemical impact unless they are simultaneously exposed to high temperatures and oxygen. These advantages make CNTs ideal candidate for many applications(including electronic devices) such as: 

   - Transistors

   - Electron-field emitters
   
   - Molecular electronics: CNT based non volatile RAM
 
   - Chemical/electrochemical sensors

   - Biosensors

   - Lithium-ion batteries

   - Hydrogen storage cells

   - Supercapacitors

   - Electrical shielding devices

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/153960910-da1881b8-9aaf-4355-953d-14d0f080d298.gif">
<br />
 Carbon Nanotubes
</p>

[Single-walled carbon nanotubes (SWCNT)](https://www.graphene-info.com/carbon-nanotubes) is a carbon nanotube made from one layer of carbon atoms. It can be formed in three different designs: Armchair, Chiral, and Zigzag. The design depends on the way the graphene is wrapped into a cylinder.  

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/153961074-e7653b1d-9487-412c-b0d6-ec22ba4c338f.png">
<br />
 Single-Walled Carbon Nanotubes (SWCNT)
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/153961129-dab8c61a-f8a8-42d5-847c-6fbceda695b2.png">
<br />
</p>

Types of carbon nanotubes: (a) armchair, (b) zigzag, (c) chiral. Source: [ResearchGate](https://www.researchgate.net/figure/9-Types-of-carbon-nanotubes-a-armchair-b-zigzag-c-chiral-Reproduced-from-55_fig9_305766738)

[Double-Walled Carbon Nanotubes (DWCNT)](https://www.ossila.com/products/double-walled-carbon-nanotubes) is a class of carbon nanotube consists of two nanotubes, with one nested within the other. The differences in the diameters of the two nanotubes can produce varying degrees of interaction between the two tubes. This allows for modifications to be made to the outer nanotube without altering the inner nanotube's properties, and results in unique and interesting properties. Additionally, DWCNTs enable a combination of solubility and functionality (which is not possible with single-walled carbon nanotubes).

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/153961095-581d6c35-9c83-4f8e-9254-897f5b7965f2.png">
<br />
 Double-Walled Carbon Nanotubes (DWCNT)
</p>


[Multi-walled carbon nanotubes (MWCNT)](https://www.graphene-info.com/carbon-nanotubes) is a carbon nanotube made consisting of several layers of graphene sheets. Multi-walled carbon nanotubes have similar properties to singlewalled nanotubes, yet the outer walls on multi-walled nanotubes can protect the inner carbon nanotubes from chemical interactions with outside materials. Multi-walled nanotubes also have a higher tensile strength than single-walled nanotubes. 

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/153961109-c5a96b79-7315-49dd-a68e-40c7382df786.png">
<br />
 Multi-walled carbon nanotubes (MWCNT)
</p>

[LLTO](https://www.patentlyapple.com/patently-apple/2021/02/apple-is-working-with-the-us-government-on-new-coatings-for-cathode-active-materials-for-mobile-batteries-beyond.html) is a lithium-ion oxide coating containing lanthanum and titanium.  

[LLGO](https://www.patentlyapple.com/patently-apple/2021/02/apple-is-working-with-the-us-government-on-new-coatings-for-cathode-active-materials-for-mobile-batteries-beyond.html) is a lithium-ion oxide containing lanthanum and germanium.

[Solid-State Battery](https://ucsdnews.ucsd.edu/pressrelease/meng_science_2021) is a battery technology that consists of a cathode composite layer, a sulfide solid electrolyte layer, and a carbon free micro-silicon anode. Before charging, discrete micro-scale Silicon particles make up the energy dense anode.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/153961151-5c0fcbbf-26f4-4cff-95ff-9d07046289f1.png">
<br />
 Solid-State Battery
</p>

# Electric charge, field, and potential
[Back to the Top](https://github.com/mikeroyal/CNT-Guide#table-of-contents)

     - Charge and electric force (Coulomb's law): Electric charge, field, and potential
     - Electric field: Electric charge, field, and potential
     - Electric potential energy, electric potential, and voltage: Electric charge, field, and potential

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784122-2c0e9166-ff73-44cf-a5b5-62d76aba80c7.png">
  <br />
</p>

 **Electric Potential Energy. Source: [sparkfun](https://learn.sparkfun.com/tutorials/what-is-electricity/electric-potential-energy)**

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784121-8f89a787-1674-4db4-ba46-b2f280706dd9.png">
  <br />
</p>

# Circuits
[Back to the Top](https://github.com/mikeroyal/CNT-Guide#table-of-contents)

    - Ohm's law and circuits with resistors: Circuits
    - Circuits with capacitors: Circuits

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784127-ad587152-0c0d-4671-b29d-9231889899ff.png">
  <br />
</p>

 **Electric Circuits. Source: [sdsu-physics](http://sdsu-physics.org/physics180/physics180B/Chapters/electric_currents.htm)**

  <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784128-941e1cf9-0cff-4702-b97b-f827d9489a20.png">
  <br />
</p>

 **Symbols of Circuits .Source: [andrewpover.co.uk](https://andrewpover.co.uk/category/physics/)**

# Magnetic forces, magnetic fields, and Faraday's law
[Back to the Top](https://github.com/mikeroyal/CNT-Guide#table-of-contents)

    - Magnets and Magnetic Force: Magnetic forces, magnetic fields, and Faraday's law
    - Magnetic field created by a current: Magnetic forces, magnetic fields, and Faraday's law
    - Electric motors: Magnetic forces, magnetic fields, and Faraday's law
    - Magnetic flux and Faraday's law

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784132-d4b67030-9e04-41f1-90d2-98b7c6beebe8.png">
  <br />
</p>

 **Magnetic Field. Source: [vecteezy](https://www.vecteezy.com/vector-art/593998-physics-science-about-the-movement-of-magnetic-fields-positive-and-negative)**

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784663-28e8ad0e-aa9d-4dbf-b285-0b2976de2d3e.png">
  <br />
</p>

 **Amphere's Law. Source: [sdsu-physics](https://sdsu-physics.org/physics180/physics196/Topics/magneticFields30.html)**

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784666-dd53913b-33c9-4ddd-8cf1-b8fa398bf3de.png">
  <br />
</p>

 **Farady's law. Source: [sdsu-physics](http://sdsu-physics.org/physics180/physics196/Topics/faradaysLaw.html)**

# Electromagnetic waves and interference
[Back to the Top](https://github.com/mikeroyal/CNT-Guide#table-of-contents)

    - Introduction to electromagnetic waves: Electromagnetic waves and interference
    - Interference of electromagnetic waves

  <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127785050-a98f0812-d723-49b9-9796-ac05bb64804a.png">
  <br />
</p>

 **Electromagnetic Wave. Source: [differencebetween](https://www.differencebetween.com/difference-between-wave-and-particle-nature-of-light/)**

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127785051-1a86c310-0e09-4f8b-be8e-99770dd0301e.png">
  <br />
</p>

 **EMI Spectrum. Source: [electrical4u](https://www.electrical4u.com/electromagnetic-interference/)**
   
# Geometric optics
[Back to the Top](https://github.com/mikeroyal/CNT-Guide#table-of-contents)

    - Reflection and refraction: Geometric optics
    - Mirrors: Geometric optics
    - Lenses

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784685-dfeb8063-7bf2-4420-9610-41c05a0b5d4d.png">
  <br />
</p>

 **Geometric Optics - Raytracing. Source: [sdsu-physics](https://sdsu-physics.org/physics180/physics180B/Topics/light/raytracing.html)**

  <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784688-5ecef6ad-3520-41fd-a206-e675ca3a1f5b.png">
  <br />
   </p>

**Geometric Optics - Reflection. Source: [sdsu-physics](https://sdsu-physics.org/physics180/physics180B/Topics/light/raytracing.html)**

# Quantum Physics
[Back to the Top](https://github.com/mikeroyal/CNT-Guide#table-of-contents)

   - Photons: Quantum Physics
   - Atoms and electrons: Quantum Physics
   - Quantum numbers and orbitals: Quantum Physics
   - Nuclei

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784717-deafb7b1-82a1-46f1-b64a-f1b2db0442f0.png">
  <br />
  </p>

  **Map of Quantum Physics. Source: [Domain of Science](https://www.youtube.com/watch?v=gAFAj3pzvAA)**

  <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784719-64e2e8dd-d050-421c-beb2-67d31cc7a4c4.png">
  <br />
  </p>

  **Quantum Physics Systems equations. Spurce: [pinterest](https://www.pinterest.com/pin/416723771749141466/)**
 
# MATLAB Development
[Back to the Top](https://github.com/mikeroyal/CNT-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/94306473-de809e80-ff27-11ea-924b-0a6947ae38bc.png">
  <br />
</p>

**[Carbon Nanotube Diameter and Metallicity Calculator for MATLAB](https://www.mathworks.com/matlabcentral/fileexchange/45694-carbon-nanotube-diameter-and-metallicity-calculator)**

## MATLAB Learning Resources

[MATLAB](https://www.mathworks.com/products/matlab.html) is a programming language that does numerical computing such as expressing matrix and array mathematics directly.

[MATLAB Documentation](https://www.mathworks.com/help/matlab/)

[Getting Started with MATLAB ](https://www.mathworks.com/help/matlab/getting-started-with-matlab.html)

[MATLAB and Simulink Training from MATLAB Academy](https://matlabacademy.mathworks.com)

[MathWorks Certification Program](https://www.mathworks.com/services/training/certification.html)

[MATLAB Online Courses from Udemy](https://www.udemy.com/topic/matlab/)

[MATLAB Online Courses from Coursera](https://www.coursera.org/courses?query=matlab)

[MATLAB Online Courses from edX](https://www.edx.org/learn/matlab)

[Building a MATLAB GUI](https://www.mathworks.com/discovery/matlab-gui.html)

[MATLAB Style Guidelines 2.0](https://www.mathworks.com/matlabcentral/fileexchange/46056-matlab-style-guidelines-2-0)

[Setting Up Git Source Control with MATLAB & Simulink](https://www.mathworks.com/help/matlab/matlab_prog/set-up-git-source-control.html)

[Pull, Push and Fetch Files with Git with MATLAB & Simulink](https://www.mathworks.com/help/matlab/matlab_prog/push-and-fetch-with-git.html)

[Create New Repository with MATLAB & Simulink](https://www.mathworks.com/help/matlab/matlab_prog/add-folder-to-source-control.html)

[PRMLT](http://prml.github.io/) is Matlab code for machine learning algorithms in the PRML book.

## MATLAB Tools

**[MATLAB and Simulink Services & Applications List](https://www.mathworks.com/products.html)**

[MATLAB in the Cloud](https://www.mathworks.com/solutions/cloud.html) is a service that allows you to run in cloud environments from [MathWorks Cloud](https://www.mathworks.com/solutions/cloud.html#browser) to [Public Clouds](https://www.mathworks.com/solutions/cloud.html#public-cloud) including [AWS](https://aws.amazon.com/) and [Azure](https://azure.microsoft.com/).

[MATLAB Online™](https://matlab.mathworks.com) is a service that allows to users to uilitize MATLAB and Simulink through a web browser such as Google Chrome.

[Simulink](https://www.mathworks.com/products/simulink.html) is a block diagram environment for Model-Based Design. It supports simulation, automatic code generation, and continuous testing of embedded systems.

[Simulink Online™](https://www.mathworks.com/products/simulink-online.html) is a service that provides access to Simulink through your web browser.

[MATLAB Drive™](https://www.mathworks.com/products/matlab-drive.html) is a service that gives you the ability to store, access, and work with your files from anywhere.

[MATLAB Parallel Server™](https://www.mathworks.com/products/matlab-parallel-server.html) is a tool that lets you scale MATLAB® programs and Simulink® simulations to clusters and clouds. You can prototype your programs and simulations on the desktop and then run them on clusters and clouds without recoding. MATLAB Parallel Server supports batch jobs, interactive parallel computations, and distributed computations with large matrices.

[MATLAB Schemer](https://github.com/scottclowe/matlab-schemer) is a MATLAB package makes it easy to change the color scheme (theme) of the MATLAB display and GUI.

[LRSLibrary](https://github.com/andrewssobral/lrslibrary) is a Low-Rank and Sparse Tools for Background Modeling and Subtraction in Videos. The library was designed for moving object detection in videos, but it can be also used for other computer vision and machine learning problems.

[Image Processing Toolbox™](https://www.mathworks.com/products/image.html) is a tool that provides a comprehensive set of reference-standard algorithms and workflow apps for image processing, analysis, visualization, and algorithm development. You can perform image segmentation, image enhancement, noise reduction, geometric transformations, image registration, and 3D image processing.

[Computer Vision Toolbox™](https://www.mathworks.com/products/computer-vision.html) is a tool that provides algorithms, functions, and apps for designing and testing computer vision, 3D vision, and video processing systems. You can perform object detection and tracking, as well as feature detection, extraction, and matching. You can automate calibration workflows for single, stereo, and fisheye cameras. For 3D vision, the toolbox supports visual and point cloud SLAM, stereo vision, structure from motion, and point cloud processing.

[Statistics and Machine Learning Toolbox™](https://www.mathworks.com/products/statistics.html) is a tool that provides functions and apps to describe, analyze, and model data. You can use descriptive statistics, visualizations, and clustering for exploratory data analysis; fit probability distributions to data; generate random numbers for Monte Carlo simulations, and perform hypothesis tests. Regression and classification algorithms let you draw inferences from data and build predictive models either interactively, using the Classification and Regression Learner apps, or programmatically, using AutoML.

[Lidar Toolbox™](https://www.mathworks.com/products/lidar.html) is a tool that provides algorithms, functions, and apps for designing, analyzing, and testing lidar processing systems. You can perform object detection and tracking, semantic segmentation, shape fitting, lidar registration, and obstacle detection. Lidar Toolbox supports lidar-camera cross calibration for workflows that combine computer vision and lidar processing.

[Mapping Toolbox™](https://www.mathworks.com/products/mapping.html) is a tool that provides algorithms and functions for transforming geographic data and creating map displays. You can visualize your data in a geographic context, build map displays from more than 60 map projections, and transform data from a variety of sources into a consistent geographic coordinate system.

[UAV Toolbox](https://www.mathworks.com/products/uav.html) is an application that provides tools and reference applications for designing, simulating, testing, and deploying unmanned aerial vehicle (UAV) and drone applications. You can design autonomous flight algorithms, UAV missions, and flight controllers. The Flight Log Analyzer app lets you interactively analyze 3D flight paths, telemetry information, and sensor readings from common flight log formats.

[Parallel Computing Toolbox™](https://www.mathworks.com/products/matlab-parallel-server.html) is a tool that lets you solve computationally and data-intensive problems using multicore processors, GPUs, and computer clusters. High-level constructs such as parallel for-loops, special array types, and parallelized numerical algorithms enable you to parallelize MATLAB® applications without CUDA or MPI programming. The toolbox lets you use parallel-enabled functions in MATLAB and other toolboxes. You can use the toolbox with Simulink® to run multiple simulations of a model in parallel. Programs and models can run in both interactive and batch modes.

[Partial Differential Equation Toolbox™](https://www.mathworks.com/products/pde.html) is a tool that provides functions for solving structural mechanics, heat transfer, and general partial differential equations (PDEs) using finite element analysis.

[ROS Toolbox](https://www.mathworks.com/products/ros.html) is a tool that provides an interface connecting MATLAB® and Simulink® with the Robot Operating System (ROS and ROS 2), enabling you to create a network of ROS nodes. The toolbox includes MATLAB functions and Simulink blocks to import, analyze, and play back ROS data recorded in rosbag files. You can also connect to a live ROS network to access ROS messages.

[Robotics Toolbox™](https://www.mathworks.com/products/robotics.html) provides a toolbox that brings robotics specific functionality(designing, simulating, and testing manipulators, mobile robots, and humanoid robots) to MATLAB, exploiting the native capabilities of MATLAB (linear algebra, portability, graphics). The toolbox also supports mobile robots with functions for robot motion models (bicycle), path planning algorithms (bug, distance transform, D*, PRM), kinodynamic planning (lattice, RRT), localization (EKF, particle filter), map building (EKF) and simultaneous localization and mapping (EKF), and a Simulink model a of non-holonomic vehicle. The Toolbox also including a detailed Simulink model for a quadrotor flying robot.

[Deep Learning Toolbox™](https://www.mathworks.com/products/deep-learning.html) is a tool that provides a framework for designing and implementing deep neural networks with algorithms, pretrained models, and apps. You can use convolutional neural networks (ConvNets, CNNs) and long short-term memory (LSTM) networks to perform classification and regression on image, time-series, and text data. You can build network architectures such as generative adversarial networks (GANs) and Siamese networks using automatic differentiation, custom training loops, and shared weights. With the Deep Network Designer app, you can design, analyze, and train networks graphically. It can exchange models with TensorFlow™ and PyTorch through the ONNX format and import models from TensorFlow-Keras and Caffe. The toolbox supports transfer learning with DarkNet-53, ResNet-50, NASNet, SqueezeNet and many other pretrained models.

[Reinforcement Learning Toolbox™](https://www.mathworks.com/products/reinforcement-learning.html) is a tool that provides an app, functions, and a Simulink® block for training policies using reinforcement learning algorithms, including DQN, PPO, SAC, and DDPG. You can use these policies to implement controllers and decision-making algorithms for complex applications such as resource allocation, robotics, and autonomous systems.

[Deep Learning HDL Toolbox™](https://www.mathworks.com/products/deep-learning-hdl.html) is a tool that provides functions and tools to prototype and implement deep learning networks on FPGAs and SoCs. It provides pre-built bitstreams for running a variety of deep learning networks on supported Xilinx® and Intel® FPGA and SoC devices. Profiling and estimation tools let you customize a deep learning network by exploring design, performance, and resource utilization tradeoffs.

[Model Predictive Control Toolbox™](https://www.mathworks.com/products/model-predictive-control.html) is a tool that provides functions, an app, and Simulink® blocks for designing and simulating controllers using linear and nonlinear model predictive control (MPC). The toolbox lets you specify plant and disturbance models, horizons, constraints, and weights. By running closed-loop simulations, you can evaluate controller performance.

[Vision HDL Toolbox™](https://www.mathworks.com/products/vision-hdl.html) is a tool that provides pixel-streaming algorithms for the design and implementation of vision systems on FPGAs and ASICs. It provides a design framework that supports a diverse set of interface types, frame sizes, and frame rates. The image processing, video, and computer vision algorithms in the toolbox use an architecture appropriate for HDL implementations.

[SoC Blockset™](https://www.mathworks.com/products/soc.html) is a tool that provides Simulink® blocks and visualization tools for modeling, simulating, and analyzing hardware and software architectures for ASICs, FPGAs, and systems on a chip (SoC). You can build your system architecture using memory models, bus models, and I/O models, and simulate the architecture together with the algorithms.

[Wireless HDL Toolbox™](https://www.mathworks.com/products/wireless-hdl.html) is a tool that provides pre-verified, hardware-ready Simulink® blocks and subsystems for developing 5G, LTE, and custom OFDM-based wireless communication applications. It includes reference applications, IP blocks, and gateways between frame and sample-based processing.

[ThingSpeak™](https://www.mathworks.com/products/thingspeak.html) is an IoT analytics service that allows you to aggregate, visualize, and analyze live data streams in the cloud. ThingSpeak provides instant visualizations of data posted by your devices to ThingSpeak. With the ability to execute MATLAB® code in ThingSpeak, you can perform online analysis and process data as it comes in. ThingSpeak is often used for prototyping and proof-of-concept IoT systems that require analytics.

[SEA-MAT](https://sea-mat.github.io/sea-mat/) is a collaborative effort to organize and distribute Matlab tools for the Oceanographic Community.

[Gramm](https://github.com/piermorel/gramm) is a complete data visualization toolbox for Matlab. It provides an easy to use and high-level interface to produce publication-quality plots of complex data with varied statistical visualizations. Gramm is inspired by R's ggplot2 library.

[hctsa](https://hctsa-users.gitbook.io/hctsa-manual) is a software package for running highly comparative time-series analysis using Matlab. 

[Plotly](https://plot.ly/matlab/) is a Graphing Library for MATLAB.

[YALMIP](https://yalmip.github.io/) is a MATLAB toolbox for optimization modeling.
  
# CUDA Development
[Back to the Top](https://github.com/mikeroyal/CNT-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/94306481-e17b8f00-ff27-11ea-832f-c85374acb3b1.png">
  <br />
</p>


<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/117718735-55a23480-b191-11eb-874d-e690d09cd490.png">
  <br />
</p>

**CUDA Toolkit. Source: [NVIDIA Developer CUDA](https://developer.nvidia.com/cuda-zone)**

## CUDA Learning Resources

[CUDA](https://developer.nvidia.com/cuda-zone) is a parallel computing platform and programming model developed by NVIDIA for general computing on graphical processing units (GPUs). With CUDA, developers are able to dramatically speed up computing applications by harnessing the power of GPUs. In GPU-accelerated applications, the sequential part of the workload runs on the CPU, which is optimized for single-threaded. The compute intensive portion of the application runs on thousands of GPU cores in parallel. When using CUDA, developers can program in popular languages such as C, C++, Fortran, Python and MATLAB.

[CUDA Toolkit Documentation](https://docs.nvidia.com/cuda/index.html)

[CUDA Quick Start Guide](https://docs.nvidia.com/cuda/cuda-quick-start-guide/index.html)

[CUDA on WSL](https://docs.nvidia.com/cuda/wsl-user-guide/index.html)

[CUDA GPU support for TensorFlow](https://www.tensorflow.org/install/gpu)

[NVIDIA Deep Learning cuDNN Documentation](https://docs.nvidia.com/deeplearning/cudnn/api/index.html)

[NVIDIA GPU Cloud Documentation](https://docs.nvidia.com/ngc/ngc-introduction/index.html)

[NVIDIA NGC](https://ngc.nvidia.com/) is a hub for GPU-optimized software for deep learning, machine learning, and high-performance computing (HPC) workloads.

[NVIDIA NGC Containers](https://www.nvidia.com/en-us/gpu-cloud/containers/) is a registry that provides researchers, data scientists, and developers with simple access to a comprehensive catalog of GPU-accelerated software for AI, machine learning and HPC. These containers take full advantage of NVIDIA GPUs on-premises and in the cloud.

## CUDA Tools Libraries, and Frameworks

[CUDA Toolkit](https://developer.nvidia.com/cuda-downloads) is a collection of tools & libraries that provide a development environment for creating high performance GPU-accelerated applications. The CUDA Toolkit allows you can develop, optimize, and deploy your applications on GPU-accelerated embedded systems, desktop workstations, enterprise data centers, cloud-based platforms and HPC supercomputers. The toolkit includes GPU-accelerated libraries, debugging and optimization tools, a C/C++ compiler, and a runtime library to build and deploy your application on major architectures including x86, Arm and POWER.

[NVIDIA cuDNN](https://developer.nvidia.com/cudnn) is a GPU-accelerated library of primitives for [deep neural networks](https://developer.nvidia.com/deep-learning). cuDNN provides highly tuned implementations for standard routines such as forward and backward convolution, pooling, normalization, and activation layers. cuDNN accelerates widely used deep learning frameworks, including [Caffe2](https://caffe2.ai/), [Chainer](https://chainer.org/), [Keras](https://keras.io/), [MATLAB](https://www.mathworks.com/solutions/deep-learning.html), [MxNet](https://mxnet.incubator.apache.org/), [PyTorch](https://pytorch.org/), and [TensorFlow](https://www.tensorflow.org/).

[CUDA-X HPC](https://www.nvidia.com/en-us/technologies/cuda-x/) is a collection of libraries, tools, compilers and APIs that help developers solve the world's most challenging problems. CUDA-X HPC includes highly tuned kernels essential for high-performance computing (HPC).

[NVIDIA Container Toolkit](https://github.com/NVIDIA/nvidia-docker) is a collection of tools & libraries that allows users to build and run GPU accelerated Docker containers. The toolkit includes a container runtime [library](https://github.com/NVIDIA/libnvidia-container) and utilities to automatically configure containers to leverage NVIDIA GPUs.

[Minkowski Engine](https://nvidia.github.io/MinkowskiEngine) is an auto-differentiation library for sparse tensors. It supports all standard neural network layers such as convolution, pooling, unpooling, and broadcasting operations for sparse tensors.

[CUTLASS](https://github.com/NVIDIA/cutlass) is a collection of CUDA C++ template abstractions for implementing high-performance matrix-multiplication (GEMM) at all levels and scales within CUDA. It incorporates strategies for hierarchical decomposition and data movement similar to those used to implement cuBLAS.

[CUB](https://github.com/NVIDIA/cub) is a cooperative primitives for CUDA C++ kernel authors.

[Tensorman](https://github.com/pop-os/tensorman) is a utility for easy management of Tensorflow containers by developed by [System76]( https://system76.com).Tensorman allows Tensorflow to operate in an isolated environment that is contained from the rest of the system. This virtual environment can operate independent of the base system, allowing you to use any version of Tensorflow on any version of a Linux distribution that supports the Docker runtime.

[Numba](https://github.com/numba/numba) is an open source, NumPy-aware optimizing compiler for Python sponsored by Anaconda, Inc. It uses the LLVM compiler project to generate machine code from Python syntax. Numba can compile a large subset of numerically-focused Python, including many NumPy functions. Additionally, Numba has support for automatic parallelization of loops, generation of GPU-accelerated code, and creation of ufuncs and C callbacks.

[Chainer](https://chainer.org/) is a Python-based deep learning framework aiming at flexibility. It provides automatic differentiation APIs based on the define-by-run approach (dynamic computational graphs) as well as object-oriented high-level APIs to build and train neural networks. It also supports CUDA/cuDNN using [CuPy](https://github.com/cupy/cupy) for high performance training and inference.

[CuPy](https://cupy.dev/) is an implementation of NumPy-compatible multi-dimensional array on CUDA. CuPy consists of the core multi-dimensional array class, cupy.ndarray, and many functions on it. It supports a subset of numpy.ndarray interface.

[CatBoost](https://catboost.ai/) is a fast, scalable, high performance [Gradient Boosting](https://en.wikipedia.org/wiki/Gradient_boosting) on Decision Trees library, used for ranking, classification, regression and other machine learning tasks for Python, R, Java, C++. Supports computation on CPU and GPU.

[cuDF](https://rapids.ai/) is a GPU DataFrame library for loading, joining, aggregating, filtering, and otherwise manipulating data. cuDF provides a pandas-like API that will be familiar to data engineers & data scientists, so they can use it to easily accelerate their workflows without going into the details of CUDA programming.

[cuML](https://github.com/rapidsai/cuml) is a suite of libraries that implement machine learning algorithms and mathematical primitives functions that share compatible APIs with other RAPIDS projects. cuML enables data scientists, researchers, and software engineers to run traditional tabular ML tasks on GPUs without going into the details of CUDA programming. In most cases, cuML's Python API matches the API from scikit-learn.

[ArrayFire](https://arrayfire.com/) is a general-purpose library that simplifies the process of developing software that targets parallel and massively-parallel architectures including CPUs, GPUs, and other hardware acceleration devices.

[Thrust](https://github.com/NVIDIA/thrust) is a C++ parallel programming library which resembles the C++ Standard Library. Thrust's high-level interface greatly enhances programmer productivity while enabling performance portability between GPUs and multicore CPUs.

[AresDB](https://eng.uber.com/aresdb/) is a GPU-powered real-time analytics storage and query engine. It features low query latency, high data freshness and highly efficient in-memory and on disk storage management.

[Arraymancer](https://mratsim.github.io/Arraymancer/) is a tensor (N-dimensional array) project in Nim. The main focus is providing a fast and ergonomic CPU, Cuda and OpenCL ndarray library on which to build a scientific computing ecosystem.

[Kintinuous](https://github.com/mp3guy/Kintinuous) is a real-time dense visual SLAM system capable of producing high quality globally consistent point and mesh reconstructions over hundreds of metres in real-time with only a low-cost commodity RGB-D sensor.

[GraphVite](https://graphvite.io/) is a general graph embedding engine, dedicated to high-speed and large-scale embedding learning in various applications.
   

# Bioinformatics
[Back to the Top](https://github.com/mikeroyal/CNT-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/126912438-49cc660e-90c5-4cbc-828b-10e807b99767.png">
  <br />
</p>

## Bioinformatics Learning Resources

[Bioinformatics](https://www.genome.gov/genetics-glossary/Bioinformatics) is a field of computational science that has to do with the analysis of sequences of biological molecules. This usually refers to genes, DNA, RNA, or protein, and is particularly useful in comparing genes and other sequences in proteins and other sequences within an organism or between organisms, looking at evolutionary relationships between organisms, and using the patterns that exist across DNA and protein sequences to figure out what their function is.

[European Bioinformatics Institute](https://www.ebi.ac.uk/)

[National Center for Biotechnology Information](https://www.ncbi.nlm.nih.gov)

[Online Courses in Bioinformatics |ISCB - International Society for Computational Biology](https://www.iscb.org/cms_addon/online_courses/index.php)

[Bioinformatics | Coursera](https://www.coursera.org/specializations/bioinformatics)

[Top Bioinformatics Courses | Udemy](https://www.udemy.com/topic/Bioinformatics/)

[Biometrics Courses | Udemy](https://www.udemy.com/course/biometrics/)

[Learn Bioinformatics with Online Courses and Lessons | edX](https://www.edx.org/learn/bioinformatics)

[Bioinformatics Graduate Certificate | Harvard Extension School](https://extension.harvard.edu/academics/programs/bioinformatics-graduate-certificate/)

[Bioinformatics and Biostatistics | UC San Diego Extension](https://extension.ucsd.edu/courses-and-programs/bioinformatics-and-biostatistics)

[Bioinformatics and Proteomics - Free Online Course Materials | MIT](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-092-bioinformatics-and-proteomics-january-iap-2005/)

[Introduction to Biometrics course - Biometrics Institute](https://www.biometricsinstitute.org/event/introduction-to-biometrics-short-course/)

## Bioinformatics Tools, Libraries, and Frameworks

[Bioconductor](https://bioconductor.org/) is an open source project that provides tools for the analysis and comprehension of high-throughput genomic data. Bioconductor uses the [R statistical programming language](https://www.r-project.org/about.html), and is open source and open development. It has two releases each year, and an active user community. Bioconductor is also available as an [AMI (Amazon Machine Image)](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html) and [Docker images](https://docs.docker.com/engine/reference/commandline/images/).

[Bioconda](https://bioconda.github.io) is a channel for the conda package manager specializing in bioinformatics software. It has a repository of packages containing over 7000 bioinformatics packages ready to use with conda install.

[UniProt](https://www.uniprot.org/) is a freely accessible database that provide users with a comprehensive, high-quality and freely accessible set of protein sequences annotated with functional information.

[Bowtie 2](https://bio.tools/bowtie2#!) is an ultrafast and memory-efficient tool for aligning sequencing reads to long reference sequences. It is particularly good at aligning reads of about 50 up to 100s or 1,000s of characters, and particularly good at aligning to relatively long (mammalian) genomes.

[Biopython](https://biopython.org/) is a set of freely available tools for biological computation written in Python by an international team of developers. It is a distributed collaborative effort to develop Python libraries and applications which address the needs of current and future work in bioinformatics.

[BioRuby](https://bioruby.open-bio.org/) is a toolkit that has components for sequence analysis, pathway analysis, protein modelling and phylogenetic analysis; it supports many widely used data formats and provides easy access to databases, external programs and public web services, including BLAST, KEGG, GenBank, MEDLINE and GO.

[BioJava](https://biojava.org/) is a toolkit that provides an API to maintain local installations of the PDB, load and manipulate structures, perform standard analysis such as sequence and structure alignments and visualize them in 3D.

[BioPHP](https://biophp.org/) is an open source project that provides a collection of open source PHP code, with classes for DNA and protein sequence analysis, alignment, database parsing, and other bioinformatics tools.

[Avogadro](https://avogadro.cc/) is an advanced molecule editor and visualizer designed for cross-platform use in computational chemistry, molecular modeling, bioinformatics, materials science, and related areas. It offers flexible high quality rendering and a powerful plugin architecture.

[Ascalaph Designer](https://www.biomolecular-modeling.com/Ascalaph/Ascalaph_Designer.html) is a program for molecular dynamic simulations. Under a single graphical environment are represented as their own implementation of molecular dynamics as well as the methods of classical and quantum mechanics of popular programs.

[Anduril](https://www.anduril.org/site/) is a workflow platform for analyzing large data sets. Anduril provides facilities for analyzing high-thoughput data in biomedical research, and the platform is fully extensible by third parties. Ready-made tools support data visualization, DNA/RNA/ChIP-sequencing, DNA/RNA microarrays, cytometry and image analysis.

[Galaxy](https://melbournebioinformatics.github.io/MelBioInf_docs/tutorials/galaxy_101/galaxy_101/) is an open source, web-based platform for accessible, reproducible, and transparent computational biomedical research. It allows users without programming experience to easily specify parameters and run individual tools as well as larger workflows. It also captures run information so that any user can repeat and understand a complete computational analysis.

[PathVisio](https://pathvisio.github.io/) is a free open-source pathway analysis and drawing software which allows drawing, editing, and analyzing biological pathways. It is developed in Java and can be extended with plugins.

[Orange](https://orangedatamining.com/) is a powerful data mining and machine learning toolkit that performs data analysis and visualization.

[Basic Local Alignment Search Tool](https://blast.ncbi.nlm.nih.gov/Blast.cgi) is a tool that finds regions of similarity between biological sequences. The program compares nucleotide or protein sequences to sequence databases and calculates the statistical significance.

[OSIRIS](https://www.ncbi.nlm.nih.gov/osiris/) is public-domain, free, and open source STR analysis software designed for clinical, forensic, and research use, and has been validated for use as an expert system for single-source samples.

[NCBI BioSystems](https://www.ncbi.nlm.nih.gov/biosystems/) is a  Database that provides integrated access to biological systems and their component genes, proteins, and small molecules, as well as literature describing those biosystems and other related data throughout Entrez.

## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/CNT-Guide/pulls).


## License

[Back to the Top](https://github.com/mikeroyal/CNT-Guide#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/).
