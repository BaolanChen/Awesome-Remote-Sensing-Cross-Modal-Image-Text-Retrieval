<div align="center">
  
# Awesome-Remote-Sensing-Cross-Modal-Retrieval
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/BaolanChen/Awesome-Remote-Sensing-Cross-Modal-Retrieval)
<img alt="GitHub watchers" src="https://img.shields.io/github/watchers/BaolanChen/Awesome-Remote-Sensing-Cross-Modal-Retrieval?style=social"> <img alt="GitHub stars" src="https://img.shields.io/github/stars/BaolanChen/Awesome-Remote-Sensing-Cross-Modal-Retrieval?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/BaolanChen/Awesome-Remote-Sensing-Cross-Modal-Retrieval?style=social">

<h4>A collection of papers, datasets, benchmarks, code, and model weights for Remote Sensing Cross-Modal Image-Text Retrieval (RSCMIT).</h4>

---
<div align="left">

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

## Survey Papers
|Title|Publication|Paper|Attribute|
|---|:---:|:---:|:---:|
|**Self-Supervised Remote Sensing Feature Learning: Learning Paradigms, Challenges, and Future Works**|TGRS2023|[Paper](https://ieeexplore.ieee.org/abstract/document/10126079)|**Vision & Vision-Language**|
|**The Potential of Visual ChatGPT For Remote Sensing**|Arxiv2023|[Paper](https://arxiv.org/abs/2304.13009)|**Vision-Language**|
|**遥感大模型：进展与前瞻**|武汉大学学报 (信息科学版) 2023|[Paper](http://ch.whu.edu.cn/cn/article/doi/10.13203/j.whugis20230341?viewType=HTML)|**Vision & Vision-Language**|

