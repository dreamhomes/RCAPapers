# RCAPapers
A collection of papers about Root Cause Analysis/Diagnosis/Detection/Location in MicroService Systems, including invocation chain, multi-dimensional metrics and machine metrics.

## Survey

- [TSE 2018] Fault Analysis and Debugging of Microservice Systems: Industrial Survey, Benchmark System, and Empirical Study. [paper](https://cspengxin.github.io/publications/tse19-msdebugging.pdf)

## Methods

Note: Different methods categoried by data type.

### Metrics, Call chain with TraceID

- [2017 WWW] Performance Monitoring and Root Cause Analysis for Cloud-hosted Web Applications. [paper](https://dl.acm.org/doi/10.1145/3038912.3052649)
- [2018 ICSOC] Microscope: Pinpoint Performance Issues with Causal Graphs in Micro-service Environments. [paper](https://link.springer.com/chapter/10.1007/978-3-030-03596-9_1)
- [2019 FSE] Latent Error Prediction and Fault Localization for Microservice Applications by Learning from System Trace Logs. [paper](https://dl.acm.org/doi/10.1145/3338906.3338961)
- [2019 ASPLOS] Seer: Leveraging Big Data to Navigate the Complexity of Performance Debugging in Cloud Microservices. [paper](https://dl.acm.org/doi/10.1145/3297858.3304004)
- [2020 MLArchSys] Sage: Leveraging ML To Diagnose Unpredictable Performance in Cloud Microservices. [paper](https://www.csl.cornell.edu/~delimitrou/papers/2020.mlarchsys.sage.pdf)

### Metrics, Call chain without TraceID

- [2013 SIGMETRICS] Root Cause Detection in a Service-Oriented Architecture [MonitorRank]. [paper](https://dl.acm.org/doi/10.1145/2465529.2465753) 
- [2015 IWQoS] A methodology for root-cause analysis in component based systems. [paper]( https://ieeexplore.ieee.org/document/7404741)
- [2017 TPDS] Failure Diagnosis for Distributed Systems Using Targeted Fault Injection. [paper](https://ieeexplore.ieee.org/document/7484300)
- [2018 IWQoS] Root Cause Analysis of Anomalies of Multitier Services in Public Clouds. [paper](https://ieeexplore.ieee.org/document/7969155)
- [2018 CCGRID] CloudRanger: Root Cause Identification for Cloud Native Systems. [paper](https://ieeexplore.ieee.org/document/8411065)
- [2018 ASE] Delta debugging microservice systems. [paper](https://dl.acm.org/doi/10.1145/3238147.3240730)
- [2019 TSC] Microservices Monitoring with Event Logs and Black Box Execution Tracing. [paper](https://ieeexplore.ieee.org/document/8826375)
- [2019 Access] A Real-Time Trace-Level Root-Cause Diagnosis System in Alibaba Datacenters. [paper](https://ieeexplore.ieee.org/document/8852648)
- [2020 JSS] Graph-based root cause analysis for service-oriented and microservice architectures. [paper](https://www.sciencedirect.com/science/article/pii/S0164121219302067)

### Only Metrics

- [2016 KDD] Ranking Causal Anomalies via Temporal and Dynamical Analysis on Vanishing Correlations. [paper](https://dl.acm.org/doi/10.1145/2939672.2939765)
- [2017 ICDM] Ranking Causal Anomalies by Modeling Local Propagations on Networked Systems. [paper](https://ieeexplore.ieee.org/document/8215592)
- [2018 CCGRID] CloudRanger: Root Cause Identiﬁcation for Cloud Native Systems. [paper](https://ieeexplore.ieee.org/document/8411065)
- [2018 IPCCC] FacGraph: Frequent Anomaly Correlation Graph Mining for Root Cause Diagnose in Micro-Service Architecture. [paper](https://ieeexplore.ieee.org/document/8711092)
- [2019 ICWS] MS-Rank: Multi-Metric and Self-Adaptive Root Cause Diagnosis for Microservice Applications. [paper](https://ieeexplore.ieee.org/document/8818432)
- [2020 Appl. Sci.] A Causality Mining and Knowledge Graph Based Method of Root Cause Diagnosis for Performance Anomaly in Cloud Applications. [paper](https://www.mdpi.com/2076-3417/10/6/2166)
- [2020 WWW] AutoMAP: Diagnose Your Microservice-based Web Applications Automatically. [paper](https://dl.acm.org/doi/10.1145/3366423.3380111)

### Metrics, Graph

Note：Graph data includes System State Graph, Dependency graph and so on.

- [2013 ICDCS] FChain: Toward Black-box Online Fault Localization for Cloud Systems. [paper](https://ieeexplore.ieee.org/document/6681572)
- [2019 ICPADS] ADGS: Anomaly Detection and Localization based on Graph Similarity in Container-based Clouds. [paper](https://ieeexplore.ieee.org/document/8975844)
- [2019 VLDB] GRANO: Interactive Graph-based Root Cause Analysis for Cloud-Native Distributed Data
  Platform. [paper](https://dl.acm.org/doi/10.14778/3352063.3352105)
- [2019 JSS] Graph-based root cause analysis for service-oriented and microservice architectures。 [peper](https://www.sciencedirect.com/science/article/pii/S0164121219302067)

### Software/Program faults

- [2019 ISSTA] DeepFL: integrating multiple fault diagnosis dimensions for deep fault localization. [paper](https://dl.acm.org/doi/10.1145/3293882.3330574)