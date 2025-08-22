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

I am a professor at the College of Computer Science, Chongqing University, Chongqing, China. I received the B.S. and Ph.D. degrees in Control Science and Engineering from Tsinghua University, Beijing, China, in 2010 and 2016 respectively. Currently, I am doing the Marie Sklodowska-Curie Fellow with the University of Exeter, Exeter, United Kingdom, under the project "KEEN: Knowledge-Driven Explainable Misinformation Detection for Trustworthy Computational Social Systems". I have published 90+ high quality journal and conference articles, including TKDE, TNNLS, TITS, TETC, TCSS, PR, DASFAA, HPCA, DAC, DATE, etc. These publications have generated 1600+ citations in Google scholar. I serve as a reviewer for several top journals and conferences, including TPAMI, TKDE, TCAD, TNNLS, TITS, KDD, AAAI, etc. I have served as a sension/workshop chair and TPC member for several prestigious conferences, including WASA'2017, HHME'2020, ICC'2019, DSONAM'2020, etc.
 <a href='https://scholar.google.com/citations?user=PC59Mr0AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>。

My research interest includes:
- Industrial Big Data Analytics
- Social Network Analysis
- Data Mining
- Machine Learning
- Explainable AI
- Graph Neural Networks
- Flight Data Analysis
  
# 📢 Updates
- [2025.07] One paper on information popularity prediction was accepted by **TKDE** (JCR Q1, IF=10.4)
- [2025.06] One paper on information diffusion prediction was accepted by **Knowledge-Based Systems** (JCR Q1, IF=7.6)
- [2025.05] One paper on flight data anlysis was accepted by **TITS** (JCR Q1, IF=8.4)
- [2025.04] One paper on flight data analysis was accepted by **EAAI** (JCR Q1, IF=8.0)
- [2025.03] One paper on aspect sentiment triplet extraction was accepted by **Data Science and Engineering** (JCR Q1, IF=4.6)
- [2025.02] One paper on wargame data mining was accepted by **Acta Automatica Sinica** (自动化学报, CCF-A类中文期刊)
 
<span class='anchor' id='employment'></span>

# 💼 Employment
- *2024.06 - now*, <a href="https://www.exeter.ac.uk/"><img class="png" src="/images/EXEU_logo.png" width="23pt"></a> Marie Curie Postdoctoral Research Fellow, Department of Computer Science, University of Exeter, U.K.
- *2023.09 - now*, <a href="https://www.cqu.edu.cn/"><img class="png" src="/images/CQU_logo.png" width="23pt"></a> Professor, College of Computer Science, Chongqing University, Chongqing China.
- *2018.09 - 2023.08*, <a href="https://www.cqu.edu.cn/"><img class="png" src="/images/CQU_logo.png" width="23pt"></a> Associate Professor, College of Computer Science, Chongqing University, Chongqing China.
- *2016.02 - 2018.08*, <a href="https://www.cqu.edu.cn/"><img class="png" src="/images/CQU_logo.png" width="23pt"></a> Lecturer, College of Computer Science, Chongqing University, Chongqing China.
- *2014.09 - 2015.01*, <a href="https://www.cityu.edu.hk/"><img class="jpg" src="/images/CityU_logo.jpg" width="23pt"></a> Research Assistant, Department of Information Systems, City University of Hong Kong, Hong Kong China.
 
<span class='anchor' id='educations'></span>

# 🎓 Educations
- *2010.09 - 2016.01*, <a href="https://www.tsinghua.edu.cn/"><img class="svg" src="/images/THU_logo.svg" width="23pt"></a> PhD Degree, Control Science and Engineering, Tsinghua University, Beijing China.
- *2006.09 - 2010.07*, <a href="https://www.tsinghua.edu.cn/"><img class="svg" src="/images/THU_logo.svg" width="23pt"></a> Bachelor Degree, Department of Automation, Tsinghua University, Beijing China.

<span class='anchor' id='publications'></span>

# 📝 Selected Publications

