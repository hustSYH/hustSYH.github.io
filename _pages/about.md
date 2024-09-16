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






欢迎来到我的主页，我是程育奇，在华中科技大学取得了学士学位（2020）和硕士学位（2023，导师：李文龙）.目前我在华中科技大学攻读博士学位，导师为沈卫明院士。

我的研究方向围绕工业视觉检测展开，涉及多视图点云的机器人采集、精简、配准、异常检测等. 后续研究重点为构建可实际使用的点云异常检测方法与更加通用的3D特征提取器。除了学术研究，我有很大的热情和兴趣参与实际项目的落地，目前我的研究成果已经在航空叶片、核电堆芯、汽车自动化产线等场景实现了应用。
如果对我的学术研究或落地项目感兴趣，任何时候都可以联系我，我非常乐意与您进行交流！
我未来十分希望能将学术研究的方法推向实际使用，如果有企业愿意给我提供这个机会，请联系我！




# 🔥 News
- *2024.08*: &nbsp;🎉🎉 We get the **Provincial Second Prize**, China International College Students’ Innovation Competition.
- *2024.07*: &nbsp;🎉🎉 Our paper addressed [Zero-shot Image Anomaly Detection](https://arxiv.org/abs/2407.15795) is accepted by ECCV.
- *2024.06*: &nbsp;🎉🎉 We release [A Survey on Visual Anomaly Detection: Challenge, Approach, and Prospect](https://arxiv.org/abs/2401.16402)
- *2024.05*: &nbsp;🎉🎉 Our paper addressed [Robust Image Anomaly Detection](https://arxiv.org/abs/2406.07176) is accepted by 2024 IEEE 20th International Conference on Automation Science and Engineering(IEEE CASE2024).
- *2024.03*: &nbsp;🎉🎉 Our paper addressed [Multi-view Point Cloud Registration](https://ieeexplore.ieee.org/abstract/document/10565771) is accepted by IEEE Transactions on Instrumentation and Measurement.
- *2024.03*: &nbsp;🎉🎉 Our paper addressed [Mesh Data Filtering](https://iopscience.iop.org/article/10.1088/1361-6501/ad317e) is accepted by Measurement Science and Technology.
- *2023.12*: &nbsp;🎉🎉 Our paper addressed [Illumination-Robust Edge Detection](https://iopscience.iop.org/article/10.1088/1742-6596/2761/1/012001) is published by 2023 3rd International Conference on Mechanical Automation and Electronic Information Engineering(MAEIE-2023).
- *2023.10*: &nbsp;🎉🎉 Our paper addressed [Panoramic Image Stitching](https://iopscience.iop.org/article/10.1088/1361-6501/acfd4d)  is accepted by Measurement Science and Technology.
- *2023.06*: &nbsp;🎉🎉 Our paper addressed [point cloud semantic segmentation](http://www.jamstjournal.com/cn/article/doi/10.51393/j.jamst.2023010) is accepted by Journal of Advanced Manufacturing Science and Technology.
- *2023.06*: &nbsp;🎉🎉 We won the 2nd place in [CVPR VAND Zero-shot Anomaly Detection Challenge](https://sites.google.com/view/vand-cvpr23/challenge). Press Coverage: [华中科技大学](https://mp.weixin.qq.com/s/HJRslaPxo1RipTwom2mngQ), [我爱计算机视觉](https://mp.weixin.qq.com/s/_mJKn4o_U_VjEqlz7DXUFQ).
- *2023.05*: &nbsp;🎉🎉 We released [Segment Any Anomaly without Training via Hybrid Prompt Regularization](https://arxiv.org/abs/2305.10724) for zero-shot anomaly segmentation.
- *2023.03*: &nbsp;🎉🎉 We get the **National First Price**, "Challenge Cup" National College Student Business Plan Competition.
- *2022.08*: &nbsp;🎉🎉 Our paper addressed [Point Cloud Simplification](https://iopscience.iop.org/article/10.1088/1361-6501/ac8ac1) is accepted by Measurement Science and Technology.
- *2022.06*: &nbsp;🎉🎉 We get the **Provincial First Price**, "Challenge Cup" National College Student Business Plan Competition.
- *2021.11*: &nbsp;🎉🎉 Our paper addressed [Surface Aperture Measurement](https://iopscience.iop.org/article/10.1088/1361-6501/ac39d0) is accepted by Measurement Science and Technology.
- *2021.09*: &nbsp;🎉🎉 We get the **National Third Prize**, China Postgraduate Robot Innovation and Design Competition.
# 📝 Publications 


<h2>
  <a href="#Peer-Reviewed Publications"><u>Peer-Reviewed Publications</u></a>&nbsp; <br> 
  <a href="#Manuscripts under Review"><u>Manuscripts under Review</u></a>&nbsp; <br>
</h2>
<span style="color:#b02418; font-weight:bold;">#</span> co-first author | <span style="color:#b02418; font-weight:bold;">*</span> corresponding author <br> 

<h2 id="Peer-Reviewed Publications" style="color: #2c4a88; padding-top: 60px; margin-top: -60px;">Peer-Reviewed Publications</h2>
<ol reversed>

  <li id="FA-Pub1"> 
    MVGR: Mean-Variance Minimization Global Registration Method for Multiview Point Cloud in Robot Inspection <a href="https://ieeexplore.ieee.org/abstract/document/10565771">[Paper]</a> <a href="NULL">[Code]</a> <br> 
    <span style="color:#b02418; font-weight:bold;">Yuqi Cheng</span>, Wenlong Li*, Cheng Jiang, Dongfang Wang, Hongwen Xing, Wei Xu <br>
    <i>IEEE Transactions on Instrumentation and Measurement <strong>(TIM).</strong></i> 2024. (JCR Q1)
  </li>

  <li id="FA-Pub2"> 
    A novel cooling hole inspection method for turbine blade using 3D reconstruction of stereo vision <a href="https://iopscience.iop.org/article/10.1088/1361-6501/ac39d0/meta">[Paper]</a> <br> 
    <span style="color:#b02418; font-weight:bold;">Yuqi Cheng</span>, Wenlong Li*, Cheng Jiang, Gang Wang, Wei Xu, Qingyu Peng<br>
    <i>Measurement Science and Technology <strong>(MST).</strong></i> 2021. (JCR Q1)
  </li>

  <li id="FA-Pub3"> 
    A novel point cloud simplification method using local conditional information <a href="https://iopscience.iop.org/article/10.1088/1361-6501/ac8ac1/meta">[Paper]</a> <br> 
    <span style="color:#b02418; font-weight:bold;">Yuqi Cheng</span>, Wenlong Li, Cheng Jiang, Dongfang Wang, Jincheng Mao*, Wei Xu <br>
    <i>Measurement Science and Technology <strong>(MST).</strong></i> 2022. (JCR Q1)
  </li>

  <li id="FA-Pub4"> 
    A point cloud semantic segmentation method for nuclear power reactors based on RandLA-Net Model <a href="http://www.jamstjournal.com/cn/article/doi/10.51393/j.jamst.2023010">[Paper]</a> <br> 
    <span style="color:#b02418; font-weight:bold;">Yuqi Cheng</span>,  Dongfang Wang, Qingyu Peng, Wenlong Li* <br>
    <i>Journal of Advanced Manufacturing Science and Technology<strong>(JAMST).</strong></i> 2023.
  </li>

  <li id="FA-Pub5"> 
    RAD: A Comprehensive Dataset for Benchmarking the Robustness of Image Anomaly Detection <a href="https://arxiv.org/abs/2406.07176">[Paper]</a> <a href="https://github.com/hustCYQ/RAD-dataset">[Code]</a> <br> 
    <span style="color:#b02418; font-weight:bold;">Yuqi Cheng</span>, Yunkang Cao, Rui Chen, Weiming Shen <br>
    <i>IEEE 20th International Conference on Automation Science and Engineering <strong>(CASE).</strong></i> 2024.
  </li>

  <li id="FA-Pub8"> 
    AdaCLIP: Adapting CLIP with Hybrid Learnable Prompts for Zero-Shot Anomaly Detection <a href="https://arxiv.org/abs/2407.15795">[Paper]</a> <a href="https://github.com/caoyunkang/AdaCLIP">[Code]</a> <br> 
    Yunkang Cao, Jiangning Zhang, Luca Frittoli, <span style="color:#b02418; font-weight:bold;">Yuqi Cheng</span>, Weiming Shen*, Giacomo Boracchi <br>
    <i>European Conference on Computer Vision <strong>(ECCV).</strong></i> 2024.
  </li>


  <li id="FA-Pub7"> 
    An adaptive anisotropic bilateral filtering method for mesh data in scale space <a href="https://iopscience.iop.org/article/10.1088/1361-6501/ad317e/meta">[Paper]</a> <br> 
    Lingjie Su, Wenlong Li*, <span style="color:#b02418; font-weight:bold;">Yuqi Cheng</span>, Dongfang Wang, Cheng Jiang, Wentao Yang, Haiwen Zhang, Wei Xu <br>
    <i>Measurement Science and Technology <strong>(MST).</strong></i> 2024. (JCR Q1)
  </li>  

   <li id="FA-Pub6"> 
    An illumination-robust edge detection method for nuclear fuel assembly deformation measurement <a href="https://iopscience.iop.org/article/10.1088/1742-6596/2761/1/012001/meta">[Paper]</a> <br> 
    Rui Chen, <span style="color:#b02418; font-weight:bold;">Yuqi Cheng</span>, Wentao Yang, Bin Yang and Wenlong Li* <br>
    <i>2023 3rd International Conference on Mechanical Automation and Electronic Information Engineering <strong>(MAEIE).</strong></i> 2023.
  </li>
  

  

  
</ol>


<h2 id="Manuscripts under Review" style="color: #2c4a88; padding-top: 60px; margin-top: -60px;">Manuscripts under Review</h2>
<ol reversed>


  <li id="FA-Manuscript1"> 
    Towards Zero-shot Point Cloud Anomaly Detection: A Multi-View Projection Framework <br> 
     <span style="color:#b02418; font-weight:bold;">Yuqi Cheng#</span>, Yunkang Cao#, Guoyang Xie, Zhichao Lu, Weiming Shen* <br>
    <i>Transactions on Automation Science and Engineering <strong>(IEEE TASE)</strong></i> . (Under Review)
  </li>


  <li id="FA-Manuscript1"> 
    Boosting Global-Local Feature Matching via Anomaly Synthesis for Multi-Class Point Cloud Anomaly Detection <br> 
    <span style="color:#b02418; font-weight:bold;">Yuqi Cheng</span>, Yunkang Cao, Dongfang Wang, Weiming Shen*, Wenlong Li<br>
    <i>IEEE Transactions on Systems, Man, and Cybernetics: Systems <strong>(IEEE TSMC)</strong></i> . (Under Review)
  </li>



  <li id="OT-Manuscript3"> 
    VTFusion: A Vision-Text Multimodal Fusion Network for Few-Shot Anomaly Detection <br> 
    Yuxin Jiang, Yunkang Cao, <span style="color:#b02418; font-weight:bold;">Yuqi Cheng</span>, Yiheng Zhang, Weiming Shen* <br>
    <i>IEEE Transactions on Cybernetics <strong>(IEEE TCYB)</strong></i>. (Under Review)
  </li>



  <li id="FA-Manuscript5"> 
    Segment any anomaly without training via hybrid prompt regularization <a href="https://arxiv.org/abs/2305.10724">[Paper]</a> <a href="https://github.com/caoyunkang/Segment-Any-Anomaly">[Code]</a> <br> 
    Yunkang Cao, Xiaohao Xu, Chen Sun, <span style="color:#b02418; font-weight:bold;">Yuqi Cheng</span>, Zongwei Du, Liang Gao, Weiming Shen* <br>
    <i>IEEE Transactions on Cybernetics <strong>(IEEE TCYB)</strong></i>. (Under Review)
  </li>


  <li id="FA-Manuscript3"> 
    A Survey on Visual Anomaly Detection: Challenge, Approach, and Prospect <a href="https://arxiv.org/abs/2401.16402">[Paper]</a> <br> 
    Yunkang Cao, Xiaohao Xu, Jiangning Zhang, <span style="color:#b02418; font-weight:bold;">Yuqi Cheng</span>, Xiaonan Huang, Guansong Pang, Weiming Shen* (Under Review) <br>
  </li>








</ol>










# 📝 Projects 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- **National First Price**, "Challenge Cup" National College Student Business Plan Competition. 2023.
- **2nd place** CVPR VAND Zero-shot Anomaly Detection Challenge. 2023. 
- **National Third Prize**, China Postgraduate Robot Innovation and Design Competition. 2021.
- **Provincial First Price**, "Challenge Cup" National College Student Business Plan Competition. 2022. 
- **Provincial Second Price**, China International College Students’ Innovation Competition. 2024.
- **Future STAR** (Highest honors in School of Mechanical Science and Engineering). 2024.
- **National Scholarship** (Rank first in the major). 2022.
- **Merit Student**, 2021, 2022.
- **The First Prize Scholarship**, 2020,2021,2022,2023.



# 📖 Educations
**- ### *2023.10 - present, Politecnico di Milano*
  Department of Electronics, Information and Bioengineering                              
- ### *2023.09 - present, Huazhong University of Science and Technology*
  State Key Laboratory of Digital Manufacturing Equipment and Technology                               
  ***Ph.D. Candidate*** in Mechanical Engineering &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Advisor**: [Weiming Shen](https://scholar.google.com/citations?hl=zh-CN&user=FuSHsx4AAAAJ&view_op=list_works&sortby=pubdate)
 
- ### *2020.09 - 2023.06, Huazhong University of Science and Technology*
  State Key Laboratory of Digital Manufacturing Equipment and Technology                               
  ***M.S.*** in Mechanical Engineering &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Advisor**: [Wenlong Li](http://mse.hust.edu.cn/info/1142/1340.htm)
 
- ### *2016.09 - 2020.06, Huazhong University of Science and Technology*
  ***B.S.*** in Mechanical Design, Manufacture & Automation &nbsp;&nbsp;&nbsp; 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
