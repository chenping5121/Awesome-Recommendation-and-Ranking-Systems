# Awesome-Recommendation-and-Ranking-Systems
Maintained by Yang Gao (ustcgaoy01@gmail.com). Last Update: 12/13/2020.

Recent advances in recommendation and ranking systems. We only focus on papers published in top conferences including RecSys, WWW, SIGIR, KDD, NIPS, ICML, and ICLR.

## Table of Contents
* [Survey](#survey)
  * [Self-Supervised](#Survey_Self-Supervised)
  * [Ranking and Retrieval](#Survey_Rank_Retrieval)
  * [Knowledge Graph and Side Information](#Survey_KG_SideInfo)
  * [Bias Correction, Fairness and Quality](#Survey_Bias_Correction)
  * [Interpretability](#Survey_Interpretability)
  * [Feature Engineering](#Survey_FE)
  * [Personalization](#Survey_Personalization)
  * [Sequence](#Survey_Sequence)
  * [Transfer and Multi-Task](#Survey_Transfer)
  * [Others](#Survey_Others)
* [Industry Papers](#industry-papers)
  * [2020](#in_2020)
  * [2019](#in_2019)
  * [2018](#in_2018)
  * [2017](#in_2017)
  * [2016](#in_2016)
  * [2013](#in_2013)
* [Academic Papers](#academic-papers)
  * [2019](#ac_2019)
  * [2018](#ac_2018)
  * [2017](#ac_2017)
  * [2016](#ac_2016)
  * [2015](#ac_2015)
* [Special Topics](#special-topics)
  * [Transformers in Recommendation/Ranking System](#transformers-in-recommendation-and-ranking-system)

<h3> Keywords </h3>
<h4> Problem </h4>

__`sca.`__: scalability &emsp; | &emsp; __`ee.`__: exploit and explore &emsp; | &emsp; __`ret.`__: retrieval &emsp; | &emsp; __`ran.`__: ranking    
__`per.`__: personalization &emsp; | &emsp; __`seq.`__: sequential info &emsp; | &emsp; __`int.`__: interpretability &emsp; | &emsp; __`cs.`__: cold start     
__`imb.`__: imbalance and long-tail &emsp; | &emsp; __`bia.`__: bias correction, fairness, and quality &emsp; | &emsp; __`pri.`__: privacy    
__`kg.`__: knowledge graph, side information and implicit feedback &emsp; | &emsp; __`tra.`__: transfer learning &emsp; | &emsp; __`mt.`__ multi-task    
__`fe.`__: feature engineering &emsp; | &emsp; __`ads.`__: computational ads &emsp; | &emsp; __`geo.`__: travel and delivery    
__`dyn.`__: dynamic &emsp; | &emsp; __`fas.`__: fashion &emsp; | &emsp; __`eco.`__: e-commerce    
__`oth`__: other topics including model selection, multi-label, command recommendation, crowdsourcing labeling, hyper-parameter tuning...
<h4> Architecture </h4>

__`mlp.`__: MLP &emsp; | &emsp; __`ae.`__: auto-encoder &emsp; | &emsp; __`cnn.`__: cnn &emsp; | &emsp; __`rnn.`__: rnn &emsp; | &emsp; __`rbm.`__: rbm &emsp; | &emsp; __`nad.`__: nade     
__`att.`__: neural attention &emsp; | &emsp; __`adv.`__: adversarial learning &emsp; | &emsp; __`gnn.`__: gnn &emsp; | &emsp; __`drl.`__: DRL &emsp; | &emsp; __`hyb.`__: hybrid    

<h4> Modality </h4>

__`txt.`__: text &emsp; | &emsp; __`img.`__: image &emsp; | &emsp; __`aud.`__: audio &emsp; | &emsp; __`vid.`__: video &emsp; | &emsp; __`net.`__: network&emsp; __`mm.`__: multimodal    

Statistics: :fire: citation >= 100 &emsp;|&emsp; :star: citation >= 50 &emsp;|&emsp; :yellow_heart: interesting &emsp;|&emsp; :x: overclaimed or non-reproducible &emsp;|&emsp; :heart_eyes: verified effective model


## Survey
<a name="Survey_Self-Supervised"></a>
### Self-Supervised 
[A Survey on Self-supervised Pre-training for Sequential Transfer Learning in Neural Networks](https://arxiv.org/pdf/2007.00800.pdf), 2020.

[A SURVEY ON CONTRASTIVE SELF-SUPERVISED LEARNING](https://arxiv.org/pdf/2011.00362.pdf), 2020.

[Deep Metric Learning: A survey](https://www.mdpi.com/2073-8994/11/9/1066/pdf), 2019.

[Self-supervised Visual Feature Learning with Deep Neural Networks: A Survey](https://arxiv.org/pdf/1902.06162.pdf), 2019.

<a name="Survey_Rank_Retrieval"></a>
### Ranking and Retrieval

<a name="Survey_KG_SideInfo"></a>
### Knowledge Graph or Side Information
[A Survey on Knowledge Graph-Based Recommender Systems](https://arxiv.org/pdf/2003.00911.pdf), 2020.

[Research Commentary on Recommendations with Side Information: A Survey and Research Directions](https://arxiv.org/pdf/1909.12807.pdf), 2019.

[Attribute-Aware Recommender System Based on Collaborative Filtering: Survey and Classification](https://www.frontiersin.org/articles/10.3389/fdata.2019.00049/pdf), 2019.

<a name="Survey_Bias_Correction"></a>
### Bias Correction or Fairness
[Bias and Debias in Recommender System: A Survey and Future Directions](https://arxiv.org/pdf/2010.03240.pdf), 2020.

<a name="Survey_Interpretability"></a>
### Interpretability
[Explainable Recommendation: A Survey and New Perspectives](https://arxiv.org/pdf/1804.11192.pdf), 2020.

<a name="Survey_FE"></a>
### Feature Engineering
[Recommendation System Based on Heterogeneous Feature: A Survey](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9197624), 2020.

<a name="Survey_Personalization"></a>
### Personalization
[A survey on news recommender system - Dealing with timeliness, dynamic user interest and content quality, and effects of recommendation on news readers.](https://arxiv.org/pdf/2009.04964.pdf), 2020.

[A Survey on Personalized News Recommendation Technology](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8854070), 2020.

[User Preferences in Recommendation Algorithms - The influence of user diversity, trust, and product category on privacy perceptions in recommender](https://dl.acm.org/doi/pdf/10.1145/3240323.3240393), 2018.

<a name="Survey_Sequence"></a>
### Sequence
[Performance Comparison of Neural and Non-Neural Approaches to Session-based Recommendation](https://dl.acm.org/doi/pdf/10.1145/3298689.3347041), 2019.

[A Survey on Session-based Recommender Systems](https://arxiv.org/pdf/1902.04864.pdf), 2019.

[Sequence-Aware Recommender Systems](https://arxiv.org/pdf/1802.08452.pdf), 2018.

[Evaluation of Session-based Recommendation Algorithms](https://arxiv.org/pdf/1803.09587.pdf), 2018.

[Sequence-Aware Recommender Systems](https://arxiv.org/pdf/1802.08452.pdf), 2018. - [Slides](https://www.slideshare.net/MassimoQuadrana/tutorial-on-sequence-aware-recommender-systems-acm-recsys-2018), [Code](https://github.com/mquad/sars_tutorial/)

<a name="Survey_Transfer"></a>
### Transfer and Multi-Task
[Cross Domain Recommender Systems: A Systematic Literature Review](https://dl.acm.org/doi/pdf/10.1145/3073565), 2017.

<a name="Survey_Others"></a>
### Others
[How Well Do People Report Time Spent on Facebook? An Evaluation of Established Survey Questions with Recommendations](https://dl.acm.org/doi/pdf/10.1145/3313831.3376435), 2020.

[Microsoft Recommenders: Best Practices for Production-Ready Recommendation Systems](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366424.3382692), WWW, 2020.

[Are We Really Making Much Progress? A Worrying Analysis of Recent Neural Recommendation Approaches](https://arxiv.org/pdf/1907.06902.pdf), 2019.

[A Troubling Analysis of Reproducibility and Progress in Recommender Systems Research](https://arxiv.org/pdf/1911.07698.pdf), 2019.

[Microsoft Recommenders](https://dl.acm.org/doi/10.1145/3298689.3346967), Microsoft, RecSys, 2019.

[Are We Evaluating Rigorously? Benchmarking Recommendation for Reproducible Evaluation and Fair Comparison](https://dl.acm.org/doi/pdf/10.1145/3383313.3412489), RecSys, 2020.

[Neural Collaborative Filtering vs. Matrix Factorization Revisited](https://dl.acm.org/doi/pdf/10.1145/3383313.3412488), Google Research, RecSys, 2020.

[How good your recommender system is? A survey on evaluations in recommendation](https://link.springer.com/content/pdf/10.1007/s13042-017-0762-9.pdf), 2019.

[A Survey of Matrix Completion Methods for Recommendation Systems](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8400447), 2020.

[Recommender Systems for the Internet of Things: A Survey](https://arxiv.org/pdf/2007.06758.pdf), 2020.

[Tour recommendation and trip planning using location-based social media: a survey](https://link.springer.com/content/pdf/10.1007/s10115-018-1297-4.pdf), 2019.

[Deep Learning based Recommender System: A Survey and New Perspectives](https://dl.acm.org/doi/pdf/10.1145/3285029). 2019.

[150 Successful Machine Learning Models: 6 Lessons Learned at Booking.com](https://dl.acm.org/doi/pdf/10.1145/3292500.3330744), Booking.com, KDD, 2019.

[A Survey of Recommender Systems Based on Deep Learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8529185), 2018.

## Industry Papers

<a name="in_2020"></a>
### 2020
[[Google](https://arxiv.org/pdf/2002.08530.pdf)] Learning Multi-granular Quantized Embeddings for Large-Vocab Categorical Features in Recommender Systems [__`mlp.`__, __`sca.`__] 

[[MSRA](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366423.3380151)] LightRec: A Memory and Search-Efficient Recommender System [__`mlp.`__, __`sca.`__] 

[[Alibaba](https://arxiv.org/pdf/2003.01917.pdf)] Learning to Hash with Graph Neural Networks for Recommender Systems [__`gnn`__, __`sca.`__, __`ret.`__, __`net.`__]

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3394486.3403342)] Large-Scale Training System for 100-Million Classification at Alibaba [__`sca.`__]

[[Taobao](https://dl.acm.org/doi/pdf/10.1145/3394486.3403309)] Privileged Features Distillation at Taobao Recommendations [ __`ads.`__, __`eco.`__,__`tra.`__,__`att.`__]

[[Google Research](https://dl.acm.org/doi/pdf/10.1145/3394486.3403296)] Scaling Graph Neural Networks with Approximate PageRank [__`sca.`__,__`ran.`__,__`gnn.`__]

[[Twitter](https://dl.acm.org/doi/pdf/10.1145/3383313.3418486)] Tuning Word2vec for Large Scale Recommendation Systems [__`mlp`__, __`sca.`__, __`txt.`__]

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3394486.3403344)] Controllable Multi-Interest Framework for Recommendation [__`mlp`__,__`seq.`__,__`ee.`__]

[[Airbnb](https://dl.acm.org/doi/pdf/10.1145/3394486.3403345)] Managing Diversity in Airbnb Search [__`hyb.`__,__`ran.`__,__`ret.`__,__`ee.`__,__`eco.`__]

[[IKEA](https://dl.acm.org/doi/pdf/10.1145/3383313.3411550)] Balancing relevance and discovery to inspire customers in the IKEA App [__`ee.`__]

[[Bloomberg](https://arxiv.org/pdf/1912.00508.pdf)] Cascading Hybrid Bandits: Online Learning to Rank for Relevance and Diversity [__`drl.`__,__`ee.`__,__`ran.`__]

[[Spotify Research](https://dl.acm.org/doi/pdf/10.1145/3383313.3418482)] Investigating Listeners’ Responses to Divergent Recommendations [__`ee.`__]

[[Facebook](https://dl.acm.org/doi/pdf/10.1145/3394486.3403305)] Embedding-based Retrieval in Facebook Search [__`ran.`__, __`ret.`__, __`txt.`__]

[[Airbnb](https://dl.acm.org/doi/pdf/10.1145/3394486.3403333)] Improving Deep Learning For Airbnb Search [__`ran.`__,__`ret.`__, __`eco.`__]

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3394486.3403350)] Learning to Generate Personalized Query Auto-Completions via a Multi-View Multi-Task Attentive Approach [__`ran.`__, __`ret.`__,__`seq.`__,__`mt.`__,__`per.`__,__`att.`__,__`txt.`__]

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3394486.3403345)] Managing Diversity in Airbnb Search [__`ran.`__,__`ret.`__,__`ee.`__]

[[Tecent](https://dl.acm.org/doi/pdf/10.1145/3394486.3403357)] Meta-Learning for Query Conceptualization at Web Scale [__`ret.`__,__`tra.`__,__`sca.`__]

[[Google](https://dl.acm.org/doi/pdf/10.1145/3394486.3403288)] Neural Input Search for Large Scale Recommendation Models [__`ran`__,__`ret.`__,__`sca.`__] :yellow_heart:

[[Adobe](https://dl.acm.org/doi/pdf/10.1145/3394486.3403324)] Personalized Image Retrieval with Sparse Graph Representation Learning [__`ret`__,__`per.`__,__`gnn.`__,__`img.`__]

[[Pinterest](https://dl.acm.org/doi/pdf/10.1145/3394486.3403372)] Shop The Look: Building a Large Scale Visual Shopping System at Pinterest [__`ret.`__,__`mt.`__,__`sca.`__,__`img.`__] :yellow_heart:

[[Tokyo Institute of Technology](https://dl.acm.org/doi/pdf/10.1145/3383313.3412262)] Doubly Robust Estimator for Ranking Metrics with Post-Click Conversions [__`ran.`__,__`bia.`__]

[[BaiDu](https://dl.acm.org/doi/pdf/10.1145/3394486.3403318)] Personalized Prefix Embedding for POI Auto-Completion in the Search Engine of Baidu Maps [__`ret.`__,__`ran.`__, __`per.`__,__`geo`__,__`hyb.`__]

[[Spotify](https://dl.acm.org/doi/pdf/10.1145/3383313.3412248)] Contextual and Sequential User Embeddings for Large-Scale Music Recommendation [__`seq.`__,__`hyb.`__,__`aud.`__, __`fe.`__]

[[Alibaba](https://arxiv.org/pdf/2008.09368.pdf)] Contextual User Browsing Bandits for Large-Scale Online Mobile Recommendation [__`bia.`__,__`drl.`__, __`fe.`__]

[[Tecent](https://dl.acm.org/doi/pdf/10.1145/3383313.3412236)] Progressive Layered Extraction (PLE): A Novel Multi-Task Learning (MTL) Model for Personalized Recommendations [__`per.`__,__`mt.`__,__`hyb.`__]

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3383313.3412238)] PURS: Personalized Unexpected Recommender System for Improving User Satisfaction [__`per.`__,__`ee.`__,__`seq.`__,__`hyb.`__]

[[CookPad](https://arxiv.org/pdf/2007.13440.pdf)] Towards Multi-Language Recipe Personalisation and Recommendation [__`ret.`__,__`per.`__, __`tra.`__]

[[Pinterest](https://dl.acm.org/doi/pdf/10.1145/3394486.3403280)] PinnerSage: Multi-Modal User Embedding Framework for Recommendations at Pinterest [__`per.`__,__`mm.`__] :yellow_heart:

[[Microsoft](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366423.3380071)] Understanding User Behavior For Document Recommendation [__`int.`__,__`sca.`__]

[[Snap](https://dl.acm.org/doi/pdf/10.1145/3394486.3403276)] Knowing your FATE: Friendship, Action and Temporal Explanations for User Engagement Prediction on Social Apps [__`int.`__,__`hyb.`__,__`net.`__,__`per.`__,__`fe.`__]

[[Spotify](https://dl.acm.org/doi/pdf/10.1145/3383313.3418491)] Inferring the Causal Impact of New Track Releases on Music Recommendation Platforms through Counterfactual Predictions [__`int.`__,__`seq.`__]

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3394486.3403393)] A Dual Heterogeneous Graph Attention Network to Improve Long-Tail Performance for Shop Search in E-Commerce [__`imb.`__,__`eco.`__,__`gnn.`__,__`cs.`__]

[[Amazon](https://dl.acm.org/doi/pdf/10.1145/3394486.3403303)] Automatic Validation of Textual Attribute Values in E-commerce Catalog by Learning with Limited Labeled Data [__`imb.`__,__`eco.`__,__`ae.`__,__`cs.`__]

[[Spotify & Walmart](https://dl.acm.org/doi/pdf/10.1145/3394486.3403394)] Learning with Limited Labels via Momentum Damped & Differentially Weighted Optimization [__`imb.`__,__`cs.`__]

[[LinkedIn](https://dl.acm.org/doi/pdf/10.1145/3394486.3403391)] Ads Allocation in Feed via Constrained Optimization [__`bia.`__,__`ads.`__]

[[Google](https://dl.acm.org/doi/pdf/10.1145/3394486.3403285)] Attribute-based Propensity for Unbiased Learning in Recommender Systems: Algorithm and Case Studies [__`bia.`__]

[[LinkedIn](https://dl.acm.org/doi/pdf/10.1145/3394486.3403336)] Debiasing Grid-based Product Search in E-commerce [__`ran.`__,__`ret.`__,__`bia.`__,__`eco.`__]

[[Google](https://dl.acm.org/doi/pdf/10.1145/3394486.3403341)] Improving Recommendation Quality in Google Drive [__`bia.`__]

[[Alibaba & Microsoft](https://dl.acm.org/doi/pdf/10.1145/3394486.3403329)] Maximizing Cumulative User Engagement in Sequential Recommendation: An Online Optimization Perspective [__`seq.`__,__`per.`__,__`fe.`__,__`per.`__]

[[Google](https://dl.acm.org/doi/pdf/10.1145/3394486.3403340)] User Sentiment as a Success Metric: Persistent Biases Under Full Randomization [__`bia.`__,__`kg.`__]

[[Microsoft](https://dl.acm.org/doi/pdf/10.1145/3383313.3412265)] Debiasing Item-to-Item Recommendations With Small Annotated Datasets [__`bia.`__, __`int.`__]

[[HuaWei](https://dl.acm.org/doi/pdf/10.1145/3383313.3412241)] Unbiased Ad Click Prediction for Position-aware Advertising [__`bia.`__,__`ads.`__,__`int.`__]

[[Fuji Xerox](https://arxiv.org/pdf/2008.04563.pdf)] Unbiased Learning for the Causal Effect of Recommendation [__`bia.`__, __`int.`__]

[[Bloomberg](https://dl.acm.org/doi/pdf/10.1145/3383313.3412254)] Global and Local Differential Privacy for Collaborative Bandits [__`pri.`__,__`drl.`__]

[[Yahoo Research](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366424.3383570)] Layered Graph Embedding for Entity Recommendation using Wikipedia in the Yahoo! Knowledge Graph [__`kg.`__,__`gnn.`__,__`net.`__]

[[DiDi](https://dl.acm.org/doi/pdf/10.1145/3394486.3403388)] Gemini: A Novel and Universal Heterogeneous Graph Information Fusing Framework for Online Recommendations [__`kg.`__,__`gnn.`__,__`net.`__]

[[Pinterest](https://dl.acm.org/doi/pdf/10.1145/3394486.3403293)] MultiSage: Empowering GCN with Contextualized Multi-Embeddings on Web-Scale Multipartite Networks [__`kg.`__,__`gnn.`__,__`net.`__, __`fe.`__]

[[Twitter](https://dl.acm.org/doi/pdf/10.1145/3394486.3403370)] SimClusters: Community-Based Representations for Heterogeneous Recommendations at Twitter [__`kg.`__,__`gnn.`__,__`net.`__]

[[DiDi](https://dl.acm.org/doi/pdf/10.1145/3394486.3403373)] Dynamic Heterogeneous Graph Neural Network for Real-time Event Prediction [__`geo.`__,__`seq.`__,__`gnn.`__,__`net.`__]

[[MSRA](https://dl.acm.org/doi/pdf/10.1145/3383313.3412237)] KRED: Knowledge-Aware Document Representation for News Recommendations [__`kg.`__,__`gnn.`__,__`net.`__, __`txt.`__]

[[Tecent](https://dl.acm.org/doi/pdf/10.1145/3394486.3403334)] General-Purpose User Embeddings based on Mobile App Usage [__`mt.`__,__`hyb.`__]

[[Facebook](https://dl.acm.org/doi/pdf/10.1145/3394486.3403311)] GrokNet: Unified Computer Vision Model Trunk and Embeddings For Commerce [__`mt.`__,__`eco.`__,__`img.`__] :yellow_heart:

[[ByteDance](https://dl.acm.org/doi/pdf/10.1145/3394486.3403384)] Jointly Learning to Recommend and Advertise [__`mt.`__,__`ads.`__,__`drl.`__]

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3394486.3403284)] M2GRL: A Multi-task Multi-view Graph Representation Learning Framework for Web-scale Recommender Systems [__`mt.`__,__`gnn.`__,__`seq.`__]

[[Tecent](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366423.3380116)] Future Data Helps Training: Modeling Future Contexts for Session-based Recommendation [__`seq.`__,__`fe.`__] :yellow_heart:

[[HuaWei](https://dl.acm.org/doi/pdf/10.1145/3394486.3403314)] AutoFIS: Automatic Feature Interaction Selection in Factorization Models for Click-Through Rate Prediction [__`fe.`__,__`mlp.`__] :yellow_heart:

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3394486.3403325)] Comprehensive Information Integration Modeling Framework for Video Titling [__`fe.`__,__`gnn.`__,__`eco.`__,__`vid.`__] :yellow_heart:

[[Facebook](https://dl.acm.org/doi/pdf/10.1145/3394486.3403364)] TIES: Temporal Interaction Embeddings for Enhancing Social Media Integrity at Facebook [__`seq.`__,__`fe.`__,__`hyb.`__] :yellow_heart:

[[Tecent](https://dl.acm.org/doi/pdf/10.1145/3394486.3403348)] A Request-level Guaranteed Delivery Advertising Planning: Forecasting and Allocation [__`ads.`__]

[[JD](https://dl.acm.org/doi/pdf/10.1145/3394486.3403319)] Category-Specific CNN for Visual-aware CTR Prediction at JD.com [__`ads.`__,__`cnn.`__,__`img.`__]

[[Baidu Research](https://dl.acm.org/doi/pdf/10.1145/3394486.3403297)] Combo-Attention Network for Baidu Video Advertising [__`ads.`__,__`mm.`__,__`att.`__,__`vid.`__] :yellow_heart:

[[JD](https://dl.acm.org/doi/pdf/10.1145/3383313.3418481)] Smart Targeting: A Relevance-driven and Configurable Targeting Framework for Advertising System [__`ads.`__]

[[Yahoo Research](https://dl.acm.org/doi/pdf/10.1145/3366423.3380001)] Recommending Themes for Ad Creative Design via Visual-Linguistic Representations [__`ads.`__,__`att.`__,__`mm.`__]

[[Google Research](https://dl.acm.org/doi/pdf/10.1145/3394486.3403376)] BusTr: Predicting Bus Travel Times from Real-Time Traffic [__`geo.`__,__`seq.`__,__`rnn.`__, __`net.`__]

[[DiDi](https://dl.acm.org/doi/pdf/10.1145/3394486.3403386)] CompactETA: A Fast Inference System for Travel Time Prediction [__`geo.`__,__`seq.`__,__`gnn.`__, __`net.`__]

[[KDD](https://dl.acm.org/doi/pdf/10.1145/3394486.3403320)] ConSTGAT: Contextual Spatial-Temporal Graph Attention Network for Travel Time Estimation at Baidu Maps [__`geo.`__,__`seq.`__,__`gnn.`__,__`att.`__,__`net.`__, __`fe.`__]

[[MeiTuan](https://dl.acm.org/doi/pdf/10.1145/3394486.3403353)] Delivery Scope: A New Way of Restaurant Retrieval For On-demand Food Delivery Service [__`geo.`__, __`ret.`__,__`net.`__]

[[JD](https://dl.acm.org/doi/pdf/10.1145/3394486.3403332)] Doing in One Go: Delivery Time Inference Based on Couriers’ Trajectories [__`geo.`__,__`seq.`__,__`net.`__]

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3394486.3403356)] Efficiently Solving the Practical Vehicle Routing Problem: A Novel Joint Learning Approach [__`geo.`__,__`hyb.`__,__`mt.`__,__`gnn.`__,__`net.`__]

[[DiDi](https://dl.acm.org/doi/pdf/10.1145/3394486.3403294)] HetETA: Heterogeneous Information Network Embedding for Estimating Time of Arrival [__`geo.`__,__`seq.`__,__`hyb.`__,__`net.`__]

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3394486.3403358)] Hybrid Spatio-Temporal Graph Convolutional Network: Improving Traffic Prediction with Navigation Data [__`geo.`__,__`seq.`__,__`hyb.`__,__`net.`__]

[[VISA Research](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366423.3380096)] OutfitNet: Fashion Outfit Recommendation with Attention-Based Multiple Instance Learning [__`fas.`__,__`att.`__,__`img.`__] :yellow_heart:

[[Pinterest](https://dl.acm.org/doi/pdf/10.1145/3394486.3403382)] Bootstrapping Complete The Look at Pinterest [__`fas.`__,__`img.`__] :yellow_heart:

[[JD](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366423.3380232)] Keywords Generation Improves E-Commerce Session-based Recommendation [__`seq.`__,__`eco.`__,__`att.`__, __`txt.`__]

[[Alibaba](https://arxiv.org/pdf/2008.09369.pdf)] Learning to Collaborate in Multi-Module Recommendation via Multi-Agent Reinforcement Learning without Communication [__`eco.`__,__`drl.`__]

[[HuaWei](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366423.3379999)] MetaSelector: Meta-Learning for Recommendation with User-Level Adaptive Model Selection [__`oth.`__] :yellow_heart:

[[Google AI](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366423.3380130)] Off-policy Learning in Two-stage Recommender Systems [__`oth.`__,__`drl.`__]

[[Alibaba](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366423.3380013)] PARS: Peers-aware Recommender System [__`eco.`__,__`ran.`__,__`fe.`__] :yellow_heart:

[[Etsy](https://dl.acm.org/doi/pdf/10.1145/3366423.3380002)] Attentive Sequential Models of Latent Intent for Next Item Recommendation [__`seq.`__,__`att.`__]

[[Amazon](https://dl.acm.org/doi/pdf/10.1145/3394486.3403368)] Taming Pretrained Transformers for Extreme Multi-label Text Classification [__`tra.`__,__`oth.`__,__`txt.`__] :yellow_heart:

[[Netflix](https://dl.acm.org/doi/pdf/10.1145/3383313.3418484)] Learning Representations of Hierarchical Slates in Collaborative Filtering [__`oth.`__]

[[Adobe Research](https://dl.acm.org/doi/pdf/10.1145/3383313.3412255)] Goal-driven Command Recommendations for Analysts [__`oth.`__]

[[Spotify](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366424.3384362)] Leveraging Behavioral Heterogeneity Across Markets for Cross-Market Training of Recommender Systems [__`tra.`__,__`fe.`__]

[[Google](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366424.3386195)] Mixed Negative Sampling for Learning Two-tower Neural Networks in Recommendations [__`fe.`__,__`ret.`__,__`ran.`__]

[[Facebook](https://dl.acm.org/doi/pdf/10.1145/3394486.3403304)] CLARA: Confidence of Labels and Raters [__`oth.`__] :yellow_heart:

[[Baidu](https://dl.acm.org/doi/pdf/10.1145/3394486.3403327)] Geodemographic Influence Maximization [__`oth.`__,__`net.`__]

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3394486.3403352)] Multi-objective Optimization for Guaranteed Delivery in Video Service Platform [__`mt.`__,__`vid.`__]

<a name="in_2019"></a>
### 2019
[[Netflix](https://arxiv.org/pdf/1905.03375.pdf)] Embarrassingly Shallow Autoencoders for Sparse Data [__`fe.`__,__`ae.`__] :heart_eyes:

[[Apple](http://ceur-ws.org/Vol-2431/paper10.pdf)] PQ-VAE: Efficient Recommendation Using Quantized Embeddings [__`ae.`__, __`sca.`__]

[[NAVER Corp.](https://arxiv.org/pdf/1908.02569.pdf)] Tripartite Heterogeneous Graph Propagation for Large-scale Social Recommendation [__`gnn`__,__`att.`__,__`sca.`__, __`ads.`__, __`eco.`__]

[[Facebook & Amazon](https://dl.acm.org/doi/pdf/10.1145/3298689.3347027) LORE: A Large-Scale Offer Recommendation Engine with Eligibility and Capacity Constraints [__`sca.`__]

[[Tecent](https://dl.acm.org/doi/pdf/10.1145/3292500.3330728)] Large-scale User Visits Understanding and Forecasting with Deep Spatial-Temporal Tensor Factorization Framework [__`hyb.`__, __`seq.`__, __`geo.`__,__`sca.`__]

[[Google](https://dl.acm.org/doi/pdf/10.1145/3292500.3330677)] TF-Ranking: Scalable TensorFlow Library for Learning-to-Rank [__`sca.`__,__`ran.`__, __`ret.`__] :star:

[[eBay and Microsoft Research](https://dl.acm.org/doi/pdf/10.1145/3298689.3347044)] When Actions Speak Louder than Clicks: A Combined Model of Purchase Probability and Long-term Customer Satisfaction [__`ee.`__, __`eco.`__]

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3308558.3313469?casa_token=Ljqto7-qUnUAAAAA:hKMUsSiva812p5WMBkDJc3lzjsQwcY9pNiP0oWf_aVnMpaVnTeY4EOjHRu-S0cJeaIlqL1VBUKA)] How Serendipity Improves User Satisfaction with Recommendations? A Large-Scale User Evaluation [__`ee.`__,__`mlp`__]

[[TrueFit](https://dl.acm.org/doi/pdf/10.1145/3298689.3347047)] Users in the Loop: A Psychologically-Informed Approach to Similar Item Retrieval [__`ret.`__,__`fas.`__,__`per.`__,__`img.`__]

[[Yahoo Research](https://dl.acm.org/doi/pdf/10.1145/3308558.3313412)] Click Feedback-Aware Query Recommendation Using Adversarial Examples [__`ran.`__,__`ret.`__,__`adv.`__,__`txt.`__] :yellow_heart:

[[Tecent](https://dl.acm.org/doi/pdf/10.1145/3292500.3330786)] A Deep Generative Approach to Search Extrapolation and Recommendation [__`ran.`__,__`ret.`__,__`rnn.`__,__`txt.`__]

[[Airbnb](https://dl.acm.org/doi/pdf/10.1145/3292500.3330658)] Applying Deep Learning To Airbnb Search [__`ran.`__,__`eco`__] :yellow_heart:

[[Google](https://dl.acm.org/doi/pdf/10.1145/3292500.3330676)] Combining Decision Trees and Neural Networks for Learning-to-Rank in Personal Search [__`ran.`__, __`per.`__, __`hyb.`__] :yellow_heart:

[[Amazon](https://dl.acm.org/doi/pdf/10.1145/3292500.3330759)] Semantic Product Search [__`ran.`__,__`ret.`__,__`mlp.`__]

[[Google](https://dl.acm.org/doi/pdf/10.1145/3292500.3330723)] Gmail Smart Compose: Real-Time Assisted Writing [__`txt.`__] :yellow_heart:

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3292500.3330659)] Personalized Attraction Enhanced Sponsored Search with Multi-task Learning [__`ran.`__,__`ret.`__,__`per.`__,__`eco.`__,__`mt.`__,__`att.`__]

[[Booking.com](http://ceur-ws.org/Vol-2431/paper3.pdf)] Combining Context Features in Sequence-Aware Recommender Systems [__`fe.`__,__`seq.`__,__`rnn.`__]

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3298689.3347000)] Personalized Re-ranking for Recommendation [__`ran.`__,__`per.`__, __`att.`__] :yellow_heart:

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3308558.3313568)] Personalized Bundle List Recommendation [__`per.`__,__`fas`__,__`ee.`__,__`hyb.`__,__`img.`__] :yellow_heart:

[[VISA Research](https://dl.acm.org/doi/pdf/10.1145/3308558.3313494)] Pcard: Personalized Restaurants Recommendation from Card Payment Transaction Records [__`geo.`__,__`per.`__,__`mlp.`__]

[[Amazon Alexa & Facebook](https://dl.acm.org/doi/pdf/10.1145/3308558.3313513)] User-Video Co-Attention Network for Personalized Micro-video Recommendation [__`per.`__,__`att.`__,__`vid.`__] :yellow_heart:

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3292500.3330659)] Personalized Attraction Enhanced Sponsored Search with Multi-task Learning [__`ran.`__,__`ret.`__,__`per.`__,__`mt.`__,__`eco.`__, __`att.`__]

[[Microsoft](https://dl.acm.org/doi/pdf/10.1145/3298689.3347038)] CB2CF: A Neural Multiview Content-to-Collaborative Filtering Model for Completely Cold Item Recommendations [__`cs.`__,__`hyb.`__] :yellow_heart:

[[KDDI Research](https://dl.acm.org/doi/pdf/10.1145/3308560.3316596)] Preliminary Investigation of Alleviating User Cold-Start Problem in E-commerce with Deep Cross-Domain Recommender System [__`cs.`__,__`tra.`__,__`eco.`__,__`mlp.`__]

[[Tecent](https://dl.acm.org/doi/pdf/10.1145/3292500.3330707)] Real-time Attention Based Look-alike Model for Recommender System [__`imb.`__,__`mlp.`__,__`att.`__,__`cs.`__]

[[Google](https://dl.acm.org/doi/pdf/10.1145/3298689.3346996)] Sampling-Bias-Corrected Neural Modeling for Large Corpus Item Recommendations [__`bia.`__,__`ret.`__, __`mlp.`__] :yellow_heart:

[[Google](https://dl.acm.org/doi/pdf/10.1145/3292500.3330745)] Fairness in Recommendation Ranking through Pairwise Comparisons [__`bia.`__] :star:

[[LinkedIn](https://dl.acm.org/doi/pdf/10.1145/3292500.3330691)] Fairness-Aware Ranking in Search & Recommendation Systems with Application to LinkedIn Talent Search [__`bia.`__]

[[JD](https://dl.acm.org/doi/pdf/10.1145/3292500.3330668)] Reinforcement Learning to Optimize Long-term User Engagement in Recommender Systems [ __`drl`__, __`fe.`__,__`per.`__]

[[Netflix](https://dl.acm.org/doi/pdf/10.1145/3298689.3347036)] Variational Low Rank Multinomials for Collaborative Filtering with Side-Information [__`kg.`__,__`mlp.`__]

[[JD](https://dl.acm.org/doi/pdf/10.1145/3308558.3313488)] Graph Neural Networks for Social Recommendation [__`gnn.`__, __`net.`__] :fire:

[[MSRA](https://dl.acm.org/doi/pdf/10.1145/3308558.3313417)] Knowledge Graph Convolutional Networks for Recommender Systems [__`kg.`__,__`gnn.`__,__`net.`__] :star:

[[Microsoft](https://dl.acm.org/doi/pdf/10.1145/3308558.3313411)] Multi-Task Feature Learning for Knowledge Graph Enhanced Recommendation [__`kg.`__,__`mt.`__,__`net.`__] :star:

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3292500.3330686)] IntentGC: a Scalable Graph Convolution Framework Fusing Heterogeneous Information for Recommendation [__`kg.`__,__`gnn.`__,__`net.`__] :yellow_heart:

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3292500.3330673)] Metapath-guided Heterogeneous Graph Neural Network for Intent Recommendation [__`kg.`__,__`gnn.`__,__`net.`__] :yellow_heart:

[[Google](https://dl.acm.org/doi/pdf/10.1145/3298689.3346997)] Recommending What Video to Watch Next: A Multitask Ranking System [__`mt.`__,__`vid.`__] :star:

[[Criteo AI Labs](https://dl.acm.org/doi/pdf/10.1145/3298689.3347004)] Domain Adaptation in Display Advertising: An Application for Partner Cold-Start [__`cs.`__,__`ads.`__,__`tra.`__,__`mlp.`__]  :yellow_start:

[[Pinterest](https://dl.acm.org/doi/pdf/10.1145/3292500.3330714)] Finding Users Who Act Alike: Transfer Learning for Expanding Advertiser Audiences [__`tra.`__,__`ads.`__] :yellow_heart:

[[Pinterest](https://dl.acm.org/doi/pdf/10.1145/3292500.3330739)] Learning a Unified Embedding for Visual Search at Pinterest [__`mt.`__,__`ret.`__,__`ran.`__,__`img.`__] :yellow_heart:

[[Pinterest](https://dl.acm.org/doi/pdf/10.1145/3292500.3330671)] PinText: A Multitask Text Embedding System in Pinterest [__`mt.`__,__`txt.`__]

[[Sina Weibo](https://dl.acm.org/doi/pdf/10.1145/3298689.3347043)] FiBiNET: Combining Feature Importance and Bilinear Feature Interaction for Click-Through Rate Prediction [__`fe.`__,__`ads.`__,__`att.`__] :yellow_heart:

[[MSR](https://dl.acm.org/doi/pdf/10.1145/3383313.3412267)] “Who doesn’t like dinosaurs?” Finding and Eliciting Richer Preferences for Recommendation [__`fe.`__]

[[Twitter](https://dl.acm.org/doi/pdf/10.1145/3298689.3347002)] Addressing Delayed Feedback for Continuous Training with Neural Networks in CTR prediction [__`ads.`__]

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3292500.3330700)] A Unified Framework for Marketing Budget Allocation [__`ads.`__]

[[Baidu](https://dl.acm.org/doi/pdf/10.1145/3292500.3330782)] AiAds: Automated and Intelligent Advertising System for Sponsored Search [__`ads.`__,__`hyb.`__]

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3292500.3330681)] Bid Optimization by Multivariable Control in Display Advertising [__`ads.`__]

[[Yahoo](https://dl.acm.org/doi/pdf/10.1145/3292500.3330740)] Carousel Ads Optimization in Yahoo Gemini Native [__`ads.`__,__`ee.`__,__`drl.`__]

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3292500.3330655)] Deep Spatio-Temporal Neural Networks for Click-Through Rate Prediction [__`ads.`__,__`geo.`__,__`seq.`__,__`mlp.`__]

[[Baidu](https://dl.acm.org/doi/pdf/10.1145/3292500.3330651)] MOBIUS: Towards the Next Generation of Query-Ad Matching in Baidu’s Sponsored Search [__`ads.`__,__`ran.`__,__`ret.`__,__`mlp.`__] :yellow_heart:

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3292500.3330666)] Practice on Long Sequential User Behavior Modeling for Click-Through Rate Prediction [__`ads.`__,__`seq.`__,__`hyb.`__] :yellow_heart:

[[Verizon Media](https://dl.acm.org/doi/pdf/10.1145/3292500.3330783)] Predicting Different Types of Conversions with Multi-Task Learning in Online Advertising [__`ads.`__,__`mt.`__,__`mlp.`__]

[[Verizon Media](https://dl.acm.org/doi/pdf/10.1145/3292500.3330749)] Recurrent Neural Networks for Stochastic Control in Real-Time Bidding [__`ads.`__,__`rnn.`__]

[[Baidu](https://dl.acm.org/doi/pdf/10.1145/3292500.3330698)] A Collaborative Learning Framework to Tag Refinement for Points of Interest [__`geo.`__, __`net.`__] :yellow_heart:

[[Baidu Research](https://dl.acm.org/doi/pdf/10.1145/3292500.3330660)] Hydra: A Personalized and Context-Aware Multi-Modal Transportation Recommendation System [__`geo.`__,__`per.`__,__`fe.`__,__`mm.`__,__`net.`__] :yellow_heart:

[[Zalando and shopify](https://dl.acm.org/doi/pdf/10.1145/3298689.3347006)] A Deep Learning System for Predicting Size and Fit in Fashion [__`fas.`__,__`per.`__,__`cs.`__,__`eco.`__] :yellow_heart:

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3292500.3330652)] POG: Personalized Outfit Generation for Fashion Recommendation at Alibaba iFashion [__`fas.`__,__`per.`__,__`att.`__,__`eco.`__] :yellow_heart:

[[Alibaba & Kuai](https://dl.acm.org/doi/pdf/10.1145/3298689.3346998)] A Pareto-Eficient Algorithm for Multiple Objective Optimization in E-Commerce Recommendation [__`ran.`__,__`eco.`__,__`mt.`__] :yellow_heart:

[[Walmart](https://dl.acm.org/doi/pdf/10.1145/3292500.3330748)] Anomaly Detection for an E-commerce Pricing System [__`eco.`__] :yellow_heart:

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3292500.3330670)] Buying or Browsing? : Predicting Real-time Purchasing Intent using Attention-based Deep Network with Multiple Behavior [__`eco.`__, __`att.`__]

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3292500.3330716)] Infer Implicit Contexts in Real-time Online-to-Offline Recommendation [__`eco.`__,__`att.`__, __`fe.`__]

[[Facebook](https://dl.acm.org/doi/pdf/10.1145/3292500.3330696)] MSURU: Large Scale E-commerce Image Classification With Weakly Supervised Search Data [__`eco.`__,__`sca.`__,__`img.`__] :yellow_heart:

[[JD](https://dl.acm.org/doi/pdf/10.1145/3292500.3330790)] Online Purchase Prediction via Multi-Scale Modeling of Behavior Dynamics [__`eco.`__,__`hyb.`__]

[[Twitter](https://dl.acm.org/doi/pdf/10.1145/3292500.3330760)] Understanding the Role of Style in E-commerce Shopping [__`eco.`__,__`fas.`__] :yellow_heart:

[[Snapchat](https://dl.acm.org/doi/pdf/10.1145/3292500.3330750)] Characterizing and Forecasting User Engagement with In-app Action Graph: A Case Study of Snapchat [__`fe.`__,__`hyb.`__,__`net.`__,__`per.`__] :yellow_heart:

[[Amazon](https://dl.acm.org/doi/pdf/10.1145/3308558.3313449)] GhostLink: Latent Network Inference for Influence-aware Recommendation [__`oth.`__,__`net.`__]

[[Google](https://dl.acm.org/doi/pdf/10.1145/3308558.3313650)] Towards Neural Mixture Recommender for Long Range Dependent User Sequences [__`seq.`__,__`fe.`__,__`att.`__] :yellow_heart:

[[Pinterest](https://dl.acm.org/doi/pdf/10.1145/3308558.3313747)] Hierarchical Temporal Convolutional Networks for Dynamic Recommender Systems [__`seq.`__,__`oth.`__] :yellow_heart:

[[Preferred Networks](https://dl.acm.org/doi/pdf/10.1145/3292500.3330701)] Optuna: A Next-generation Hyperparameter Optimization Framework [__`oth.`__] :fire:

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3292500.3330726)] Sequential Scenario-Specific Meta Learner for Online Recommendation [__`per.`__,__`tra.`__,__`seq.`__]

[[Google](https://dl.acm.org/doi/pdf/10.1145/3331184.3331211)] Transparent, Scrutable and Explainable User Models for Personalized Recommendation [__`int.`__,__`per.`__]

[[Alibaba](https://arxiv.org/pdf/1907.00687.pdf)] A Capsule Network for Recommendation and Explaining What You Like and Dislike [__`kg.`__,__`fe.`__]

<a name="in_2018"></a>
### 2018
[[Microsoft Research](https://arxiv.org/pdf/1803.05170.pdf)] xDeepFM: Combining Explicit and Implicit Feature Interactions for Recommender Systems [__`mlp.`__, __`fe.`__] :fire: :heart_eyes:

[[Deezer SA](https://arxiv.org/pdf/1804.04212.pdf)] Word2vec applied to Recommendation: Hyperparameters Matter [__`fe.`__,__`tra.`__,__`txt.`__] :star:

[[Spotify](https://static1.squarespace.com/static/5ae0d0b48ab7227d232c2bea/t/5ba849e3c83025fa56814f45/1537755637453/BartRecSys.pdf)] Explore, Exploit, and Explain: Personalizing Explainable Recommendations with Bandits [__`ee.`__,__`int.`__,__`drl.`__,__`per.`__] :star:

[[Netflix](https://dl.acm.org/doi/pdf/10.1145/3240323.3240372)] Calibrated Recommendations [__`ee.`__,__`bia.`__] :star:

[[JD](https://arxiv.org/pdf/1805.02343.pdf)] Deep Reinforcement Learning for Page-wise Recommendations [__`seq.`__,__`drl.`__] :fire:

[[MSRA](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3209978.3210083)] Attention-driven Factor Model for Explainable Personalized Recommendation [__`per.`__,__`int.`__,__`att.`__,__`fe.`__]

[[Google](https://arxiv.org/pdf/1804.10862.pdf)] Collaborative Memory Network for Recommendation Systems [__`fe.`__,__`att.`__,__`kg.`__] :fire: :x:

[[LinkedIn](https://arxiv.org/pdf/1809.06481.pdf)] Talent Search and Recommendation Systems at LinkedIn: Practical Challenges and Lessons Learned [__`ran.`__,__`ret.`__] :yellow_heart:

[[HTC](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3209978.3210017)] Improving Sequential Recommendation with Knowledge-Enhanced Memory Networks [__`seq.`__,__`kg.`__,__`rnn.`__] :fire:

[[Pinterest](https://arxiv.org/pdf/1711.07601.pdf)] Pixie: A System for Recommending 3+ Billion Items to 200+ Million Users in Real-Time [__`sca.`__,__`per.`__,__`net.`__] :star:

[[Amazon](https://dl.acm.org/doi/pdf/10.1145/3178876.3186149)] Bayesian Models for Product Size Recommendations [__`fas.`__,__`per.`__,__`eco.`__] :yellow_heart:

[[MSRA](https://arxiv.org/pdf/1801.08284.pdf)] DKN: Deep Knowledge-Aware Network for News Recommendation [__`kg.`__,__`att.`__,__`per.`__] :fire:

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3219819.3220122)] Stabilizing Reinforcement Learning in Dynamic Environment with Application to Online Recommendation [__`drl.`__] :star:

[[Google](http://alexbeutel.com/papers/q-and-r-kdd2018.pdf)] Q&R: A Two-Stage Approach towards Interactive Recommendation [__`rnn.`__,__`vid.`__,__`seq.`__]

[[JD](https://arxiv.org/pdf/1808.01075.pdf)] Learning from History and Present: Next-item Recommendation via Discriminatively Exploiting User Behaviors [__`seq.`__,__`rnn.`__,__`fe.`__] :star:

[[Alibaba](https://arxiv.org/pdf/1803.02349.pdf)] Billion-scale Commodity Embedding for E-commerce Recommendation in Alibaba [__`eco.`__,__`sca.`__,__`imb.`__,__`cs.`__,__`net.`__,__`kg.`__] :fire:

[[Pinterest](https://arxiv.org/pdf/1806.01973.pdf)] Graph Convolutional Neural Networks for Web-Scale Recommender Systems [__`kg.`__,__`gnn.`__,__`sca.`__,__`net.`__,__`fe.`__] :fire:

[[JD](https://arxiv.org/pdf/1802.06501.pdf)] Recommendations with Negative Feedback via Pairwise Deep Reinforcement Learning [__`drl.`__,__`fe.`__] :fire:

[[Alibaba](https://arxiv.org/pdf/1801.02294.pdf)] Learning Tree-based Deep Model for Recommender Systems [__`fe.`__,__`sca.`__] :star:

[[Google AI](https://dl.acm.org/doi/pdf/10.1145/3219819.3219856)]  Collaborative Deep Metric Learning for Video Understanding [__`fe.`__,__`cnn.`__,__`vid.`__]

<a name="in_2017"></a>
### 2017
[[HuaWei](https://arxiv.org/pdf/1703.04247.pdf)] DeepFM: A Factorization-Machine based Neural Network for CTR Prediction [__`mlp.`__,__`ads.`__, __`fe.`__] :fire: :heart_eyes:

[[Microsoft Research](https://www.microsoft.com/en-us/research/uploads/prod/2019/07/pp004-lian.pdf)] CCCFNet: A Content-Boosted Collaborative Filtering Neural Network for Cross Domain Recommender Systems [__`tra.`__,__`mlp.`__, __`fe.`__,__`kg.`__] :star:

[[Alibaba](http://papers.www2017.com.au.s3.amazonaws.com/companion/p769.pdf)] Locally Connected Deep Learning Framework for Industrial-scale Recommender Systems [__`fe.`__,__`mlp.`__,__`sca.`__] :yellow_heart:

[[Google](https://arxiv.org/pdf/1804.10862.pdf)] Memory Networks for Recommendation [__`fe.`__,__`att.`__] :fire:

[[Google & Pinterest](http://www.alexbeutel.com/papers/www2017_focused_learning.pdf)] Beyond Globally Optimal: Focused Learning for Improved Recommendations [__`imb.`__, __`kg.`__,__`cs.`__] :star:

[[Yahoo Lab](https://arxiv.org/pdf/1607.06182.pdf)] Streaming Recommender Systems [__`seq.`__,__`dyn.`__,__`sca.`__] :fire:

[[Pinterest](https://arxiv.org/pdf/1702.07969.pdf)] Related Pins at Pinterest: The Evolution of a Real-World Recommender System. [__`ran.`__,__`ret.`__,__`fe.`__] :star: 

[[Tecent](https://www.comp.nus.edu.sg/~xiangnan/papers/sigir17-AttentiveCF.pdf)] Attentive Collaborative Filtering: Multimedia Recommendation with Item- and Component-Level Attention. [__`fe.`__,__`att.`__,__`mlp.`__] :fire: :x:

[[IBM Research](https://dl.acm.org/doi/pdf/10.1145/3077136.3080776)] Personalized Key Frame Recommendation [__`per.`__,__`mm.`__,__`vid.`__] :star:

[[Twitter and Google Brain](https://papers.nips.cc/paper/2017/file/51e6d6e679953c6311757004d8cbbba9-Paper.pdf)] A Meta-Learning Perspective on Cold-Start Recommendations for Items [__`cs.`__,__`tra.`__,__`mlp.`__] :star:

[[layers6.ai](https://proceedings.neurips.cc/paper/2017/file/dbd22ba3bd0df8f385bdac3e9f8be207-Paper.pdf)] DropoutNet: Addressing Cold Start in Recommender Systems [__`cs.`__, __`fe.`__] :star:

[[Yahoo](http://library.usc.edu.ph/ACM/KKD%202017/pdfs/p1933.pdf)] Embedding-based News Recommendation for Millions of Users [__`sca.`__,__`hyb.`__,__`fe.`__,__`rnn.`__,__`seq.`__] :fire:

[[LinkedIn & Google](http://cseweb.ucsd.edu/classes/fa17/cse291-b/reading/rrn_wsdm2017.pdf)] Recurrent Recommender Networks [__`seq.`__,__`rnn.`__,__`fe.`__] :fire:

[[Google Research](https://openreview.net/pdf?id=Bkv9FyHYx)] Joint Training of Ratings and Reviews with Recurrent Recommender Networks [__`mt.`__,__`seq.`__,__`rnn.`__,__`fe.`__,__`kg.`__] 

[[LinkedIn & Amazon ML](https://cseweb.ucsd.edu/classes/fa17/cse291-b/reading/p515-jing.pdf)] Neural Survival Recommender [__`seq.`__,__`rnn.`__,__`fe.`__,__`mt.`__] :fire:

[[Google](https://arxiv.org/pdf/1708.05123.pdf)] Deep & Cross Network for Ad Click Predictions [__`fe.`__,__`mlp.`__] :fire: :heart_eyes:

<a name="in_2016"></a>
### 2016
[[Google](https://arxiv.org/pdf/1606.07792.pdf)] Wide & Deep Learning for Recommender Systems [__`mlp.`__, __`fe.`__] :fire: :heart_eyes:

[[Google](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45530.pdf)] Deep neural networks for youtube recommendations. [__`mlp.`__,__`sca.`__, __`fe.`__] :fire:

[[Microsoft Research](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/frp1159-songA.pdf)] A Multi-View Deep Learning Approach for Cross Domain User Modeling in Recommendation Systems [__`fe.`__,__`sca.`__,__`tra.`__] :fire:

[[Netflix](https://arxiv.org/pdf/1511.06939.pdf)] Session-based recommendations with recurrent neural networks. [__`seq.`__,__`rnn.`__,__`fe.`__] :fire:

[[NetEase](https://cfm.uestc.edu.cn/~zhangdongxiang/papers/ICDE16_industry_231.pdf)] Personal Recommendation Using Deep Recurrent Neural Networks in NetEase [__`seq.`__,__`rnn.`__,__`fe.`__,__`per.`__] :fire:

[[Microsoft](https://www.kdd.org/kdd2016/papers/files/adf0975-shanA.pdf)] Deep Crossing: Web-Scale Modeling without Manually Crafted Combinatorial Features [__`fe.`__,__`cnn.`__] :fire: :heart_eyes:

<a name="in_2013"></a>
### 2013
[[Microsoft](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/cikm2013_DSSM_fullversion.pdf)] Learning Deep Structured Semantic Models for Web Search using Clickthrough Data [__`fe.`__,__`sca.`__] :fire:

## Academic Papers

<a name="ac_2019"></a>
### 2019
[[KDD](https://dl.acm.org/doi/pdf/10.1145/3292500.3330664)] Mathematical Notions vs. Human Perception of Fairness: A Descriptive Approach to Fairness for Machine Learning [__`bia.`__]

[[KDD](https://dl.acm.org/doi/pdf/10.1145/3292500.3330835)] Effective and Efficient Reuse of Past Travel Behavior for Route Recommendation [__`geo.`__,__`net.`__]

[[KDD](https://dl.acm.org/doi/pdf/10.1145/3292500.3330839)] Streaming Session-based Recommendation [__`seq.`__,__`att.`__]

[[KDD](https://arxiv.org/pdf/1908.00413.pdf)] MeLU: Meta-Learned User Preference Estimator for Cold-Start Recommendation [__`cs.`__,__`tra.`__]

[[KDD](https://dl.acm.org/doi/pdf/10.1145/3292500.3330906)] DAML: Dual Attention Mutual Learning between Ratings and Reviews for Item Recommendation [__`att.`__,__`kg.`__,__`fe.`__]

[[KDD](https://arxiv.org/pdf/1906.09217.pdf)] Hierarchical Gating Networks for Sequential Recommendation [__`seq.`__,__`fe.`__,__`per.`__]

[[KDD](https://arxiv.org/pdf/1905.07854.pdf)] KGAT: Knowledge Graph Attention Network for Recommendation [__`kg.`__,__`gnn.`__,__`fe.`__] :fire:

[[KDD](https://arxiv.org/pdf/1905.04413.pdf)] Knowledge-aware Graph Neural Networks with Label Smoothness Regularization for Recommender Systems [__`kg.`__,__`gnn.`__,__`fe.`__] :star:

[[KDD](https://arxiv.org/pdf/1907.05559.pdf)] NPA: Neural News Recommendation with Personalized Attention [__`per.`__,__`att.`__,__`cnn.`__]

[[SIGIR](https://dl.acm.org/doi/pdf/10.1145/3331184.3331254)] Personalized Fashion Recommendation with Visual Explanations based on Multimodal Attention Network [__`fas.`__,__`per.`__,__`mm.`__,__`att.`__,__`int.`__]

[[SIGIR](https://dl.acm.org/doi/pdf/10.1145/3331184.3331192)] An Efficient Adaptive Transfer Neural Network for Social-aware Recommendation [__`tra.`__,__`net.`__]

[[SIGIR](https://staff.fnwi.uva.nl/m.derijke/wp-content/papercite-data/pdf/wang-2019-collaborative.pdf)] A Collaborative Session-based Recommendation Approach with Parallel Memory Modules [__`seq.`__,__`fe.`__,__`rnn.`__,__`att.`__]

[[SIGIR](https://arxiv.org/pdf/1904.10322.pdf)] A Neural Influence Diffusion Model for Social Recommendation [__`fe.`__,__`net.`__] :star:

[[SIGIR](https://arxiv.org/pdf/1906.05237.pdf)] Reinforcement Knowledge Graph Reasoning for Explainable Recommendation [__`drl.`__,__`kg.`__,__`int.`__,__`net.`__]

[[SIGIR](https://arxiv.org/pdf/1904.12796.pdf)] Relational Collaborative Filtering: Modeling Multiple Item Relations for Recommendation [__`att.`__,__`fe.`__]

[[ICML](https://arxiv.org/pdf/1812.10613.pdf)] Generative Adversarial User Model for Reinforcement Learning Based Recommendation System [__`drl.`__,__`adv.`__,__`fe.`__]

[[ICML](http://proceedings.mlr.press/v97/wang19n/wang19n.pdf)] Doubly Robust Joint Learning for Recommendation on Data Missing Not at Random [__`mt.`__,__`imb.`__,__`bia.`__]

<a name="ac_2018"></a>
### 2018
[[IJCAI](https://www.ijcai.org/Proceedings/2018/0510.pdf)] NeuRec: On Nonlinear Transformation for Personalized Ranking [__`mlp.`__, __`per.`__， __`ran.`__,__`fe.`__] :x:

[[RecSys](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3240323.3240383)] RecGAN: Recurrent Generative Adversarial Networks for Recommendation Systems [__`seq.`__,__`adv.`__,__`rnn.`__,__`dyn.`__] :x:

[[RecSys](https://arxiv.org/pdf/1706.07639.pdf)] Causal Embeddings for Recommendation [__`int.`__,__`tra.`__]

[[RecSys](https://arxiv.org/pdf/1710.11214.pdf)] How Algorithmic Confounding in Recommendation Systems Increases Homogeneity and Decreases Utility [__`ee.`__] :star:

[[RecSys](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3240323.3240407)] Audio-visual Encoding of Multimedia Content for Enhancing Movie Recommendations [__`mm.`__,__`fe.`__]

[[RecSys](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3240323.3240373)] Exploring Author Gender in Book Rating and Recommendation [__`bia.`__,__`eco.`__]

[[RecSys](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3240323.3240358)] Effects of Personal Characteristics on Music Recommender Systems with Different Levels of Controllability [__`fe.`__,__`per.`__,__`aud.`__]

[[RecSys](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3240323.3240384)] StreamingRec: A Framework for Benchmarking Stream-based News Recommenders [__`seq.`__,__`sca.`__]

[[RecSys](https://arxiv.org/pdf/1807.01227.pdf)] Providing Explanations for Recommendations in Reciprocal Environments [__`int.`__]

[[RecSys](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3240323.3240365)] Why I like it: Multi-task Learning for Recommendation and Explanation [__`mt.`__,__`int.`__,__`per.`__,__`ret.`__,__`adv.`__]

[[RecSys](https://cseweb.ucsd.edu/~jmcauley/pdfs/recsys18e.pdf)] Decomposing Fit Semantics for Product Size Recommendation in Metric Spaces [__`fas.`__,__`eco.`__,__`per.`__]

[[RecSys](https://cseweb.ucsd.edu/~jmcauley/pdfs/recsys18a.pdf)] Translation-based Factorization Machines for Sequential Recommendation [__`seq.`__,__`fe.`__,__`sca.`__] :star:

[[RecSys](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3240323.3240361)] Recurrent Knowledge Graph Embedding for Effective Recommendation [__`kg.`__,__`att.`__,__`rnn.`__,__`fe.`__] :star: :x:

[[RecSys](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3240323.3240347)] On the Robustness and Discriminative Power of Information Retrieval Metrics for Top-N Recommendation [__`oth.`__] :star:

[[RecSys](https://cseweb.ucsd.edu/~jmcauley/pdfs/recsys18b.pdf)] Item Recommendation on Monotonic Behavior Chains [__`fe.`__,__`seq.`__] :star:

[[RecSys](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3240323.3240381)] HOP-Rec: High-Order Proximity for Implicit Recommendation [__`fe.`__,__`net.`__,__`mlp.`__]

[[RecSys](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3240323.3240355)] Unbiased offline recommender evaluation for missing-not-at-random implicit feedback [__`bia.`__] :star:

[[SIGIR](https://arxiv.org/pdf/1808.03908.pdf)] Adversarial Personalized Ranking for Recommendation [__`per.`__,__`adv.`__,__`ran.`__] :fire:

[[SIGIR](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3209978.3210129)] An Attribute-aware Neural Attentive Model for Next Basket Recommendation [__`fe.`__,__`att.`__,__`seq.`__,__`rnn.`__] 

[[SIGIR](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3209978.3210014)] Should I Follow the Crowd? A Probabilistic Analysis of the Effectiveness of Popularity in Recommender Systems [__`oth.`__]

[[SIGIR](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3209978.3209998)] Attentive Group Recommendation [__`cs.`__,__`att.`__,__`fe.`__] :star:

[[SIGIR](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3209978.3210042)] A Contextual Attention Recurrent Architecture for Context-Aware Venue Recommendation [__`fe.`__,__`geo.`__,__`seq.`__,__`att.`__,__`dyn.`__] :x:

[[SIGIR](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3209978.3210023)] Attentive Recurrent Social Recommendation [__`att.`__,__`fe.`__,__`dyn.`__,__`rnn.`__,__`net.`__] :star:

[[SIGIR](https://arxiv.org/pdf/1806.03277.pdf)] Conversational Recommender System [__`seq.`__,__`per.`__,__`drl.`__] :fire:

[[SIGIR](https://dl.acm.org/doi/pdf/10.1145/3209978.3210037)] The Rise of Guardians: Fact-checking URL Recommendation to Combat Fake News [__`net.`__,__`int.`__]

[[SIGIR](https://arxiv.org/pdf/1806.03568.pdf)] Explainable Recommendation via Multi-Task Learning in Opinionated Text Data [__`int.`__,__`mt.`__,__`txt.`__,__`per.`__] :star:

[[SIGIR](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3209978.3210016)] Streaming Ranking Based Recommender Systems [__`seq.`__,__`ret.`__,__`sca.`__]

[[WWW](https://dl.acm.org/doi/pdf/10.1145/3178876.3186158)] Coevolutionary Recommendation Model: Mutual Learning between Ratings and Reviews [__`mt.`__,__`att.`__,__`rnn.`__,__`int.`__, __`kg.`__] :star:

[[WWW](https://dl.acm.org/doi/pdf/10.1145/3178876.3186140)] Algorithmic Glass Ceiling in Social Networks: The effects of social recommendations on network diversity [__`bia.`__,__`ee.`__]

[[WWW](https://dl.acm.org/doi/pdf/10.1145/3184558.3191558)] Travel Itinerary Recommendations with Must-see Points-of-Interest [__`geo.`__,__`net.`__]

[[WWW](http://staff.ustc.edu.cn/~hexn/papers/www18-tem.pdf)] TEM: Tree-enhanced Embedding Model for Explainable Recommendation [__`int.`__,__`fe.`__] :fire:

[[WWW](https://arxiv.org/pdf/1809.05822.pdf)] Aesthetic-based Clothing Recommendation [__`fas.`__,__`kg.`__,__`fe.`__,__`per.`__] :fire:

[[WWW](https://www.personal.psu.edu/~gjz5038/paper/www2018_reinforceRec/www2018_reinforceRec.pdf)] DRN: A Deep Reinforcement Learning Framework for News Recommendation [__`drl.`__,__`dyn.`__] :fire:

[[KDD](http://www.shichuan.org/doc/47.pdf)] Leveraging Meta-path based Context for Top-N Recommendation with A Neural Co-Attention Model [__`kg.`__,__`att.`__,__`fe.`__,__`net.`__] :fire: :x:

[[KDD](https://dl.acm.org/doi/pdf/10.1145/3219819.3220072)] Explanation Mining: Post Hoc Interpretability of Latent Factor Models for Recommendation Systems [__`int.`__]

[[KDD](https://arxiv.org/pdf/1809.07428.pdf)] Ranking Distillation: Learning Compact Ranking Models With High Performance for Recommender System [__`tra.`__,__`ran.`__]

[[KDD](https://arxiv.org/pdf/1801.09251.pdf)] Multi-Pointer Co-Attention Networks for Recommendation [__`kg.`__,__`fe.`__,__`att.`__] :fire: :x:

[[KDD](https://dl.acm.org/doi/pdf/10.1145/3219819.3220004)] Neural Memory Streaming Recommender Networks with Adversarial Training [__`seq.`__,__`adv.`__,__`fe.`__] :star:

[[KDD](https://arxiv.org/pdf/1807.01473.pdf)] Supervised Reinforcement Learning with Recurrent Neural Network for Dynamic Treatment Recommendation [__`seq.`__,__`drl.`__,__`rnn.`__] :star:

[[WWW](https://arxiv.org/pdf/1802.05814.pdf)] Variational Autoencoders for Collaborative Filtering [__`ae.`__,__`fe.`__] :fire: :heart_eyes:

[[IJCAI](https://arxiv.org/pdf/1808.03912.pdf)] Outer Product-based Neural Collaborative Filtering [__`fe.`__,__`cnn.`__] :fire: :x:

[[WSDM](https://arxiv.org/pdf/1809.07426.pdf)] Personalized Top-N Sequential Recommendation via Convolutional Sequence Embedding [__`per.`__,__`seq.`__,__`cnn.`__,__`fe.`__] :fire:

[[Arxiv](https://www.kdd.org/kdd2018/files/deep-learning-day/DLDay18_paper_32.pdf)] Graph Convolutional Matrix Completion [__`fe.`__,__`gnn.`__,__`kg.`__,__`net.`__] :fire:

[[WWW](https://arxiv.org/pdf/1707.05176.pdf)] Latent Relational Metric Learning via Memory-based Attention for Collaborative Ranking [__`att.`__,__`ran.`__,__`fe.`__] :fire: :x:

[[IJCAI](https://www.ijcai.org/Proceedings/2018/0546.pdf)] Sequential Recommender System based on Hierarchical Attention Network [__`seq.`__,__`att.`__,__`fe.`__] :fire:

[[Arxiv](https://arxiv.org/pdf/1808.06414.pdf)] Next Item Recommendation with Self-Attention [__`att.`__,__`seq.`__] :star:

<a name="ac_2017"></a>
### 2017
[[WWW](https://arxiv.org/pdf/1708.05031.pdf)] Neural Collaborative Filtering [__`mlp.`__,__`fe.`__] :fire: :x:

[[SIGIR](https://arxiv.org/pdf/1706.03205.pdf)] Item Silk Road: Recommending Items from Information Domains to Social Users [__`mlp.`__,__`tra.`__,__`fe.`__] :fire:

[[IJCAI](https://www.ijcai.org/Proceedings/2017/0447.pdf)] Deep Matrix Factorization Models for Recommender Systems [__`mlp.`__,__`fe.`__] :fire: :x:

[[SIGIR](https://arxiv.org/pdf/1708.05027.pdf)] Neural Factorization Machines for Sparse Predictive Analytics [__`mlp.`__,__`fe.`__] :fire:

[[AAAI](https://www.researchgate.net/publication/309919310_Examples-Rules_Guided_Deep_Neural_Network_for_Makeup_Recommendation)] Examples-Rules Guided Deep Neural Network for Makeup Recommendation [__`kg.`__, __`mlp.`__,__`fas.`__,__`img.`__] :star:

[[WWW](http://www.cs.cornell.edu/~ylongqi/paper/HsiehYCLBE17.pdf)] Collaborative metric learning. [__`mlp.`__,__`fe.`__] :fire:

[[RecSys](https://dl.acm.org/doi/pdf/10.1145/3109859.3109912)] Controlling Popularity Bias in Learning-to-Rank Recommendation [__`bia.`__,__`imb.`__,__`ran.`__,__`cs.`__] :star:

[[RecSys](https://arxiv.org/pdf/1704.02298.pdf)] TransNets: Learning to Transform for Recommendation [__`fe.`__,__`cnn.`__] :fire:

[[RecSys](https://cseweb.ucsd.edu/classes/fa17/cse291-b/reading/p152-donkers.pdf)] Sequential User-based Recurrent Neural Network Recommendations [__`seq.`__,__`per.`__,__`rnn.`__] :fire:

[[RecSys](https://dl.acm.org/doi/pdf/10.1145/3109859.3109908)] Exploring the Semantic Gap for Movie Recommendations [__`fe.`__] 

[[RecSys](https://dl.acm.org/doi/pdf/10.1145/3109859.3109894)] Recommending Personalized News in Short User Sessions [__`seq.`__,__`per.`__,__`dyn.`__] 

[[RecSys](https://arxiv.org/pdf/1707.02410.pdf)] Translation-based Recommendation [__`seq.`__,__`fe.`__,__`sca.`__] :fire:

[[RecSys](https://dl.acm.org/doi/pdf/10.1145/3109859.3109872)]  When Recurrent Neural Networks meet the Neighborhood for Session-Based Recommendation [__`seq.`__,__`sca.`__,__`rnn.`__] :fire:

[[RecSys](https://dl.acm.org/doi/pdf/10.1145/3109859.3109861)] Deep Cross-Domain Fashion Recommendation [__`fas.`__,__`tra.`__,__`cnn.`__] 

[[RecSys](https://dl.acm.org/doi/pdf/10.1145/3109859.3109887)] Fairness-Aware Group Recommendation with Pareto-Efficiency [__`bia.`__,__`mt.`__,__`ee.`__] :star:

[[RecSys](https://dl.acm.org/doi/pdf/10.1145/3109859.3109905)] A Multi-criteria Recommender System Exploiting Aspect-based Sentiment Analysis of Users’ Reviews [__`fe.`__,__`kg.`__,__`per.`__,__`bia.`__]

[[RecSys](http://giusepperizzo.github.io/publications/Palumbo_Rizzo-RecSys2017.pdf)] entity2rec: Learning User-Item Relatedness from Knowledge Graphs for Top-N Item Recommendation [__`kg.`__,__`ran.`__,__`fe.`__] :star:

[[RecSys](https://arxiv.org/pdf/1706.04148.pdf)] Personalizing Session-based Recommendations with Hierarchical Recurrent Neural Networks [__`seq.`__,__`per.`__,__`rnn.`__] :fire:

[[RecSys](https://cseweb.ucsd.edu/classes/fa17/cse291-b/reading/p5-rafailidis.pdf)] Learning to Rank with Trust and Distrust in Recommender Systems [__`ran.`__,__`fe.`__,__`net.`__]

[[RecSys](https://cseweb.ucsd.edu/classes/fa17/cse291-b/reading/p243-sembium.pdf)] Recommending Product Sizes to Customers [__`fas.`__,__`per.`__,__`eco.`__]

[[RecSys](https://dl.acm.org/doi/pdf/10.1145/3109859.3109900)] 3D Convolutional Networks for Session-based Recommendation with Content Features [__`seq.`__,__`cnn.`__,__`fe.`__] :star: :x:

[[RecSys](https://cseweb.ucsd.edu/classes/fa17/cse291-b/reading/Modeling%20the%20Assimilation-Contrast%20Effects%20in%20Online%20Product%20Rating%20Systems%20Debiasing%20and%20Recommendations.pdf)] Modeling the Assimilation-Contrast Effects in Online Product Rating Systems: Debiasing and Recommendations [__`bia.`__]

[[WWW](https://dl.acm.org/doi/pdf/10.1145/3038912.3052573)] Investigating the Healthiness of Internet-Sourced Recipes: Implications for Meal Planning and Recommender Systems :star:

[[WWW](https://www.researchgate.net/profile/Xin_Wang274/publication/315865891_Learning_Personalized_Preference_of_Strong_and_Weak_Ties_for_Social_Recommendation/links/5a29089baca2727dd8871e3e/Learning-Personalized-Preference-of-Strong-and-Weak-Ties-for-Social-Recommendation.pdf)] Learning Personalized Preference of Strong and Weak Ties for Social Recommendation [__`per.`__,__`net.`__] :star:

[[WWW](http://www.public.asu.edu/~skai2/files/WWW_suhang.pdf)] What Your Images Reveal: Exploiting Visual Contents for Point-of-Interest Recommendation [__`geo.`__,__`img.`__, __`net.`__] :fire:

[[SIGIR](https://dl.acm.org/doi/pdf/10.1145/3077136.3080779)] Embedding Factorization Models for Jointly Recommending Items and User Generated Lists [__`cs.`__,__`kg.`__, __`mt.`__] :star:

[[SIGIR](https://dl.acm.org/doi/pdf/10.1145/3077136.3080826)] Exploiting Food Choice Biases for Healthier Recipe Recommendation [__`eco.`__,__`img.`__] :star:

[[SIGIR](https://dl.acm.org/doi/pdf/10.1145/3077136.3080774)] Cross-Domain Recommendation via Clustering on Multi-Layer Graphs [__`tra.`__,__`kg.`__,__`net.`__]

[[SIGIR](https://arxiv.org/pdf/1708.00154.pdf)] Neural Rating Regression with Abstractive Tips Generation for Recommendation [__`eco.`__,__`mt.`__,__`rnn.`__, __`seq.`__,__`kg.`__] :fire:

[[SIGIR](https://dl.acm.org/doi/pdf/10.1145/3077136.3080778)] Personalized Itinerary Recommendation with Queuing Time Awareness [__`geo.`__,__`per.`__,__`img.`__,__`net.`__]

[[SIGIR](https://dl.acm.org/doi/pdf/10.1145/3077136.3080658)] DeepStyle: Learning User Preferences for Visual Recommendation [__`fas.`__,__`eco.`__,__`img.`__] :star:

[[SIGIR](https://dl.acm.org/doi/pdf/10.1145/3077136.3080769)] Multi-site User Behavior Modeling and Its Application in Video Recommendation [__`tra.`__,__`vid.`__]

[[KDD](https://dl.acm.org/doi/pdf/10.1145/3097983.3098173)] Post Processing Recommender Systems for Diversity [__`ee.`__] 

[[KDD](https://www.cs.uic.edu/~liub/publications/FINAL_aspect_recommendations.pdf)] Aspect Based Recommendations: Recommending Items with the Most Valuable Aspects Based on User Reviews [__`per.`__,__`fe.`__,__`kg.`__] :star:

[[KDD](https://arxiv.org/pdf/1703.01442.pdf)] Recurrent Poisson Factorization for Temporal Recommendation [__`seq.`__,__`dyn.`__] 

[[KDD](https://dl.acm.org/doi/pdf/10.1145/3097983.3098077)] Collaborative Variational Autoencoder for Recommender Systems [__`imb.`__,__`ae.`__,__`cs.`__, __`fe.`__] :fire: :x:

[[KDD](https://arxiv.org/pdf/1706.06239.pdf)] A Location-Sentiment-Aware Recommender System for Both Home-Town and Out-of-Town Users [__`geo`__,__`per.`__, __`dyn.`__,__`kg.`__]

[[KDD](http://wnzhang.net/papers/dadm-kdd.pdf)] Dynamic Attention Deep Model for Article Recommendation by Learning Human Editors' Demonstration. [__`att.`__,__`cnn.`__,__`per.`__,__`kg.`__] :fire:

[[KDD](http://chaozhang.org/papers/2017-kdd-poi-recommendation.pdf)] Bridging Collaborative Filtering and Semi-Supervised Learning: A Neural Approach for POI Recommendation. [__`imb.`__,__`cs.`__,__`geo.`__,__`fe.`__,__`mt.`__] :fire:

[[KDD](http://cseweb.ucsd.edu/classes/fa17/cse291-b/reading/Meta-Graph%20Based%20Recommendation%20Fusion%20over%20Heterogeneous%20Information%20Networks.pdf)] Meta-Graph Based Recommendation Fusion over Heterogeneous Information Networks. [__`kg.`__,__`net.`__,__`mlp.`__,__`fe.`__] :fire:

[[IJCAI](https://www.ijcai.org/Proceedings/2017/0446.pdf)] Tag-Aware Personalized Recommendation Using a Hybrid Deep Model [__`fe.`__,__`sca.`__] :x:

[[Arxiv](https://arxiv.org/pdf/1704.00551.pdf)] AutoSVD++: An Efficient Hybrid Collaborative Filtering Model via Contractive Auto-encoders [__`fe.`__,__`ae.`__,__`kg.`__] :star:

[[WWWJ](https://www.cs.ccu.edu.tw/~wtchu/papers/2017WWW-chu2.pdf)]  A hybrid recommendation system considering visual information for predicting favorite restaurants. [__`img.`__,__`cnn.`__,__`fe.`__] :star:

[[PAKDD](https://www.ismll.uni-hildesheim.de/pub/pdfs/nguyen17_pakdd.pdf)] Personalized Deep Learning for Tag Recommendation [__`fe.`__,__`cnn.`__,__`per.`__]

[[WSDM](https://arxiv.org/pdf/1701.04783.pdf)] Joint Deep Modeling of Users and Items Using Reviews for Recommendation [__`kg.`__,__`cnn.`__,__`cs.`__,__`int.`__,__`fe.`__] :fire:

[[Arxiv](https://arxiv.org/pdf/1706.03847.pdf)] Recurrent Neural Networks with Top-k Gains for Session-based Recommendations [__`seq.`__,__`rnn.`__,__`fe.`__,__`ran.`__] :fire:

[[DLRS](https://arxiv.org/pdf/1706.07684.pdf)] Contextual Sequence Modeling for Recommendation with Recurrent Neural Networks [__`seq.`__,__`fe.`__,__`rnn.`__] :star:

[[Arxiv](https://arxiv.org/pdf/1711.06632.pdf)] ATRank: An Attention-Based User Behavior Modeling Framework for Recommendation [__`att.`__,__`fe.`__] :fire:

[[IJCAI](http://qizhang.info/paper/ijcai2017hashtag.pdf)] Hashtag Recommendation for Multimodal Microblog Using Co-Attention Network [__`att.`__,__`mm.`__] :star:

[[SIGIR](https://www.cse.scu.edu/~yfang/NCN.pdf)] Neural Citation Network for Context-Aware Citation Recommendation [__`att.`__,__`net.`__,__`kg.`__] :star:

[[CIKM](https://dl.acm.org/doi/pdf/10.1145/3132847.3132892)] Joint Representation Learning for Top-N Recommendation with Heterogeneous Information Sources [__`mm`__] :fire:

<a name="ac_2016"></a>
### 2016
[[CIKM](https://zhenghuaxu.info/files/CIKM2016.pdf)] Tag-Aware Personalized Recommendation Using a Deep-Semantic Similarity Model with Negative Sampling [__`fe.`__,__`sca.`__]

[[Arxiv](https://arxiv.org/pdf/1606.07659.pdf)] Hybrid Recommender System based on Autoencoders [__`fe.`__,__`ae.`__] :fire:

[[WSDM](https://alicezheng.org/papers/wsdm16-cdae.pdf)] Collaborative Denoising Auto-Encoders for Top-N Recommender Systems [__`ae.`__,__`fe.`__] :fire: :x:

[[PAKDD](http://inpluslab.com/chenliang/homepagefiles/paper/hao-pakdd2016.pdf)] Collaborative deep ranking: a hybrid pair-wise recommendation algorithm with implicit feedback [__`ae.`__,__`fe.`__, __`kg.`__]

[[Arxiv](https://discovery.dundee.ac.uk/ws/files/39505275/Recommendation_system_for_cold_start_items.pdf)] Collaborative filtering and deep learning based hybrid recommendation for cold start problem [__`cs.`__,__`ae.`__,__`fe.`__] 

[[WWW](https://arxiv.org/pdf/1602.01585.pdf)] Ups and Downs: Modeling the Visual Evolution of Fashion Trends with One-Class Collaborative Filtering [__`fe.`__,__`fas.`__,__`cnn.`__,__`per.`__] :fire:

[[AAAI](https://arxiv.org/pdf/1510.01784.pdf)] VBPR: Visual Bayesian Personalized Ranking from Implicit Feedback [__`fe.`__,__`cnn.`__,__`sca.`__,__`cs.`__,__`kg.`__] :fire:

[[CVPR](https://arxiv.org/pdf/1604.01252.pdf)] Comparative Deep Learning of Hybrid Representations for Image Recommendations [__`fe.`__,__`cnn.`__,__`img.`__] :star:
 
 [[RecSys](http://uclab.khu.ac.kr/resources/publication/C_351.pdf)] Convolutional matrix factorization for document context-aware recommendation [__`fe.`__,__`cnn.`__,__`kg.`__] :fire: :x:
 
 [[Arxiv](https://arxiv.org/pdf/1606.08117.pdf)] Improved Recurrent Neural Networks for Session-based Recommendations [__`fe.`__,__`rnn.`__,__`seq.`__] :fire:
 
 [[RecSys](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/2959100.2959167)] Parallel Recurrent Neural Network Architectures for Feature-rich Session-based Recommendations [__`fe.`__,__`seq.`__,__`rnn.`__]
 
 [[RecSys](https://www.cc.gatech.edu/~lsong/papers/DaiWanTriSon16.pdf)] Recurrent coevolutionary latent feature processes for continuous-time recommendation [__`seq.`__,__`rnn.`__,__`fe.`__]
 
 [[RecSys](https://arxiv.org/pdf/1609.02116.pdf)] Ask the GRU: Multi-Task Learning for Deep Text Recommendations [__`seq.`__,__`rnn.`__,__`mt.`__,__`cs.`__] :fire:
 
 [[SIGIR](http://sonyis.me/paperpdf/spr209-song_sigir16.pdf)] Multi-rate deep learning for temporal recommendation [__`seq.`__,__`rnn.`__,__`sca.`__,__`dyn.`__] :fire:
 
 [[COLING](https://www.aclweb.org/anthology/C16-1284.pdf)] Hashtag Recommendation with Topical Attention-Based LSTM [__`att.`__,__`rnn.`__,__`fe.`__] :star:
 
 [[IJCAI](https://www.ijcai.org/Proceedings/16/Papers/395.pdf)] Hashtag Recommendation Using Attention-Based Convolutional Neural Network [__`att.`__,__`cnn.`__,__`fe.`__] :fire:
 
 [[RecSys](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/2959100.2959162)] Modelling Contextual Information in Session-Aware Recommender Systems with Neural Networks [__`seq.`__,__`kg.`__,__`rnn.`__] :star:
 
 [[WWW](http://www.cs.cornell.edu/~ylongqi/paper/HsiehYWNE16.pdf)] Immersive recommendation: News and event recommendations using personal digital traces [__`per.`__,__`kg.`__] :star:
 
<a name="ac_2015"></a>
### 2015
[[Arxiv](https://arxiv.org/pdf/1511.06443.pdf)] Neural network matrix factorization. [__`kg.`__,__`dyn.`__,__`mlp.`__,__`fe.`__] :star:

[[WWW](https://users.cecs.anu.edu.au/~akmenon/papers/autorec/autorec-paper.pdf)] AutoRec: Autoencoders Meet Collaborative Filtering [__`ae.`__,__`fe.`__] :fire:

[[NIPS](https://hal.inria.fr/hal-01256422v1/document)] Collaborative Filtering with Stacked Denoising AutoEncoders and Sparse Inputs [__`fe.`__,__`ae.`__] :fire:

[[KDD](https://arxiv.org/pdf/1409.2944.pdf)] Collaborative Deep Learning for Recommender Systems [__`fe.`__,__`kg.`__,__`ae.`__] :fire: :x:

## Special Topics
### Transformers in Recommendation and Ranking System
[Taming Pretrained Transformers for Extreme Multi-label Text Classification](https://dl.acm.org/doi/pdf/10.1145/3394486.3403368), Amazon, KDD, 2020.

[SSE-PT: Sequential Recommendation Via Personalized Transformer](https://dl.acm.org/doi/pdf/10.1145/3383313.3412258), RecSys, 2020. - [Video](https://vimeo.com/455947093)

[What does BERT know about books, movies and music? Probing BERT for Conversational Recommendation](https://dl.acm.org/doi/pdf/10.1145/3383313.3412249), RecSys, 2020. - [Video](https://vimeo.com/455951047)

[BERT, ELMo, USE and InferSent Sentence Encoders: The Panacea for Research-Paper Recommendation?](http://ceur-ws.org/Vol-2431/paper2.pdf), RecSys, 2019.

### AR/VR 
[In-Store Augmented Reality-Enabled Product Comparison and Recommendation](https://dl.acm.org/doi/pdf/10.1145/3383313.3412266), RecSys, 2020. - [Video](https://vimeo.com/455946175)

[Nostalgin: Extracting 3D City Models from Historical Image Data](https://dl.acm.org/doi/pdf/10.1145/3292500.3330743), Google, KDD, 2019.