### English (\*Corresponding author)
---
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TKDE 2025</div><img src='images/DVCAE_TKDE.png' alt="DVCAE" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	`Jiaxing Shang*`, Xueqi Jia, Xiaoquan Li, Fei Hao, Ruiyuan Li, Geyong Min. DVCAE: Semi-Supervised Dual Variational Cascade Autoencoders for Information Popularity Prediction. *IEEE Transactions on Knowledge and Data Engineering*, 2025. (JCR Q1; IF=10.4)
[[HTML]](https://ieeexplore.ieee.org/abstract/document/11087707) [[Code]](https://github.com/jxshang/DVCAE)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TITS 2025</div><img src='images/TF-QAR-TITS.png' alt="TF-QAR" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	Jiongbiao Cai, `Jiaxing Shang*`, Xu Li, Chengxiang Li, Linjiang Zheng. Fine-Grained Time and Hidden Feature Learning for Interpretable Hard Landing Prediction Based on QAR Data. *IEEE Transactions on Intelligent Transportation Systems*. 2025. (JCR Q1; IF=8.4)  
[[HTML]](https://ieeexplore.ieee.org/abstract/document/11015832) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KBS 2025</div><img src='images/SDVD_KBS.png' alt="SDVD" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	Haoyu Xiong, `Jiaxing Shang*`, Fei Hao, Dajiang Liu, Geyong Min. SDVD: Self-supervised dual-view modeling of user and cascade dynamics for information diffusion prediction. *Knowledge-Based Systems*. 2025, 326(27): 114005. (JCR Q1; IF=7.6)  
[[HTML]](https://www.sciencedirect.com/science/article/abs/pii/S0950705125010500) [[Code]](https://github.com/jxshang/SDVD) 

</div>
</div>


- Xinyuan Zhu, Fei Hao\*, Ming Lei, Aziz Nasridinov, `Jiaxing Shang`, Zhengxin Yu, Longjiang Guo. *Future Generation Computer Systems*. 2026, 175: 108033. (JCR Q1; IF=6.1)  
[[HTML]](https://www.sciencedirect.com/science/article/abs/pii/S0167739X25003280)


- `Jiaxing Shang*`, Xiaoquan Li, Ruixiang Zhang, Linjiang Zheng, Xu Li, Riquan Zhang, Xinbin Zhao, Fan Li, Hong Sun. A Dual Two-Stage Attention-based Model for Interpretable Hard Landing Prediction from Flight Data. *Engineering Applications of Artificial Intelligence*. 2025,154(15): 110911. (JCR Q1; IF=8.0)  
[[HTML]](https://www.sciencedirect.com/science/article/abs/pii/S095219762500911X) [[Code]](https://github.com/jxshang/DUTSAM)


- `Jiaxing Shang*`, Yuxuan Zhang, Linyang Zhong, Ruiyuan Li. Syntactic-Enhanced Multi-Task Learning Model for Aspect Sentiment Triplet Extraction. *Data Science and Engineering*. 2025. (JCR Q1; IF=4.6)  
[[HTML]](https://link.springer.com/article/10.1007/s41019-025-00289-8)


- Lei Song, Xu Li, Hongtao Liu, Lin Wu, Hong Sun, Linjiang Zheng\*, `Jiaxing Shang*`. MDGNN: Multiple Flight Safety Incidents Prediction Model Based on Dynamic Graph Neural Networks. *IEEE Transactions on Intelligent Transportation Systems*. 2025, 26(4): 5598-5612. (JCR Q1; IF=8.4)  
[[HTML]](https://ieeexplore.ieee.org/abstract/document/10923645)


- Longquan Liao, Linjiang Zheng\*, `Jiaxing Shang`, Xu Li, Fengwen Chen. ATPF: An Adaptive Temporal Perturbation Framework for Adversarial Attacks on Temporal Knowledge Graph. *IEEE Transactions on Knowledge and Data Engineering*. 2025, 37(3): 1091-1104. (JCR Q1; IF=10.4)  
[[HTML]](https://ieeexplore.ieee.org/abstract/document/10777929)


- Xiaojuan Yang,  `Jiaxing Shang*`, Qinghong Hu, Dajiang Liu. ARIS: Efficient admitted influence maximizing in large-scale networks based on valid path reverse influence sampling. *IEEE Transactions on Emerging Topics in Computing*. 2024, 12(3): 700-714. (JCR Q1; IF=5.4)  
[[HTML]](https://ieeexplore.ieee.org/abstract/document/10777929)


- Yincheng Han, Dajiang Liu, `Jiaxing Shang*`, Linjiang Zheng, Jiang Zhong, Weiwei Cao, Hong Sun, Wu Xie. BALQUE: Batch active learning by querying unstable examples with calibrated confidence. *Pattern Recognition*. 2024, 151: 110385. (JCR Q1; IF=7.6)  
[[HTML]](https://www.sciencedirect.com/science/article/abs/pii/S0031320324001365) [[Code]](https://github.com/zkoladzl/balque)


- Dajiang Liu\*, Decai Pan, Xiao Xiong, `Jiaxing Shang`, Shouyi Yin. PMP: Pattern Morphing-based Memory Partitioning in High-Level Synthesis. *Proceedings of the 61st ACM/IEEE Design Automation Conference*. 2024.
[[HTML]](https://dl.acm.org/doi/abs/10.1145/3649329.3658239)


- Hong Yin, Jiang Zhong\*, Rongzhen Li, `Jiaxing Shang`, Chen Wang, Xue Li. High-order neighbors aware representation learning for knowledge graph completion. *IEEE Transactions on Neural Networks and Learning Systems*. 2024, 36(3): 5273-5287. (JCR Q1, IF=8.9)
[[HTML]](https://ieeexplore.ieee.org/abstract/document/10506111)


- Xu Li, `Jiaxing Shang*`, Linjiang Zheng\*, Qixing Wang, Dajiang Liu, Xiaodong Liu, Fan Li, Weiwei Cao, Hong Sun. IMTCN: An Interpretable Flight Safety Analysis and Prediction Model Based on Multi-Scale Temporal Convolutional Networks. *IEEE Transactions on Intelligent Transportation Systems*. 2024, 25(1): 289-302. (JCR Q1, IF=8.4)
[[HTML]](https://ieeexplore.ieee.org/abstract/document/10251795)


- Mengya Guan, Xinjun Cai, `Jiaxing Shang*`, Fei Hao, Dajiang Liu, Xianlong Jiao, Wancheng Ni. HMSG: Heterogeneous graph neural network based on metapath subgraph learning. *Knowledge-Based Systems*. 2023, 279: 110930. (JCR Q1; IF=7.6)  
[[HTML]](https://www.sciencedirect.com/science/article/abs/pii/S0950705123006809) [[Code]](https://github.com/junxincai/HMSG)


- Haodong Chen, `Jiaxing Shang*`, Linjiang Zheng\*, Xu Li, Xiaodong Liu, Hong Sun, Xinbin Zhao, Liling Yu. SDTAN: Scalable Deep Time-Aware Attention Network for Interpretable Hard Landing Prediction. *IEEE Transactions on Intelligent Transportation Systems*. 2023, 24(9): 10211-10223. (JCR Q1; IF=8.4)  
[[HTML]](https://www.sciencedirect.com/science/article/abs/pii/S0950705123006809)


- Xueqi Jia, `Jiaxing Shang*`, Dajiang Liu, Haidong Zhang, Wancheng Ni\*. HeDAN: Heterogeneous diffusion attention network for popularity prediction of online content. *Knowledge-Based Systems*. 2022, 254: 109659. (JCR Q1; IF=7.6)  
[[HTML]](https://www.sciencedirect.com/science/article/abs/pii/S0950705123006809)


- Ziwei Jin, `Jiaxing Shang*`, Wancheng Ni*, Liang Zhao, Dajiang Liu, Baohua Qiang, Wu Xie, Geyong Min. IM2Vec: Representation learning-based preference maximization in geo-social networks. *Information Sciences*. 2022, 604: 170-196. (JCR Q1; IF=6.8)  
[[HTML]](https://www.sciencedirect.com/science/article/abs/pii/S0020025522004200)


- Xu Li, `Jiaxing Shang*`, Linjiang Zheng\*, Qixing Wang, Hong Sun, Lin Qi. Curvecluster+: Curve clustering for hard landing pattern recognition and risk evaluation based on flight data. *IEEE Transactions on Intelligent Transportation Systems*. 2022, 23(8): 12811-12821. (JCR Q1; IF=8.4)  
[[HTML]](https://ieeexplore.ieee.org/abstract/document/9569759)


- Xianren Zhang, `Jiaxing Shang*`, Xueqi Jia, Dajiang Liu, Fei Hao, Zhiqing Zhang. CollaborateCas: popularity prediction of information cascades based on collaborative graph attention networks. *International Conference on Database Systems for Advanced Applications*. 2022, 714-721.   
[[HTML]](https://link.springer.com/chapter/10.1007/978-3-031-00123-9_56)


- `Jiaxing Shang*`, Shangbo Zhou, Xin Li, Lianchen Liu, Hongchun Wu. CoFIM: A community-based framework for influence maximization on large-scale networks. *Knowledge-Based Systems*. 2017, 117: 88-100. (JCR Q1, IF=7.6)   
[[HTML]](https://www.sciencedirect.com/science/article/abs/pii/S0950705116303598) [[Code]](https://sourceforge.net/projects/cofim-com-based-fast-influ-max/)


### Chinese
---
- 陈露, `尚家兴*`, 刘大江, 张玉芳, 倪晚成. 基于异构图神经网络的可解释兵棋态势预测方法. *自动化学报*. 2025, 51(6): 1248-1260. (**CCF-A**)  
[[HTML]](https://www.aas.net.cn/article/doi/10.16383/j.aas.c240468)

- 潘德财, 牟迪, `尚家兴`, 刘大江\*. 基于访存图案变形的CGRA存储划分优化. *计算机研究与发展*. 2025, 62(4): 1003-1016. (**CCF-A**)  
[[HTML]](https://crad.ict.ac.cn/article/doi/10.7544/issn1000-1239.202440079)

- 冯永\*, 张春平, 强保华, 张逸扬, `尚家兴`. GP-WIRGAN: 梯度惩罚优化的Wasserstein图像循环生成对抗网络模型. *计算机学报*. 2020, 2: 190-205. (**CCF-A**)  
[[HTML]](http://cjc.ict.ac.cn/qwjs/view.asp?id=5296) [[PDF]](http://cjc.ict.ac.cn/online/onlinepaper/fy-2020119220733.pdf)


- 冯永\*, 张备, 强保华, 张逸扬, `尚家兴`. MN-HDRM：长短兴趣多神经网络混合动态推荐模型. *计算机学报*. 2019, 1: 16-28. (**CCF-A**)  
[[HTML]](http://cjc.ict.ac.cn/qwjs/view.asp?id=5111) [[PDF]](http://cjc.ict.ac.cn/online/onlinepaper/fy-201916190947.pdf)


<span class='anchor' id='honors-and-awards'></span>

# 🏅 Honors and Awards
- *2023.02* Marie Sklodowska-Curie Postdoctoral Fellowship (Acceptance rate: 17.53%)
- *2022.09* Outstanding Young Teacher Award, Chongqing University
- *2021* IEEE Outstanding Service Award as Invited Talk Speaker of the 20th IEEE International Conference on Trust, Security and Privacy in Computing and Communications (TrustCom’2021).
- *2021* IEEE Outstanding Service Award as Workshop Chair of the 15th IEEE International Conference on Big Data Science and Engineering (BigDataSE’2021).
- *2021* IEEE Outstanding Service Award as Workshop Chair of the 3rd International Workshop on Machine Learning assisted Smart System (MLSys’2021).
- *2021* IEEE Outstanding Service Award as General Chair of the 4th International Workshop on Next Generation Data-driven Networks (NGDN’2021).
- *2020* IEEE Outstanding Service Award as Workshop Chair of the 1st International Workshop on Data-driven Social Network Analysis and Mining: Algorithms and Applications (DSONAM’2020).
- *2019* IEEE Outstanding Service Award as Workshop Chair of the 2nd International Workshop on Next Generation Data-driven Networks (NGDN’2019).

<span class='anchor' id='conferences'></span>

# 🏛️ Conferences
- *2022.10*, The 18th EAI International Conference on Collaborative Computing: Networking, Applications and Worksharing (CollaborateCom 2022), Oral.
- *2022.08*, International Conference on Knowledge Science, Engineering and Management (KSEM 2022), Oral.
- *2022.07*, The 34th International Conference on Software Engineering and Knowledge Engineering (SEKE 2022), Oral.
- *2022.04*, International Conference on Database Systems for Advanced Applications (DASFAA 2022), Oral.
- *2021.10*, The 20th IEEE International Conference on Trust, Security and Privacy in Computing and Communications (TrustCom’2021), Invited Talk.
- *2021.06*, 2021 22nd IEEE International Conference on Mobile Data Management (MDM), Oral.
- *2020.10*, The 21st International Conference on Web Information Systems Engineering (WISE 2020), Oral.
- *2018.12*, The 25th International Conference on Neural Information Processing (ICONIP 2018), Oral.
- *2017.11*, The 24th International Conference on Neural Information Processing (ICONIP 2017), Oral.
- *2017.06*, The 12th International Conference on Wireless Algorithms, Systems, and Applications (WASA 2017), Oral.

<span class='anchor' id='keen-project'></span>

# 💻 Keen Project
- *2025.08*, We have a paper on fake news detection submitted to *WSDM 2026*.
- *2025.06*, We have a paper on information diffusion prediction accepted by *Knowledge-Based Systems* (JCR Q1, IF=7.6).
- *2025.04*, We have a paper on fake news detection submitted to *IEEE Transactions on Knowledge and Data Engineering*.


