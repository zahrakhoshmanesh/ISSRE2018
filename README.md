# ISSRE2018 Memphis, TN October, 15-18
## My plan
 - Monday(Morning Session)
   - Doctoral Symposium  
 - Monday (Afternoon Session)
 - Tuesday (Morning Session)
 - Tuesday(Afternoon Session)
 - Wednesday (Morning Session)
 - Wednesday (Afternoon Session)
 - Thursday (Morning Session)
 - Thursday (Afternoon Session)


#### Keynote: Having the cake and eating it (Mladen Vouk)
talking about pursuing work in university vs. industry
- professional begging
- staying in academy
  - start-up
  - administration

#### Safety Analysis for highly automated driving. Tobias Schmid

- highly automated Systems
- failsafe
   - fail-silent
   - fail operational, fail-degraded
     - redundant architecture
- common cause failure
- qualitative approach lack applicability and standards
  - creating checklist structure
  - deriving a methodical process based on the literature
  - validation
     - case study
     - validation by field datasets
     - identification of common cause failure
- quantification
  - old : related to 1980 nuclear planet
  - analyzing failure of failure datasets
  - common cause are established in other industries
  - corellating vehicle charactericts and common cause environment
  - identifying of necessary independence

  summary

  - fail-operational affords Systems
  -


#### Testing Extract-Transform-Load Process in Data Warehouse Systems. Hajar Homayouni

- testing
  - data quality testing
   - expert based
  - balancing tests
   -
- how to detect constraint violation that are missed by domain experts?
- how to automated
- data quality test approaches
- proposed balancing test approach
- evaluating :
  - previously detected by existing tool vs. newly detected
  - metrics for balancing :
    - number of faults
    - total timely
- detect undetected faults,
- newly detected faults are faulty by unsupervised approaches
   - use unsupervised clustering to group newly detected fault based on their similarity
   - ask domain experts to validate each group of faults
- want to genralize and reduced domain base approach : unsupervised

#### Software Reliability Assessment: Modeling and Algorithms. Vidhyas Nagaraju

- SRGM: software reliability growth models
-  framework for heteregenous single changepoint software reliability growth models
- changepoint and coevoriate
- before and after change point :
  - applied ECM algorithm to identify paramete estimate
  - online changepoint analysis is demonestrated
  - heteregenous models characterize 6 out of 10 failures
  - SERAT( software reliability tool in R)





#### Enhancing Security and Reliability for Smart-* Systems' Architectures. Florian Hofer









Classroom 227 , Monday, October 15th, 2:00PM - 5:30PM (3:30PM-4:00 Coffee break),
**Tutorial 2: Anomaly Detection in Networks.**

Speaker: **Veena Mendiratta (Nokia Bell Labs, USA)**

 **Abstract**

The application of analytics methods to data collected from communication networks provides valuable information about the network state, and for detecting and predicting anomalous behavior in the network. Large volumes of operation data, including textual and log files, are collected from communication networks; and the inherent value of this data is recognized by academics, practitioners as well as network operators, who need easy to use and robust methods to detect and analyze anomalies based on the network data. The anomalies are indicators of vulnerabilities in the network. From an operations perspective, it is important to detect the anomalies and correct the problem (based on knowing the root cause) in a timely manner. The goal of this tutorial is to deliver a balanced mix of theory and hands-on practice. The first part of the tutorial will focus on introducing analytics methods for network anomaly detection. Next, a real-world case study is presented applying non-parametric machine learning techniques and PCA based methods to detect anomalies in wireless networks. Once an anomaly is detected, message patterns are analyzed for root cause analysis by comparing the message patterns of the anomaly data to those of the normal data to determine where the problems are occurring. Neural network based Kohonen Self Organizing Maps (SOMs) and visual analytics are also used for exploring the anomalous behavior. Data from a 4G network will be used for the analyses. The case study is significant, as communications traffic on wireless networks generates large
volumes of log metadata with hundreds of fields including error codes on a continuous basis across the various servers involved in a communication session. The last third of the tutorial will provide a hands-on session where attendees will be guided in the analysis of real log data using the techniques described above, in particular, the use of Kohonen SOMs. The hands-on session will focus on exploratory data analysis and modeling approaches using the provided (real) datasets. The hands-on session will be conducted using: the R software environment, the rstudio user interface for R, and various R packages.

