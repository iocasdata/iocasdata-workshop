---
layout: default
title: IOCAS Ocean Data Analysis Platform 
---

## 平台包括数据资源汇聚系统、数据业务核心系统、数据门户、云端在线数据分析系统。 
![infrastucture](https://github.com/iocasdata/iocasdata-workshop/raw/master/images/image2.png)
---
* 数据资源汇聚系统负责将海洋研究所的科考船调查、近海观测浮标台站、深海潜标观测网、卫星遥感等获取的原始数据进行完整性检查、质量控制、格式标准化等预处理操作之后，形成数据资源池。

* 数据业务核心系统位于数据资源和平台应用之间。针对不同来源数据，按照ISO 19115-2标准建立元数据模型。按照[CF(Climate and Forcast)](http://cfconventions.org/)规范形成元数据描述信息。按照统一的标准格式存储入NetCDF和关系型数据。对外提供包括OpenDAP、RESTFull、Errdap、WMS等数据接口服务。  

* [数据门户(Data Portal)](http://portal.qdio.ac.cn)定时自动化读取业务系统提供的数据接口，抽取元数据描述信息，按照不同数据分类发布数据目录。面向用户提供数据申请，经在线审批通过后获取数据实体。数据资源池如有新增数据，数据门户能够及时感知并抓取元数据信息，发布数据集。  

* [在线数据分析系统](https://datalab.iocasdata.com)，通过建设分布式集群，集成数据资源和数据挖掘分析、可视化和地球科学领域科研应用软件工具，提供基于Web浏览器的在线数据分析环境。  

Summery：
  1. 海洋研究所自有数据资源已形成完整性校验、预处理、质量控制、元数据信息关联、格式标准化等流程，以统一的数据格式和关系型数据库存储。提供多种WebService数据接口。
  2. 数据分析系统依托亚马逊AWS集群建设，能够以近毫秒级速度直接读取和分析AWS S3和Google Cloud Storage存储的公开数据集，无需下载到本地。
     目前，亚马逊AWS提供的[开放数据集](https://registry.opendata.aws/)达到143个，涉及卫星遥感、海洋与大气再分析数据集等。Google Cloud storage 已经存储包括NASA/NOAA/USGS/NCAR/ESA/CNES等机构的数据集。
    





Our workshop brings together earth scientists and machine learning experts to try to solve some of the earth's greatest problems.  We've divided our workshop into several themed sections: [Atmospheric Science](#atmospheric-science), [Hydro and Cryospheres](#hydro-and-cryospheres), [Solid Earth](#solid-earth), [Theoretical Advances](#theoretical-advances), [Remote Sensing](#remote-sensing), [EnviroNet](#environet), [Keynotes](#keynotes). 

## Schedule

Tune into our [livestream](https://slideslive.com/38926826/ai-for-earth-sciences) on April 26 from 7am-4pm PDT (San Francisco) time to see the talks. Join us in [slack](https://join.slack.com/t/ai4earth/shared_invite/zt-e30wpddc-lVNgNthtO_HYQOmR0Id~yQ) to mingle with workshop attendees. 

The duration shown in the schedule is approximate time allocated for introduction, video recording, and Q&A for each topic.

*Zoom attendees must completely close the ICLR stream before speaking in the zoom conference (seriously - you will regret it if you don't)*

All times are listed in Pacific Daylight Time (San Francisco, USA).

| Start | End | Type | Speaker | Title | 
| ---- | ---- | --------- | ---------------- | -------- |
| ~~7:00~~ | ~~7:03~~ | Welcome   | Organising Team |[AI for Earth Sciences](https://ai4earthscience.github.io/iclr-2020-workshop/organizers.html) |


### Atmospheric Science    

| Start | End | Type | Speaker & Video| Title | 
| ---- | ---- | --------- | ---------------- | -------- | 
| ~~7:03~~ | ~~7:20~~ | Invited   | [Amy McGovern](https://slideslive.com/38926362/) | [Using Machine Learning And Model Interpretation And Visualization Techniques To Gain Physical Insights In Atmospheric Science](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth16.pdf) |   
| ~~7:20~~ | ~~7:40~~ | Spotlight | [Haolin Fei](https://slideslive.com/38926356/) | [Accurate Air Quality Prediction: A Physical-temporal Collection Model](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth09.pdf) |   
| ~~7:40~~ | ~~7:50~~ | Lightning | [Jing Li](https://slideslive.com/38926372/) | [A Random Forest Model For The Probability Of Large Wildfires In California](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth20.pdf) |   
| ~~7:50~~ | ~~8:00~~ | Lightning | [Ashray Manepalli](https://slideslive.com/38926373/) | [Generalization Properties Of Machine Learning Based Weather Model Downscaling](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth25.pdf) |   
| ~~8:00~~ | ~~8:10~~ | Lightning | [Adway Mitra](https://slideslive.com/38926367/) | [A Probabilistic Graphical Model Approach To Identifying Spatial Changes In Monthly Precipitation Under Climate Change](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth11.pdf)  |    

### Hydro and Cryospheres   

| Start | End | Type | Speaker & Video Link | Title and Paper Link |    
| ---- | ---- | --------- | ---------------- | -------- |        
| ~~8:10~~ | ~~8:25~~ | Invited | [Kelly Kochanski](https://slideslive.com/38926355/) | [Surrogate Sea Ice Model Enables Efficient Tuning](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth26.pdf) |
| ~~8:25~~ | ~~8:48~~ | [Invited](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth04slides.pdf) | [Zach Moshe](https://slideslive.com/38926352/) | [Hydronets: Leveraging River Structure for Hydrologic Modeling](https://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth04.pdf) |   
| ~~8:48~~ | ~~9:00~~ | Lightning | [Brian Cerrón](https://slideslive.com/38926369/) | [Detection Of Housing And Agriculture Areas On Dry-riverbeds For The Evaluation Of Risk By Landslides Using Low-resolution Satellite Imagery Based On Deep Learning. Study Zone: Lima, Peru](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth13.pdf) |    
| ~~XX~~ | ~~XX~~ | Abstract  | Mearg Belay B. Shibeshi |  [Geo-spatial Approach For Assessing The Impact Of Land-use And Land-cover Change On Groundwater Recharge: A Case Study In Akaki Catchment, Central Ethiopia](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth05.pdf) |    
| ~~9:00~~ | ~~9:10~~ | Morning Break | | |

### Solid Earth   

| Start | End | Type | Speaker & Video Link| Title & Paper Link |    
| ---- | ---- | --------- | ---------------- | -------- |     
| ~~9:10~~ | ~~9:30~~ | Spotlight | [Seyed M Mousavi](https://slideslive.com/38926364/) | [Hierarchical Attentive Modeling Of Earthquake Signals](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth06.pdf) |    
| ~~9:30~~ | ~~9:48~~ | Regular | [Bas Peters](https://slideslive.com/38926360/) | [Fully Reversible Neural Networks For Large-scale Surface And Sub-surface Characterization Via Remote Sensing](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth24.pdf) |    
| ~~9:48~~ | ~~10:00~~  | Lightning | [Tue Boesen](https://slideslive.com/38926368/) | [Semi-supervised Clustering For Oil Prospectivity](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth12.pdf) |   
| ~~XX~~ | ~~XX~~ | Abstract | Hadeer A El Ashhab | [Modeling Hydrocarbons Flow From Earth Using Deep Learning](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth17.pdf) |   



### Theoretical Advances  

| Start | End | Type | Speaker & Video Link | Title & Paper Link |    
| ---- | ---- | --------- | ---------------- | -------- |     
| ~~10:00~~ | ~~10:30~~ | Spotlight | [Arvind T Mohan](https://slideslive.com/38926358/) | [Embedding Hard Physical Constraints In Convolutional Neural Networks For 3d Turbulence](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth14.pdf) |   
| ~~10:30~~ | ~~10:55~~ | Spotlight | [Arvind T Mohan](https://slideslive.com/38926370/) | [Wavelet-powered Neural Networks For Turbulence](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth15.pdf) |   
| ~~10:55~~ | ~~11:15~~ | [Regular](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth23slides.pdf) | [Srija Chakraborty](https://slideslive.com/38926359/) | [Time-varying Semantic Representations Of Planetary Observations For Discovering Novelties](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth23.pdf) |   
| ~~XX~~  | ~~XX~~ | Abstract | Taesung Kim | [Gaganet: End-to-end Multivariate Time Series Imputation And Prediction With Gated Generated Adversarial Networks](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth03.pdf) |  
| ~~11:15~~ | ~~11:30~~ | Noon Break | | | 


### Remote Sensing  

| Start | End | Type | Speaker & Video Link | Title & Paper Link |   
| --- | --- | --- | --- | --- |     
| ~~11:30~~ | ~~12pm~~ | Invited | [Ethan Weber & Hassan Kane](https://slideslive.com/38926353/) | [Building Disaster Damage Assessment in Satellite Imagery with Multi-Temporal Fusion](https://arxiv.org/abs/2004.05525) |    
| ~~12pm~~ | ~~12:30~~ | [Spotlight](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth10slides.pdf) | [Maxim Neumann](https://slideslive.com/38926357) | [In-domain Representation Learning For Remote Sensing](http://ai4earthscience.github.io/iclr-2020-workshop/papers/ai4earth10.pdf) |   




### Keynotes & Discussion

| Start | End | Type | Speaker & Video Link | Title & Website |    
| ---- | ---- | --------- | ---------------- | -------- |     
| ~~14:30~~ | ~~15:00~~ | Keynote | [Prof. Daniel M. Kammen, UC Berkeley](https://slideslive.com/38926760/) | [Data Science for the Clean Energy Revolution](https://en.wikipedia.org/wiki/Daniel_Kammen) | 
| ~~15:00~~ | ~~15:30~~ | Discussion | Keynote & AI for Earth Sciences Team | AI Synergies in Energy, Resources & Earth System |
| ~~15:30~~ | ~~16:00~~ | Closing Keynote | Paul Miller aka DJ Spooky | [Art, AI & Earth Sciences](https://en.wikipedia.org/wiki/DJ_Spooky) |     
 
 
## Contact Us

Send inquiries to ai4earthscience[at]gmail[dot]com
