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

I am currently a Post-Doctoral Fellow at [Medical Mechatronics Lab](http://www.labren.org/mm/) of the Department of Electronic Engineering, The Chinese University of Hong Kong (CUHK), supervised by [Prof. Hongliang Ren](https://www.ee.cuhk.edu.hk/en-gb/people/academic-staff/professors/prof-ren-hongliang). I served as a Researcher at the Quanzhou Institute of Equipment Manufacturing (QIEM), Chinese Academy of Sciences (CAS), Quanzhou, China, from 2015 to 2018. After that, I pursued my Ph.D. degree under the joint program of Fuzhou University and QIEM, supervised by [Prof. Shuying Cheng](https://wx.fzu.edu.cn/info/1004/1066.htm) and [Prof. Houde Dai](https://people.ucas.ac.cn/~dhd). 

My research interests include Magnetic Tracking, Intelligent Perception, Robot Localization, SLAM, and Multi-sensor fusion. I have been actively engaged in knowledge exchange between
academia and industry, and published more than 20 papers at the top international journals and conferences with total <a href='https://scholar.google.com/citations?user=2Qkb_f8AAAAJ&hl'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.


# 🔥 News
- *2023.08*: &nbsp;🎉🎉 One paper about geomagnetic vector separation is accepted by IEEE TITS, a top journal. 
- *2022.12*: &nbsp;🎉🎉 One paper about six-DoF pose estimation is accepted by IEEE TII, a top journal.



# 📝 Selected Publications
- **First & Corresponding Author Publications**
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TII</div><img src='paper_images/TII-2022.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**1. AMagPoseNet: Real-Time 6-DoF Magnet Pose Estimation by Dual-Domain Few-Shot Learning from Prior Model**

**S. Su**, S. Yuan, M. Xu, H. Gao, H. Ren*

IEEE Transactions on Industrial Informatics, 2023

[pdf](https://ieeexplore.ieee.org/document/10005853) \| [dataset](http://ieee-dataport.org/10101) \| [video](https://www.bilibili.com/video/BV14T411T7sZ/?spm_id_from=333.999.0.0&vd_source=1104cb40508c1b1b02880720a07ad062)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TITS</div><img src='paper_images/TITS-2022.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**2. Magnetic Tracking with Real-Time Geomagnetic Vector Separation for Robotic Dockable Charging**

**S. Su**, H. Dai\*, Y. Zhang, S. Yuan, H. Ren

IEEE Transactions on Intelligent Transportation Systems, 2023

[pdf](https://ieeexplore.ieee.org/document/10226461)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE T-MECH</div><img src='paper_images/TMECH-2021.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**3. A Simplified Magnetic Positioning Approach Based on Analytical Method and Data Fusion for Automated Guided Vehicles**

H. Dai, P. Guo, **S. Su\***, S. Song\*, and S. Cheng

IEEE/ASME Transactions on Mechatronics, 2022

[pdf](https://ieeexplore.ieee.org/abstract/document/9535115)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TITS</div><img src='paper_images/TITS-2021.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**4. An Improved Magnetic Guidance Approach for Automated Guided Vehicles by Error Analysis and Prior Knowledge**

**S. Su**, H. Dai, S. Cheng\*, Z. Chen

IEEE Transactions on Intelligent Transportation Systems, 2020

[pdf](https://ieeexplore.ieee.org/abstract/document/9108604) 

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TIM</div><img src='paper_images/TIM-2020.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**5. A Robust Magnetic Tracking Approach Based on Graph Optimization**

**S. Su**, H. Dai, S. Cheng\*, P. Len

IEEE Transactions on Instrumentation and Measurement, 2020

[pdf](https://ieeexplore.ieee.org/abstract/document/9085357)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE ITSM</div><img src='paper_images/ITSM-2018.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**6. Positioning Accuracy Improvement of Automated Guided Vehicles Based on A Novel Magnetic Tracking Approach**

**S. Su**, X. Zeng, W. Yang, H. Dai\*, et al.

IEEE Intelligent Transportation Systems Magazine, 2018

[pdf](https://ieeexplore.ieee.org/abstract/document/8565961)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE Sensors J.</div><img src='paper_images/Sensors J.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**7. Investigation of the Relationship between Tracking Accuracy and Tracking Distance of a Novel Magnetic Tracking System**

**S. Su**, W. Yang, H. Dai\*, X. Xia, M. Lin, B. Sun, et al.

IEEE Sensors Journal, 2017

[pdf](https://ieeexplore.ieee.org/abstract/document/7944672) \| [video](https://www.bilibili.com/video/BV1jE411L7xz?p=1&vd_source=1104cb40508c1b1b02880720a07ad062)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TIM</div><img src='paper_images/TIM-2018.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**8. Geomagnetic Compensation for the Rotating of Magnetometer Array During Magnetic Tracking**

H. Dai, C. Hu, **S. Su\***, et al.

IEEE Transactions on Instrumentation and Measurement, 2018

[pdf](https://ieeexplore.ieee.org/abstract/document/8519764)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE ROBIO</div><img src='paper_images/ROBIO-2019.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**9. An Efficient Human-Following Method by Fusing Kernelized Correlation Filter and Depth Information for Mobile Robot**

**S. Su**, S. Cheng, H. Dai\*, H. Yu

IEEE International Conference on Robotics and Biomimetics (ROBIO), Dali, China, 2019.

[pdf](https://ieeexplore.ieee.org/abstract/document/8961459)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE ICIA</div><img src='paper_images/ICIA-2016.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**10. Home Energy Management System Using Smart Socket with Appliance Recognition**

**S. Su**, H. Dai\*, Y. Zeng, Z. Lin, X. Xia, and Z. Wu

IEEE International Conference on Information and Automation (ICIA), Ningbo, China, pp. 109-113, 2016. 

[pdf](https://ieeexplore.ieee.org/abstract/document/7831805)

</div>
</div>


Full publication list: See my [Google Scholar](https://scholar.google.com.hk/citations?user=2Qkb_f8AAAAJ&hl=zh-CN) or [ResearchGate](https://www.researchgate.net/profile/Shijian-Su-2)


# 🕒 Academic Services
**Reviewer in**
- IEEE Transactions on Industrial Informatics
- IEEE Transactions on Industrial Electronics
- IEEE Transactions on Intelligent Transportation System
- IEEE Access, IEEE Sensor Journal, Computers & Operations Research
- ...

**Organize Research Topic (Special Issue) ** 
- Organized research topic about "Advances in Structure Design, Sensing and Actuation for Soft Medical Robotics" at Frontiers in Robotics and AI.


# 🎖 Honors and Awards
- 2023　　　　IEEE Senior Member
- 2021　　　　Selected and Sponsored by CUHK Mainland Postdoctoral Sponsorship Program
- 2018　　　　5th Level of High-level Talents in Quanzhou
- 2016　　　　Outstanding Staff Award of QIEM, CAS
- 2015　　　　Outstanding Master Thesis Award of FZU
- 2012　　　　Outstanding Graduate Award of FZU
- 2011　　　　1st Prize in Fujian Electronic Design Contest
- 2011　　　　1st Prize in Fujian Embedded System Design Contest
- 2011　　　　National Scholarship
- 2009-2012 　1st Prize Scholarship (3 times) and 2nd Prize Scholarship (1 times) of FZU


# 📖 Educations
- 2022.02 - Present, Post-Doctoral Fellow, The Chinese University of Hong Kong, Hong Kong, China. 
- 2018.09 - 2021.06, Ph.D., Circuits and Systems, Fuzhou University & Quanzhou Institute of Equipment Manufacturing (QIEM), Haixi Institutes, Chinese Academy of Sciences, Fuzhou, China. 
- 2012.09 - 2015.06, M.E., Micro-Electronics and Solid State Electronics, Fuzhou University, Fuzhou, China. 
- 2008.09 - 2012.06, B.E., Electronic Science and Technology, Fuzhou University, Fuzhou, China (Ranking Top 2%, Excellent Graduates). 


# 💻 Working Experiences
- 2021.08 - 2022.02, Senior R&D Engineer, Visual semantic SLAM and planning for automated valet parking (AVP), [TungThih Electronic Co., Ltd.](http://www.tungthih.com.tw/en/about.php?show=2)
- 2020.08 - 2021.07, Part-time Research Assistant, Multi-target localization for spinal rod implant system, [AIMed, Hong Kong University](https://www.aimed.hku.hk/)
- 2020.08 - 2021.07, Senior Engineer, Surface Defect Detection for Industrial Products, [Research Institute of Ruijie Network Co., Ltd.](https://www.ruijie.com.cn/)
- 2015.06 - 2020.07, Engineer, Magnetic driven and localization system, Wireless Capsule Endoscopy (WCE), [Quanzhou Institute of Equipment Manufacturing (QIEM), Haixi Institutes, CAS](http://www.casqiem.ac.cn/)
- 2012.06 - 2015.02, Part-time Lecture @ Training Institution, Embedded software course (C/C++/Linux/Qt), [Great Education](http://www.51great.org/) & [Fuzhou Ding Quan Computer Tech.](https://baike.baidu.com/item/%E7%A6%8F%E5%B7%9E%E9%BC%8E%E5%B5%8C%E8%AE%A1%E7%AE%97%E6%9C%BA%E6%8A%80%E6%9C%AF%E5%92%A8%E8%AF%A2%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8/8423560)


# 🏓 Skills
- **Robot Localization:** Magnetic tracking system, Lidar and Visual SLAM
- **Deep Learning:** Few-shot/Cross-domain/Metric/Transfer/Active/Self-supervised Learning
- **Machine Learning:** Optimization (LM, PSO, WOA), KNN, random forest, SVM, clustering, and EM.
- **Hardware:** STM32, ARM9, PCB design, NVIDIA TX2, Raspberry Pi, MEMS inertial sensor
- **Programming Skills:** C/C++, Python, QT, ROS, QML, MATLAB, OpenCV, ceres, g2o, Linux SDK
