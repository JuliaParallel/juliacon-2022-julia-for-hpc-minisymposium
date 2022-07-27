# Julia for HPC Minisymposium at JuliaCon 2022

[![YouTube](https://img.shields.io/youtube/views/fog1x9rs71Q?style=social)](https://www.youtube.com/watch?v=fog1x9rs71Q)


This repository provides information and material regarding the [Julia for High-Performance Computing](https://live.juliacon.org/talk/LUWYRJ) minisymposium at [JuliaCon 2022](https://juliacon.org/2022/), which took place on 27th July 2022, 4pm - 6:30pm UTC.

**Organizers:** [William F Godoy](https://github.com/williamfgc), [Michael Schlottke-Lakemper](https://github.com/sloede), [Carsten Bauer](https://github.com/carstenbauer), [Hendrik Ranocha](https://github.com/ranocha), [Johannes Blaschke](https://github.com/jblaschke), [Jeffrey Vetter](https://www.ornl.gov/staff-profile/jeffrey-s-vetter)

Below you will find information on the [presentations](#presentations), the [abstract](#abstract) and [description](#description) of the minisymposium, and information on the [sharing and redistributing](#license) the slides.

## Presentations
In the following, you can find the list of talks with PDFs (if shared), timestamped YouTube links, and links to additional resources:
* [William F Godoy](https://github.com/williamfgc) & [Michael Schlottke-Lakemper](https://github.com/sloede): **Julia for High-Performance Computing** ([PDF](presentations/William_F_Godoy-Julia_for_High-Performance_Computing.pdf), [YouTube](https://youtu.be/fog1x9rs71Q?t=80))
* [Samuel Omlin](https://github.com/omlins): **Scalability of the Julia/GPU stack** ([PDF](presentations/Samuel_Omlin-Scalability_of_the_Julia_GPU_stack.pdf), [YouTube](https://youtu.be/fog1x9rs71Q?t=407))
  * [ImplicitGlobalGrid.jl](https://github.com/eth-cscs/ImplicitGlobalGrid.jl)
* [Simon Byrne](https://github.com/simonbyrne): **MPI.jl** ([PDF](presentations/Simon_Byrne-MPI.jl.pdf), [YouTube](https://youtu.be/fog1x9rs71Q?t=959))
  * [MPI.jl](https://github.com/JuliaParallel/MPI.jl)
* [Tim Besard](https://github.com/maleadt): **CUDA.jl: Update on new features and developments** ([PDF](presentations/Tim_Besard-CUDA.jl-Update_on_new_features_and_developments.pdf), [YouTube](https://youtu.be/fog1x9rs71Q?t=1967))
  * [CUDA.jl](https://github.com/JuliaGPU/CUDA.jl)
* [Julian Samaroo](https://github.com/jpsamaroo): **AMDGPU.jl: State of development and roadmap to the future** ([YouTube](https://youtu.be/fog1x9rs71Q?t=2568))
  * [AMDGPU.jl](https://github.com/JuliaGPU/AMDGPU.jl)
* [Albert Reuther](https://github.com/areuther): **Supporting Julia Users at MIT LL Supercomputing Center** ([PDF](presentations/Albert_Reuther-Supporting_Julia_Users_at_MIT_LL_Supercomputing_Center.pdf), [YouTube](https://youtu.be/fog1x9rs71Q?t=3600))
  * [MIT Lincoln Laboratory](https://www.ll.mit.edu/)
* [Johannes Blaschke](https://github.com/jblaschke): **Supporting Julia users on NERSC’s “Cori” and “Perlmutter” systems** ([PDF](presentations/Johannes_Blaschke-Supporting_Julia_users_on_NERSCs_Cori_and_Perlmutter_systems.pdf), [YouTube](https://youtu.be/fog1x9rs71Q?t=4178))
  * [NERSC](https://www.nersc.gov/)
* [Michael Schlottke-Lakemper](https://github.com/sloede): **Running Julia code in parallel with MPI: Lessons learned** ([PDF](presentations/Michael_Schlottke-Lakemper-Running_Julia_code_in_parallel_with_MPI_Lessons_learned.pdf), [YouTube](https://youtu.be/fog1x9rs71Q?t=5172))
  * [Trixi.jl](https://github.com/trixi-framework/Trixi.jl)
* [Ludovic Räss](https://github.com/luraess): **Julia and GPU-HPC for geoscience applications** ([PDF](presentations/Ludovic_Raess-Julia_and_GPU-HPC_for_geoscience_applications.pdf), [YouTube](https://youtu.be/fog1x9rs71Q?t=5926))
  * [GPU4GEO](https://ptsolvers.github.io/GPU4GEO/)

## Abstract
The "Julia for HPC" minisymposium aims to gather current and prospective Julia practitioners in the field of high-performance computing (HPC) from multidisciplinary applications. We invite participation from industry, academia, and government institutions interested in Julia’s capabilities for supercomputing. The goal is to provide a venue for Julia enthusiasts to share best practices, discuss current limitations, and identify future developments in the scientific HPC community.

## Description
As we approach the era of exascale computing, scalable performance and fast development on extremely heterogeneous hardware have become ever more important aspects for high-performance computing (HPC). Scientists and developers with interest in Julia for HPC need to know how to leverage the capabilities of the  language and ecosystem to address these issues and which tools and best practices can help them to achieve their performance goals.

What do we mean by HPC? While HPC can be mainly associated with running large-scale physical simulations like computational fluid dynamics, molecular dynamics, high-energy physics, climate models etc., we use a more inclusive definition beyond the scope of computational science and engineering. More recently, rapid prototyping with high-productivity languages like Julia, machine learning training, data management, computer science research, research software engineering, large scale data visualization and in-situ analysis have expanded the scope for defining HPC. For us, the core of HPC is not to run simple test problems faster but involves everything that enables solving challenging problems in simulation or data science, on heterogeneous hardware platforms, from a high-end workstation to the world's largest supercomputers powered with different vendors CPUs and accelerators (e.g. GPUs).

In this two-hour minisymposium, we will give an overview of the current state of affairs of Julia for HPC in a series of eight 10-minute talks. The focus of these overview talks is to introduce and motivate the audience by highlighting aspects making the Julia language beneficial for scientific HPC workflows such as scalable deployments, compute accelerator support, user support, and HPC applications. In addition, we have reserved some time for participants to interact, discuss and share the current landscape of their investments in Julia HPC, while encouraging networking with their colleagues over topics of common interest.

The minisymposium schedule, with confirmed speakers and topics, is as follows:

* 0:00: *William F Godoy (ORNL) & Michael Schlottke-Lakemper (U Stuttgart/HLRS):* **Julia for High-Performance Computing**
* 0:05: *Samuel Omlin (CSCS):* **Scalability of the Julia/GPU stack**
* 0:15: *Simon Byrne (Caltech/CliMA):* **MPI.jl**
* 0:25: Q&A
* 0:30: *Tim Besard (Julia Computing):* **CUDA.jl: Update on new features and developments**
* 0:40: *Julian Samaroo (MIT):* **AMDGPU.jl: State of development and roadmap to the future**
* 0:50: Q&A
* 1:00: *Albert Reuther (MIT):* **Supporting Julia Users at MIT LL Supercomputing Center**
* 1:10: *Johannes Blaschke (NERSC):* **Supporting Julia users on NERSC’s “Cori” and “Perlmutter” systems**
* 1:20: Q&A
* 1:25: *Michael Schlottke-Lakemper (U Stuttgart/HLRS):* **Running Julia code in parallel with MPI: Lessons learned**
* 1:35: *Ludovic Räss (ETH Zurich):* **Julia and GPU-HPC for geoscience applications**
* 1:45: Q&A, Discussion & Wrap up

The overall goal of the minisymposium is to identify and summarize current practices, limitations, and future developments as Julia experiences growth and positions itself in the larger HPC community due to its appeal in scientific computing. It also exemplifies the strength of the existing Julia HPC community that collaboratively prepared this event. We are an international, multi institutional, and multi disciplinary group interested in advancing Julia for HPC applications in our academic and national laboratory environments. We would like to welcome new people from multiple backgrounds sharing our interest and bring them together in this minisymposium.

In this spirit, the minisymposium will serve as a starting point for further Julia HPC activities at JuliaCon 2022. During the main conference, **a Birds of Feather session** will provide an opportunity to bring together the community for more discussions and to allow new HPC users to join the conversation. Furthermore, a number of talks will be dedicated to topics relevant for HPC developers and users alike.

## License
The copyright of the individual presentations remains with the respective authors, unless noted otherwise. In case you would like to use or redistribute some of their slides, please first get in touch with the corresponding author.