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

Through my educational pursuits and professional experiences, I have cultivated a robust interdisciplinary research background. During my doctoral studies, I specialized in applying AI techniques (e.g., machine learning and evolutionary algorithms) to address engineering problems, particularly uncertainty analysis, material parameter identification, and fatigue damage analysis in mechanical engineering. Transitioning into my postdoctoral role from March 2018 to September 2020, I concentrated on the automatic algorithm configuration for AI algorithms, specifically for evolutionary algorithms and other intelligent optimization algorithms. Since late 2020, my research trajectory has evolved towards the areas of AI ethics and trustworthy AI, which are not only current global research trends but also pivotal future developmental directions of AI. At present, my research is centered on AI Ethics and Trustworthy AI, with a strong emphasis on essential ethical considerations including transparency, explainability, fairness, safety, and privacy. I have published more than 30 research papers with total <a href='https://scholar.google.com/citations?user=QRnmYfkAAAAJ'>google scholar citations <strong><span id='total_cit'>600+</span></strong></a>. 

- **AI Ethics** is an emerging multidisciplinary research field that investigates ethical issues and societal impacts arising from the design, development, implementation, and use of AI technologies. My efforts span the exploration of Ethical Issues and Challenges in AI, Ethical Guidelines and Principles for AI, and AI Ethical Governance Practice.

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
-	L. Tan, **C. Huang∗**, and X. Yao, “[A Concept-Based Local Interpretable Model-agnostic Explanation Approach for Deep Neural Networks in Image Classification,](https://link.springer.com/chapter/10.1007/978-3-031-57919-6_9)” Intelligent Information Processing XII, pp. 119-133, 2024.
-	Z. Wang, **C. Huang**, Y. Li, and X. Yao∗, “[Multi-objective Feature Attribution Explanation For Explainable Machine Learning,](https://dl.acm.org/doi/10.1145/3617380)” ACM Transactions on Evolutionary Learning and Optimization, vol. 4, no. 1, pp. 1–32, Feb. 2024.
-	K. Wu, **C. Huang∗**, and X. Yao∗, “[Confidence Estimation Based on the Explanations of Model’s Predictions,](https://ieeexplore.ieee.org/document/10462812)” 2023 International Conference on Neuromorphic Computing (ICNC), Wuhan, China, 2023, pp. 414-423.
-	**C. Huang**, Z. Zhang, B. Mao, and X. Yao∗, “[An Overview of Artificial Intelligence Ethics,](https://ieeexplore.ieee.org/document/9844014)” IEEE Transactions on Artificial Intelligence, vol. 4, no. 4, pp. 799-819, Aug. 2023. (<font color=blue>Most Popular Article in IEEE TAI</font>)
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
-	**C. Huang**, Y. Li, and X. Yao∗, “[A Survey of Automatic Parameter Tuning Methods for Metaheuristics,](https://ieeexplore.ieee.org/document/8733017/authors#authors)” IEEE Transactions on Evolutionary Computation, vol. 24, no. 2, pp. 201-216, Apr. 2020. (<font color=blue>ESI Highly Cited Paper</font>)
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

# 🏆 Honors and Awards
- Our paper “A Concept-Based Local Interpretable Model-agnostic Explanation Approach for Deep Neural Networks in Image Classification” achieved the <font color=blue>Best Student Paper Award</font> in 13th International Conference on Intelligent Information Processing (IIP 2024), 2024.

- Our paper “An Overview of Artificial Intelligence Ethics” was selected as the <font color=blue>Excellent Science and Technology Academic Paper</font> by the Shenzhen Association for Science and Technology (深圳市第二届优秀科技学术论文奖), 2022. 

- Scholarship from China Scholarship Council (CSC) to pursue Ph.D. study, 2013-2017.

- First-Class Graduate Student Fellowship of BJTU, 2011.

- Outstanding University Graduate of Sichuan Province, 2010.

- Outstanding Undergraduate Graduate Design and Thesis of SWJTU, 2010.

- National Scholarship, 2006 and 2009.


<br/>
<br/>

# 🧑‍🏫 Invited Talks
- December 2023, I was invited to participate in the New Generation of Artificial Intelligence and Education expert consultation seminar ([“新一代人工智能与教育”专家咨询研讨会](https://efuture.sustech.edu.cn/news/detail/753.html?lang=zh-cn)), and delivered a keynote talk on the topic of “The Talent View of AI Era: Combining Virtue with Abilities”(AI 时代德才兼备的人才观).

- July 2023, I was invited to give a lecture on “Ethics and Safety in the AI Era” (AI 时代的伦理与安全) at the training program for principals on AI education leadership enhancement in Shenzhen primary and secondary schools ([“深圳市中小学校长人工智能教育领导力提升研训”培训班](https://efuture.sustech.edu.cn/news/detail/741.html?lang=zh-cn)).

- July 2023, I was invited to deliver a lecture on “AI Ethics and Safety” (AI 伦理与安全) at the training program for outstanding teachers in Shenzhen primary and secondary schools to improve their teaching capabilities ([“深圳市中小学骨干教师教学能力提升研训”培训班](https://efuture.sustech.edu.cn/news/detail/747.html?lang=zh-cn)).

- October 2022, I was invited to present a keynote talk titled “An Overview of Artificial Intelligence Ethics” (人工智能伦理研究现状) at the 2022 AI Ethics Governance Forum ([2022 年人工智能伦理治理论坛](https://saai.net.cn/2464.html)) organized by the Shenzhen Association for Artificial Intelligence (SAAI).


<br/>
<br/>

# 💻 Professional Service
-	Member of the First Medical Artificial Intelligence Ethics Committee of “Chinese Medical Ethics” (《中国医学伦理学》第一届[医学人工智能伦理专委会](https://mp.weixin.qq.com/s/fQlfktkta3muEz6MMJaY5Q)委员), since May 2024.

-	Chair of the Session on “Machine Learning”  at 13th IFIP International Conference on Intelligent Information Processing, Shenzhen, May 2024.
	
-	Core member of the Artificial Intelligence Education Research Center, Southern University of Science and Technology ([南方科技大学人工智能教育研究中心](https://efuture.sustech.edu.cn/news/detail/744.html?lang=zh-cn)), since October 2023.

-	Chair of the Session on "Neural Networks and Intelligent Algorithms" at the [International Conference on Neuromorphic Computing (ICNC2023)](http://icnc2023.org/), December 2023.

-	Secretary Member of the AI Ethics Governance Committee of [Shenzhen Association for Artificial Intelligence (SAAI)](https://saai.net.cn/) (深圳市人工智能学会AI伦理治理专委会秘书委员), since November 2022.

-	Member of the Institute of Electrical and Electronics Engineers (IEEE), since October 2019.

-	Member of Chinese Association for Artificial Intelligence (CAAI), since September 2022.

-	Member of China Computer Federation (CCF), since October 2021.

-	Reviewer for international journals such as IEEE TEVC, IEEE TAI, Knowledge-Based Systems, Memetic Computing, etc.


<br/>
<br/>

# 🌐 Resources

## AI Ethics relevant documents (Name of document, Issuer, Year)
-	[Recommendation on the Ethics of Artificial Intelligence](https://en.unesco.org/artificial-intelligence/ethics ), UNESCO, 2021.
-	[A guide to good practice for digital and data-driven health technologies](https://www.gov.uk/government/publications/code-of-conduct-for-data-driven-health-and-care-technology/initial-code-of-conduct-for-data-driven-health-and-care-technology), Government of United Kingdom, 2021.
-	[Data Ethics Impact Assessment](https://dataethics.eu/wp-content/uploads/dataethics-impact-assessment-2021.pdf), DataEthics.eu, 2021.
-	[Responsible AI: From Principles to Practice](https://www.accenture.com/us-en/insights/artificial-intelligence/responsible-ai-principles-practice), Accenture, 2021.
-	[Ethical Principles for Artificial Intelligence](https://www.ai.mil/docs/Ethical_Principles_for_Artificial_Intelligence.pdf), U.S. Department of Defense, 2020.
-	[Turkcell Artificial Intelligence Principles](https://www.turkcell.com.tr/en/aboutus/corporate-social-responsibility/turkcell-artificial-intelligence-principles-), Turkcell, 2020.
-	[Guidance for Regulation of Artificial Intelligence Applications](https://www.whitehouse.gov/wp-content/uploads/2020/11/M-21-06.pdf), The White House Office of Science and Technology Policy (OSTP), United States, 2020.
-	[Rome Call For AI Ethics](https://www.romecall.org/), The Pontifical Academy for Life, Microsoft, IBM, FAO, the Italian Ministry of Innovation, 2020.
-	[OECD Principles on AI](https://www.oecd.org/going-digital/ai/principles/), The Organisation for Economic Co-operation and Development (OECD), 2020.
-	[A Framework For The Ethical Use Of Advanced Data Science Methods In The Humanitarian Sector](https://5f2cd2ba-741c-4b29-ae47-00a8291b1d3c.filesusr.com/ugd/d1cf5c_6af8feb771194453817d62c92cee2a21.pdf), The Humanitarian Data Science and Ethics Group (DSEG), 2020.
-	[“ARCC”: An Ethical Framework for Artificial Intelligence](https://www.tisi.org/13747), Tencent Research Institute, 2020.
-	[Code of Ethics](https://pocketconfidant.com/code-of-ethics/), PocketConfidant AI, 2020.
-	[Model AI Governance Framework (Second Edition)](https://www.pdpc.gov.sg/-/media/files/pdpc/pdf-files/resource-for-organisation/ai/sgmodelaigovframework2.pdf), Personal Data Protection Commission (PDPC), Singapore, 2020.
-	[The Morals of Algorithms – A contribution to the ethics of AI systems](https://www.nxp.com/docs/en/white-paper/AI-ETHICAL-FRAMEWORK-WP.pdf), NXP Semiconductors, 2020.
-	[Ethics Framework ](https://www.migarage.ai/ethics/ethics-framework/), Machine Intelligence Garage’s Ethics Committee, 2020.
-	[Ethical Principles](https://koahealth.com/legal/ethical-principles), Koa Health, 2020.
-	[Responsible AI: A Roadmap For The Enterprise](https://integrate.ai/resources/responsible-ai/), Integrate.AI, 2020.
-	[Advancing AI ethics beyond compliance - From principles to practice](https://www.ibm.com/thought-leadership/institute-business-value/report/ai-ethics), IBM, 2020.
-	[Assessment List for Trustworthy Artificial Intelligence (ALTAI) for self-assessment](https://digital-strategy.ec.europa.eu/en/library/assessment-list-trustworthy-artificial-intelligence-altai-self-assessment), High-Level Expert Group on Artificial Intelligence (AI HLEG), 2020.
-	[Data Ethics Framework](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/923108/Data_Ethics_Framework_2020.pdf), Government Digital Service, 2020.
-	[White Paper on Artificial Intelligence: a European approach to excellence and trust](https://ec.europa.eu/info/publications/white-paper-artificial-intelligence-european-approach-excellence-and-trust_en), European Commission, 2020.
-	[White Paper on Data Ethics in Public Procurement of AI-based Services and Solutions](https://dataethics.eu/wp-content/uploads/dataethics-whitepaper-april-2020.pdf), DataEthics.eu, 2020.
-	[Bosch code of ethics for AI](https://www.bosch.com/stories/ethical-guidelines-for-artificial-intelligence/), Bosch, 2020.
-	[Seven principles for AI: BMW Group sets out code of ethics for the use of artificial intelligence](https://www.press.bmwgroup.com/global/article/detail/T0318411EN/seven-principles-for-ai:-bmw-group-sets-out-code-of-ethics-for-the-use-of-artificial-intelligence?language=en), BMW, 2020.
-	[Using artificial intelligence to make decisions: Addressing the problem of algorithmic bias](https://www.infogovanz.com/ai-ethics/using-artificial-intelligence-to-make-decisions-addressing-the-problem-of-algorithmic-bias/), Australian Human Rights Commission, 2020.
-	[AI4People's 7 AI Global Frameworks](https://ai4people.eu/wp-content/pdf/AI4People7AIGlobalFrameworks.pdf), AI4People, 2020.
-	[From Principles to Practice – An interdisciplinary framework to operationalise AI ethics](https://www.ai-ethics-impact.org/en), AI Ethics Impact Group (AIEI Group), 2020.
-	[Ethical Application of Artificial Intelligence Framework ](https://www.actiac.org/act-iac-white-paper-ethical-application-ai-framework), ACT-IAC Emerging Technology COI, 2020.
-	[10 Principles of Responsible AI](https://womenleadinginai.org/wp-content/uploads/2019/02/WLiAI-Report-2019.pdf), Women Leading in AI, 2019.
-	[US Chamber of Commerce: Principles on Artificial Intelligence](https://iapp.org/media/pdf/resource_center/chamber_ai_principles_-_general.pdf), The U.S. Chamber of Commerce, 2019.
-	[Understanding Artificial Intelligence Ethics and Safety](https://www.turing.ac.uk/sites/default/files/2019-06/understanding_artificial_intelligence_ethics_and_safety.pdf), The Alan Turing Institute, 2019.
-	[Guiding Principles on Trusted AI Ethics](https://www.teliacompany.com/globalassets/telia-company/documents/about-telia-company/public-policy/2018/guiding-principles-on-trusted-ai-ethics.pdf), Telia Company, 2019.
-	[Dutch Artificial Intelligence Manifesto](http://ii.tudelft.nl/bnvki/wp-content/uploads/2019/09/Dutch-AI-Manifesto-2019.pdf), Special Interest Group on Artificial Intelligence (SIGAI), ICT Platform Netherlands (IPN), 2019.
-	[Principles for AI Ethics](https://research.samsung.com/artificial-intelligence), Samsung, 2019.
-	[AI Ethics](https://einstein.ai/ethics), Salesforce, 2019.
-	[Artificial Intelligence (AI) in Health](https://www.aomrc.org.uk/wp-content/uploads/2019/01/Artificial_intelligence_in_healthcare_0119.pdf), Royal College of Physicians, 2019.
-	[Decree of the President of the Russian Federation on the Development of Artificial Intelligence in the Russian Federation](https://cset.georgetown.edu/wp-content/uploads/Decree-of-the-President-of-the-Russian-Federation-on-the-Development-of-Artificial-Intelligence-in-the-Russian-Federation-.pdf), Office of the President of the Russian Federation, 2019.
-	[Governance Principles for a New Generation of Artificial Intelligence: Develop Responsible Artificial Intelligence 《新一代人工智能治理原则——发展负责任的人工智能》](https://www.newamerica.org/cybersecurity-initiative/digichina/blog/translation-chinese-expert-group-offers-governance-principles-responsible-ai/), National New Generation Artificial Intelligence Governance Expert Committee, China’s Ministry of Science and Technology, 2019.
-	[MorphL AI Guiding Principles](https://morphl.io/ai-principles.html), MorphL, 2019.
-	[Principles to Promote Fairness, Ethics, Accountability and Transparency (FEAT) in the Use of AI & Data Analytics in Singapore’s Financial Sector](https://www.mas.gov.sg/~/media/MAS/News%20and%20Publications/Monographs%20and%20Information%20Papers/FEAT%20Principles%20Final.pdf), Monetary Authority of Singapore, 2019.
-	[AI Application Criteria 人工智能应用准则](https://megvii.com/news_detail/id/60), MEGVII, 2019.
-	[Social Principles of Human centric AI](https://stip.oecd.org/stip/policy-initiatives/2019%2Fdata%2FpolicyInitiatives%2F24341), Integrated Innovation Strategy Promotion Council, 2019.
-	[Ethical Aspects of Autonomous and Intelligent Systems](http://globalpolicy.ieee.org/wp-content/uploads/2019/06/IEEE19002.pdf), IEEE , 2019.
-	[Policy and investment recommendations for trustworthy Artificial Intelligence](https://digital-strategy.ec.europa.eu/en/library/policy-and-investment-recommendations-trustworthy-artificial-intelligence), High-Level Expert Group on AI (AI HLEG), 2019.
-	[G20 AI Principles](https://www.g20-insights.org/wp-content/uploads/2019/07/G20-Japan-AI-Principles.pdf), G20 Ministerial Meeting on Trade and Digital Economy, 2019.
-	[A governance framework for algorithmic accountability and transparency](https://www.europarl.europa.eu/RegData/etudes/STUD/2019/624262/EPRS_STU(2019)624262_EN.pdf), European Parliamentary Research Service, 2019.
-	[Ethics guidelines for trustworthy AI](https://digital-strategy.ec.europa.eu/en/library/ethics-guidelines-trustworthy-ai), European Commission High Level Expert Group on AI, 2019.
-	[Digia’s ethical principles for utilising artificial intelligence](https://digia.com/en/actual/news/digias-ethical-principles-for-utilising-artificial-intelligence-published/), Digia, 2019.
-	[AI Ethics: The next big thing in Government](https://www2.deloitte.com/xe/en/pages/about-deloitte/articles/secure-benefits-ai-government-society.html..html), Deloitte, 2019.
-	[DeepMind Ethics & Society Themes](https://deepmind.com/about/ethics-and-society), DeepMind Ethics & Society, 2019.
-	[National Strategy for Artificial Intelligence](https://eng.em.dk/media/13081/305755-gb-version_4k.pdf), Danish Government, 2019.
-	[Joint Pledge on Artificial Intelligence Industry Self-Discipline (Draft for Comment) 人工智能行业自律公约 （征求意见稿）](https://www.newamerica.org/cybersecurity-initiative/digichina/blog/translation-chinese-ai-alliance-drafts-self-discipline-joint-pledge/), China's Artificial Intelligence Industry Alliance (AIIA), 2019.
-	[Bejing AI Principles](https://www.baai.ac.cn/news/beijing-ai-principles-en.html), Bejing Academy of Artificial Intelligence, 2019.
-	[AI Ethics Principles](https://www.industry.gov.au/data-and-publications/building-australias-artificial-intelligence-capability/ai-ethics-framework/ai-ethics-principles), Australian Government Department of Industry, Innovation and Science, 2019.
-	[Artificial Intelligence: Australia’s Ethics Framework (A Discussion Paper)](https://consult.industry.gov.au/strategic-policy/artificial-intelligence-ethics-framework/), Australian Government Department of Industry Innovation and Science, 2019.
-	[Artificial Intelligence at AT&T: Our Guiding Principles](https://about.att.com/innovationblog/2019/05/our_guiding_principles.html), AT&T , 2019.
-	[Ethics of AI in Radiology: European and North American Multisociety Statement](https://pubs.rsna.org/doi/10.1148/radiol.2019191586), American College of Radiology; European Society of Radiology; Radiology Society of North America; Society for Imaging Informatics in Medicine; European Society of Medical Imaging Informatics; Canadian Association of Radiologists; American Association of Physicists in Medicine, 2019.
-	[On Good AI Governance: 14 Priority Actions, a S.M.A.R.T. Model of Governance, and a Regulatory Toolbox](https://www.eismd.eu/wp-content/uploads/2019/11/AI4Peoples-Report-on-Good-AI-Governance_compressed.pdf), AI4People, 2019.
-	[Responsible AI and Robotics: An Ethical Framework](https://www.accenture.com/gb-en/company-responsible-ai-robotics), Accenture, 2019.
-	[White Paper: How to Prevent Discriminatory Outcomes in Machine Learning](https://www.unicef.org/innovation/reports/how-prevent-discriminatory-outcomes-machine-learning), WEF, Global Future Council on Human Rights 2016-2018, 2018.
-	[Montréal Declaration: Responsible AI](https://monoskop.org/images/b/b2/Report_Montreal_Declaration_for_a_Responsible_Development_of_Artificial_Intelligence_2018.pdf), Université de Montréal (University of Montreal), 2018.
-	[Unity’s Guiding Principles for Ethical AI](https://blogs.unity3d.com/2018/11/28/introducing-unitys-guiding-principles-for-ethical-ai/), Unity Technologies, 2018.
-	[White Paper – Building Ethics into Privacy Frameworks for Big Data and AI](https://iapp.org/resources/article/building-ethics-into-privacy-frameworks-for-big-data-and-ai/), UN Global Pulse and IAPP, 2018.
-	[AI in the UK: Ready, Willing and Able?](https://publications.parliament.uk/pa/ld201719/ldselect/ldai/100/100.pdf), UK House of Lords, Select Committee on Artificial Intelligence, 2018.
-	[Initial Code of Conduct for Data-Driven Health and Care Technology](http://allcatsrgrey.org.uk/wp/download/informatics/www_gov_uk_government_publications_code_of_conduct_for_data_.pdf), UK Department of Health & Social Care, 2018.
-	[Federal Data Strategy Framework](https://strategy.data.gov/overview/), U.S. Government, 2018.
-	[Tieto’s AI Ethics Guidelines](https://www.tietoevry.com/contentassets/b097de43d84d4c84832f1fff2cb6a30d/tieto-s-ai-ethics-guidelines.pdf), Tieto, 2018.
-	[Universal Guidelines for Artificial Intelligence](https://thepublicvoice.org/ai-universal-guidelines/), The Public Voice, 2018.
-	[Artificial Intelligence and Privacy](https://www.datatilsynet.no/globalassets/global/english/ai-and-privacy.pdf), The Norwegian Data Protection Authority, 2018.
-	[The Responsible Machine Learning Principles](https://ethical.institute/principles.html), The Institute for Ethical AI & Machine Learning, 2018.
-	[Toward a G20 Framework for Artificial Intelligence in the Workplace](https://www.cigionline.org/publications/toward-g20-framework-artificial-intelligence-workplace/), The Centre for International Governance Innovation (CIGI), 2018.
-	[AI Principles of Telefónica](https://www.telefonica.com/documents/364672/143939197/principios-ai-eng-2018.pdf/f3e86fb8-d0c3-a8ac-a2c5-6aae553e71a3), Telefónica, 2018.
-	[Introducing Stanford's Human-Centered AI Initiative](https://hai.stanford.edu/news/introducing-stanfords-human-centered-ai-initiative), Stanford Institute for Human-Centered Artificial Intelligence, 2018.
-	[Sony Group AI Ethics Guidelines](https://www.sony.com/en/SonyInfo/sony_ai/responsible_ai.html), Sony, 2018.
-	[AI Principles & Ethics](https://www.smartdubai.ae/initiatives/ai-principles-ethics), Smart Dubai, 2018.
-	[SAP’s Guiding Principles for Artificial Intelligence](https://www.sap.com/documents/2018/09/940c6047-1c7d-0010-87a3-c30de2ffd8ff.html), SAP, 2018.
-	[The Ethics of Code: Developing AI for Business with Five Core Principles](https://www.itworldcanada.com/ai/wp-content/uploads/2018/08/business-builders-ethics-of-code-1.pdf), Sage, 2018.
-	[Privacy and Freedom of Expression in the Age of Artificial Intelligence](https://privacyinternational.org/sites/default/files/2018-04/Privacy%20and%20Freedom%20of%20Expression%20%20In%20the%20Age%20of%20Artificial%20Intelligence.pdf), Privacy International, 2018.
-	[Discussion Paper on Artificial Intelligence (AI) and Personal Data — Fostering Responsible Development and Adoption of AI](https://www.pdpc.gov.sg/-/media/Files/PDPC/PDF-Files/Resource-for-Organisation/AI/Discussion-Paper-on-AI-and-PD---050618.pdf?la=en), Personal Data Protection Commission Singapore, 2018.
-	[Tenets](https://www.partnershiponai.org/tenets/), Partnership on AI, 2018.
-	[OpenAI Charter](https://openai.com/charter/), OpenAI, 2018.
-	[OP Financial Group's Ethical Guidelines for Artificial Intelligence](http://www.ethicscodescollection.org/detail/e054e805-117c-4500-899d-4e8b74bb62eb), OP Group, 2018.
-	[Discussion Paper: National Strategy for Artificial Intelligence](https://niti.gov.in/writereaddata/files/document_publication/NationalStrategy-for-AI-Discussion-Paper.pdf), National Institution for Transforming India (NITI Aayog), 2018.
-	[Draft AI Utilization Principles](https://www.soumu.go.jp/main_content/000581310.pdf), Ministry of Internal Affair and Communications of Japan, The Conference toward AI Network Society, 2018.
-	[Work in the Age of Artificial Intelligence: Four Perspectives on the Economy, Employment, Skills and Ethics](https://julkaisut.valtioneuvosto.fi/bitstream/handle/10024/160980/TEMjul_21_2018_Work_in_the_age.pdf?sequence=1&isAllowed=y), Ministry of Economic Affairs and Employment, 2018.
-	[Responsible Bots: 10 Guidelines for Developers of Conversational AI](https://www.microsoft.com/en-us/research/uploads/prod/2018/11/Bot_Guidelines_Nov_2018.pdf), Microsoft, 2018.
-	[Charlevoix Common Vision for the Future of Artificial Intelligence](https://www.mofa.go.jp/files/000373837.pdf), Leaders of the G7, 2018.
-	[Kakao Algorithm Ethics](https://www.kakaocorp.com/page/responsible/detail/algorithm?lang=ENG), Kakao, 2018.
-	[Declaration on Ethics and Data Protection in Artificial Intelligence](http://globalprivacyassembly.org/wp-content/uploads/2018/10/20180922_ICDPPC-40th_AI-Declaration_ADOPTED.pdf), International Conference of Data Protection and Privacy Commissioners (ICDPPC), 2018.
-	[Intel’s AI Privacy Policy White Paper: Protecting Individuals’ Privacy and Data in the Artificial Intelligence World](https://www.intel.com/content/www/us/en/artificial-intelligence/solutions/ai-privacy-policy-white-paper.html), Intel Corporation, 2018.
-	[Business Ethics and Artificial Intelligence](https://www.ibe.org.uk/uploads/assets/5f167681-e05f-4fae-ae1bef7699625a0d/ibebriefing58businessethicsandartificialintelligence.pdf), Institute of Business Ethics (IBE), 2018.
-	[IBM’s Principles for Trust and Transparency](https://www.ibm.com/blogs/policy/trust-principles/), IBM, 2018.
-	[Everyday Ethics for Artificial Intelligence](https://www.ibm.com/design/ai/ethics/everyday-ethics/), IBM, 2018.
-	[Responsible AI – Key Themes, Concerns & Recommendations for European Research and Innovation](https://futurium.ec.europa.eu/en/european-ai-alliance/open-library/responsible-ai-key-themes-concerns-recommendations-european-research-and-innovation), HUB4NGI, 2018.
-	[Responsible use of artificial intelligence (AI)](https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/responsible-use-ai.html), Government of Canada, 2018.
-	[Artificial Intelligence at Google: Our Principles](https://ai.google/principles/), Google, 2018.
-	[GE Healthcare AI Principles](https://www.gehealthcare.com/article/ethics-in-healthcare-arent-new-but-their-application-has-never-been-more-important/?utm_source=twitter.com&utm_medium=GESocial&utm_content=&utm_campaign=AI+Principles), GE Healthcare, 2018.
-	[The Malicious Use of Artificial Intelligence: Forecasting, Prevention, and Mitigation](https://arxiv.org/ftp/arxiv/papers/1802/1802.07228.pdf), Future of Humanity Institute; University of Oxford; Centre for the Study of Existential Risk; University  of Cambridge; Center for a New American Security; Electronic Frontier Foundation; OpenAI, 2018.
-	[Ethical, Social, and Political Challenges of Artificial Intelligence in Health](https://wellcome.org/sites/default/files/ai-in-health-ethical-social-political-challenges.pdf), Future Advocacy, 2018.
-	[Towards a Digital Ethics](https://edps.europa.eu/sites/edp/files/publication/18-01-25_eag_report_en.pdf), European Data Protection Supervisor & Ethics Advisory Group, 2018.
-	[Artificial Intelligence: A European Perspective](https://publications.jrc.ec.europa.eu/repository/handle/JRC113826), European Commission, Joint Research Centre, 2018.
-	[Statement on Artificial Intelligence, Robotics and ‘Autonomous’ Systems](https://www.unapcict.org/sites/default/files/2019-01/EC_AI-%20Robotics-%20and%20Autonomous%20Systems.pdf), European Commission, European Group on Ethics in Science and New Technologies, 2018.
-	[AI Guidelines](https://www.telekom.com/en/company/digital-responsibility/details/artificial-intelligence-ai-guideline-524366), Deutsche Telekom, 2018.
-	[Data Ethics - Principles and Guidelines for Companies, Authorities & Organisations](https://dataethics.eu/data-ethics-principles/), DataEthics.eu, 2018.
-	[Governing Artificial Intelligence: Upholding Human Rights & Dignity](https://datasociety.net/library/governing-artificial-intelligence/), Data & Society, 2018.
-	[European Ethical Charter on the Use of Artificial Intelligence in Judicial Systems and Their Environment](https://rm.coe.int/ethical-charter-en-for-publication-4-december-2018/16808f699c), Council of Europe: European Commission for the Efficiency of Justice (CEPEJ), 2018.
-	[The Toronto Declaration: Protecting the Right to Equality and Non-discrimination in Machine Learning Systems](https://www.torontodeclaration.org/#:~:text=The%20Toronto%20Declaration,-Protecting%20the%20right&text=It%20calls%20on%20governments%20and,to%20equality%20and%20non%2Ddiscrimination.&text=Read%20the%20Declaration%20in%20English%2C%20French%2C%20Arabic%20and%20Simplified%20Chinese.), Amnesty International; Access Now, 2018.
-	[People’s Guide to AI](https://alliedmedia.org/resources/peoples-guide-to-ai), Allied Media Group, 2018.
-	[AI4People-An Ethical Framework for a Good AI Society: Opportunities, Risks, Principles, and Recommendations](https://www.eismd.eu/wp-content/uploads/2019/02/Ethical-Framework-for-a-Good-AI-Society.pdf), AI4People, 2018.
-	[Algorithmic Impact Assessments: A Practical Framework for Public Agency Accountability](https://ainowinstitute.org/aiareport2018.pdf), AI Now Institute, 2018.
-	[AI Now 2018 Report](https://ainowinstitute.org/AI_Now_2018_Report.pdf), AI Now Institute, 2018.
-	[For a Meaningful Artificial Intelligence: Towards a French and European Strategy](https://knowledge4policy.ec.europa.eu/publication/meaningful-artificial-intelligence-towards-french-european-strategy_en), AI for Humanity , 2018.
-	[Top 10 Principles for Ethical Artificial Intelligence](http://www.thefutureworldofwork.org/opinions/10-principles-for-ethical-ai/), UNI Global Union, 2017.
-	[Machine Learning: The Power and Promise of Computers that Learn by Example](https://royalsociety.org/~/media/policy/projects/machine-learning/publications/machine-learning-report.pdf), The Royal Society, 2017.
-	[Human Rights in the Robot Age: Challenges arising from the use of robotics, artificial intelligence, and virtual and augmented reality](https://www.rathenau.nl/en/digitale-samenleving/human-rights-robot-age), The Rathenau Instituut, 2017.
-	[The Japanese Society for Artificial Intelligence Ethical Guidelines](http://ai-elsi.org/archives/514), The Japanese Society for Artificial Intelligence (JSAI), 2017.
-	[Principles for the Governance of AI](https://thefuturesociety.org/2017/07/15/principles-law-and-society-initiative/), The Future Society, 2017.
-	[Ethical Principles for Artificial Intelligence and Data Analytics](https://history.siia.net/Portals/0/pdf/Policy/Ethical%20Principles%20for%20Artificial%20Intelligence%20and%20Data%20Analytics%20SIIA%20Issue%20Brief.pdf?ver=2017-11-06-160346-990), Software & Information Industry Association (SIIA), 2017.
-	[Accelerating innovation - How to build trust and confidence in AI](https://www.pwc.com/sg/en/publications/assets/ra-accelerating-innovation-build-trust-confidence-in-ai.pdf), PricewaterhouseCoopers, 2017.
-	[Draft AI R&D Guidelines for International Discussions](https://www.soumu.go.jp/main_content/000507517.pdf), Ministry of Internal Affair and Communications of Japan, The Conference toward AI Network Society, 2017.
-	[Mid- to Long-Term Master Plan in Preparation for the Intelligent Information Society: Managing the Fourth Industrial Revolution](https://k-erc.eu/wp-content/uploads/2017/12/Master-Plan-for-the-intelligent-information-society.pdf), Minister of Science, ICT and Future Planning (MSIP), 2017.
-	[Microsoft AI principles](https://www.microsoft.com/en-us/ai/responsible-ai?activetab=pivot1:primaryr6), Microsoft, 2017.
-	[Artificial Intelligence and Machine Learning: Policy Paper](https://pdf4pro.com/download/artificial-intelligence-and-machine-learning-policy-paper-3fec9e.html), Internet Society, 2017.
-	[Artificial Intelligence: The Public Policy Opportunity](https://blogs.intel.com/policy/files/2017/10/Intel-Artificial-Intelligence-Public-Policy-White-Paper-2017.pdf), Intel Corporation, 2017.
-	[ITI AI Policy Principles](https://www.itic.org/public-policy/ITIAIPolicyPrinciplesFINAL.pdf), Information Technology Industry Council (ITI), 2017.
-	[AI Policy Principles](https://www.itic.org/dotAsset/50ed66d5-404d-40bb-a8ae-9eeeef55aa76.pdf), Information Technology Industry Council (ITI), 2017.
-	[Big Data, Artificial Intelligence, Machine Learning and Data Protection](https://rcn.fpf.org/2017/08/28/big-data-artificial-intelligence-machine-learning-and-data-protection/), Information Commissioner’s Office, 2017.
-	[Ethically Aligned Design: A Vision for Prioritizing Human Well-being with Autonomous and Intelligent Systems, Version 2](https://standards.ieee.org/content/dam/ieee-standards/standards/web/documents/other/ead_v2.pdf), IEEE, 2017.
-	[Asilomar Principles](https://futureoflife.org/ai-principles/), Future of Life Institute, 2017.
-	[How Can Humans Keep the Upper Hand? Report on the Ethical Matters Raised by AI Algorithms](https://iapp.org/media/pdf/resource_center/CNIL_AI.pdf), French Data Protection Authority (CNIL), 2017.
-	[Ethics Commission: Automated and Connected Driving](https://www.bmvi.de/SharedDocs/EN/publications/report-ethics-commission-automated-and-connected-driving.pdf?__blob=publicationFile), Federal Ministry of Transport and Digital Infrastructure, 2017.
-	[Report with Recommendations to the Commission on Civil Law Rules on Robotics](https://www.europarl.europa.eu/doceo/document/A-8-2017-0005_EN.pdf), European Parliament, 2017.
-	[Report of COMEST on Robotics Ethics](https://unescoblob.blob.core.windows.net/pdf/UploadCKEditor/REPORT%20OF%20COMEST%20ON%20ROBOTICS%20ETHICS%2014.09.17.pdf), COMEST/UNESCO, 2017.
-	[Statement on Algorithmic Transparency and Accountability](https://www.acm.org/binaries/content/assets/public-policy/2017_joint_statement_algorithms.pdf), Association for Computing Machinery (ACM), 2017.
-	[Ethics and algorithmic processes for decision making and decision support](https://algorithmwatch.org/en/ethics-and-algorithmic-processes-for-decision-making-and-decision-support/), AlgorithmWatch , 2017.
-	[AI Now 2017 Report](https://ainowinstitute.org/AI_Now_2017_Report.pdf), AI Now Institute, 2017.
-	[Report on Artificial Intelligence and Human Society (Unofficial translation)](https://www8.cao.go.jp/cstp/tyousakai/ai/summary/aisociety_en.pdf), Advisory Board on Artificial Intelligence and Human Society (initiative of the Minister of State for Science and Technology Policy), 2017.
-	[Position on Robotics and Artificial Intelligence](https://juliareda.eu/wp-content/uploads/2017/02/Green-Digital-Working-Group-Position-on-Robotics-and-Artificial-Intelligence-2016-11-22.pdf), The Greens (Green Working Group Robots) European Free Alliance, 2016.
-	[The National Artificial Intelligence Research and Development Strategic Plan](https://www.nitrd.gov/pubs/national_ai_rd_strategic_plan.pdf), National Science and Technology Council; Networking and Information Technology Research and Development Subcommittee, 2016.
-	[Ethically Aligned Design: A Vision for Prioritizing Human Well-being with Autonomous and Intelligent Systems, Version 1](https://standards.ieee.org/content/dam/ieee-standards/standards/web/documents/other/ead_v1.pdf), IEEE, 2016.
-	[Principles for Accountable Algorithms and a Social Impact Statement for Algorithms](https://www.fatml.org/resources/principles-for-accountable-algorithms), Fairness, Accountability, and Transparency in Machine Learning (FAT/ML), 2016.
-	[Preparing for the Future of Artificial Intelligence](https://obamawhitehouse.archives.gov/sites/default/files/whitehouse_files/microsites/ostp/NSTC/preparing_for_the_future_of_ai.pdf), Executive Office of the President; National Science and Technology Council; Committee on Technology, 2016.
-	[The AI Now Report: The Social and Economic Implications of Artificial Intelligence Technologies in the Near-Term](https://ainowinstitute.org/AI_Now_2016_Report.pdf), AI Now Institute, 2016.
-	[Universal Principles of Data Ethics](http://www.ethicscodescollection.org/detail/603bdf83-62a2-4725-8dd4-e6cf350d5228), Accenture, 2016.
-	[Unified Ethical Frame for Big Data Analysis: IAF Big Data Ethics Initiative, Part A](https://bigdata.fpf.org/wp-content/uploads/2015/11/IAF-Unified-Ethical-Frame-for-Big-Data-Analysis.pdf), The Information Accountability Foundation, 2015.
-	[Ethics Policy](https://www.iiim.is/ethics-policy/), Icelandic Institute for Intelligent Machines (IIIM), 2015.
											