download
 - R
 - Rstudio
 Packages:
  - dplyr
  - Kohonen
  - dummies
  - ggplot2
  - sp
  - reshape2
  - R colorBrewer
  - magrittr

Anamoly detection
 - "anamoly detection: A survey" by chandola
 - distributed approach for anamoly detection in intrusion Detection
 - change point Detection
 - "detecting and predicting outages in mobile networks wth log data" by Gurbani
 - self-organizing map: unsupervised neural networks Algorithms
 - another paper by Veena Mendiratta unsupervised approach for anomaly Detection

### Tuesday
 - key Keynote
   - Jennifer yates

#### Enhancing customer experience through machine learning by Jennifer
reliability for networks

**_network design for reliability_**
  - redundant capacity built into network to deal with failures
  - complex planning to understand failure modes, identity capacity required
  - protocol with very fast failover
- software defined network(STN)
  - commodity hardware are cheap but not reliable
  - solution : software to manage resilency
- software control : ONAP
- policy learning
 - offline ONAP control loop policy learning
   - data extraction and cleaning - signature learning - signature validation - deploy signature
 - Online closed loop learning -reinforcement learning
 - service quality management
    - fault, performance and service metrics and alarms service paths - > quality management analytics - >detect localize and resolve silent failure & quantify customer impact of network issues
- reduce energy consumption without impacting customer experience

open problem :
ONAP need more recovery and monitoring
- data integrity
- transactions
- microservices and analytics
- policy learning
- use cases
- underestanding customer experience
- ml applications for enhancing reliability and customer experience
- optimize energy saving whilst maintaining customer experience
- ONAP application


### Research paper

#### Fully Automated HTML and Javascript Rewriting for Constructing a Self-healing Web Proxy. Thomas Durieux (INRIA), Youssef Hamadi (LIX) and Martin Monperrus (KTH).

Repair Strategy

- java script Strategy
  - HTTP/HTTPS
  - HTML Element Creator
  - Library Injector
- General Strategy


#### Robust and Rapid Adaption for Concept Drift in Software System Anomaly Detection. Minghua Ma (Tsinghua University), Shenglin Zhang (Nankai University), Dan Pei (Tsinghua University), Xin Huang and Hongwei Dai (Sogou Inc)

- concept Drift
- step wise
- challenges
  - scalability
  - roboutnes and adaption delay
- detection and semi automated classification

#### Run-time Reliability Estimation of Microservice Architectures. Roberto Pietrantuono, Stefano Russo and Antonio Guerriero (University of Naples Federico II)​

- MSA microsoft system Architectures
-

#### Fast Track Presentation

**Evaluation & Construction of Covering Arrays utilizing prior information**
by Ryan Lekivetz

- covering Arrays
- prior information
- weight coverage

**predicting software defect based on the cognitive error theory**
- human error prediction
- ATM example

** Software Reliability Evaluation Method based on a software network ** by

- module reliability risk:
  - module complexity
    - structural
    - code complexity

 - module change related

 last talk:
 - anti patterns
 - Resilience pattern example : circuit breaker
 - chaos engineering
 - relation between resilence pattern, anti pattern and fault injection

#### Tuesday, October 16th, 4:00PM - 6:00PM (2 hours), R3: Reliability, Security and Safety Analysis

Session Chair: Tadashi Dohi

**Online Model-based Testing Under Uncertainty. Matteo Camilli (University of Milan), Angelo Gargantini and Patrizia Scandurra (University of Bergamo)​**

