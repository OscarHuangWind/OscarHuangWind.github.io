---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# About Me
Ciao! I am Wenhui (Oscar) Huang, a Ph.D. candidate and Research Associate in the [Automated Driving and Human-Machine System Lab](https://lvchen.wixsite.com/automan) at Nanyang Technological University (NTU), advised by Prof. Chen Lv. This March, I am excited to join the [Harvard Computational Robotics Group](https://computationalrobotics.seas.harvard.edu/) as a visiting fellow, hosted by Prof. Hank Yang. Previously, I had the pleasure of collaborating with Prof. Francesco Braghin during my time at the [i.Drive Lab](https://www.idrive.polimi.it/).

📌 I will graduate in Summer 2025 and am actively seeking a postdoctoral researcher position! Please reach out to me if you think I might be a good fit. 📌

# Research Interests

| **Research Field**       |**Research Application**            |
|--------------------------|------------------------------------|
| Reinforcement Learning   | Intelligent Tranporatation Systems |
| Continual Learning       | Robotics                           |
| VLM and VLA              | Autonomous Vehicles                |
| Human-in-the-Loop AI     | Visual Navigation                  |


<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *Apr. 2025*: &nbsp;🏅🏅 I am honored to be recognized as a [featured PhD candidate](https://ieeexplore.ieee.org/document/10938667) in ITS field by IEEE Intelligent Transportation Systems Society (ITSS)! 
- *Mar. 2025*: &nbsp;🌱🌱 Our paper on deep imitative reinforcement learning-based decision-making for autonomous driving has been accepted by Transportation Research Part C! 
- *Jan. 2025*: &nbsp;☃️☃️ Our paper on integrated hybrid prediction and planning for autonomous driving has been accepted by TPAMI! 
- *Dec. 2024*: &nbsp;🎄🎄 Our work on VLM-based closed-loop autonomous driving is now available on arXiv! [WiseAD](https://arxiv.org/abs/2412.09951) 
- *Jul. 2024*: &nbsp;🏖️🏖️ Our ITSC 2025 invited session on [Learning-empowered Intelligent Transportation Systems: Foundation Vehicles and Coordination Technique](https://oscarhuangwind.github.io/Foundation_Vehicle/) received 11 paper submissions, and 10 papers were accepted. Congratulations to all the authors! Looking forward to seeing you in Edmonton, Canada!
- *Jun. 2024*: &nbsp;🏖️🏖️ Our paper on safety human-in-the-loop RL for autonomous driving has been accepted by T-ITS! 
- *Jun. 2024*: &nbsp;🏆🏆 Our team secured first place in the Waymo Open Dataset Occupancy Flow Challenge and second place in the Sim Agents Challenge! Check out our technical reports on the [Waymo challenge website](https://waymo.com/open/challenges/) and [CVPR 2024 Workshop on Autonomous Driving](https://cvpr2024.wad.vision/).
- *May. 2024*: &nbsp;🌱🌱 Visited [Gran Turismo Sophy team](https://www.gran-turismo.com/us/gran-turismo-sophy/) at Sony AI, Japan, and gave a talk on RL for autonomous racing!
- *Apr. 2024*: &nbsp;🌱🌱 Our paper on robust RL for autonomous driving has been accepted by Transportation Research Part C: Emerging Technologies! 
- *Jan. 2024*: &nbsp;☃️☃️ Our paper on uncertainty-aware RL with human guidance for autonomous driving has been accepted by ICRA! See you in Yokohama, Japan!
- *Nov. 2023*: &nbsp;☃️☃️ Our paper on robust RL for decision-making has been accepted by Engineering!
- *Oct. 2023*: &nbsp;🍁🍁 Our paper on learning from demonstration for RL-based eco-driving has been accepted by Energy!
- *Sep. 2023*: &nbsp;🍁🍁 Our paper on sampling efficient preference-guided DQN (PGDQN) algorithm has been accepted by TNNLS!
- *Sep. 2023*: &nbsp;🍁🍁 Our paper on goal-oriented transformer-based autonomous navigation has been accepted by T-ITS!
- *Sep. 2023*: &nbsp;🏅🏅 We won the best paper runner-up award in ITSC 2023!
- *Dec. 2022*: &nbsp;🥈🥈 Our team secured second place at [Intelligent Algorithm Final of Alibaba Global Future Vehicle Challenge](https://tianchi.aliyun.com/competition/entrance/531996)!

# 📝 Publications 

## Highlights

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv'24</div><img src='images/WiseAD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[WiseAD: Knowledge Augmented End-to-End Autonomous Driving with Vision-Language Model](https://arxiv.org/abs/2412.09951) [![](https://img.shields.io/github/stars/wyddmw/WiseAD?style=social&label=Code Stars)](https://github.com/wyddmw/WiseAD)

Songyan Zhang<sup>1</sup>, **Wenhui Huang<sup>1</sup>**, Zihui Gao, Hao Chen, Chen Lv <br>
<sup>1</sup>Equal Contributions

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Hpatee0AAAAJ&citation_for_view=Hpatee0AAAAJ:IWHjjKOFINEC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- we investigate the **effects of the depth and breadth of fundamental driving knowledge** on **closed-loop driving performance** and introduce WiseAD, a specialized VLM tailored for end-to-end autonomous driving capable of driving reasoning, action justification, object recognition, risk analysis, driving suggestions, and trajectory planning across diverse scenarios. 
</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-ITS'24</div><img src='images/SafeHiLRL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">T-ITS'24</div>
      <img src='images/SafeHIL.gif' alt="动态演示" width="100%" style="height: auto; object-fit: contain;">>
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[Safety-aware human-in-the-loop reinforcement learning with shared control for autonomous driving](https://ieeexplore.ieee.org/abstract/document/10596046) [![](https://img.shields.io/github/stars/OscarHuangWind/Safe-Human-in-the-Loop-RL?style=social&label=Code Stars)](https://github.com/OscarHuangWind/Safe-Human-in-the-Loop-RL)

**Wenhui Huang**, Haochen Liu, Zhiyu Huang, Chen Lv 

[**Project**](https://github.com/OscarHuangWind/Safe-Human-in-the-Loop-RL) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- we propose a **safe human-in-the-loop RL** (SafeHiL-RL), combined with curriculum guidance, to enable safe and efficient decision-making policies for autonomous vehicles.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA'24</div><img src='images/RealWorld Test.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Uncertainty-aware Reinforcement Learning for Autonomous Driving with Multimodal Digital Driver Guidance](https://ieeexplore.ieee.org/abstract/document/10610272) [![](https://img.shields.io/github/stars/OscarHuangWind/Learning-from-Intervention?style=social&label=Code Stars)](https://github.com/OscarHuangWind/Learning-from-Intervention)

**Wenhui Huang**, Zitong Shan, Shanhe Lou, Chen Lv

Video: [Youtube](https://www.youtube.com/watch?v=P4XWiXknpDA) \| [BiliBili](https://www.bilibili.com/video/BV1TC4y1o75U/?vd_source=18187e5a3c867d8cb394aa035fc03c49)

[**Project**](https://oscarhuangwind.github.io/Learning-from-Intervention/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose an **uncertainty-aware RL** (UnaRL) framework, incorporating multimodal human guidance, to achieve robust decision-making policies for autonomous vehicles.
</div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">T-ITS'23</div>
      <img src='images/GTRL.gif' alt="动态演示" width="100%" style="height: auto; object-fit: contain;">>
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[Goal-guided Transformer-enabled Reinforcement Learning for Efficient Autonomous Navigation](https://github.com/OscarHuangWind/DRL-Transformer-SimtoReal-Navigation) [![](https://img.shields.io/github/stars/OscarHuangWind/DRL-Transformer-SimtoReal-Navigation?style=social&label=Code Stars)](https://github.com/OscarHuangWind/DRL-Transformer-SimtoReal-Navigation)

**Wenhui Huang**, Yanxin Zhou, Xiangkun He, Chen Lv 

Sim to Real Video: [Youtube](https://www.youtube.com/watch?v=P4XWiXknpDA&feature=youtu.be) \| [BiliBili](https://www.bilibili.com/video/BV1Mj41147Md/?vd_source=18187e5a3c867d8cb394aa035fc03c49)

[**Project**](https://github.com/OscarHuangWind/DRL-Transformer-SimtoReal-Navigation) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a goal-oriented transformer-based RL algorithm to realize efficient and adaptative visual navigation.
</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">TNNLS'23</div>
      <img src='images/PGDQN.gif' alt="动态演示" width="100%" style="height: auto; object-fit: contain;">>
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[Sampling Efficient Deep Reinforcement Learning Through Preference-Guided Stochastic Exploration](https://github.com/OscarHuangWind/Preference-Guided-DQN-Atari) [![](https://img.shields.io/github/stars/OscarHuangWind/Preference-Guided-DQN-Atari?style=social&label=Code Stars)](https://github.com/OscarHuangWind/Preference-Guided-DQN-Atari)

**Wenhui Huang**, Cong Zhang, Jingda Wu, Xiangkun He, Jie Zhang, Chen Lv

[**Project**](https://github.com/OscarHuangWind/Preference-Guided-DQN-Atari) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a sampling efficient stochastic exploration policy, preference-guided DQN (PGDQN), to enhance the performance of reinforcement learning algorithms.
</div>
</div>



## Selected Publications
- [Hybrid-Prediction Integrated Planning for Autonomous Driving](https://ieeexplore.ieee.org/abstract/document/10833731), Haochen Liu, Zhiyu Huang, **Wenhui Huang**, Haohan Yang, Xiaoyu Mo, Chen Lv, **IEEE T-PAMI'25** [![](https://img.shields.io/github/stars/georgeliu233/HPP?style=social&label=Code Stars)](https://github.com/georgeliu233/HPP)

- [WiseAD: Knowledge Augmented End-to-End Autonomous Driving with Vision-Language Model](https://arxiv.org/abs/2412.09951), Songyan Zhang<sup>1</sup>, **Wenhui Huang<sup>1</sup>**, Zihui Gao, Hao Chen, Chen Lv, **arXiv'24** [![](https://img.shields.io/github/stars/wyddmw/WiseAD?style=social&label=Code Stars)](https://github.com/wyddmw/WiseAD)

- [Safety-aware human-in-the-loop reinforcement learning with shared control for autonomous driving](https://ieeexplore.ieee.org/abstract/document/10596046), **Wenhui Huang**, Haochen Liu, Zhiyu Huang, Chen Lv, **IEEE T-ITS'24** [![](https://img.shields.io/github/stars/OscarHuangWind/Safe-Human-in-the-Loop-RL?style=social&label=Code Stars)](https://github.com/OscarHuangWind/Safe-Human-in-the-Loop-RL)

- [Trustworthy autonomous driving via defense-aware robust reinforcement learning against worst-case observational perturbations](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Hpatee0AAAAJ&sortby=pubdate&citation_for_view=Hpatee0AAAAJ:mVmsd5A6BfQC), Xiangkun He, **Wenhui Huang**, Chen Lv, **Transportation Research Part C: Emerging Technologies'24**

- [Uncertainty-aware Reinforcement Learning for Autonomous Driving with Multimodal Digital Driver Guidance](https://ieeexplore.ieee.org/abstract/document/10610272), **Wenhui Huang**, Zitong Shan, Shanhe Lou, Chen Lv, **IEEE ICRA'24** [![](https://img.shields.io/github/stars/OscarHuangWind/Learning-from-Intervention?style=social&label=Code Stars)](https://github.com/OscarHuangWind/Learning-from-Intervention)

- [Toward trustworthy decision-making for autonomous vehicles: A robust reinforcement learning approach with safety guarantees](https://www.sciencedirect.com/science/article/pii/S2095809923004708), Xiangkun He, **Wenhui Huang**, Chen Lv, **Engineering'24**

- [Expert-demonstration-augmented reinforcement learning for lane-change-aware eco-driving traversing consecutive traffic lights](https://www.sciencedirect.com/science/article/abs/pii/S0360544223028669), Chuntao Zhang, **Wenhui Huang**, Xingyu Zhou, Chen Lv, Chao Sun, **Energy'24**

- [Sampling efficient deep reinforcement learning through preference-guided stochastic exploration](https://ieeexplore.ieee.org/abstract/document/10269149), **Wenhui Huang**, Cong Zhang, Jingda Wu, Xiangkun He, Jie Zhang, Chen Lv, **IEEE TNNLS'23** [![](https://img.shields.io/github/stars/OscarHuangWind/Preference-Guided-DQN-Atari?style=social&label=Code Stars)](https://github.com/OscarHuangWind/Preference-Guided-DQN-Atari)

- [Goal-guided transformer-enabled reinforcement learning for efficient autonomous navigation](https://ieeexplore.ieee.org/abstract/document/10254445),**Wenhui Huang**, Yanxin Zhou, Xiangkun He, Chen Lv, **IEEE T-ITS'23** [![](https://img.shields.io/github/stars/OscarHuangWind/DRL-Transformer-SimtoReal-Navigation?style=social&label=Code Stars)](https://github.com/OscarHuangWind/DRL-Transformer-SimtoReal-Navigation)

- [Potential hazard-aware adaptive shared control for human-robot cooperative driving in unstructured environment](https://ieeexplore.ieee.org/abstract/document/10004306), **Wenhui Huang**, Yanxin Zhou, Jianhuang Li, Chen Lv, **IEEE ICARCV'22**

- [Safe decision-making for lane-change of autonomous vehicles via human demonstration-aided reinforcement learning](https://ieeexplore.ieee.org/abstract/document/10004306), Jingda Wu, **Wenhui Huang**, Niels de Boer, Yanghui Mo, Xiangkun He, Chen Lv, **IEEE ITSC'22**

- [Prioritized experience-based reinforcement learning with human guidance for autonomous driving](https://ieeexplore.ieee.org/abstract/document/9793564), Jingda Wu, Zhiyu Huang, **Wenhui Huang**, Chen Lv, **IEEE TNNLS'22**

- [Learning to drive via apprenticeship learning and deep reinforcement learning](https://ieeexplore.ieee.org/abstract/document/8995417), **Wenhui Huang**, Francesco Braghin, Zhuo Wang, **IEEE ICTAI'19**

- [Autonomous vehicle driving via deep deterministic policy gradient](https://asmedigitalcollection.asme.org/IDETC-CIE/proceedings-abstract/IDETC-CIE2019/59216/1069916), **Wenhui Huang**, Francesco Braghin, Stefano Arrigoni, **ASME IDETC-CIE'19**

# 🎖 Honors and Awards
- *Apr. 2025* [Featured PhD Candidate in ITS field](https://ieeexplore.ieee.org/document/10938667), IEEE ITSM.
- *Jun. 2024* [1st Place Winner, Waymo Open Dataset Occupancy Flow Challenge](https://cvpr2024.wad.vision/), CVPR Workshop on Autonomous Driving. 
- *Sep. 2024* Best Paper Runner-up Award, ITSC 2023. 
- *Dec. 2022* 2nd Place Winner, Intelligent Algorithm Final of Alibaba Global Future Vehicle Challenge.
- *Mar. 2017* Politecnico Di Milano DSU Scholarship.
- *Jun. 2015* Outstanding Graduate (Top 1%).
- *Oct. 2014* National Scholarship (Top 1%).
- *Oct. 2013* First Prize Scholarship.
- *Oct. 2012* Excellent Student Scholarship.

<!-- # 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📚 Academic Services

## Program Committee
- Lead organizer of Invited Session on "Foundation Model-Enabled Scene Understanding, Reasoning, and Decision-Making for Autonomous Driving and ITS" at ITSC, 2025. (Website to be updated)
- Lead organizer of Invited Session on [Learning-empowered Intelligent Transportation Systems: Foundation Vehicles and Coordination Technique](https://oscarhuangwind.github.io/Foundation_Vehicle/) at ITSC, 2024

## Journal Reviewer
- IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)
- IEEE Transactions on Intelligent Transportation Systems (T-ITS)
- IEEE Transactions on Neural Networks and Learning Systems (TNNLS)
- IEEE Transactions on Vehicular Technology (TVT)
- IEEE Transactions on Intelligent Vehicles (TIV)
- IEEE Transactions on Automation Science and Engineering (T-ASE)
- Engineering

## Conference Reviewer
- IEEE / CVF Computer Vision and Pattern Recognition Conference (CVPR) 2025
- IEEE International Conference on Robotics and Automation (ICRA) 2023 – 2025
- IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2023 - 2025
- IEEE Intelligent Vehicles Symposium (IV) 2023 – 2025
- IEEE Intelligent Transportation Systems Conference (ITSC) 2023 – 2025

# 💬 Invited Talks
- *Mar 2025*, Reinforced Continual Evolution of Decision-Making Systems <br>
  School of Vehicle and Mobility, Tsinghua University, Beijing, China. <br>
  Traffic Operations and Simulations Lab, Tongji University, Shanghai, China.
- *Feb. 2025*, Reinforced Continual Evolution of Decision-Making Systems <br>
  Engineering Research Center for Intelligent Electrified Mobility, SouthEast University, Nanjing, China. <br>
  Prof. Chunhua Shen's Lab, Zhejiang University, Hangzhou, China.
- *Nov. 2024*, Reinforced Continual Evolution of Decision-Making Systems, Harvard Computational Robotics Group, Harvard University, Cambridge, USA.
- *Sep. 2024*, Reinforcement Learning-empowered Decision Making for Autonomous
Driving under Knowledge Guidance, Michigan Traffic Lab, University of Michigan, Michigan, USA.
- *May. 2024*, Uncertainty-aware Reinforcement Learning for Autonomous Driving
and Autonomous Racing, Gran Turismo Sophy team, Sony AI, Tokyo, Japan.
<!-- - *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- comming soon! -->
<!-- - *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->