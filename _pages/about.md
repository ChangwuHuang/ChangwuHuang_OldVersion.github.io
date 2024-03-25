---
permalink: /
title: "Changwu Huang"
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


I am currently a Research Associate Professor in the [Department of Computer Science and Engineering (CSE)](https://cse.sustech.edu.cn/) at [Southern University of Science and Technology (SUSTech)](https://www.sustech.edu.cn/), Shenzhen, China. I received my Bachelor’s degree from Southwest Jiaotong University, Chengdu, China, in 2010, Master’s degree from Beijing Jiaotong University, Beijing, China, in 2013, and Ph.D. degree from Institut National des Sciences Appliquées de Rouen Normandie (INSA Rouen Normandie), Rouen, France, in 2018. Since March 2018, I have been a member of Professor [Xin Yao](https://cse.sustech.edu.cn/faculty/~xiny/)’s team at SUSTech, serving consecutively as a Postdoctoral Fellow (03/2018-09/2020), Research Assistant Professor (10/2020-09/2023), and Research Associate Professor (10/2023-Present). My research interests mainly include Artificial Intelligence Ethics (AI Ethics), Trustworthy Artificial Intelligence (Trustworthy AI), Evolutionary Computation (EC), and their practical applications.


## Research Interests

Through my educational pursuits and professional experiences, I have cultivated a robust interdisciplinary research background. During my doctoral studies, I specialized in applying AI techniques (e.g., machine learning and evolutionary algorithms) to address engineering problems, particularly uncertainty analysis, material parameter identification, and fatigue damage analysis in mechanical engineering. Transitioning into my postdoctoral role from March 2018 to September 2020, I concentrated on the automatic algorithm configuration for AI algorithms, specifically for evolutionary algorithms and other intelligent optimization algorithms. Since late 2020, my research trajectory has evolved towards the areas of AI ethics and trustworthy AI, which are not only current global research trends but also pivotal future developmental directions of AI. At present, my research is centered on AI Ethics and Trustworthy AI, with a strong emphasis on essential ethical considerations including transparency, explainability, fairness, safety, and privacy. I have published more than 30 research papers with total <a href='https://scholar.google.com/citations?user=QRnmYfkAAAAJ'>google scholar citations <strong><span id='total_cit'>500+</span></strong></a>. 

- **AI Ethics** is an emerging multidisciplinary research field that investigates ethical issues and societal impacts arising from the design, development, implementation, and use of AI technologies. My efforts span the exploration of Ethical Issues & Challenges in AI, Ethical Guidelines & Principles for AI, and AI Ethical Governance Practice. 
- **Trustworthy AI** aims to develop AI systems that are aligned with ethical principles (such as transparency, fairness, privacy, safety, security, accountability, etc.), fostering trust from users and society in AI technologies. My research is centered on Explainable Machine Learning, Fairness-Aware Machine Learning, and Privacy-Preserving Machine Learning.
- **Evolutionary Computation** is a computational methodology inspired by biological evolution and natural selection for addressing optimization and search problems. My research involves Surrogate-Assisted Evolutionary Optimization, Automatic Algorithm Configuration (Parameter Tuning), and Surrogate Modeling in engineering tasks (e.g., uncertainty analysis, fatigue damage analysis, material parameter identification). 



<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/AI_Ethics.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

I manage the WeChat public account “**AI Ethics**”. The ongoing emergence of risk issues in the development and application of Artificial Intelligence (AI) has captured substantial global attention. Emphasizing AI ethics, strengthening AI governance, and fostering trustworthy AI have evolved into a worldwide consensus. This platform is committed to disseminating information and updates concerning AI ethics, AI governance, and trustworthy AI. 

</div>
</div>

<br/>
<br/>

# 📑 Research

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/MOFAE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-objective Feature Attribution Explanation for Explainable Machine Learning](https://dl.acm.org/doi/pdf/10.1145/3617380)

Ziming Wang, **Changwu Huang**, Yun Li, Xin Yao*

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=QRnmYfkAAAAJ&sortby=pubdate&citation_for_view=QRnmYfkAAAAJ:geHnlv5EZngC) <strong><span class='show_paper_citations' data='QRnmYfkAAAAJ:geHnlv5EZngC'></span></strong>