-



Reliability Evaluation of Functionally Equivalent Simulink PID Controller Implementations. Kai Ding, Andrey Morozov and Klaus Janschek (TU Dresden)​

A Natural Language Programming Approach for Requirements-based Security Testing. Phu X. Mai, Fabrizio Pastore, Arda Goknil and Lionel Briand (University of Luxembourg)

Safe-AR: Reducing Risk While Augmenting Reality (WAP paper). Robyn Lutz (Iowa State University)



#### Wednesday, October 17th, 9:00 - 10:30am

When Software Reliability Engineering Meets Artificial Intelligence

Michael R. Lyu

Professor and Chairman Computer Science & Engineering Department, The Chinese University of Hong Kong

www.cse.cuhk.edu.hk/lyu

Abstract:

“Software is eating the world, but A.I. is going to eat software.” We have already witnessed software engineering shaping every last facet of our 21st century existence. We currently see the coming of A.I. storms from the horizon. In this talk I will try to connect A.I. with Software Reliability Engineering (SRE). On one hand, A. I. techniques, empowered by data-driven machine learning algorithms, can enhance SRE tasks with new paradigms. On the other hand, SRE techniques are essential to modern A.I. applications. Regarding the first aspect, we have investigated on the design of novel A.I. approaches and machine learning techniques to facilitate three major phases in software reliability engineering: development, operation, and analysis. I will explain the challenges in each phase and describe our recently achieved methodologies. Regarding the second aspect, I will examine how the conventional SRE techniques, fault avoidance, fault removal, fault tolerance, and fault prediction, can be applied to A.I. software, and present some of our current findings. I will also discuss the ethical issues on A.I. applications, and address how we can attack these issues with SRE techniques.

##### apply AI to SRE
 - code-based : source code->code metric
 - review-based: user behavior->user review
 - log-based: log->trace
- code based :code completion/suggestion , defect prediction -> RNN with attention, classification
- review data: topic Modeling
- log data: deep learning
- code completion : language modeling , out of vocabulary problem: pointer mixture network, long-range dependencies: mitigated by rnn/LSTM with attention,
- defect prediction :
 - classifier to predict code area that have fault based on code features
 - CNN , DP-CNN
- Review data:
  - apply issue prioritizing
  - clustering for topic modeling,
  - app issue prioritizing framework
    - data extraction: crawling
    - topic modeling
    - semantic and sentiment aspect
    - visualization
    - issue analysis: top rank review in each topic
    - Identifying Emerging App issue
    - online topic Modeling
    - Jensen-shanon Detection
    - AI for Log-Based SRE
  - learning to log : exception snippets, return value check pointer, 23% exception snippets are loged. 10% return-value-check snippets are logged
    - framework of learning to log : like defect prediction
    - contextual :
       - structure features : error type, method, containing methods
       - text features: identifier, comment
       - syntactic features : setting flag,
       - yuan et al. osdl'12
       - framework of logging statement generation: code embedding
       - log management : log parsing ->matrix (block id, log event)->log mining
       - log management application :
          - anomaly detection, deep log embedding based anomaly Detection
          - problem identification: log parsing -> sequence vactorization -> correletion analysis -> cascading clustering
          - cascading clustering : efficient and effective
          - github/logpai tools for techniques discussed

##### apply SRE to AI
 - reinforcement learning: reward based: policy, action-value
 - deep q-learning : learn action value Function
 - deep learning are unreliable
    - reliability and availability challenges
    - vulnerability to data perturbations
       - szegedy '13
       - pei' 17
    - DNN are employed in many safety and safety-critical situation
    - fault avoidance : adversial example , ICLR 2018 Toward deep learning models resistent to adversial attacks
    - machine learning fault removal
     - high code coverage but low behavior coverage
      - N- version deep learning programming
    - AI fault prediction
      - recent work focus on app level
