# SOD-COD Research Map

Papers, datasets, and notes on **Salient Object Detection (SOD)**, **Camouflaged Object Detection (COD)**, RGB-D perception, SAM adaptation, and unified foreground segmentation.

Last updated: 2026-07-07

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## About

I use this repository to keep track of papers and resources related to SOD and COD, especially RGB-D SOD, RGB-D COD, SAM-based adaptation, and joint SOD-COD learning.

In the topic sections, each paper is placed under one main direction. The colored task label shows its primary task, while the tag column keeps extra information such as `RGB-D`, `SAM`, `Open-Vocab`, `Weak`, or `Video`.

Pull requests and paper suggestions are welcome.

## Contents

- [Task Labels](#task-labels)
- [Latest Work](#latest-work)
- [Surveys and Benchmarks](#surveys-and-benchmarks)
- [Salient Object Detection](#salient-object-detection)
- [RGB-D Salient Object Detection](#rgb-d-salient-object-detection)
- [Camouflaged Object Detection](#camouflaged-object-detection)
- [Weak / Semi / Unsupervised COD](#weak--semi--unsupervised-cod)
- [Open-Vocabulary / Referring COD](#open-vocabulary--referring-cod)
- [SAM and Foundation Models](#sam-and-foundation-models)
- [Joint SOD-COD / Universal Foreground](#joint-sod-cod--universal-foreground)
- [Video and Instance-Level Tasks](#video-and-instance-level-tasks)
- [Datasets](#datasets)

## Task Labels

| Label | Scope |
| --- | --- |
| ![SOD](https://img.shields.io/badge/-SOD-2EA44F?style=flat-square) | Salient object detection |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | Camouflaged object detection / segmentation |
| ![SOD-COD](https://img.shields.io/badge/-SOD--COD-8E44AD?style=flat-square) | Joint SOD-COD or general foreground segmentation |
| ![RGBD-SOD](https://img.shields.io/badge/-RGBD--SOD-F2994A?style=flat-square) | RGB-D salient object detection |
| ![RGBD-COD](https://img.shields.io/badge/-RGBD--COD-D35400?style=flat-square) | RGB-D camouflaged object detection |
| ![VIDEO](https://img.shields.io/badge/-VIDEO-00A6A6?style=flat-square) | Video SOD / COD |
| ![SURVEY](https://img.shields.io/badge/-SURVEY-6C757D?style=flat-square) | Survey, benchmark, or dataset paper |

## Latest Work

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2026/Jun | CVPR | SDDF: Specificity-Driven Dynamic Focusing for Open-Vocabulary Camouflaged Object Detection | `Open-Vocab` `Text` `Detection` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Liang_SDDF_Specificity-Driven_Dynamic_Focusing_for_Open-Vocabulary_Camouflaged_Object_Detection_CVPR_2026_paper.html) / [Code](https://github.com/Zh1fen/SDDF) |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2026/Jun | CVPR | Seeing Both Sides: Towards Bidirectional Semantic Alignment for Open-Vocabulary Camouflaged Object Segmentation | `Open-Vocab` `Text` `CLIP` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Zhang_Seeing_Both_Sides_Towards_Bidirectional_Semantic_Alignment_for_Open-Vocabulary_Camouflaged_CVPR_2026_paper.html) / [Code](https://github.com/okmaybach/BaCLIP-CVPR2026) |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2026/Jun | CVPR | EReCu: Pseudo-label Evolution Fusion and Refinement with Multi-Cue Learning for Unsupervised Camouflage Detection | `Unsupervised` `Pseudo-Label` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Jiang_EReCu_Pseudo-label_Evolution_Fusion_and_Refinement_with_Multi-Cue_Learning_for_CVPR_2026_paper.html) / [arXiv](https://arxiv.org/abs/2603.11521) |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2026/Jun | CVPR | Beyond Weak Supervision: MLLMs-Guided Graded Knowledge Distillation for Unsupervised Camouflaged Object Detection | `Unsupervised` `MLLM` `Distillation` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Chen_Beyond_Weak_Supervision_MLLMs-Guided_Graded_Knowledge_Distillation_for_Unsupervised_Camouflaged_CVPR_2026_paper.html) |
| ![RGBD-SOD](https://img.shields.io/badge/-RGBD--SOD-F2994A?style=flat-square) | 2026/Jun | CVPR | M4-SAM: Multi-Modal Mixture-of-Experts with Memory-Augmented SAM for RGB-D Video Salient Object Detection | `RGB-D` `Video` `SAM2` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Liu_M4-SAM_Multi-Modal_Mixture-of-Experts_with_Memory-Augmented_SAM_for_RGB-D_Video_Salient_CVPR_2026_paper.html) |

## Surveys and Benchmarks

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| ![SURVEY](https://img.shields.io/badge/-SURVEY-6C757D?style=flat-square) | 2024/Aug | arXiv | A Survey of Camouflaged Object Detection and Beyond | `COD` `Survey` | [Paper](https://arxiv.org/abs/2408.14562) |
| ![SURVEY](https://img.shields.io/badge/-SURVEY-6C757D?style=flat-square) | 2023/Apr | arXiv | Advances in Deep Concealed Scene Understanding | `COD` `Survey` `Benchmark` | [Paper](https://arxiv.org/abs/2304.11234) / [Project](https://github.com/DengPingFan/CSU) |
| ![SURVEY](https://img.shields.io/badge/-SURVEY-6C757D?style=flat-square) | 2020/Aug | arXiv | RGB-D Salient Object Detection: A Survey | `RGBD-SOD` `Survey` `Benchmark` | [Paper](https://arxiv.org/abs/2008.00230) / [Project](https://github.com/taozh2017/RGBDSODsurvey) |
| ![SURVEY](https://img.shields.io/badge/-SURVEY-6C757D?style=flat-square) | 2020/Jun | CVPR | Camouflaged Object Detection | `COD10K` `SINet` `Benchmark` | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Fan_Camouflaged_Object_Detection_CVPR_2020_paper.html) / [Code](https://github.com/DengPingFan/SINet/) |
| ![SURVEY](https://img.shields.io/badge/-SURVEY-6C757D?style=flat-square) | 2020/Jun | CVPR | Rethinking RGB-D Salient Object Detection: Models, Data Sets, and Large-Scale Benchmarks | `RGBD-SOD` `SIP` `Benchmark` | [Paper](https://arxiv.org/abs/1907.06781) / [Project](https://github.com/DengPingFan/D3NetBenchmark) |

## Salient Object Detection

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| ![SOD](https://img.shields.io/badge/-SOD-2EA44F?style=flat-square) | 2019/Apr | CVPR | A Simple Pooling-Based Design for Real-Time Salient Object Detection | `PoolNet` `Real-Time` | [Paper](https://arxiv.org/abs/1904.09569) / [Project](http://mmcheng.net/poolnet/) |
| ![SOD](https://img.shields.io/badge/-SOD-2EA44F?style=flat-square) | 2019/Apr | CVPR | Cascaded Partial Decoder for Fast and Accurate Salient Object Detection | `CPD` `Fast` | [Paper](https://arxiv.org/abs/1904.08739) |

## RGB-D Salient Object Detection

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| ![RGBD-SOD](https://img.shields.io/badge/-RGBD--SOD-F2994A?style=flat-square) | 2020/Jun | CVPR | UC-Net: Uncertainty Inspired RGB-D Saliency Detection via Conditional Variational Autoencoders | `RGB-D` `Uncertainty` | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_UC-Net_Uncertainty_Inspired_RGB-D_Saliency_Detection_via_Conditional_Variational_Autoencoders_CVPR_2020_paper.html) |
| ![RGBD-SOD](https://img.shields.io/badge/-RGBD--SOD-F2994A?style=flat-square) | 2020/Jul | ECCV | Cross-Modal Weighting Network for RGB-D Salient Object Detection | `RGB-D` `Fusion` | [Paper](https://arxiv.org/abs/2007.04901) |
| ![RGBD-SOD](https://img.shields.io/badge/-RGBD--SOD-F2994A?style=flat-square) | 2021/Jan | arXiv | RGB-D Salient Object Detection via 3D Convolutional Neural Networks | `RGB-D` `3D-CNN` | [Paper](https://arxiv.org/abs/2101.10241) / [Code](https://github.com/PPOLYpubki/RD3D) |
| ![RGBD-SOD](https://img.shields.io/badge/-RGBD--SOD-F2994A?style=flat-square) | 2021/Sep | TIP | RGB-D Salient Object Detection with Ubiquitous Target Awareness | `RGB-D` `Depth-Free Inference` | [Paper](https://arxiv.org/abs/2109.03425) |
| ![RGBD-SOD](https://img.shields.io/badge/-RGBD--SOD-F2994A?style=flat-square) | 2023/Oct | arXiv | Salient Object Detection in RGB-D Videos | `RGB-D` `Video` `Dataset` | [Paper](https://arxiv.org/abs/2310.15482) / [Code](https://github.com/kerenfu/RDVS/) |
| ![RGBD-SOD](https://img.shields.io/badge/-RGBD--SOD-F2994A?style=flat-square) | TODO | TODO | RGB-D SOD with SAM fine-tuning | `RGB-D` `SAM` `PEFT` | Paper / Code |

## Camouflaged Object Detection

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2020/Jun | CVPR | Camouflaged Object Detection | `COD10K` `SINet` | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Fan_Camouflaged_Object_Detection_CVPR_2020_paper.html) / [Code](https://github.com/DengPingFan/SINet/) |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2022/Mar | CVPR | Zoom In and Out: A Mixed-scale Triplet Network for Camouflaged Object Detection | `ZoomNet` `Scale` | [Paper](https://arxiv.org/abs/2203.02688) / [Code](https://github.com/lartpang/ZoomNet) |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2022/May | MIR | Deep Gradient Learning for Efficient Camouflaged Object Detection | `DGNet` `Gradient` `Efficient` | [Paper](https://arxiv.org/abs/2205.12853) / [Code](https://github.com/GewelsJI/DGNet) |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2026/Jun | CVPR | Beyond Appearance: Camouflaged Object Detection via Geometric Structure | `Geometry` `DepthSAM` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Han_Beyond_Appearance_Camouflaged_Object_Detection_via_Geometric_Structure_CVPR_2026_paper.html) |

## Weak / Semi / Unsupervised COD

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2024/Aug | arXiv | SAM-COD: SAM-guided Unified Framework for Weakly-Supervised Camouflaged Object Detection | `Weak` `SAM` | [Paper](https://arxiv.org/abs/2408.10760) |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2026/Jun | CVPR | EReCu: Pseudo-label Evolution Fusion and Refinement with Multi-Cue Learning for Unsupervised Camouflage Detection | `Unsupervised` `Pseudo-Label` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Jiang_EReCu_Pseudo-label_Evolution_Fusion_and_Refinement_with_Multi-Cue_Learning_for_CVPR_2026_paper.html) |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2026/Jun | CVPR | Beyond Weak Supervision: MLLMs-Guided Graded Knowledge Distillation for Unsupervised Camouflaged Object Detection | `Unsupervised` `MLLM` `Distillation` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Chen_Beyond_Weak_Supervision_MLLMs-Guided_Graded_Knowledge_Distillation_for_Unsupervised_Camouflaged_CVPR_2026_paper.html) |

## Open-Vocabulary / Referring COD

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2026/Jun | CVPR | SDDF: Specificity-Driven Dynamic Focusing for Open-Vocabulary Camouflaged Object Detection | `Open-Vocab` `Text` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Liang_SDDF_Specificity-Driven_Dynamic_Focusing_for_Open-Vocabulary_Camouflaged_Object_Detection_CVPR_2026_paper.html) / [Code](https://github.com/Zh1fen/SDDF) |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2026/Jun | CVPR | Seeing Both Sides: Towards Bidirectional Semantic Alignment for Open-Vocabulary Camouflaged Object Segmentation | `Open-Vocab` `CLIP` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Zhang_Seeing_Both_Sides_Towards_Bidirectional_Semantic_Alignment_for_Open-Vocabulary_Camouflaged_CVPR_2026_paper.html) / [Code](https://github.com/okmaybach/BaCLIP-CVPR2026) |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2026/Jun | CVPR | Training-Free Open-Vocabulary Camouflaged Object Segmentation via Fine-Grained Object Binding and Adaptive Hybrid Prompt | `Open-Vocab` `Training-Free` `Prompt` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Ren_Training-Free_Open-Vocabulary_Camouflaged_Object_Segmentation_via_Fine-Grained_Object_Binding_and_CVPR_2026_paper.html) |

## SAM and Foundation Models

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| ![SOD-COD](https://img.shields.io/badge/-SOD--COD-8E44AD?style=flat-square) | 2023/Apr | ICCV | Segment Anything | `SAM` `Foundation` | [Paper](https://arxiv.org/abs/2304.02643) / [Project](https://segment-anything.com) |
| ![VIDEO](https://img.shields.io/badge/-VIDEO-00A6A6?style=flat-square) | 2024/Aug | arXiv | SAM 2: Segment Anything in Images and Videos | `SAM2` `Video` | [Paper](https://arxiv.org/abs/2408.00714) |
| ![SOD](https://img.shields.io/badge/-SOD-2EA44F?style=flat-square) | 2024/Aug | ACM MM | Multi-Scale and Detail-Enhanced Segment Anything Model for Salient Object Detection | `SAM` `Adapter` | [Paper](https://arxiv.org/abs/2408.04326) / [Code](https://github.com/BellyBeauty/MDSAM) |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2025/Sep | ACM MM | SAM-TTT: Segment Anything Model via Reverse Parameter Configuration and Test-Time Training for Camouflaged Object Detection | `SAM` `TTA` | [Paper](https://arxiv.org/abs/2509.11884) / [Code](https://github.com/guobaoxiao/SAM-TTT) |
| ![RGBD-SOD](https://img.shields.io/badge/-RGBD--SOD-F2994A?style=flat-square) | 2025/Nov | AAAI | SAM-DAQ: Segment Anything Model with Depth-guided Adaptive Queries for RGB-D Video Salient Object Detection | `RGB-D` `Video` `SAM2` | [Paper](https://arxiv.org/abs/2511.09870) |

## Joint SOD-COD / Universal Foreground

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| ![SOD-COD](https://img.shields.io/badge/-SOD--COD-8E44AD?style=flat-square) | 2021/Apr | arXiv | Uncertainty-aware Joint Salient Object and Camouflaged Object Detection | `Joint` `Uncertainty` | [Paper](https://arxiv.org/abs/2104.02628) |
| ![SOD-COD](https://img.shields.io/badge/-SOD--COD-8E44AD?style=flat-square) | 2023/May | arXiv | Explicit Visual Prompting for Universal Foreground Segmentations | `Prompt` `PEFT` `Universal` | [Paper](https://arxiv.org/abs/2305.18476) / [Code](https://github.com/NiFangBaAGe/Explicit-Visual-Prompt) |
| ![SOD-COD](https://img.shields.io/badge/-SOD--COD-8E44AD?style=flat-square) | 2023/Nov | arXiv | VSCode: General Visual Salient and Camouflaged Object Detection with 2D Prompt Learning | `Prompt` `Generalist` | [Paper](https://arxiv.org/abs/2311.15011) / [Code](https://github.com/Sssssuperior/VSCode) |
| ![SOD-COD](https://img.shields.io/badge/-SOD--COD-8E44AD?style=flat-square) | TODO | TODO | Joint RGB-D COD and SOD training | `RGB-D` `Multi-Task` | Paper / Code |

## Video and Instance-Level Tasks

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| ![VIDEO](https://img.shields.io/badge/-VIDEO-00A6A6?style=flat-square) | 2022/Mar | CVPR | Implicit Motion Handling for Video Camouflaged Object Detection | `VCOD` `MoCA-Mask` | [Paper](https://arxiv.org/abs/2203.07363) / [Project](https://xueliancheng.github.io/SLT-Net-project) |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2021/Mar | CVPR | Camouflaged Instance Segmentation In-The-Wild: Dataset, Method, and Benchmark Suite | `CIS` `CAMO++` | [Paper](https://arxiv.org/abs/2103.17123) |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2023/Aug | ACM MM | A Unified Query-based Paradigm for Camouflaged Instance Segmentation | `CIS` `Query` | [Paper](https://arxiv.org/abs/2308.07392) / [Code](https://github.com/dongbo811/UQFormer) |

## Datasets

| Dataset | Task | Link |
| --- | --- | --- |
| COD10K | COD / COS | [Project](http://mmcheng.net/cod) |
| CAMO / CAMO++ | COD / CIS | [Project](https://sites.google.com/view/ltnghia/research/camo_plus_plus) |
| MoCA-Mask | VCOD | [Project](https://xueliancheng.github.io/SLT-Net-project) |
| SIP | RGB-D SOD | [Project](https://github.com/DengPingFan/D3NetBenchmark) |
| RDVS | RGB-D VSOD | [Project](https://github.com/kerenfu/RDVS/) |

## Contributing

Contributions are welcome.

Recommended entry format:

```markdown
| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2026/Jun | CVPR | Paper Title | `SAM` `Open-Vocab` | [Paper](url) / [Code](url) |
```

## Citation

If this repository is useful for your work, please consider starring it and citing the original papers listed here.
