---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S./Ph.D. in Electrical and Computer Engineering, University of California San Diego (UCSD), 2019 to 2024 (expected)
* B.S. in Electrical Engineering, National Taiwan University (NTU), 2013 to 2017

Work experience
======
* Research Assistant from July 2017 to June 2019 @ Center of Artificial Intelligence and Advanced Robotics (AiROBO), National Taiwan University
  1. Improved a self-conscious-based decision model for Pepper
  2. Developed an intelligent secretary system for RoBoHoN  ([GitHub](https://github.com/SarahChiu/RoBoHoN_Remote))

* Part-Time Student Intern from July 2016 to December 2016 @ Mechanical and Mechatronics Systems Research Laboratories, ITRI, Taiwan
  1. Developed virtual reality functions on Oculus
  2. Implemented a simultaneous localization and mapping (SLAM) algorithm in Gazebo
  
Publications
======
  Please check out the publication list [here]({{ site.data.navigation.main[0].url }}). 

Research Projects
====== 
* Motion Planning for Autonomous Suturing
  * Advised by Professor Michael Yip @ ARCLab, UCSD
  * Developing and testing an autonomous suturing framework, including perception, planning, and control 

* Suture Needle 6D Pose Tracking ([Paper](https://arxiv.org/abs/2109.12722), [Video](https://www.youtube.com/watch?v=qpp2ucKn76Q))
  * Advised by Professor Michael Yip @ ARCLab, UCSD
  * Tracked the 6D pose of suture needles with particle filter under different scenarios, including ex vivo environments.
  * Proposed three observation models based on the circular geometry of suture needles, and derived the noise variance for one of the models.
  * Experimental results demonstrated that our proposed method outperforms previous ones and is robust under occlusion and complex backgrounds.

* Bimanual Regrasping for Suture Needles ([Paper](https://ieeexplore.ieee.org/abstract/document/9561673), [Video](https://www.youtube.com/watch?v=da9ir9lnwSA))
  * Advised by Professor Michael Yip @ ARCLab, UCSD
  * Proposed ego-centric state/action spaces and mixed exploration strategy for reinforcement learning (RL) to learn a generalizable policy for suture needle regrasping
  * Achieved 97% success rate in simulation and 73.3%/90.5% success rate in real-robot experiments

* Parallelized Reverse Curriculum Generation ([Paper](https://arxiv.org/abs/2108.02128))
  * Advised by Professor Hung-Yi Lee and Professor Li-Chen Fu @ AiROBO, NTU
  * Improved reverse curriculum generation by training multiple actor-critic (AC) pairs and swapping their critics periodically
  * Achieved better convergence and generality, and the proposed method is applied to several robotic manipulation tasks

* Robots Learn Hand-Ear Coordination ([Report](https://drive.google.com/file/d/1UCnayxogjIVJYwlmIQxqyihN3EtpR_Zs/view))
  * Advised by Professor Li-Chen Fu @ EE Department, NTU
  * Implemented Deep Q-network (DQN) and prioritized experience replay for a robot to react to musical tempo from noisy music
  * Achieved 97% accuracy of end-point detection by dropout and L2 regularization

* Avatar: Robot Imitates Human Motions in Real Time using Kinect 2 ([Report 1](https://drive.google.com/file/d/0B6A-IUXDGma0bTBFRkxkZWFOelE/view?resourcekey=0-iZUkauwZNbNibczOwZlZZg), [Report 2](https://drive.google.com/file/d/0B6A-IUXDGma0OWt0V0Q1dUNFaDA/view?resourcekey=0--w-FlJje_soY-C9S2BPTBQ))
  * Advised by Professor Li-Chen Fu @ EE Department, NTU
  * Mapped the skeleton data, extracted from Kinect 2, and robot postures by (1) direct joint mapping and (2) supervised learning

Term Projects
======
* Automatic Piano Accompaniment Robot ([Report](https://drive.google.com/file/d/0B6A-IUXDGma0M25MdnQ1VGttWHc/view?resourcekey=0-cbsItrJelHF49CwEKhTqyw), [Video](https://drive.google.com/file/d/0B6A-IUXDGma0c1B3YVBsQnN5LXM/view?resourcekey=0-gBMFOvC4RXL5FVrLA0ETNA))
  * Advised by Professor Li-Chen Fu @ CSIE Department, NTU
  * Used LEGO EV3 to build a robot, and implemented retrieval by singing and humming as well as trajectory planning in Matlab

Honors and Awards
======
* 2022 Grace Hopper Celebration Student Scholarship
* 2022 Inclusion@RSS Program Fellowship
* 2016 The 24th Conference on Automation Technology College Student Paper Contest, Second Place
* 2016 Innovate Asia Design Contest Outstanding Achievement Award

Academic Service
======
* Program Committee, ICLR 2022 Workshop on Generalizable Policy Learning in the Physical World
* Reviewer, IEEE International Conference on Robotics and Automation (ICRA)
* Reviewer, IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)

Skills
======
* **Programming Languages**: Python, C++, Matlab, Android Development, Java, System Verilog
* **API and Toolkits**: Tensorflow, PyTorch, CoppeliaSim, Gazebo, PyBullet, OpenCV, OpenPose, Oculus, LaTex
* **Operating System**: Linux, ROS, NAOqi, Windows
* **Languages**: Mandarin (native), English (proficient), Japanese (basic)