The feature attribution-based explanation (FAE) methods, which indicate how much each input feature contributes to the model’s output for a given data point, are one of the most popular categories of explainable machine learning techniques. This work formulates the problem of creating FAE explainable models as a multi-objective learning problem that considers multiple explanation quality metrics simultaneously. Experimental results comparing with six state-of-the-art FAE methods on eight datasets demonstrate that our method can optimize multiple conflicting metrics simultaneously and can provide explanations with higher faithfulness, lower sensitivity, and lower complexity than the compared methods. Moreover, the results have shown that our method has better diversity, i.e., it provides various explanations that achieve different tradeoffs between multiple conflicting explanation quality metrics. Therefore, it can provide tailored explanations to different stakeholders based on their specific requirements.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/Overview_of_AI_Ethics.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An Overview of Artificial Intelligence Ethics](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9844014) ([Most popular article in IEEE TAI](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=9078688))

**Changwu Huang**, Zeqi Zhang, Bifei Mao, Xin Yao*

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=QRnmYfkAAAAJ&citation_for_view=QRnmYfkAAAAJ:K3LRdlH-MEoC) <strong><span class='show_paper_citations' data='QRnmYfkAAAAJ:K3LRdlH-MEoC'></span></strong>

AI ethics is an important emerging topic among academia, industry, government, society, and individuals. In the past decades, many efforts have been made to study the ethical issues in AI. This article offers a comprehensive overview of the AI ethics field, including a summary and analysis of AI ethical issues, ethical guidelines and principles, approaches to address AI ethical issues, and methods to evaluate the ethics of AI technologies. Additionally, research challenges and future perspectives are discussed. This article will help researchers to gain a birds eye view of AI ethics, and thus facilitate their further investigation and research.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/MSSP_ResNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Estimation of Probability Distribution of Long-term Fatigue Damage on Wind Turbine Tower using Residual Neural Network](https://www.sciencedirect.com/science/article/pii/S0888327023000080)

Hao Bai, Lujie Shi, Younes Aoues, **Changwu Huang***, Didier Lemosse

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=QRnmYfkAAAAJ&sortby=pubdate&citation_for_view=QRnmYfkAAAAJ:vRqMK49ujn8C) <strong><span class='show_paper_citations' data='QRnmYfkAAAAJ:vRqMK49ujn8C'></span></strong>

Fatigue is one of the most significant failure modes in structural and mechanical design. However, fatigue analysis usually suffers from two main challenges: 1) fatigue failure is hard to be predicted accurately, and 2) numerical fatigue damage estimation approaches are time-consuming. To overcome these drawbacks, this work firstly proposes a probabilistic fatigue analysis framework to estimate the fatigue damage of wind turbine tower based on numerical simulations. Then, to reduce the computational cost of numerical approach, a residual neural network (ResNet)-assisted fatigue estimation approach is designed for the assessment of long-term fatigue loads under the proposed probabilistic fatigue analysis framework, where machine learning model is used to approximate the relationship between the load (i.e., wind speed in our study case) and the fatigue damage so that a large number of simulations can be replaced by model prediction. Our proposed method is validated by numerical studies with a state-of-the-art wind turbine and has been applied in a wind turbine design with real-world wind loads.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/OAC_DE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Online Algorithm Configuration for Differential Evolution Algorithm](https://link.springer.com/article/10.1007/s10489-021-02752-1)

**Changwu Huang**, Hao Bai, Xin Yao*

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=QRnmYfkAAAAJ&sortby=pubdate&citation_for_view=QRnmYfkAAAAJ:uWQEDVKXjbEC) <strong><span class='show_paper_citations' data='QRnmYfkAAAAJ:uWQEDVKXjbEC'></span></strong>

