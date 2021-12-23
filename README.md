# Public EEG Dataset

本期推文是 Public Neuroscience Dataset 系列主题的第一期内容。开篇编者整理了 EEG 公开数据集，供研究者学习。

许多研究者使用EEG这项技术开展科研工作时，经常会遇到这样一个问题：有很好的idea但苦于缺乏足够的数据支持和验证。尤其是在2019 - 2020年COVID-19期间，许多高校实验室处于封闭状态，不能进入实验室采集脑电数据。在缺乏足够数据支持的情况下，如何开展与EEG有关的课题研究，又一次成为一个焦点。其实网络上有许多机构或组织以及研究者或研究团队会公开自己已开展研究的数据库，供大家开放使用。
本期编者搜集整理了目前互联网中的 EEG公开数据集，主要分为五大模块，各位研究者可根据自己的需要获取数据集。

汇总信息同步托管到GitHub，各位有其他EEG公开数据集，也可以加入协作补充（https://github.com/hubandad/eeg-dataset）。



**[Ⅰ] 事件相关电位数据集（Event Related Potential Dataset）**

1、ERP Core 数据集 

ERP Core是一个开源的人类ERP研究项目，该项目涵盖了ERP研究常用的范式和数据集（共计6个ERP范式，7个ERP成分）。该项目发起人之一是我们熟知的Steve Luck 教授，该项目创立的主要目的是为了更好地推进ERP技术进入社会实践，传播ERP技术，造福人类。
项目官网：https://erpinfo.org/erp-core 
项目介绍：https://www.sciencedirect.com/science/article/pii/S1053811920309502 
数据集获取地址：https://osf.io/thsqg/ 

2、OpenNeuro 数据库

OpenNeuro 是一个由Poldrack及其团队创建的免费且开源的神经影像学数据库共享平台，提供了大量可用于共享的MRI，MEG，EEG，iEEG，ECoG，ASL和PET数据集，截至目前（2021年5月），OpenNeuro上已经有540个公开可供使用的数据集，共计18108名科研工作者加入到此平台的数据库贡献工作中。只需打开OpenNeuro，根据需要通过检索关键词（如：EEG），即可搜索相关类型的数据集，整个过程无需注册。今天我向大家分享的是OpenNeuro中的一个使用go / nogo 探测和分类任务的ERP数据集，在该数据集中，作者采集了男女受试者各7名的ERP数据，同时也提供了数据分析脚本和参考文献。
OpenNeuro项目官网：https://openneuro.org/
OpenNeuro检索地址：https://openneuro.org/public/datasets 
go / nogo数据集获取地址：https://openneuro.org/datasets/ds002680/versions/1.0.0 


**[Ⅱ] 功能性脑疾病数据集（Functional Brain Disease Dataset）**

1、癫痫数据集

目前网络上可以搜集到的免费且公开的癫痫数据集不多，因为许多数据库都加入了收费的欧洲癫痫数据库（European Epilepsy Database）项目，需要单独购买。
笔者尽可能仔细查找并整理了以下小样本的癫痫数据集，供大家学习使用。

1.1新德里Hauz Khas的神经和睡眠中心收集的10名癫痫患者的EEG样例数据。数据是根据10-20分布，采样频率为200 Hz的MAT文件。在采集期间，数据带通滤波范围：0.5到70 Hz，并细分为癫痫发作前，发作间和发作阶段。可通过压缩包中的txt文本获取详细信息。
数据集获取地址：https://www.researchgate.net/publication/308719109_EEG_Epilepsy_Datasets 

1.2 CHB-MIT Scalp EEG Database
CHB-MIT Scalp EEG Database
该数据库收集自波士顿儿童医院，其中包括患有难治性癫痫发作的儿科患者的脑电图记录。详细信息可参考数据库网页信息。
数据库获取地址：https://physionet.org/content/chbmit/1.0.0/ 

