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

Hello, everyone! Here is **Bingyang Guo**'s academic page. Thanks for the template provided by [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io)!

# Biography

I received the doctoral degree in the Software College at the [Northeastern University](https://www.neu.edu.cn/) (Shenyang, China), advised by [Prof. Ruiyun Yu](http://faculty.neu.edu.cn/yury/). I received the bachelor's degree in the School of Mechanical Engineering at the [Shenyang Ligong University](https://www.sylu.edu.cn/), and the master's degree in the School of Mechanical Engineering and Automation at the [Northeastern University](https://www.neu.edu.cn/), advised by [Prof. Yunhui Yan](http://team.neu.edu.cn/MVR/zh_CN/more/263427/tdld/index.htm) and [Prof. Kechen Song](http://faculty.neu.edu.cn/songkechen/zh_CN/index.htm), within [Machine Vision & Robotics Lab](http://team.neu.edu.cn/MVR).

My academic interests revolve around AI4Industry, especially focus on **Industrial Surface Defect Segmentation under Data-scarcity Scenarios**, including Zero/Few-shot segmentation, Weakly-supervised segmentation, 2D-3D visual fusion, and Large Vision Model. If you are interested in any aspect of me, I am always open to discussions and collaborations. Feel free to reach out to me at - guobingyang0410@gmail.com

<span class="anchor" id="news"></span>
# News
- *2026.05*: Our paper addressed zero-shot classification in IC field is accepted by Pattern Recognition!
- *2026.04*: Our paper addressed few-shot segmentation in IC field is accepted by IEEE Transactions on Industrial Informatics!
- *2026.03*: I was invited to serve as a guest editor for a special issue of Electronics! We welcome contributions from experts and scholars!
- *2026.02*: Our paper addressed super resolution in industrial detection is accepted by IEEE/ASME Transactions on Mechatronics!
- *2025.12*: Our [paper](https://arxiv.org/pdf/2511.13115v2) addressed 3D-AD is accepted by Pattern Recognition!
- *2025.11*: Our paper addressed Integrated circuits package substrate 3D segmentation is accepted by AAAI 2026! The new dataset [CPS3D-Seg](https://github.com/Bingyang0410/CPS3D-Seg) proposed in the paper is the first 3D defect detection dataset of integrated circuit!
- *2025.09*: Our achievement [high precision visual inspection technology and application of ceramic package substrate](http://www.cainet.org.cn/xwzx/xhdt/art/2025/art_7c3cfa18f06f428f8c560b9dea833a25.html) won the gold award of the 11th International Invention Exhibition!
- *2025.08*: Our dataset CPS2D-AD is selected into the first batch of [high-quality dataset cases](https://mp.weixin.qq.com/s/aMUeV_bZgoxM9Vd877vW-g) of the national data administration!
- *2025.07*: Our paper addressed Integrated circuits package substrate few-shot classification is accepted by IECON 2025!
- *2025.06*: Our paper addressed [Integrated circuits package substrate anomaly detection](https://openaccess.thecvf.com/content/ICCV2025/html/Yu_Anomaly_Detection_of_Integrated_Circuits_Package_Substrates_Using_the_Large_ICCV_2025_paper.html) is accepted by ICCV 2025! The new dataset CPS2D-AD proposed in the paper is currently the largest integrated circuit defect detection dataset in the world!
- *2025.03*: Our paper addressed [Few-shot metal surface segmentation](https://ieeexplore.ieee.org/abstract/document/10898041) is accepted by IEEE TIM!
- *2024.09*: We acquire the funding from the key research and development projects of Liaoning Province (**Research and Application of Key Technologies for Multi-modal Industrial Product Surface Defect Detection Large Model**)!
- *2024.04*: Our paper addressed [Transferable recommendation](https://ieeexplore.ieee.org/abstract/document/10491370/) is accepted by IEEE TKDE (CCF A)!
- *2024.03*: Our paper addressed [Weakly-supervised metal surface segmentation](https://ieeexplore.ieee.org/abstract/document/10483094/) is accepted by IEEE TIM!
- *2023.12*: Our large vision model for industrial surface defect detection **Qing Que** obtained Huawei Ascend Technology Certification!
- *2023.05*: We acquire the funding from the Fundamental Research Funds for the Central Universities.
- *2023.01*: Our paper addressed [Real-time metal surface segmentation](https://ieeexplore.ieee.org/abstract/document/10018467/) is accepted by IEEE TII!
- *2022.08*: Our paper addressed [Few-shot metal surface segmentation](https://ieeexplore.ieee.org/abstract/document/9855496/) is accepted by IEEE TIM!

# Educations
- *2021.09 - 2026.06*, Northeastern University, Software College, ***Ph.D*** in Software Engineering
- *2018.09 - 2021.06*, Northeastern University, School of Mechanical Engineering & Automation, ***M.S.*** in Mechanical Design & Theory
- *2014.09 - 2018.06*, Shenyang Ligong University, School of Mechanical Engineering, ***B.S.*** in Mechanical Design, Manufacture & Automation

<span class="anchor" id="publications"></span>
# Publications

<span style="color:#b02418; font-weight:bold;">#</span> co-first author <span style="color:#b02418; font-weight:bold;">*</span> corresponding author <br>

<h2 class="pub-section-heading" id="journal-publications">Journal Publications</h2>
<div class="publication-list">
  <article class="publication-item" id="U-Pub5">
    <h3>EDNet: Zero-shot Classification for Ceramic Package Substrates Surface Defect with Embedding Diffusion Network</h3>
    <p class="pub-authors"><span class="author-highlight">Bingyang Guo</span><span class="author-mark">#</span>, Yuting Wang<span class="author-mark">#</span>, Ruiyun Yu*</p>
    <p class="pub-venue">Pattern Recognition <strong>(PR)</strong>, 2025.</p>
  </article>
  <article class="publication-item" id="U-Pub10">
    <h3>Hybrid-space Interaction Network for Effective Single-Image Super-Resolution in Defect Detection</h3>
    <p class="pub-authors">Haoyuan Li, Ruiyun Yu*, <span class="author-highlight">Bingyang Guo</span>, Bang An, Shi Zhen</p>
    <p class="pub-venue">IEEE/ASME Transactions on Mechatronics <strong>(T-Mech)</strong>, 2025.</p>
  </article>
  <article class="publication-item" id="U-Pub9">
    <h3>Dynamic Cross Characterization Network for Few-Shot IC Package Substrates Surface Defect Segmentation</h3>
    <p class="pub-authors">Ruiyun Yu, Haoyuan Li*, <span class="author-highlight">Bingyang Guo</span></p>
    <p class="pub-venue">IEEE Transactions on Industrial Informatics <strong>(TII)</strong>, 2025.</p>
  </article>
  <article class="publication-item" id="J-Pub8-3D">
    <h3>A Lightweight 3D Anomaly Detection Method with Rotationally Invariant Features</h3>
    <p class="pub-authors">Hanzhe Liang, Jie Zhou, Can Gao*, <span class="author-highlight">Bingyang Guo</span>, Jinbao Wang, Linlin Shen</p>
    <p class="pub-venue">Pattern Recognition <strong>(PR)</strong>, 2025.</p>
    <p class="pub-links"><a class="pub-badge" href="https://arxiv.org/pdf/2511.13115v2">Paper</a></p>
  </article>
  <article class="publication-item" id="J-Pub8-FS">
    <h3>Background-weaken Generalization Network for Few-Shot Industrial Metal Defect Segmentation</h3>
    <p class="pub-authors">Ruiyun Yu, Haoyuan Li*, <span class="author-highlight">Bingyang Guo</span>, Ziming Zhao</p>
    <p class="pub-venue">IEEE Transactions on Instrumentation and Measurement <strong>(TIM)</strong>, 2025.</p>
    <p class="pub-links"><a class="pub-badge" href="https://ieeexplore.ieee.org/abstract/document/10898041">Paper</a></p>
  </article>
  <article class="publication-item" id="J-Pub6">
    <h3>Dynamic Reasoning Network for Image-level Supervised Segmentation on Metal Surface Defect</h3>
    <p class="pub-authors">Ruiyun Yu, <span class="author-highlight">Bingyang Guo*</span>, Kang Yang</p>
    <p class="pub-venue">IEEE Transactions on Instrumentation and Measurement <strong>(TIM)</strong>, 2024.</p>
    <p class="pub-links"><a class="pub-badge" href="https://ieeexplore.ieee.org/abstract/document/10483094/">Paper</a></p>
  </article>
  <article class="publication-item" id="J-Pub5">
    <h3>Is multi-level data enhancement helpful for knowledge graph? A new perspective on multimodal fusion</h3>
    <p class="pub-authors">Kang Yang, Ruiyun Yu*, <span class="author-highlight">Bingyang Guo</span></p>
    <p class="pub-venue">Knowledge-Based Systems <strong>(KBS)</strong>, 2024.</p>
    <p class="pub-links"><a class="pub-badge" href="https://www.sciencedirect.com/science/article/pii/S0950705124009195">Paper</a></p>
  </article>
  <article class="publication-item" id="J-Pub4">
    <h3>Interaction Subgraph Sequential Topology-Aware Network for Transferable Recommendation</h3>
    <p class="pub-authors">Kang Yang, Ruiyun Yu*, <span class="author-highlight">Bingyang Guo</span>, Jie Li</p>
    <p class="pub-venue">IEEE Transactions on Knowledge and Data Engineering <strong>(TKDE)</strong>, 2024.</p>
    <p class="pub-links"><a class="pub-badge" href="https://ieeexplore.ieee.org/abstract/document/10491370/">Paper</a></p>
  </article>
  <article class="publication-item" id="J-Pub3">
    <h3>SPEED: Semantic prior and extremely efficient dilated convolution network for real-time metal surface defects detection</h3>
    <p class="pub-authors"><span class="author-highlight">Bingyang Guo</span>, Ruiyun Yu*, Kang Yang</p>
    <p class="pub-venue">IEEE Transactions on Industrial Informatics <strong>(TII)</strong>, 2023.</p>
    <p class="pub-links"><a class="pub-badge" href="https://ieeexplore.ieee.org/abstract/document/10018467/">Paper</a></p>
  </article>
  <article class="publication-item" id="J-Pub2">
    <h3>Selective prototype network for few-shot metal surface defect segmentation</h3>
    <p class="pub-authors">Ruiyun Yu, <span class="author-highlight">Bingyang Guo*</span>, Kang Yang</p>
    <p class="pub-venue">IEEE Transactions on Instrumentation and Measurement <strong>(TIM)</strong>, 2022.</p>
    <p class="pub-links"><a class="pub-badge" href="https://ieeexplore.ieee.org/abstract/document/9855496/">Paper</a></p>
  </article>
  <article class="publication-item" id="J-Pub1">
    <h3>NERNet: Noise estimation and removal network for image denoising</h3>
    <p class="pub-authors"><span class="author-highlight">Bingyang Guo</span>, Kechen Song*, Hongwen Dong, Yunhui Yan*, Zhibiao Tu, Liu Zhu</p>
    <p class="pub-venue">Journal of Visual Communication and Image Representation <strong>(JVCIR)</strong>, 2020.</p>
    <p class="pub-links"><a class="pub-badge" href="https://www.sciencedirect.com/science/article/pii/S1047320320301024">Paper</a></p>
  </article>
</div>

<h2 class="pub-section-heading" id="conference-publications">Conference Publications</h2>
<div class="publication-list">
  <article class="publication-item" id="C-Pub4">
    <h3>Point Cloud Segmentation of Integrated Circuits Package Substrates Surface Defects Using Causal Inference: Dataset Construction and Methodology</h3>
    <p class="pub-authors"><span class="author-highlight">Bingyang Guo</span>, Hongjie Li, Ruiyun Yu*</p>
    <p class="pub-venue">The 40th Annual AAAI Conference on Artificial Intelligence <strong>(AAAI)</strong>, 2026.</p>
    <p class="pub-links"><span class="pub-badge pub-badge--muted">Coming soon</span></p>
  </article>
  <article class="publication-item" id="C-Pub3">
    <h3>Fine-Grained Region Perception Network for Few-shot Defect Classification of IC Package Substrates: Benchmark Methodology and Dataset</h3>
    <p class="pub-authors">Haoyuan Li, Ruiyun Yu*, <span class="author-highlight">Bingyang Guo</span></p>
    <p class="pub-venue">The Annual Conference of the IEEE Industrial Electronics Society <strong>(IECON)</strong>, 2025.</p>
    <p class="pub-links"><span class="pub-badge pub-badge--muted">Coming soon</span></p>
  </article>
  <article class="publication-item" id="C-Pub2">
    <h3>Anomaly Detection of Integrated Circuits Package Substrates Using the Large Vision Model SAIC: Dataset Construction, Methodology, and Application</h3>
    <p class="pub-authors">Ruiyun Yu, <span class="author-highlight">Bingyang Guo*</span>, Haoyuan Li</p>
    <p class="pub-venue">International Conference on Computer Vision <strong>(ICCV)</strong>, 2025.</p>
    <p class="pub-links"><a class="pub-badge" href="https://openaccess.thecvf.com/content/ICCV2025/html/Yu_Anomaly_Detection_of_Integrated_Circuits_Package_Substrates_Using_the_Large_ICCV_2025_paper.html">Paper</a></p>
  </article>
  <article class="publication-item" id="C-Pub1">
    <h3>The interaction graph auto-encoder network based on topology-aware for transferable recommendation</h3>
    <p class="pub-authors">Ruiyun Yu, Kang Yang*, <span class="author-highlight">Bingyang Guo</span></p>
    <p class="pub-venue">Proceedings of the 31st ACM International Conference on Information &amp; Knowledge Management <strong>(CIKM)</strong>, 2022.</p>
    <p class="pub-links"><a class="pub-badge" href="https://dl.acm.org/doi/abs/10.1145/3511808.3557471">Paper</a></p>
  </article>
</div>

<h2 class="pub-section-heading" id="manuscripts-under-review">Manuscripts under Review</h2>
<div class="publication-list">
  <article class="publication-item" id="U-Pub3">
    <h3>3D Anomaly Detection: Approaches, Benchmark, Challenges, and Prospects for Intelligent Manufacturing</h3>
    <p class="pub-authors">Hanzhe Liang<span class="author-mark">#</span>, <span class="author-highlight">Bingyang Guo</span><span class="author-mark">#</span>, Can Gao<span class="author-mark">#</span>, Jiayi Lyu, Yunkang Cao, Guoyang Xie, Jinbao Wang, Ruiyun Yu, Linlin Shen, Pan Li, Weiming Shen</p>
    <p class="pub-venue">Journal of Intelligent Manufacturing <strong>(JIMS)</strong>, under review.</p>
  </article>
  <article class="publication-item" id="U-Pub2">
    <h3>IEC3D-AD: A 3D Dataset of Industrial Equipment Components for Unsupervised Point Cloud Anomaly Detection</h3>
    <p class="pub-authors"><span class="author-highlight">Bingyang Guo</span>, Hongjie Li, Ruiyun Yu*</p>
    <p class="pub-venue">IEEE Transactions on Circuits and Systems for Video Technology <strong>(TCSVT)</strong>, major revision.</p>
  </article>
  <article class="publication-item" id="U-Pub1">
    <h3>When Large Models Meet Integrated Circuit: A Unified Multimodal Framework for Semantic and Spatial Understanding on Ceramic Package Substrate Surface Defects</h3>
    <p class="pub-authors"><span class="author-highlight">Bingyang Guo</span>, Ruiyun Yu*, Haoyuan Li, Bang An</p>
    <p class="pub-venue">Pattern Recognition <strong>(PR)</strong>, under review.</p>
  </article>
</div>

<span class="anchor" id="projects"></span>
# Projects

<div class="projects-list">
  <article class="project-card">
    <img src="images/AOI2.png" alt="AOI Equipment for final product inspection">
    <div class="project-card__body">
      <div class="project-card__meta">2025.09 - Now</div>
      <h3>Auto Optical Inspection (AOI) Equipment for Final Product of Ceramic Package Substrate</h3>
      <ul>
        <li>Constructed an AOI equipment platform for ceramic package substrate final product inspection.</li>
        <li>Collected a comprehensive multi-view image dataset for ceramic package substrate surface inspection.</li>
      </ul>
    </div>
  </article>

  <article class="project-card">
    <img src="images/AOI1.png" alt="AOI Equipment for printing process inspection">
    <div class="project-card__body">
      <div class="project-card__meta">2024.07 - Now</div>
      <h3>Auto Optical Inspection (AOI) Equipment for Printing Process of Ceramic Package Substrate</h3>
      <ul>
        <li>Constructed an AOI equipment platform for the printing process.</li>
        <li>Collected a comprehensive high-resolution image dataset for ceramic package substrate surface inspection.</li>
      </ul>
    </div>
  </article>

  <article class="project-card">
    <img src="images/3DS.png" alt="Double CCD structured light measurement system">
    <div class="project-card__body">
      <div class="project-card__meta">2024.02 - 2024.07</div>
      <h3>Double CCD Structured Light Measurement System</h3>
      <ul>
        <li>Constructed a double CCD structured light measurement system for mechanical basic components.</li>
        <li>Collected a high-resolution point cloud dataset for 3D anomaly detection of mechanical basic components.</li>
      </ul>
    </div>
  </article>

  <article class="project-card">
    <img src="images/3D.png" alt="Multiple line laser scanning equipment">
    <div class="project-card__body">
      <div class="project-card__meta">2023.11 - 2024.06</div>
      <h3>Multiple Line Laser Scanning Equipment</h3>
      <ul>
        <li>Constructed multiple line laser scanning equipment for ceramic package substrate surfaces.</li>
        <li>Collected high-resolution point clouds for ceramic package substrate 3D inspection.</li>
      </ul>
    </div>
  </article>

  <article class="project-card">
    <img src="images/fdj.png" alt="Engine automatic assembly system">
    <div class="project-card__body">
      <div class="project-card__meta">2021.12 - 2023.09</div>
      <h3>Engine Automatic Assembly System</h3>
      <ul>
        <li>Constructed a multi-axis linkage digital installation rack vehicle.</li>
        <li>Constructed an automatic installation digital twin system for aircraft engines.</li>
      </ul>
    </div>
  </article>
</div>

# Academic Service
- *Journal Editor*, Electronics - Intelligent Sensing Empowered by Artificial Intelligence, Guest Editor.
- *Journal Reviewer*, IEEE TIP, IEEE TNNLS, IEEE TII, IEEE TIM, etc.
- *Conference Reviewer*, CVPR, ACM MM, NeurIPS, etc.

<span class="anchor" id="honors-and-awards"></span>
# Honors and Awards
- NortheasternUniversity President's Medal (only 10 students selected each year)
- First Prize of the China Invention Association Invention and Entrepreneurship Award
- Gold Award at the 11th International Invention Exhibition

# Generalist
- [Intern of Qsinghua LAMIC](http://115.28.22.69/index.php)
- [Zhihu Column Author](https://www.zhihu.com/people/guo-bing-yang-yang-yang-yang)
- [Yousan AI WeChat Official Account Author](https://mp.weixin.qq.com/s/4Nd2a2dWGvEtz9Bt9n008w)
- [CSDN Teacher](https://edu.csdn.net/lecturer/4129/course)

# Visitor Map
<img src="https://s01.flagcounter.com/map/RBG7/size_s/txt_000000/border_CCCCCC/pageviews_1/viewers_0/flags_0/" alt="Flag Counter" border="0">
