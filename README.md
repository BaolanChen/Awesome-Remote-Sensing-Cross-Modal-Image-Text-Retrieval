<div align='center'>
  
# Awesome-Remote-Sensing-Cross-Modal-Retrieval
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/BaolanChen/Awesome-Remote-Sensing-Cross-Modal-Retrieval)
<img alt="GitHub watchers" src="https://img.shields.io/github/watchers/BaolanChen/Awesome-Remote-Sensing-Cross-Modal-Retrieval?style=social">
<img alt="GitHub forks" src="https://img.shields.io/github/forks/BaolanChen/Awesome-Remote-Sensing-Cross-Modal-Retrieval?style=social">
<img alt="GitHub stars" src="https://img.shields.io/github/stars/BaolanChen/Awesome-Remote-Sensing-Cross-Modal-Retrieval?style=social">
<h4>A collection of papers, datasets, benchmarks, code, and model weights for Remote Sensing Cross-Modal Image-Text Retrieval (RSCMIT).</h4>

---
</div>

## 📢 Latest Updates
:fire::fire::fire: Last Updated on 2024.12.05 :fire::fire::fire:

- **2024.12.05**: Update SIRS and HVSA.

## Table of Contents
- **Models**
  - [Remote Sensing Vision Foundation Models](#remote-sensing-vision-foundation-models)
  - [Remote Sensing Vision-Language Foundation Models](#remote-sensing-vision-language-foundation-models)
  - [Remote Sensing Generative Foundation Models](#remote-sensing-generative-foundation-models)
  - [Remote Sensing Vision-Location Foundation Models](#remote-sensing-vision-location-foundation-models)
  - [Remote Sensing Vision-Audio Foundation Models](#remote-sensing-vision-audio-foundation-models)
- **Datasets & Benchmarks**
  - [Benchmarks for RSFMs](#benchmarks-for-rSFMs)
  - [(Large-scale) Pre-training Datasets](#Remote-Sensing-Captions-Datasets)
- **Others**
  - [Relevant Projects](#relevant-projects)
  - [Survey Papers](#survey-papers)
  

## 📊 Remote Sensing Captions Datasets
> Collect the more popular image-text pairs datasets on remote sensing, and welcome contact for additions if there are more.

| Dataset Name                                                         | Image size | Image Resolution      | VLMs |
| ------------------------------------------------------------ | ---------- | --------------- | ------------------------------------------------------------ |
| [UCM-Captions](https://github.com/201528014227051/RSICD_optimal) | 613        | 256 × 256       | - |
| [Sydney-Captions](https://github.com/201528014227051/RSICD_optimal) | 2,100      | 500 × 500       | - |
| [RSICD](https://github.com/201528014227051/RSICD_optimal)    | 10,921     | 224 × 224       | - |
| [RSITMD](https://github.com/xiaoyuan1996/AMFMN/tree/master/RSITMD) | 4,743      | 256 × 256       | - |
| [NWPU-Captions](https://github.com/HaiyanHuang98/NWPU-Captions) | 31,500     | 256 × 256       | - |
| [RS5M](https://github.com/om-ai-lab/RS5M)                    | 5 million+ | All Resolutions | [GeoRSCLIP](https://huggingface.co/Zilun/GeoRSCLIP) |
| [SkyScript](https://github.com/wangzhecheng/SkyScript)                    | 5.2 million+ | All Resolutions | [SkyCLIP](https://github.com/wangzhecheng/SkyScript) |

  
## Remote Sensing Cross-Modal Image-Text Retrieval Models

|Paper|Title|Publication|Affiliation|Code|Note
|:---:|---|:---:|:---:|:---:|:---:|
|[VSE++](https://arxiv.org/abs/1707.05612)|**VSE++: Improving Visual-Semantic Embeddings with Hard Negatives**|BMVC 2018 spotlight |University of Toronto|[Github](https://github.com/fartashf/vsepp)|
|[PE-RSITR](https://ieeexplore.ieee.org/abstract/document/10231134)|**Parameter-Efficient Transfer Learning for Remote Sensing Image–Text Retrieval**|TGRS 2023|Northwestern Polytechnical University|[Github](https://github.com/ZhanYang-nwpu/PE-RSITR)|
|[SkyEyeGPT](https://arxiv.org/abs/2401.09712)|**Unifying Remote Sensing Vision-Language Tasks via Instruction Tuning with Large Language Model**|Arxiv 2024|Northwestern Polytechnical University|[Github](https://github.com/ZhanYang-nwpu/SkyEyeGPT)|
|[PIR](https://dl.acm.org/doi/abs/10.1145/3581783.3612374)|**A Prior Instruction Representation Framework for Remote Sensing Image-text Retrieval**|ACMMM 2023 oral|Zhejiang University of Technology|[Github](https://github.com/Zjut-MultimediaPlus/PIR-pytorch)|
|[GaLR](https://ieeexplore.ieee.org/document/9745546)|**Remote Sensing Cross-Modal Text-Image Retrieval Based on Global and Local Information**|TGRS 2022|Aerospace Information Research Institute,  Chinese Academy of Sciences|[Github](https://github.com/xiaoyuan1996/GaLR)|
|[AMFMN](https://ieeexplore.ieee.org/document/9745546)|**Exploring a Fine-Grained Multiscale Method for Cross-Modal Remote Sensing Image Retrieval**|TGRS 2021|Aerospace Information Research Institute,  Chinese Academy of Sciences|[Github](https://github.com/xiaoyuan1996/GaLR)|
|[RemoteCLIP](https://ieeexplore.ieee.org/document/9745546)|**RemoteCLIP: A Vision Language Foundation Model for Remote Sensing**|TGRS 2024|Hohai University|[Github](https://github.com/ChenDelong1999/RemoteCLIP)|
|[SIRS](https://ieeexplore.ieee.org/document/10533243)|**Multitask Joint Learning for Remote Sensing Foreground-Entity Image–Text Retrieval**|TGRS 2024|Soochow University|[Github](https://github.com/StarBurstStream0/SIRS)|
|[HVSA](https://ieeexplore.ieee.org/document/10533243)|**Hypersphere-Based Remote Sensing Cross-Modal Text–Image Retrieval via Curriculum Learning**|TGRS 2023|Aerospace Information Research Institute,  Chinese Academy of Sciences|[Github](https://github.com/ZhangWeihang99/HVSA)|
|[SWAN](https://dl.acm.org/doi/abs/10.1145/3591106.3592236)|**Reducing Semantic Confusion Scene-aware Aggregation Network for Remote Sensing Cross-modal Retrieval**|ICMR 2023 oral|Zhejiang University of Technology |[Github](https://github.com/jaychempan/SWAN)|

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
|**GRAFT**|**Remote Sensing Vision-Language Foundation Models without Annotations via Ground Remote Alignment**|ICLR2024|[GRAFT](https://openreview.net/pdf?id=w9tc699w3Z)|-|

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