1.3 Kaggle competition on seizure prediction 数据集
该数据集为Kaggle 癫痫预测项目竞赛中的数据，数据采集的狗和人的ECoG数据，详细信息可参考项目网站介绍。
项目介绍：https://www.kaggle.com/c/seizure-detection/overview
数据库获取地址：https://www.kaggle.com/c/seizure-detection/data 

1.4 CHB-MIT Scalp EEG Database
该数据库包含23名儿童癫痫患者的脑电数据。
数据库介绍文献：https://dspace.mit.edu/handle/1721.1/54669 
项目及数据库地址：https://archive.physionet.org/pn6/chbmit/ 

2、帕金森EEG数据集

在该模块，笔者向各位介绍几个已发表文献的帕金森EEG数据集，方便各位参照文献学习。

2.1 该数据集为41名帕金森患者静息态EEG数据集，在该数据集下开展的研究中，研究者试图通过EEG 算法区分帕金森病人和正常人。相关研究成果于2020年10月发表在Parkinsonism & Related Disorders 杂志。
发表成果：https://www.sciencedirect.com/science/article/pii/S1353802020306672?via%3Dihub  
数据集获取地址：https://bit.ly/3pP1pts （OneDrive链接） 

2.2 该数据集为26名帕金森患者任务态EEG数据集，在该数据集下开展的研究中，研究者探究了帕金森患者在下肢运动过程中（Lower Limb Pedaling Task）额叶theta和beta振荡是否存在异常。
发表成果：https://www.sciencedirect.com/science/article/abs/pii/S1388245720300092 
数据集获取地址：https://bit.ly/32dsmMS （OneDrive链接）

2.3 该数据集为28名帕金森患者任务态EEG数据（Reinforcement Learning Task），在该数据集下开展的研究中，研究者旨在研究帕金森氏病临床诊断的EEG标记物。相关研究成果于2020年1月发表在 brain research 杂志。
发表成果：https://www.sciencedirect.com/science/article/abs/pii/S0006899319305955?via%3Dihub
数据集获取地址：https://bit.ly/2AIPl9b （OneDrive链接）

2.4 该数据集为28名帕金森患者的任务态EEG数据（Cost Conflict Simon Task），在该数据集下开展的研究中，研究者发现帕金森氏病患者在执行与认知控制有关任务过程中，额中叶theta活动减弱。相关研究成果于2018年发表在 Neuropsychologia 杂志。
发表成果：https://www.sciencedirect.com/science/article/abs/pii/S0028393218302185?via%3Dihub 
数据集获取地址：http://bit.ly/2FauZTt 

2.5 该数据集为27名帕金森患者的静息态EEG数据，在该数据集下开展的研究中，研究者开发了一种分类算法用来分类健康人和帕金森氏病人，特异性高达82%。相关研究成果于2018年发表在 Clinical Neurophysiology杂志。
发表成果：https://www.sciencedirect.com/science/article/abs/pii/S1388245717311719 
数据集获取地址：http://bit.ly/2rfCkNP 

3、强迫症EEG 数据集

该数据集为23名强迫症患者的任务态EEG数据（Flanker Task），在该数据集下开展的研究中，研究者探究了侧抑制任务下OCD患者的错误关联负波与健康对照的差异。相关研究成果于2009年发表在 Neuropsychologia杂志。
发表成果：https://www.sciencedirect.com/science/article/abs/pii/S0028393209001298?via%3Dihub 
数据集获取地址： https://bit.ly/2MG4ZHz 

4、抑郁症 EEG 数据集

4.1 任务态抑郁症EEG数据集
该数据集为46名抑郁症患者的任务态EEG数据（Reinforcement Learning Task），在该数据集下开展的研究中，研究者探究了侧抑制任务下OCD患者的错误关联负波与健康对照的差异。相关研究成果于2019年发表。
发表成果： https://direct.mit.edu/cpsy/article/doi/10.1162/cpsy_a_00024/5365/Multiple-Dissociations-Between-Comorbid-Depression
数据集获取地址： https://bit.ly/2F11Zwv 

