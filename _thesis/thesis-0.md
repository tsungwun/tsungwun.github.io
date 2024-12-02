---
title: "Research Contributions"
excerpt: "In the summer of 2023, I successfully defended my thesis titled **Development of 3D Reconstruction and Navigation for Mobile Robots**. As the title suggests, my research integrates two key components: 3D reconstruction and autonomous mobile robots (AMRs). This work not only forms the basis of my [master’s thesis](http://tsungwun.github.io/files/thesis_abstract.pdf), which was published at National Taiwan University, but also encompasses **three** distinct paper drafts, each exploring different aspects of my research. <br><br> After reading the [summary](https://tsungwun.github.io/thesis/thesis-0/) of the thesis and my contributions, you can visualize my experiments through the following videos."
collection: thesis
---

My [master’s thesis](http://tsungwun.github.io/files/thesis_abstract.pdf) can be categorized into three parts (3 first-authored papers), from 3D reconstruction to 2D and 3D navigation of AMRs. 

Publications
======
* Title: **Vision-based Autonomous Robot Navigation in 3D Dynamic Environments**
    * Authors: Tsung-Wun Wang, Han-Pang Huang, and Yu-Lin Zhao
    * Status: **Best Paper Award** (November 2024) awarded by the 41st National Conference on Mechanical Engineering of CSME, Kaohsiung, Taiwan. 
    * Description: \
      _This paper presents an innovative 3D vision-based autonomous navigation system for wheeled mobile robots equipped with an RGB-D camera. The system integrates Simultaneous Localization and Mapping (SLAM), motion planning, and obstacle avoidance in both static and dynamic environments. A real-time pipeline is introduced to construct sparse and dense maps for precise relocalization and path planning. The approach utilizes navigation meshes (NavMeshes) derived from 3D reconstruction and orchestrates A* planning for real-time navigation towards waypoints. The system dynamically detects obstacles using a "U-map" derived from depth data and regenerates NavMesh for efficient obstacle avoidance. This paradigm extends beyond 2D space and adapts to diverse terrains, such as uneven surfaces and ramps. The approach achieves real-time operational standards, presenting a holistic solution to 3D vision-guided robotic navigation._
 
* Title: <b>Search-based Path Replanning for Autonomous Navigation and Obstacle Avoidance</b>
    * Authors: Tsung-Wun Wang, Han-Pang Huang, Yu-Lin Zhao, and Cheng-Chi Lee
    * Status: **Best Student Paper Award** (November 2024) awarded by the 21st International Conference on Automation Technology, Taipei, Taiwan.
    * Description: \
      _This paper explores search-based path replanning algorithms for autonomous 2D navigation and obstacle avoidance. It reviews various pathfinding techniques including A*, AO*, WAO*, DAO*, D* Lite, and DDAO*, analyzing their performance in dynamic environments. Enhancements to the DAO* and DDAO* algorithms are introduced to improve real-time performance with different update rates for real-world applications. The study incorporates dynamic environments and obstacle avoidance strategies, culminating in the DDAO* algorithm, which efficiently handles new obstacles. Through laboratory experiments, insights into algorithmic behavior and trade-offs between path length and computation time are explored, providing a foundation for future work in more complex terrains._

* Title: <b>Improved Real-Time Dense ORB SLAM with GPU Implementation</b>
    * Authors: Tsung-Wun Wang, Han-Pang Huang, Chiou-Shann Fuh
    * Status: Accepted (August 2023) by the 36th IPPR Conference on Computer Vision, Graphics, and Image Processing, Kinmen, Taiwan.
    * Description: \
      _This paper presents a GPU-accelerated improvement to the real-time RGB-D SLAM system, utilizing parallel computing to enhance depth measurement quality with a bilateral filter. Experimental results demonstrate accurate camera pose estimation and dense surfel-based mapping. The system operates efficiently in resource-constrained environments, offering real-time performance and advanced 3D reconstruction for RGB-D SLAM applications._

<br>

In addition to the aforementioned research, I have explored topics such as **GMapping** and **NavMesh** for robotics:

* Conducted 2D LiDAR SLAM and presented an enhanced GMapping approach that addresses **loop-closing** issues.
* Developed various pathfinding algorithms based on navigation meshes (NavMesh) and implemented path **replanning** mechanisms to improve autonomous navigation.

<br>

Additionally, when I was an undergraduate student, I also published a first-authored conference paper titled: \
"**Robotic Arm with A Parallel Gripper Applying Mask R-CNN for Garbage Classification**"

If you are interested in discussing any of these topics or my research in more detail, feel free to contact me directly via email.
