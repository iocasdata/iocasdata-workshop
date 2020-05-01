---
layout: default
title: IOCAS Ocean Data Platform 
---

## 海洋大数据平台(IODP)由数据资源层、数据业务核心平台和平台应用层。
![infrastucture](http://msdc.qdio.ac.cn/Web/Tpl/default/img/image2.png)

---

## 目前已完成的功能子系统，包括数据资源汇聚系统、数据业务核心系统、数据门户(Data Portal)、大规模数据在线分析系统以及卫星遥感数据应用、人工智能应用等。 
* 数据资源汇聚系统负责将海洋研究所的科考船调查、近海观测浮标台站、深海潜标观测网、卫星遥感等获取的原始数据进行完整性检查、质量控制、格式标准化等预处理操作之后，形成数据资源池。

* 数据业务核心系统位于数据资源和平台应用之间。针对不同来源数据，按照ISO 19115-2标准建立元数据模型。按照[CF(Climate and Forcast)](http://cfconventions.org/)规范形成元数据描述信息。按照统一的标准格式存储入NetCDF和关系型数据。对外提供包括OpenDAP、RESTFull、Errdap、WMS等数据接口服务。  

* [数据门户(Data Portal)](http://portal.qdio.ac.cn)定时自动化读取业务系统提供的数据接口，及时感知数据资源池的新增数据，然后抽取元数据描述信息，按照不同数据分类发布数据目录。面向用户提供数据申请，经在线审批通过后获取数据实体。
![Portal](http://msdc.qdio.ac.cn/Web/Tpl/default/img/portal.png)

* [在线数据分析系统](https://datalab.iocasdata.com)，通过建设分布式集群，集成数据资源和数据挖掘分析、可视化和地球科学领域科研应用软件工具，提供基于Web浏览器的在线数据分析环境。  

Summary：
  1. 海洋研究所自有数据资源已形成完整性校验、预处理、质量控制、元数据信息关联、格式标准化等流程，以统一的数据格式和关系型数据库存储。提供多种WebService数据接口。
  2. 数据分析系统依托亚马逊AWS集群建设，能够以近毫秒级速度直接读取和分析AWS S3和Google Cloud Storage存储的公开数据集，无需下载到本地。
     目前，亚马逊AWS提供的[开放数据集](https://registry.opendata.aws/)达到143个，涉及卫星遥感、海洋与大气再分析数据集等。Google Cloud storage 已经存储包括NASA/NOAA/USGS/NCAR/ESA/CNES等机构的数据集。
    
## Demo




 
 
 
## Contact Us

Send inquiries to sjzx[at]qdio[dot]ac[dot]cn
