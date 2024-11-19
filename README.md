# Awesome-Remote-Sensing-Cross-Modal-Retrieval

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/BaolanChen/Awesome-Remote-Sensing-Cross-Modal-Retrieval)
<img alt="GitHub watchers" src="https://img.shields.io/github/watchers/BaolanChen/Awesome-Remote-Sensing-Cross-Modal-Retrieval?style=social"> <img alt="GitHub stars" src="https://img.shields.io/github/stars/BaolanChen/Awesome-Remote-Sensing-Cross-Modal-Retrieval?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/BaolanChen/Awesome-Remote-Sensing-Cross-Modal-Retrieval?style=social">

A collection of papers, datasets, benchmarks, code, and model weights for Remote Sensing Cross-Modal Image-Text Retrieval (RSCMIT).


:star2:**A collection of papers, datasets, benchmarks, code, and pre-trained weights for Remote Sensing Foundation Models (RSFMs).**

## 📢 Latest Updates
:fire::fire::fire: Last Updated on 2024.11.13 :fire::fire::fire:

- **2024.11.13**: Update DDFAV and PIEViT.
- **2024.11.06**: Update MMM-RS.
- **2024.10.31**: Update CrossEarth and OReole-FM.
- **2024.10.30**: Update two survey papers, Change-Agent.