4.2 MODMA 数据集
MODMA dataset 是一个专业开放的脑疾病多模态数据库，网站目前提供EEG和音频数据库。经笔者确认，该数据库目前提供MDD脑电数据。但数据集不能直接下载获取，需要使用机构邮箱注册账号并获得批准后方可下载使用。
数据库介绍：http://modma.lzu.edu.cn/data/index/ 
数据库介绍文献：https://arxiv.org/pdf/2002.09283.pdf 
数据集获取地址：http://modma.lzu.edu.cn/data/application/#data_1 
注意：请务必认真阅读网站顶部账号注册要求，否则会注册失败哦。

5、精神分裂症 EEG 数据集

5.1 该数据集为46名精神分裂症患者的任务态EEG数据（Cost Conflict Simon Task），在该数据集下开展的研究中，研究者探究了精神分裂症患者在空间响应上存在反应冲突效应增强的现象。相关研究成果于2019年发表在 Neuropsychologia 杂志。
发表成果：https://www.sciencedirect.com/science/article/pii/S0028393218301726 
数据集获取地址：https://bit.ly/2J7BeJc 

5.2 该数据集为健康青少年和被诊断为精神分裂症青少年的EEG数据。
数据详细介绍及获取方式：http://brain.bio.msu.ru/eeg_schizophrenia.htm 

5.3 该数据集为精神分裂症患者执行基本感觉任务的EEG 数据。
数据详细介绍及获取方式： https://www.kaggle.com/broach/button-tone-sz


**[Ⅲ] 脑机接口脑电数据集（Brain Computer Interface EEG Dataset）**


1、BCI竞赛数据库

BCI竞赛旨在为广大BCI研究者提供高质量的神经科学数据而创立。目前网络上公开的数据集有三个，分别为第二、三和四届BCI数据集，具体获取方式如下：
第二届BCI大赛数据集：https://www.bbci.de/competition/ii/ 
第三届BCI大赛数据集：https://www.bbci.de/competition/iii/ 
第四届BCI大赛数据集：https://www.bbci.de/competition/iv/ 

2、2020年国际BCI竞赛数据库

受COVID-19疫情影响，2020年国际BCI竞赛颁奖活动未能如期举行。大赛组委会决定将测试的数据不开放标签向大众共享，用户可以免费使用大赛测试数据。
2020年BCI大赛介绍wiki：https://osf.io/pq7vb/wiki/home/ 
2020年BCI大赛数据集获取：https://osf.io/pq7vb/  

3、BNCI HORIZON 2020 数据库

BNCI Horizon 2020是一项由欧盟委员会框架计划7资助的项目。该项目旨在大众提供公开的BCI数据集，以助力BCI研究和发展。目前该项目已经汇总了28个与BCI相关的数据集。用户在遵循授权许可的情况下，可以免费下载使用。
项目官网：http://bnci-horizon-2020.eu/ 
项目介绍：http://bnci-horizon-2020.eu/project 
数据库获取地址：http://bnci-horizon-2020.eu/database/data-sets 

4、MEDICON 2019 Scientific Challenge 数据集

MEDICON 2019 Scientific Challenge 是一项BCI项目挑战赛，参与者可以从15个临床EEG数据集中测试基于BCI的p300成分，训练患有ASD青少年遵循社交线索的实验。每位受试者在4个月的时间内接受了7次训练。
项目介绍及数据集获取地址：https://www.medicon2019.org/scientific-challenge/ 

5、其他:

5.1 Havard dataverse BCI运动想象数据集，由天津大学某研究者贡献。
 https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/27306 

5.2 EEG Motor Movement/Imagery Dataset
https://www.physionet.org/content/eegmmidb/1.0.0/ 

5.3 ERP-based Brain-Computer Interface recordings 
https://www.physionet.org/content/erpbci/1.0.0/ 


**[Ⅳ] 睡眠脑电数据集（Sleep EEG Dataset）**

1、NCH Sleep DataBank

