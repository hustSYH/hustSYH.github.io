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



欢迎来到我的主页！我是孙依晗，目前我在华中科技大学攻读硕士学位，导师为[沈卫明院士](http://mse.hust.edu.cn/info/1143/1385.htm)。此前，我在中南大学取得了学士学位（2024），并有幸获得了湖南省优秀毕业生奖。展望未来，我很期望能在即将到来的2027年秋季攻读博士学位。

Welcome to my homepage! I am Yihan Sun(孙依晗). Currently, I am pursuing a master's degree at Huazhong University of Science and Technology under the supervision of Prof. [Shen Weiming](https://scholar.google.com/citations?hl=zh-CN&user=FuSHsx4AAAAJ&view_op=list_works&sortby=pubdate). Previously, I obtained my bachelor's degree from Central South University in 2024 and was fortunate to receive the Excellent Graduate Award of Hunan Province. Looking ahead, I am excited to pursue a doctoral degree in the upcoming fall of 2027.

我的研究方向围绕**工业视觉检测**展开，涉及图像与点云的机器人采集、异常检测等，硕士期间后续的研究重点为构建**高性能的点云异常检测方法**。如果对我的研究感兴趣，随时可以联系我，我非常乐意与您进行交流！😊😊😊


My research focuses on **industrial visual inspection**, covering areas such as robotic acquisition of images and point clouds, anomaly detection, etc. The subsequent research focus during my master's studies will be on developing **high-performance point cloud anomaly detection methods**. If you are interested in my research, please feel free to contact me at any time, and I will be happy to communicate with you!😊😊😊





# 📝 Publications 



<span style="color:#b02418; font-weight:bold;">#</span> co-first author | <span style="color:#b02418; font-weight:bold;">*</span> corresponding author <br> 

<h2 id="Peer-Reviewed Publications" style="color: #2c4a88; padding-top: 60px; margin-top: -60px;">Peer-Reviewed Publications</h2>
<ol reversed>



  <li id="FA-Pub6"> 
    Multi-View Reconstruction with Global Context for 3D Anomaly Detection <br> 
    <span style="color:#b02418; font-weight:bold;">Yihan Sun</span>, Yuqi Cheng, Yunkang Cao, Yuxin Zhang, Weiming Shen* <br>
    <i>IEEE International Conference on Systems, Man, and Cybernetics <strong>(IEEE SMC).</strong></i> 2025.
  </li>




  
</ol>


<h2 id="Manuscripts under Review" style="color: #2c4a88; padding-top: 60px; margin-top: -60px;">Manuscripts under Review</h2>
<ol reversed>


  <li id="FA-Manuscript1"> 
    Visual Anomaly Detection under Complex View-Illumination Interplay: A Large-Scale Benchmark <a href="https://arxiv.org/abs/2505.10996">[Paper]</a> <a href="https://github.com/hustCYQ/M2AD">[Code]</a> <br> 
     Yunkang Cao#, Yuqi Cheng#, Xiaohao Xu, Yiheng Zhang, <span style="color:#b02418; font-weight:bold;">Yihan Sun</span>, Yuxiang Tan, Yuxin Zhang, Xiaonan Huang, Weiming Shen* <br>
    <i>Submitted to Neural Information Processing Systems <strong>(NeurIPS 2025)</strong></i>. (Under Review)
  </li>

  <li id="FA-Manuscript1"> 
    Towards High-Resolution 3D Anomaly Detection: A Scalable Dataset and Real-Time Framework for Subtle Industrial Defects <a href="https://arxiv.org/abs/2507.07435">[Paper]</a> <a href="https://github.com/hustCYQ/MiniShift-Simple3D">[Code]</a> <br> 
     Yuqi Cheng#, <span style="color:#b02418; font-weight:bold;">Yihan Sun#</span>, Hui Zhang, Weiming Shen*, Yunkang Cao* <br>
    <i>Submitted to AAAI Conference on Artificial Intelligence <strong>(AAAI 2026)</strong></i>.
  </li>



</ol>






# 💻 Projects 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIM 2024</div><img src='images/PC0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Multi-view registration of car body

[**Introduction**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- An industrial robot is equipped with 3D sensors to collect point clouds from multiple perspectives, and the proposed method MVGR is utilized for multi-view point cloud registration to obtain high-quality car body data.

[**Challenge**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Due to the positioning deviation of the robot, the point clouds collected by various poses inevitably have uneven density and stratification, leading to a significant compromise in the overall quality of multiview point clouds.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MST 2021</div><img src='images/blade0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Inspection of turbine blade cooling holes

[**Introduction**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- An industrial robot is equipped with binocular camera to collect images of the blade, and then the number and aperture of cooling holes are calculated by the distribution property and binocular reconstruction principle.


[**Challenge**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Complex blade shape; holes distributed on the curved surface; weak feature.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MST 2023</div><img src='images/Stitch0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">



Panoramic image stitching and dimension calculation for nuclear fuel assemblies.

[**Introduction**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- The videos are recorded when pulling the fuel assembly under water. Then the videos are utilized to restore the panoramic images to further calculate the key dimensions.

[**Challenge**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Radiation noise, thermal disturbance, weak texture, large-scale object.


</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CASE 2024</div><img src='images/CASE0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Foreign object recognition

[**Introduction**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Instances of machine wear or human error may result in foreign objects falling onto the platform, thereby disrupting operations and posing safety hazards. Consequently, detecting foreign objects on the work platform is framed as an unsupervised anomaly detection challenge.


[**Challenge**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Abnormal data are hard to collect, uneven illumination, domain gap.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Work</div><img src='images/Phone0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Mobile E-Ink Screen Surface Defect Detection

[**Introduction**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A high-resolution detection device is built to detect abnormal products by using unsupervised anomaly detection technology.


[**Challenge**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- Tiny defect, illumination dependent, abnormal data are hard to collect.
</div>
</div>





# 🥇 Honors and Awards
- **Outstanding Reviewers** of the IEEE Instrumentation and Measurement Society (IEEE TIM). 2024.
- **National First Price**, "Challenge Cup" National College Student Business Plan Competition. 2023. (Leader)
- **2nd place** CVPR VAND Zero-shot Anomaly Detection Challenge. 2023. (Participator)
- **National Third Prize**, China Postgraduate Robot Innovation and Design Competition. 2021. (Leader)
- **Provincial First Price**, "Challenge Cup" National College Student Business Plan Competition. 2022. (Leader)
- **Provincial Second Price**, China International College Students’ Innovation Competition. 2024. (Leader)
- **Future STAR** (Highest honors in School of Mechanical Science and Engineering). 2024.
- **National Scholarship** (Rank first in the major). 2022.
- **Merit Student**, 2021, 2022.
- **The First Prize Scholarship**, 2020,2021,2022,2023.



# 📖 Educations
                          
- ### *2024.09 - present, Huazhong University of Science and Technology*
  State Key Laboratory of Digital Manufacturing Equipment and Technology                               
  ***M.S.*** in Mechanical Engineering &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Advisor**: [Weiming Shen](https://scholar.google.com/citations?hl=zh-CN&user=FuSHsx4AAAAJ&view_op=list_works&sortby=pubdate)
 
- ### *2020.09 - 2024.06, Central South University*
  ***B.S.*** in Mechanical Design, Manufacture & Automation &nbsp;&nbsp;&nbsp; 


# 💻 Internships
- *2024.10 - Now*, CATL(宁德时代), China. Research on 3D measurement and anomaly detection of battery pack.




# 🌐 Miscellaneous
In my free time, I love sports and enjoy exploring new activities, including playing basketball 🏀, playing badminton 🏸, and cycling 🚴. I also look forward to sharing these sports with friends.


<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=a&t=tt&d=GEx5UNgsTQZO0HXocUoir2X2jb3xYvYzLS-DAh9BvTY&co=2793de&ct=ffffff'></script>