The performance of evolutionary algorithms (EAs) is strongly affected by their configurations. Thus, algorithm configuration (AC) problem, that is, to properly set algorithm’s configuration, including the operators and parameter values for maximizing the algorithm’s performance on given problem(s) is an essential and challenging task in the design and application of EAs. In this paper, an online algorithm configuration (OAC) approach is proposed for differential evolution (DE) algorithm to adapt its configuration in a data-driven way. In our proposed OAC, the multi-armed bandit algorithm is adopted to select trial vector generation strategies for DE, and the kernel density estimation method is used to adapt the associated control parameters during the evolutionary search process. 
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/SAEA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Surrogate Models in Evolutionary Single-objective Optimization: A New Taxonomy and Experimental Study](https://www.sciencedirect.com/science/article/pii/S0020025521002395)

Hao Tong, **Changwu Huang**, Leandro L. Minku, Xin Yao

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=QRnmYfkAAAAJ&citation_for_view=QRnmYfkAAAAJ:xtRiw3GOFMkC) <strong><span class='show_paper_citations' data='QRnmYfkAAAAJ:xtRiw3GOFMkC'></span></strong>

Surrogate-assisted evolutionary algorithms (SAEAs), which use efficient surrogate models or meta-models to approximate the fitness function in evolutionary algorithms (EAs), are effective and popular methods for solving computationally expensive optimization problems. This paper dedicates to providing a more systematical review and comprehensive empirical study of surrogate models used in single-objective SAEAs. 
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/AAC_procedure.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Survey of Automatic Parameter Tuning Methods for Metaheuristics](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8733017&tag=1) ([ESI highly cited paper](https://www.webofscience.com/wos/alldb/full-record/WOS:000524328700001))

**Changwu Huang**, Yuanxiang Li, Xin Yao*

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=QRnmYfkAAAAJ&citation_for_view=QRnmYfkAAAAJ:bFI3QPDXJZMC) <strong><span class='show_paper_citations' data='QRnmYfkAAAAJ:bFI3QPDXJZMC'></span></strong>

Parameter tuning, that is, to find appropriate parameter settings (or configurations) of algorithms so that their performance is optimized, is an important task in the development and application of metaheuristics. Automating this task, i.e., developing algorithmic procedure to address parameter tuning task, is highly desired and has attracted significant attention from the researchers and practitioners. During last two decades, many automatic parameter tuning approaches have been proposed. This paper presents a comprehensive survey of automatic parameter tuning methods for metaheuristics. A new classification (or taxonomy) of automatic parameter tuning methods is introduced according to the structure of tuning methods. The existing automatic parameter tuning approaches are reviewed and their main strengths and weaknesses are discussed, which is helpful for new researchers or practitioners to select appropriate tuning methods to use.
</div>
</div>


## Pulication List
-	L. Tan, **C. Huang∗**, and X. Yao, “A Concept-Based Local Interpretable Model-agnostic Explanation Approach for Deep Neural Networks in Image Classification,” 13th International Conference on Intelligent Information Processing (IIP20204), Accepted.
-	K. Wu, **C. Huang∗**, and X. Yao∗, “[Confidence Estimation Based on the Explanations of Model’s Predictions,](https://ieeexplore.ieee.org/document/10462812)” 2023 International Conference on Neuromorphic Computing (ICNC), Wuhan, China, 2023, pp. 414-423.
-	Z. Wang, **C. Huang**, Y. Li, and X. Yao∗, “[Multi-objective Feature Attribution Explanation For Explainable Machine Learning,](https://dl.acm.org/doi/10.1145/3617380)” ACM Transactions on Evolutionary Learning and Optimization, vol. 4, no. 1, pp. 1–32, Feb. 2024.
-	**C. Huang**, Z. Zhang, B. Mao, and X. Yao∗, “[An Overview of Artificial Intelligence Ethics,](https://ieeexplore.ieee.org/document/9844014)” IEEE Transactions on Artificial Intelligence, vol. 4, no. 4, pp. 799-819, Aug. 2023. (Most Popular Article in IEEE TAI, over 23,221 views on IEEE Xplore)
-	Z. Yang, Z. Wang, **C. Huang∗**, and X. Yao, “[An Explainable Feature Selection Approach for Fair Machine Learning,](https://link.springer.com/chapter/10.1007/978-3-031-44198-1_7)” 32nd International Conference on Artificial Neural Networks, Crete, Greece, 2023, pp. 75-86. 
-	Z. Wang, **C. Huang**, and X. Yao∗, “[Feature Attribution Explanation to Detect Harmful Dataset Shift,](https://ieeexplore.ieee.org/abstract/document/10191221)” 2023 International Joint Conference on Neural Networks (IJCNN), Gold Coast, Australia, Jun. 2023, pp. 1-8.
-	S. Gui, Q. Zhang, **C. Huang**, and B. Yuan∗, “[Fairer Machine Learning Through the Hybrid of Multi-objective Evolutionary Learning and Adversarial Learning,](https://ieeexplore.ieee.org/abstract/document/10191821)” 2023 International Joint Conference on Neural Networks (IJCNN), Gold Coast, Australia, Jun. 2023, pp. 1-9.
-	H. Bai, L. Shi, Y. Aoues, **C. Huang∗**, and D. Lemosse, “[Estimation of probability distribution of long-term fatigue damage on wind turbine tower using residual neural network,](https://www.sciencedirect.com/science/article/pii/S0888327023000080?dgcid=author)” Mechanical Systems and Signal Processing, vol. 190, pp. 110101, May 2023.
-	**C. Huang**, Z. Zhang, B. Mao, and X. Yao∗, “[Preventing Undesirable Behaviors of Neural Networks via Evolutionary Constrained Learning,](https://ieeexplore.ieee.org/abstract/document/9891926)” 2022 International Joint Conference on Neural Networks (IJCNN), Padua, Italy, Jul. 2022, pp. 1-7.
-	**C. Huang**, L. Li, C. He, R. Cheng, and X. Yao, “[Adaptive multiobjective evolutionary algorithm for large-scale transformer ratio error estimation,](https://link.springer.com/article/10.1007/s12293-022-00368-7)” Memetic Computing, vol. 14, no. 2, pp. 237-251, May 2022.
-	**C. Huang**, H. Bai, and X. Yao∗, “[Online algorithm configuration for differential evolution algorithm,](https://link.springer.com/article/10.1007/s10489-021-02752-1)” Applied Intelligence, vol. 52, no. 8, pp. 9193-9211, Jan. 2022.
-	X. Yao, K. Tang, Y. Mei, J. Liu, **C. Huang**, and H. Tong, “[Capacitated Arc Routing Problems in Smart Cities,](https://www.nstl.gov.cn/paper_detail.html?id=ad122f4c2dab6cc7a2ccbc3c32976aec)” Artificial Intelligence View, vol 05, pp. 102-114, 2021.
-	H. Bai, **C. Huang**, and X. Yao∗, “[Adaptive Differential Evolution based on Exploration and Exploitation Control,](https://ieeexplore.ieee.org/document/9504876)” 2021 IEEE Congress on Evolutionary Computation (CEC), Kraków, Poland, Jun. 2021, pp. 41-48.
-	**C. Huang**, L. Li, C. He, R. Cheng∗, and X. Yao, “[Operator-Adapted Evolutionary Large-Scale Multiobjective Optimization for Voltage Transformer Ratio Error Estimation,](https://link.springer.com/chapter/10.1007/978-3-030-72062-9_53)” 11th International Conference on Evolutionary Multi-Criterion Optimization, Shenzhen, China, Mar. 2021, pp. 672-683.
-	H. Tong∗, **C. Huang**, L. L. Minku, and X. Yao∗, “[Surrogate models in evolutionary single-objective optimization: A new taxonomy and experimental study,](https://www.sciencedirect.com/science/article/pii/S0020025521002395?via%3Dihub)” Information Sciences, vol. 562, pp. 414-437, Jul. 2021.
-	H. Bai∗, D. Lemosse, Y. Aoues, J. Cherfils, and **C. Huang∗**, “[A Probabilistic Approach In Long-Term Fatigue Analysis Of Onshore Wind Turbine Tower,](https://www.scipedia.com/public/Bai_et_al_2021a)” 14th WCCM-ECCOMAS Congress, Jan. 2021, pp. 1-11.
-	**C. Huang**, Y. Li, and X. Yao∗, “[A Survey of Automatic Parameter Tuning Methods for Metaheuristics,](https://ieeexplore.ieee.org/document/8733017/authors#authors)” IEEE Transactions on Evolutionary Computation, vol. 24, no. 2, pp. 201-216, Apr. 2020. (ESI Highly Cited Paper)
-	**C. Huang**, Y. Li, and X. Yao∗, “[Online Parameter Tuned SAHiD Algorithm for Capacitated Arc Routing Problems,](https://ieeexplore.ieee.org/document/9185627)” 2020 IEEE Congress on Evolutionary Computation (CEC), Glasgow, UK, Jul. 2020, pp. 1-8.
-	**C. Huang**, Y. Li, and X. Yao∗, “[Adaptive-SAHiD Algorithm for Capacitated Arc Routing Problems,](https://ieeexplore.ieee.org/document/9002657)” 2019 IEEE Symposium Series on Computational Intelligence (SSCI), Xiamen, China, Dec. 2019, pp. 1668-1675.
-	H. Tong, S. Zhang, **C. Huang**, and X. Yao∗, “[Algorithm Portfolio for Parameter Tuned Evolutionary Algorithms,](https://ieeexplore.ieee.org/document/9003101)” 2019 IEEE Symposium Series on Computational Intelligence (SSCI), Xiamen, China, Dec. 2019, pp. 1849-1856.
-	**C. Huang**, B. Yuan, Y. Li, and X. Yao∗, “[Automatic Parameter Tuning using Bayesian Optimization Method,](https://ieeexplore.ieee.org/document/8789891)” 2019 IEEE Congress on Evolutionary Computation (CEC), Wellington, New Zealand, Jun. 2019, pp. 2090-2097.
-	H. Tong, **C. Huang**, J. Liu, and X. Yao∗, “[Voronoi-based Efficient Surrogate-assisted Evolutionary Algorithm for Very Expensive Problems,](https://ieeexplore.ieee.org/document/8789910)” 2019 IEEE Congress on Evolutionary Computation (CEC), Wellington, New Zealand, Jun. 2019, pp. 1996-2003.
-	**C. Huang∗**, B. Radi, A. El Hami, and H. Bai, “[CMA evolution strategy assisted by kriging model and approximate ranking,](https://link.springer.com/article/10.1007/s10489-018-1193-3)” Applied Intelligence, vol. 48, no. 11, pp. 4288-4304, Jun. 2018.
-	**C. Huang∗**, A. El Hami, and B. Radi, “[Metamodel-based inverse method for parameter identification: elastic-plastic damage model,](https://www.tandfonline.com/doi/full/10.1080/0305215X.2016.1206537)” Engineering Optimization, vol. 49, no. 4, pp. 633-653, Jul. 2016.
-	**C. Huang∗**, B. Radi, and A. E. Hami, “[Uncertainty analysis of deep drawing using surrogate model based probabilistic method,](https://link.springer.com/article/10.1007/s00170-016-8436-4)” The International Journal of Advanced Manufacturing Technology, vol. 86, no. 9-12, pp. 3229-3240, Feb. 2016.
-	**C. Huang∗**, A. El Hami, and B. Radi, “[Overview of Structural Reliability Analysis Methods — Part I: Local Reliability Methods,](https://www.openscience.fr/Overview-of-Structural-Reliability-Analysis-Methods-Part-I-Local-Reliability-608)” Uncertainties and Reliability of Multiphysical Systems, vol. 17, no. 1, pp. 1-10, Feb. 2017.
-	**C. Huang∗**, A. El Hami, and B. Radi, “[Overview of Structural Reliability Analysis Methods — Part II: Sampling Methods,](https://www.openscience.fr/Overview-of-Structural-Reliability-Analysis-Methods-Part-II-Sampling-Methods-610)” Uncertainties and Reliability of Multiphysical Systems, vol. 17, no. 1, pp. 1-10, Feb. 2017.
-	**C. Huang∗**, A. El Hami, and B. Radi, “[Overview of Structural Reliability Analysis Methods — Part III: Global Reliability Methods,](https://www.openscience.fr/Overview-of-Structural-Reliability-Analysis-Methods-Part-III-Global-Reliability)” Uncertainties and Reliability of Multiphysical Systems, vol. 17, no. 1, pp. 1-8, Feb. 2017.
-	**C. W. Huang**, G. X. Yang, N. J. Fu, and J. L. Xie, “[Research on Fretting Fatigue Life of Interference Fit and its Influencing Factors,](https://www.scientific.net/AMM.251.293)” Applied Mechanics and Materials, vol. 251, pp. 293-300, Dec. 2012.
-	J. L. Li, N. Xiao, **C. W. Huang**, and N. J. Fu, “[Thermal Elasto-Plastic FEM Analysis of the New Heavy-Haul Freight Car Wheel Plate,](https://www.scientific.net/AMM.251.304)” Applied Mechanics and Materials, vol. 251, pp. 304-309, Dec. 2012.
-	N. J. Fu, J. L. Xie, **C. W. Huang**, and Y. Teng, “[Research on Fatigue Properties of Grade B Steel Casted by the Resin Sand Process,](https://www.scientific.net/AMM.189.218)” Applied Mechanics and Materials, vol. 189, pp. 218-224, Jul. 2012. 



## Projects and Grants
- Joint Project between Huawei Technologies Co., Ltd. and SUSTech, “Conceptual Analysis and Path Exploration of Transparency in AI Governance” (智能系统透明治理的概念辨析及路径探索), **Principal Investigator**, 08/2023 - 08/2024.

- Youth Program of Guangdong Basic and Applied Basic Research Foundation, “Automatic Design of Evolutionary Algorithms” (进化算法的自动设计), **Principal Investigator**, 01/2020 - 12/2021.

- Shenzhen Postdoctoral Research Funding, **Principal Investigator**, 10/2020 - 10/2023

- Key Program of Guangdong Basic and Applied Basic Research Foundation, “Research on Trustworthy, Explainable, and Evolvable Intelligent Computing Theory and Methods” (可信、可解释和可进化的智能计算理论和方法研究), Core Member, 01/2023 - 12/2027.

- Joint Project between Huawei Technologies Co., Ltd. and SUSTech, “Basic Theory and Key Technologies for Trustworthy Intelligent Systems” (可信系统基础理论和关键技术), Core Member, 01/2021 - 06/2022.

- Pearl River Talent Program for Guangdong Introducing Innovative and Entrepreneurial Teams, “Reconfigurable Brain-like Intelligent Computing System” (可重构类脑智能计算系统), Member, 09/2018 - 08/2023. 



## Patents
-	Ziming Wang, **Changwu Huang**, and Xin Yao, “A Data Set Shift Identification Method Based on Feature Attribution Explanation Techniques” (一种基于特征归因解释技术的数据集偏移识别方法), CN202310410718.7, 2023.

-	Chao Pan, **Changwu Huang**, Bo Yuan, Xin Yao, “Method, Apparatus, Device, and Storage Medium for Automatic Acquisition of Case Information” (案件信息的自动获取方法、装置、设备和存储介质), CN202010590436.6, 2020.



<br/>
<br/>

# 🏫 Experiences

## Education Experience
- 09/2013 -- 02/2018, Ph.D. in Mechanics, [INSA Rouen Normandie](https://www.insa-rouen.fr/), France.
  - Dissertation Title: [Kriging-Assisted Evolution Strategy for Optimization and Application in Material Parameters Identification](https://theses.hal.science/tel-03669789/).
  - Laboratory: [Laboratoire de Mécanique de Normandie (LMN)](https://www.insa-rouen.fr/recherche/laboratoires/lmn)
  - Supervisor: Abdelkhalak EL HAMI

- 09/2010 -- 01/2013, M.S. in Vehicle Engineering, [Beijing Jiaotong University (BJTU)](https://www.bjtu.edu.cn/), China.
  - Recommended for the UT-INSA Ph.D. program founded by the China Scholarship Council.

- 09/2006 -- 06/2010, B.S. in Vehicle Engineering, [Southwest Jiaotong University (SWJTU)](https://www.swjtu.edu.cn/), China.
    - Graduated with honor as Outstanding Graduate of Sichuan Province.
    - Recommended for admission to postgraduate study, exempted from the Admission Examination.


## Work Experience
- 10/2023 -- Present, Research Associate Professor (Master Supervisor), Department of CSE, SUSTech, Shenzhen, China.
  - OPtimization And Learning (OPAL) Laboratory, led by Prof. [Xin Yao](https://cse.sustech.edu.cn/faculty/~xiny/)

- 10/2020 -- 09/2023, Research Assistant Professor (Master Supervisor), Department of CSE, SUSTech, Shenzhen, China.
    - OPtimization And Learning (OPAL) Laboratory, led by Prof. [Xin Yao](https://cse.sustech.edu.cn/faculty/~xiny/)

- 03/2018 -- 09/2020, Postdoctoral Researcher, Department of CSE, SUSTech, Shenzhen, China.
    - Cooperation Supervisor: Prof. [Xin Yao](https://cse.sustech.edu.cn/faculty/~xiny/)


<br/>
<br/>

# 🎖️ Honors and Awards
- Our paper “An Overview of Artificial Intelligence Ethics” was selected as the Excellent Science & Technology Academic Paper by the Shenzhen Association for Science and Technology (深圳市第二届优秀科技学术论文奖), 2022. 

- Scholarship from China Scholarship Council (CSC) to pursue Ph.D. study, 2013-2017.

- First-Class Graduate Student Fellowship of BJTU, 2011.

- Outstanding University Graduate of Sichuan Province, 2010.

- Outstanding Undergraduate Graduate Design & Thesis of SWJTU, 2010.

- National Scholarship, 2006 and 2009.


<br/>
<br/>

# 👨‍🏫 Invited Talks
- December 2023, I was invited to participate in the New Generation of Artificial Intelligence and Education expert consultation seminar ([“新一代人工智能与教育”专家咨询研讨会](https://efuture.sustech.edu.cn/news/detail/753.html?lang=zh-cn)), and delivered a keynote talk on the topic of “The Talent View of AI Era: Combining Virtue with Abilities”(AI 时代德才兼备的人才观).

- July 2023, I was invited to give a lecture on “Ethics and Safety in the AI Era” (AI 时代的伦理与安全) at the training program for principals on AI education leadership enhancement in Shenzhen primary and secondary schools ([“深圳市中小学校长人工智能教育领导力提升研训”培训班](https://efuture.sustech.edu.cn/news/detail/741.html?lang=zh-cn)).

- July 2023, I was invited to deliver a lecture on “AI Ethics and Safety” (AI 伦理与安全) at the training program for outstanding teachers in Shenzhen primary and secondary schools to improve their teaching capabilities ([“深圳市中小学骨干教师教学能力提升研训”培训班](https://efuture.sustech.edu.cn/news/detail/747.html?lang=zh-cn)).

- October 2022, I was invited to present a keynote talk titled “An Overview of Artificial Intelligence Ethics” (人工智能伦理研究现状) at the 2022 AI Ethics Governance Forum ([2022 年人工智能伦理治理论坛](https://saai.net.cn/2464.html)) organized by the Shenzhen Association for Artificial Intelligence (SAAI).


<br/>
<br/>

# 🖥️ Professional Service
-	Core member of the Artificial Intelligence Education Research Center, Southern University of Science and Technology ([南方科技大学人工智能教育研究中心](https://efuture.sustech.edu.cn/news/detail/744.html?lang=zh-cn)), since October 2023.

-	Session Chair for the Neural Networks and Intelligent Algorithms session at the [International Conference on Neuromorphic Computing (ICNC2023)](http://icnc2023.org/), December 2023.

-	Secretary Member of the AI Ethics Governance Committee of [Shenzhen Association for Artificial Intelligence (SAAI)](https://saai.net.cn/) (深圳市人工智能学会AI伦理治理专委会秘书委员), since November 2022.

-	Member of the Institute of Electrical and Electronics Engineers (IEEE), since October 2019.

-	Member of Chinese Association for Artificial Intelligence (CAAI), since September 2022.

-	Member of China Computer Federation (CCF), since October 2021.

-	Reviewer for international journals such as IEEE TEVC, IEEE TAI, Knowledge-Based Systems, Memetic Computing, etc.