为了加快对小儿睡眠及其与健康的联系的研究，全国儿童医院（NCH）和卡内基梅隆大学（CMU）推出了NCH睡眠数据库。该数据集于2017年至2019年期间在美国俄亥俄州哥伦布的NCH对3673名独特患者进行了3984例儿科睡眠研究，以及患者的纵向临床数据。出版的多导睡眠监测仪（PSG）包含患者的生理信号以及技术人员对睡眠阶段的评估以及其他异常情况的描述。
数据集获取地址：https://www.physionet.org/content/nch-sleep/0.1.0/ 

2、Sleep-EDF Database Expanded

该数据集包含197例睡眠脑电图的数据，数据为EDF格式。
数据库获取地址：https://www.physionet.org/content/sleep-edfx/1.0.0/
EDFbrowser：https://www.teuniz.net/edfbrowser/ 

3、ISRUC-SLEEP Dataset

该数据集包含100例病人的PSG数据。
项目介绍：https://sleeptight.isr.uc.pt/ 
数据库获取地址：https://sleeptight.isr.uc.pt/?page_id=48 
数据库介绍：http://dataset.isr.uc.pt/ISRUC_Sleep/Content.pdf 
数据库文献介绍：https://www.researchgate.net/publication/283734463_ISRUC-Sleep_A_comprehensive_public_dataset_for_sleep_researchers 

4、Dreem Sleep Stage Classification Challenge Dataset

使用简单的头带式EEG设备采集的30s 简短的EEG数据，对睡眠阶段进行区分。
项目介绍：https://www.kaggle.com/c/dreem-sleep-stages/overview 
数据库获取地址：https://www.kaggle.com/c/dreem-sleep-stages/data 

5、Newborn sleep EEG data

该数据集包含MATLAB中的1,110个睡眠EEG，这些睡眠EEG在临床状况下记录了来自36至45周的10个年龄组的新生儿的临床状况。
项目介绍文献：https://www.ncbi.nlm.nih.gov/pubmed/15055799 / https://www.ncbi.nlm.nih.gov/pubmed/10406020 
数据库获取地址：https://figshare.com/articles/dataset/Newborn_sleep_EEG_data/4729840 



**[Ⅴ] 创伤性脑疾病数据集（Traumatic Brain Disease Dataset）**

1、轻度创伤性脑损伤

1.1  使用 Dot Probe Expectancy Task 测试脑损伤病人的认知功能。
发表成果：https://link.springer.com/article/10.1007/s11682-019-00171-y 
数据集获取地址：https://bit.ly/2GNej6D 

1.2 使用3阶 Auditory Oddball Task 探测脑损伤病人的脑功能变化情况。
发表成果：https://www.sciencedirect.com/science/article/abs/pii/S0028393219301630?via%3Dihub
数据集获取地址：https://bit.ly/2QkPB4d 



**[Ⅵ] 其他EEG 数据库**

1、Healthy Brain Network Dataset 

HBND是一个公益性的提供儿童青少年精神病学研究数据库的组织，该组织提供超过1万多名儿童和青少年大脑影像数据，包括EEG，MRI等数据。
该项目目前共计发行了9个EEG数据库版本，约合3000例数据。
项目介绍文献：https://www.nature.com/articles/sdata2017181 
数据库获取地址：
http://fcon_1000.projects.nitrc.org/indi/cmi_healthy_brain_network/sharing_neuro.html 

2、Temple University EEG Corpus

天普大学EEG 数据库，包含12000名病人，16通道，EDF格式的EEG数据。
项目地址：https://www.isip.piconepress.com/projects/tuh_eeg/ 
注意：该数据库需要注册账号才可访问。

3、DEAP dataset

一个包含视频数据和EEG数据的情绪数据库，采用注册邀请制访问，需获取授权后方可访问资源。
项目地址：http://www.eecs.qmul.ac.uk/mmv/datasets/deap/
申请授权时，务必仔细阅读授权说明，按照要求和格式填写授权信息表格。
不过根据编者的个人经验，该数据库获取授权方式较困难（编者提交申请1.5个月后未得到任何答复。）

4、其他未整理的公开数据集地址汇总

https://github.com/hubandad/eegdataset/ 欢迎大家协作更新。


latested update 23th Dec,2021