## Table of Contents
- **Models**
  - [Remote Sensing Vision Foundation Models](#remote-sensing-vision-foundation-models)
  - [Remote Sensing Vision-Language Foundation Models](#remote-sensing-vision-language-foundation-models)
  - [Remote Sensing Generative Foundation Models](#remote-sensing-generative-foundation-models)
  - [Remote Sensing Vision-Location Foundation Models](#remote-sensing-vision-location-foundation-models)
  - [Remote Sensing Vision-Audio Foundation Models](#remote-sensing-vision-audio-foundation-models)
  - [Remote Sensing Task-specific Foundation Models](#remote-sensing-task-specific-foundation-models)
  - [Remote Sensing Agents](#remote-sensing-agents)
- **Datasets & Benchmarks**
  - [Benchmarks for RSFMs](#benchmarks-for-rSFMs)
  - [(Large-scale) Pre-training Datasets](#large-scale-Pre-training-Datasets)
- **Others**
  - [Relevant Projects](#relevant-projects)
  - [Survey Papers](#survey-papers)
  
## Remote Sensing <ins>Vision</ins> Foundation Models

|Abbreviation|Title|Publication|Paper|Code & Weights|
|:---:|---|:---:|:---:|:---:|
|**GeoKR**|**Geographical Knowledge-Driven Representation Learning for Remote Sensing Images**|TGRS2021|[GeoKR](https://ieeexplore.ieee.org/abstract/document/9559903)|[link](https://github.com/flyakon/Geographical-Knowledge-driven-Representaion-Learning)|
|**-**|**Self-Supervised Learning of Remote Sensing Scene Representations Using Contrastive Multiview Coding**|CVPRW2021|[Paper](https://openaccess.thecvf.com/content/CVPR2021W/EarthVision/html/Stojnic_Self-Supervised_Learning_of_Remote_Sensing_Scene_Representations_Using_Contrastive_Multiview_CVPRW_2021_paper.html)|[link](https://github.com/vladan-stojnic/CMC-RSSR)|
|**GASSL**|**Geography-Aware Self-Supervised Learning**|ICCV2021|[GASSL](https://openaccess.thecvf.com/content/ICCV2021/html/Ayush_Geography-Aware_Self-Supervised_Learning_ICCV_2021_paper.html)|[link](https://github.com/sustainlab-group/geography-aware-ssl)|

## Remote Sensing <ins>Vision-Language</ins> Foundation Models

|Abbreviation|Title|Publication|Paper|Code & Weights|
|:---:|---|:---:|:---:|:---:|
|**RSGPT**|**RSGPT: A Remote Sensing Vision Language Model and Benchmark**|Arxiv2023|[RSGPT](https://arxiv.org/abs/2307.15266)|[link](https://github.com/Lavender105/RSGPT)|
|**RemoteCLIP**|**RemoteCLIP: A Vision Language Foundation Model for Remote Sensing**|Arxiv2023|[RemoteCLIP](https://arxiv.org/abs/2306.11029)|[link](https://github.com/ChenDelong1999/RemoteCLIP)|
|**GeoRSCLIP**|**RS5M: A Large Scale Vision-Language Dataset for Remote Sensing Vision-Language Foundation Model**|Arxiv2023|[GeoRSCLIP](https://arxiv.org/abs/2306.11300)|[link](https://github.com/om-ai-lab/RS5M?tab=readme-ov-file)|
|**GRAFT**|**Remote Sensing Vision-Language Foundation Models without Annotations via Ground Remote Alignment**|ICLR2024|[GRAFT](https://openreview.net/pdf?id=w9tc699w3Z)|null|
|**-**|**Charting New Territories: Exploring the Geographic and Geospatial Capabilities of Multimodal LLMs**|Arxiv2023|[Paper](https://arxiv.org/abs/2311.14656)|[link](https://github.com/jonathan-roberts1/charting-new-territories)|
|**-**|**Remote Sensing ChatGPT: Solving Remote Sensing Tasks with ChatGPT and Visual Models**|Arxiv2024|[Paper](https://arxiv.org/abs/2401.09083)|[link](https://github.com/HaonanGuo/Remote-Sensing-ChatGPT)|
|**SkyEyeGPT**|**SkyEyeGPT: Unifying Remote Sensing Vision-Language Tasks via Instruction Tuning with Large Language Model**|Arxiv2024|[Paper](https://arxiv.org/abs/2401.09712)|[link](https://github.com/ZhanYang-nwpu/SkyEyeGPT)|
|**EarthGPT**|**EarthGPT: A Universal Multi-modal Large Language Model for Multi-sensor Image Comprehension in Remote Sensing Domain**|Arxiv2024|[Paper](https://arxiv.org/abs/2401.16822)|null|
|**SkyCLIP**|**SkyScript: A Large and Semantically Diverse Vision-Language Dataset for Remote Sensing**|AAAI2024|[SkyCLIP](https://arxiv.org/abs/2312.12856)|[link](https://github.com/wangzhecheng/SkyScript)|
|**GeoChat**|**GeoChat: Grounded Large Vision-Language Model for Remote Sensing**|CVPR2024|[GeoChat](https://arxiv.org/abs/2311.15826)|[link](https://github.com/mbzuai-oryx/GeoChat)|
|**LHRS-Bot**|**LHRS-Bot: Empowering Remote Sensing with VGI-Enhanced Large Multimodal Language Model**|Arxiv2024|[Paper](https://arxiv.org/abs/2402.02544)|[link](https://github.com/NJU-LHRS/LHRS-Bot)|
|**H2RSVLM**|**H2RSVLM: Towards Helpful and Honest Remote Sensing Large Vision Language Model**|Arxiv2024|[Paper](https://arxiv.org/abs/2403.20213)|[link](https://github.com/opendatalab/H2RSVLM)|
|**RS-LLaVA**|**RS-LLaVA: Large Vision Language Model for Joint Captioning and Question Answering in Remote Sensing Imagery**|RS2024|[Paper](https://www.mdpi.com/2072-4292/16/9/1477)|[link](https://github.com/BigData-KSU/RS-LLaVA?tab=readme-ov-file)|
|**SkySenseGPT**|**SkySenseGPT: A Fine-Grained Instruction Tuning Dataset and Model for Remote Sensing Vision-Language Understanding**|Arxiv2024|[Paper](https://arxiv.org/abs/2406.10100)|[link](https://github.com/Luo-Z13/SkySenseGPT)|
|**EarthMarker**|**EarthMarker: Visual Prompt Learning for Region-level and Point-level Remote Sensing Imagery Comprehension**|Arxiv2024|[Paper](https://arxiv.org/abs/2407.13596)|[link](https://github.com/wivizhang/EarthMarker)|
|**GeoText**|**Towards Natural Language-Guided Drones: GeoText-1652 Benchmark with Spatial Relation Matching**|ECCV2024|[Paper](https://arxiv.org/abs/2311.12751)|[link](https://multimodalgeo.github.io/GeoText/)|
|**TEOChat**|**TEOChat: Large Language and Vision Assistant for Temporal Earth Observation Data**|Arxiv2024|[Paper](https://arxiv.org/abs/2410.06234)|[link](https://github.com/ermongroup/TEOChat)|

## Remote Sensing <ins>Vision-Location</ins> Foundation Models

|Abbreviation|Title|Publication|Paper|Code & Weights|
|:---:|---|:---:|:---:|:---:|
|**CSP**|**CSP: Self-Supervised Contrastive Spatial Pre-Training for Geospatial-Visual Representations**|ICML2023|[CSP](https://arxiv.org/abs/2305.01118)|[link](https://gengchenmai.github.io/csp-website/)|
|**GeoCLIP**|**GeoCLIP: Clip-Inspired Alignment between Locations and Images for Effective Worldwide Geo-localization**|NeurIPS2023|[GeoCLIP](https://arxiv.org/abs/2309.16020)|[link](https://vicentevivan.github.io/GeoCLIP/)|
|**SatCLIP**|**SatCLIP: Global, General-Purpose Location Embeddings with Satellite Imagery**|Arxiv2023|[SatCLIP](https://arxiv.org/abs/2311.17179)|[link](https://github.com/microsoft/satclip)|

## Remote Sensing <ins>Vision-Audio</ins> Foundation Models

|Abbreviation|Title|Publication|Paper|Code & Weights|
|:---:|---|:---:|:---:|:---:|
|**-**|**Self-supervised audiovisual representation learning for remote sensing data**|JAG2022|[Paper](https://www.sciencedirect.com/science/article/pii/S1569843222003181)|[link](https://github.com/khdlr/SoundingEarth)|


## Remote Sensing <ins>Task-specific</ins> Foundation Models

|Abbreviation|Title|Publication|Paper|Code & Weights|Task|
|:---:|---|:---:|:---:|:---:|:---:|
|**SS-MAE**|**SS-MAE: Spatial-Spectral Masked Auto-Encoder for Mulit-Source Remote Sensing Image Classification**|TGRS2023|[Paper](https://ieeexplore.ieee.org/document/10314566/)|[link](https://github.com/summitgao/SS-MAE?tab=readme-ov-file)|Image Classification|
|**-**|**A Decoupling Paradigm With Prompt Learning for Remote Sensing Image Change Captioning**|TGRS2023|[Paper](https://ieeexplore.ieee.org/document/10271701)|[link](https://github.com/Chen-Yang-Liu/PromptCC)|Remote Sensing Image Change Captioning|
|**TTP**|**Time Travelling Pixels: Bitemporal Features Integration with Foundation Model for Remote Sensing Image Change Detection**|Arxiv2023|[Paper](https://arxiv.org/abs/2312.16202)|[link](https://github.com/KyanChen/TTP)|Change Detection|

## Remote Sensing Agents
|Abbreviation|Title|Publication|Paper|Code & Weights|
|:---:|---|:---:|:---:|:---:|
|**GeoLLM-QA**|**Evaluating Tool-Augmented Agents in Remote Sensing Platforms**|ICLR 2024 ML4RS Workshop|[Paper](https://arxiv.org/abs/2405.00709)|null|
|**RS-Agent**|**RS-Agent: Automating Remote Sensing Tasks through Intelligent Agents**|Arxiv2024|[Paper](https://arxiv.org/abs/2406.07089)|null|
|**Change-Agent**|**Change-Agent: Toward Interactive Comprehensive Remote Sensing Change Interpretation and Analysis**|TGRS2024|[Paper](https://ieeexplore.ieee.org/abstract/document/10591792)|[link](https://github.com/Chen-Yang-Liu/Change-Agent)|

## Benchmarks for RSFMs
|Abbreviation|Title|Publication|Paper|Link|Downstream Tasks|
|:---:|---|:---:|:---:|:---:|:---:|
|**-**|**Revisiting pre-trained remote sensing model benchmarks: resizing and normalization matters**|Arxiv2023|[Paper](https://arxiv.org/abs/2305.13456)|[link](https://github.com/isaaccorley/resize-is-all-you-need)|Classification|
|**GEO-Bench**|**GEO-Bench: Toward Foundation Models for Earth Monitoring**|Arxiv2023|[Paper](https://arxiv.org/abs/2306.03831)|[link](https://github.com/ServiceNow/geo-bench)|Classification & Segmentation|
|**FoMo-Bench**|**FoMo-Bench: a multi-modal, multi-scale and multi-task Forest Monitoring Benchmark for remote sensing foundation models**|Arxiv2023|[FoMo-Bench](https://arxiv.org/abs/2312.10114)|Comming soon|Classification & Segmentation & Detection for forest monitoring|


## (Large-scale) Pre-training Datasets

|Abbreviation|Title|Publication|Paper|Attribute|Link|
|:---:|---|:---:|:---:|:---:|:---:|
|**fMoW**|**Functional Map of the World**|CVPR2018|[fMoW](https://openaccess.thecvf.com/content_cvpr_2018/html/Christie_Functional_Map_of_CVPR_2018_paper.html)|**Vision**|[link](https://github.com/fMoW)|
|**SEN12MS**|**SEN12MS -- A Curated Dataset of Georeferenced Multi-Spectral Sentinel-1/2 Imagery for Deep Learning and Data Fusion**|-|[SEN12MS](https://arxiv.org/abs/1906.07789)|**Vision**|[link](https://arxiv.org/abs/1906.07789)|
|**BEN-MM**|**BigEarthNet-MM: A Large Scale Multi-Modal Multi-Label Benchmark Archive for Remote Sensing Image Classification and Retrieval**|GRSM2021|[BEN-MM](https://ieeexplore.ieee.org/abstract/document/9552024)|**Vision**|[link](https://ieeexplore.ieee.org/abstract/document/9552024)|

# Relevant Projects
*（TODO. This section is dedicated to recommending more relevant and impactful projects, with the hope of promoting the development of the RS community. :smile: :rocket:）*
|Title|Link|Brief Introduction|
|---|:---:|:---:|
|**RSFMs (Remote Sensing Foundation Models) Playground**|[link](https://github.com/synativ/RSFMs)|An open-source playground to streamline the evaluation and fine-tuning of RSFMs on various datasets.|
|**PANGAEA**|[link](https://github.com/yurujaja/pangaea-bench)|A Global and Inclusive Benchmark for Geospatial Foundation Models.|

## Survey Papers
|Title|Publication|Paper|Attribute|
|---|:---:|:---:|:---:|
|**Self-Supervised Remote Sensing Feature Learning: Learning Paradigms, Challenges, and Future Works**|TGRS2023|[Paper](https://ieeexplore.ieee.org/abstract/document/10126079)|**Vision & Vision-Language**|
|**The Potential of Visual ChatGPT For Remote Sensing**|Arxiv2023|[Paper](https://arxiv.org/abs/2304.13009)|**Vision-Language**|
|**遥感大模型：进展与前瞻**|武汉大学学报 (信息科学版) 2023|[Paper](http://ch.whu.edu.cn/cn/article/doi/10.13203/j.whugis20230341?viewType=HTML)|**Vision & Vision-Language**|
|**地理人工智能样本：模型、质量与服务**|武汉大学学报 (信息科学版) 2023|[Paper](http://ch.whu.edu.cn/article/id/5e67ed6a-aae5-4ec0-ad1b-f2aba89f4617)|**-**|
|**Brain-Inspired Remote Sensing Foundation Models and Open Problems: A Comprehensive Survey**|JSTARS2023|[Paper](https://ieeexplore.ieee.org/abstract/document/10254282)|**Vision & Vision-Language**|
|**Revisiting pre-trained remote sensing model benchmarks: resizing and normalization matters**|Arxiv2023|[Paper](https://arxiv.org/abs/2305.13456)|**Vision**|
|**An Agenda for Multimodal Foundation Models for Earth Observation**|IGARSS2023|[Paper](https://ieeexplore.ieee.org/abstract/document/10282966)|**Vision**|
|**Transfer learning in environmental remote sensing**|RSE2024|[Paper](https://www.sciencedirect.com/science/article/pii/S0034425723004765)|**Transfer learning**|
|**遥感基础模型发展综述与未来设想**|遥感学报2023|[Paper](https://www.ygxb.ac.cn/zh/article/doi/10.11834/jrs.20233313/)|**-**|
|**On the Promises and Challenges of Multimodal Foundation Models for Geographical, Environmental, Agricultural, and Urban Planning Applications**|Arxiv2023|[Paper](https://arxiv.org/abs/2312.17016)|**Vision-Language**|
|**Vision-Language Models in Remote Sensing: Current Progress and Future Trends**|IEEE GRSM2024|[Paper](https://arxiv.org/abs/2305.05726)|**Vision-Language**|
|**On the Foundations of Earth and Climate Foundation Models**|Arxiv2024|[Paper](https://arxiv.org/abs/2405.04285)|**Vision & Vision-Language**|
|**Towards Vision-Language Geo-Foundation Model: A Survey**|Arxiv2024|[Paper](https://arxiv.org/abs/2406.09385)|**Vision-Language**|
|**AI Foundation Models in Remote Sensing: A Survey**|Arxiv2024|[Paper](https://arxiv.org/abs/2408.03464)|**Vision**|
|**Foundation model for generalist remote sensing intelligence: Potentials and prospects**|Science Bulletin2024|[Paper](https://www.sciencedirect.com/science/article/pii/S2095927324006510?via%3Dihub)|**-**|
|**Advancements in Visual Language Models for Remote Sensing: Datasets, Capabilities, and Enhancement Techniques**|Arxiv2024|[Paper](https://arxiv.org/abs/2410.17283)|**Vision-Language**|
|**Foundation Models for Remote Sensing and Earth Observation: A Survey**|Arxiv2024|[Paper](https://arxiv.org/abs/2410.16602)|**Vision & Vision-Language**|
