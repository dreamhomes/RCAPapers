# RCAPapers
A collection of papers about Root Cause Analysis/Diagnosis/Localization in MicroService Systems, including invocation chain, multi-dimensional metrics and machine metrics.

Reference of paper notes: [https://dreamhomes.top/](https://dreamhomes.top/)

## Survey

- [2018 *TSE*] Fault Analysis and Debugging of Microservice Systems: Industrial Survey, Benchmark System, and Empirical Study. [paper](https://cspengxin.github.io/publications/tse19-msdebugging.pdf)

## Methods

Note: Different methods categoried by data type.

### Metrics, Invocation

- [2013 *SIGMETRICS*] Root Cause Detection in a Service-Oriented Architecture [MonitorRank]. [paper](https://dl.acm.org/doi/10.1145/2465529.2465753)
- [2015 *IWQoS*] A methodology for root-cause analysis in component based systems. [paper]( https://ieeexplore.ieee.org/document/7404741)
- [2017 *TPDS*] Failure Diagnosis for Distributed Systems Using Targeted Fault Injection. [paper](https://ieeexplore.ieee.org/document/7484300)
- [2018 *IWQoS*] Root Cause Analysis of Anomalies of Multitier Services in Public Clouds. [paper](https://ieeexplore.ieee.org/document/7969155)
- [2018 *CCGRID*] CloudRanger: Root Cause Identification for Cloud Native Systems. [paper](https://ieeexplore.ieee.org/document/8411065)
- [2018 *ASE*] Delta debugging microservice systems. [paper](https://dl.acm.org/doi/10.1145/3238147.3240730)
- [2019 *TSC*] Microservices Monitoring with Event Logs and Black Box Execution Tracing. [paper](https://ieeexplore.ieee.org/document/8826375)
- [2019 *Access*] A Real-Time Trace-Level Root-Cause Diagnosis System in Alibaba Datacenters. [paper](https://ieeexplore.ieee.org/document/8852648)
- [2020 *JSS*] Graph-based root cause analysis for service-oriented and microservice architectures. [paper](https://www.sciencedirect.com/science/article/pii/S0164121219302067)
- [2016 *KDD*] Ranking Causal Anomalies via Temporal and Dynamical Analysis on Vanishing Correlations. [paper](https://dl.acm.org/doi/10.1145/2939672.2939765)
- [2017 *ICDM*] Ranking Causal Anomalies by Modeling Local Propagations on Networked Systems. [paper](https://ieeexplore.ieee.org/document/8215592)
- [2018 *CCGRID*] CloudRanger: Root Cause Identiﬁcation for Cloud Native Systems. [paper](https://ieeexplore.ieee.org/document/8411065)
- [2018 *ICST*] Localizing Faults in Cloud Systems. [paper](https://ieeexplore.ieee.org/document/8367054)
- [2018 *IPCCC*] FacGraph: Frequent Anomaly Correlation Graph Mining for Root Cause Diagnose in Micro-Service Architecture. [paper](https://ieeexplore.ieee.org/document/8711092)
- [2019 *ICWS*] MS-Rank: Multi-Metric and Self-Adaptive Root Cause Diagnosis for Microservice Applications. [paper](https://ieeexplore.ieee.org/document/8818432)
- [2020 *Appl. Sci.*] A Causality Mining and Knowledge Graph Based Method of Root Cause Diagnosis for Performance Anomaly in Cloud Applications. [paper](https://www.mdpi.com/2076-3417/10/6/2166)
- [2020 *WWW*] AutoMAP: Diagnose Your Microservice-based Web Applications Automatically. [paper](https://dl.acm.org/doi/10.1145/3366423.3380111)
- [2020 *IWQoS*] Localizing Failure Root Causes in a Microservice through Causality Inference. [paper](https://ieeexplore.ieee.org/document/9213058)
- [2021 *ICSE*] MicroHECL: High-Efficient Root Cause Localization in Large-Scale Microservice Systems. [paper](https://arxiv.org/pdf/2103.01782.pdf)
- [2021 *ISSTA*] Faster, Deeper, Easier: Crowdsourcing Diagnosis of Microservice Kernel Failure from User Space. [paper](https://dl.acm.org/doi/10.1145/3460319.3464805)
- [2021 *SEKE*] AAMR: Automated Anomalous Microservice Ranking in Cloud-Native Environment. [paper](https://ksiresearch.org/seke/seke21paper/paper091.pdf)

### Metrics, Trace

- [2017 *WWW*] Performance Monitoring and Root Cause Analysis for Cloud-hosted Web Applications. [paper](https://dl.acm.org/doi/10.1145/3038912.3052649)
- [2018 *ICSOC*] Microscope: Pinpoint Performance Issues with Causal Graphs in Micro-service Environments. [paper](https://link.springer.com/chapter/10.1007/978-3-030-03596-9_1)
- [2019 *FSE*] Latent Error Prediction and Fault Localization for Microservice Applications by Learning from System Trace Logs. [paper](https://dl.acm.org/doi/10.1145/3338906.3338961)
- [2019 *ASE*] Root Cause Localization for Unreproducible Builds via Causality Analysis over System Call Tracing. [paper](http://taoxie.cs.illinois.edu/publications/ase19-reptrace.pdf)
- [2019 *ASPLOS*] Seer: Leveraging Big Data to Navigate the Complexity of Performance Debugging in Cloud Microservices. [paper](https://dl.acm.org/doi/10.1145/3297858.3304004)
- [2020 *MLArchSys*] Sage: Leveraging ML To Diagnose Unpredictable Performance in Cloud Microservices. [paper](https://www.csl.cornell.edu/~delimitrou/papers/2020.mlarchsys.sage.pdf)
- [2020 *ISSRE*] Unsupervised Detection of Microservice Trace Anomalies through Service-Level Deep Bayesian Networks. [paper](https://netman.aiops.org/wp-content/uploads/2020/09/%E5%88%98%E5%B9%B3issre.pdf)
- [2020 *ESEC/FSE*] Graph-Based Trace Analysis for Microservice Architecture Understanding and Problem Diagnosis. [paper](https://dl.acm.org/doi/10.1145/3368089.3417066)
- [2021 *WWW*] MicroRank: End-to-End Latency Issue Localization with Extended Spectrum Analysis in Microservice Environments. [paper](https://theweb.miteam.eu/asset/Cmj4NWeaKnu9enL53)
- [2021 *ICSE*] TraceLingo: Trace representation and learning for performance issue diagnosis in cloud services. [notes](https://dreamhomes.top/posts/202105181534.html)
- [2021 *IWQoS*] Practical Root Cause Localization for Microservice Systems via Trace Analysis. [paper](https://netman.aiops.org/wp-content/uploads/2021/05/1570705191.pdf)
- [2021 *ASE*] AID: Efﬁcient Prediction of Aggregated Intensity of Dependency in Large-scale Cloud Systems. [paper](https://arxiv.org/abs/2109.04893)
- [2022 *ICSE*] Trace-Log Combined Microservice Anomaly Detection through Graph-based Deep Learning. [paper](https://cspengxin.github.io/publications/icse22-DeepTraLog.pdf)
### Metrics, Dependency graph

Note：Graph data includes System State Graph, Dependency graph and so on.

- [2013 *ICDCS*] FChain: Toward Black-box Online Fault Localization for Cloud Systems. [paper](https://ieeexplore.ieee.org/document/6681572)
- [2019 *ICPADS*] ADGS: Anomaly Detection and Localization based on Graph Similarity in Container-based Clouds. [paper](https://ieeexplore.ieee.org/document/8975844)
- [2019 *VLDB*] GRANO: Interactive Graph-based Root Cause Analysis for Cloud-Native Distributed Data
  Platform. [paper](https://dl.acm.org/doi/10.14778/3352063.3352105)
- [2019 *JSS*] Graph-based root cause analysis for service-oriented and microservice architectures. [peper](https://www.sciencedirect.com/science/article/pii/S0164121219302067)
- [2020 *NOMS*] MicroRCA: Root Cause Localization of Performance Issues in Microservices. [paper](https://hal.inria.fr/hal-02441640)
- [2020 *ICSOC*] Localization of Operational Faults in Cloud Applications by Mining Causal Dependencies in Logs using Golden Signals. [paper](https://www.researchgate.net/publication/344435606_Localization_of_Operational_Faults_in_Cloud_Applications_by_Mining_Causal_Dependencies_in_Logs_using_Golden_Signals)
- [2020 *SoSE*] Graph Based Root Cause Analysis in Cloud Data Center. [paper](https://ieeexplore.ieee.org/document/9130526)
- [2021 *ICSE*] MicroDiag: Fine-grained Performance Diagnosis for Microservice Systems. [paper](https://hal.inria.fr/hal-03155797/document)
- [2021 *ASE*] Groot: An Event-graph-based Approach for Root Cause Analysis in Industrial Settings. [paper](https://arxiv.org/abs/2108.00344)

### Software/Program faults

- [2019 *ISSTA*] DeepFL: integrating multiple fault diagnosis dimensions for deep fault localization. [paper](https://dl.acm.org/doi/10.1145/3293882.3330574)
- [2019 *ASE*] Root Cause Localization for Unreproducible Builds via Causality Analysis over System Call Tracing. [paper](https://ieeexplore.ieee.org/document/8952375)
- [2019 *TSE*] An Empirical Study of Boosting Spectrum-based Fault Localization via PageRank. [paper](https://ieeexplore.ieee.org/document/8698881)
- [2020 *AAAI*] Control Flow Graph Embedding based on Multi-Instance Decomposition for Bug Localization. [paper](https://ojs.aaai.org//index.php/AAAI/article/view/5844)
