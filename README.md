[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)  

English | [中文](/README_zh.md)  

## Overview
Qualitis is a data quality management platform that supports quality verification, notification, and management for various datasource. It is used to solve various data quality problems caused by data processing.

Based on Spring Boot, Qualitis submits quality model task to [Linkis](https://github.com/apache/incubator-linkis) platform. It provides functions such as data quality model construction, data quality model execution, data quality verification, reports of data quality generation and so on.

At the same time, Qualitis provides enterprise-level features of financial-level resource isolation, management and access control. It is also guaranteed working well under high-concurrency, high-performance and high-availability scenarios.

## Features
- **Define Data Quality Model**  
Supports data quality model below:  
1.Model of single table.  
2.Model of multi-table.  
3.Custom model.  
<br /> At the same time, Qualitis presets multiple data quality verification templates, including common checks such as null check, blank check, number check, enumeration check and so on, which simplifies data quality model definition.  

- **Data Quality Model Scheduling**  
Supports data quality model scheduling.  

- **Data Quality Report**  
Supports generating data quality reports.  

- **Log Management**
Supports management of data quality task.  

- **Abnormal Data Management**  
Supports abnormal data storage, which can quickly locate problems.    

- **Workflow**  
Supports workflow  
Workflow needs [DataSphereStudio](https://github.com/WeBankFinTech/DataSphereStudio).

- **Administrator Console**  
Administrator console provided.  
And it also supports personnel management, access control management, privilege control management, metadata management and so on.  

## Compared with similar systems
![](images/en_US/ch1/CompareSimilarSystem.png)

## Documents
[Quick Deploy](docs/en_US/ch1/QuickDeploy.md)  
[User Manual](docs/en_US/ch1/User%20Manual.md)  
[Architecture Design](docs/en_US/ch1/Architecture%20Design.md)  
<br/>
**Click [here](docs/en_US/ch1) to view more documents**

## Architecture
![](images/en_US/ch1/Architecture.png)

## Road Map
### 1. Support Verification in Report Data

- Support verification in report data in workflow

### 2. Support Verification in Multi-Storage

- Support data quality verification between Hive, HDFS, and MySQL  
- Support data quality verification between kafka  

### 3. Support generating data quality report

Supports generating data quality reports with optional latitude.

### 4. Support intelligent discovery of data quality problems
<br/>

## Communication
If you desire immediate response, please kindly raise issues to us or scan the below QR code by WeChat and QQ to join our group:   
![](images/en_US/ch1/ContractUs.png)

## License
**Qualitis is under the Apache 2.0 license. See the [LICENSE](/LICENSE) file for details.**

## Tips
The front-end code of Qualitis adopts the front-end framework FES self-developed by WeBank. The FES framework is currently open source, and the source code can be downloaded through the ui folder in the root directory. Of course, it can also be used directly by downloading the release. The default front-end compilation package is installed in Qualitis-x.x.x/conf/static.