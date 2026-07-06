# SOD-COD Research Map

Papers, datasets, and notes on **Salient Object Detection (SOD)**, **Camouflaged Object Detection (COD)**, RGB-D perception, SAM adaptation, and unified foreground segmentation.

Last updated: 2026-07-07

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## About

I use this repository to keep track of papers and resources related to SOD and COD, especially RGB-D SOD, RGB-D COD, SAM-based adaptation, and joint SOD-COD learning.

In the topic sections, each paper is placed under one main direction. The task cell uses a readable text label with a color strip, while the tag column keeps extra information such as `RGB-D`, `SAM`, `Open-Vocab`, `Weak`, or `Video`.

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
| <b>SOD</b><br>🟩🟩🟩 | Salient object detection |
| <b>COD</b><br>🟦🟦🟦 | Camouflaged object detection / segmentation |
| <b>SOD-COD</b><br>🟪🟪🟪 | Joint SOD-COD or general foreground segmentation |
| <b>RGBD-SOD</b><br>🟧🟧🟧 | RGB-D salient object detection |
| <b>RGBD-COD</b><br>🟫🟫🟫 | RGB-D camouflaged object detection |
| <b>VIDEO</b><br>🟨🟨🟨 | Video SOD / COD |
| <b>SURVEY</b><br>⬛⬛⬛ | Survey, benchmark, or dataset paper |

## Latest Work

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| <b>COD</b><br>🟦🟦🟦 | 2026/Jun | CVPR | SDDF: Specificity-Driven Dynamic Focusing for Open-Vocabulary Camouflaged Object Detection | `Open-Vocab` `Text` `Detection` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Liang_SDDF_Specificity-Driven_Dynamic_Focusing_for_Open-Vocabulary_Camouflaged_Object_Detection_CVPR_2026_paper.html) / [Code](https://github.com/Zh1fen/SDDF) |
| <b>COD</b><br>🟦🟦🟦 | 2026/Jun | CVPR | Seeing Both Sides: Towards Bidirectional Semantic Alignment for Open-Vocabulary Camouflaged Object Segmentation | `Open-Vocab` `Text` `CLIP` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Zhang_Seeing_Both_Sides_Towards_Bidirectional_Semantic_Alignment_for_Open-Vocabulary_Camouflaged_CVPR_2026_paper.html) / [Code](https://github.com/okmaybach/BaCLIP-CVPR2026) |
| <b>COD</b><br>🟦🟦🟦 | 2026/Jun | CVPR | EReCu: Pseudo-label Evolution Fusion and Refinement with Multi-Cue Learning for Unsupervised Camouflage Detection | `Unsupervised` `Pseudo-Label` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Jiang_EReCu_Pseudo-label_Evolution_Fusion_and_Refinement_with_Multi-Cue_Learning_for_CVPR_2026_paper.html) / [arXiv](https://arxiv.org/abs/2603.11521) |
| <b>COD</b><br>🟦🟦🟦 | 2026/Jun | CVPR | Beyond Weak Supervision: MLLMs-Guided Graded Knowledge Distillation for Unsupervised Camouflaged Object Detection | `Unsupervised` `MLLM` `Distillation` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Chen_Beyond_Weak_Supervision_MLLMs-Guided_Graded_Knowledge_Distillation_for_Unsupervised_Camouflaged_CVPR_2026_paper.html) |
| <b>RGBD-SOD</b><br>🟧🟧🟧 | 2026/Jun | CVPR | M4-SAM: Multi-Modal Mixture-of-Experts with Memory-Augmented SAM for RGB-D Video Salient Object Detection | `RGB-D` `Video` `SAM2` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Liu_M4-SAM_Multi-Modal_Mixture-of-Experts_with_Memory-Augmented_SAM_for_RGB-D_Video_Salient_CVPR_2026_paper.html) |

## Surveys and Benchmarks

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| <b>SURVEY</b><br>⬛⬛⬛ | 2024/Aug | arXiv | A Survey of Camouflaged Object Detection and Beyond | `COD` `Survey` | [Paper](https://arxiv.org/abs/2408.14562) |
| <b>SURVEY</b><br>⬛⬛⬛ | 2023/Apr | arXiv | Advances in Deep Concealed Scene Understanding | `COD` `Survey` `Benchmark` | [Paper](https://arxiv.org/abs/2304.11234) / [Project](https://github.com/DengPingFan/CSU) |
| <b>SURVEY</b><br>⬛⬛⬛ | 2020/Aug | arXiv | RGB-D Salient Object Detection: A Survey | `RGBD-SOD` `Survey` `Benchmark` | [Paper](https://arxiv.org/abs/2008.00230) / [Project](https://github.com/taozh2017/RGBDSODsurvey) |
| <b>SURVEY</b><br>⬛⬛⬛ | 2020/Jun | CVPR | Camouflaged Object Detection | `COD10K` `SINet` `Benchmark` | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Fan_Camouflaged_Object_Detection_CVPR_2020_paper.html) / [Code](https://github.com/DengPingFan/SINet/) |
| <b>SURVEY</b><br>⬛⬛⬛ | 2020/Jun | CVPR | Rethinking RGB-D Salient Object Detection: Models, Data Sets, and Large-Scale Benchmarks | `RGBD-SOD` `SIP` `Benchmark` | [Paper](https://arxiv.org/abs/1907.06781) / [Project](https://github.com/DengPingFan/D3NetBenchmark) |

## Salient Object Detection

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| <b>SOD</b><br>🟩🟩🟩 | 2019/Apr | CVPR | A Simple Pooling-Based Design for Real-Time Salient Object Detection | `PoolNet` `Real-Time` | [Paper](https://arxiv.org/abs/1904.09569) / [Project](http://mmcheng.net/poolnet/) |
| <b>SOD</b><br>🟩🟩🟩 | 2019/Apr | CVPR | Cascaded Partial Decoder for Fast and Accurate Salient Object Detection | `CPD` `Fast` | [Paper](https://arxiv.org/abs/1904.08739) |

## RGB-D Salient Object Detection

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| <b>RGBD-SOD</b><br>🟧🟧🟧 | 2023/Oct | arXiv | Salient Object Detection in RGB-D Videos | `RGB-D` `Video` `Dataset` | [Paper](https://arxiv.org/abs/2310.15482) / [Code](https://github.com/kerenfu/RDVS/) |
| <b>RGBD-SOD</b><br>🟧🟧🟧 | 2021/Sep | TIP | RGB-D Salient Object Detection with Ubiquitous Target Awareness | `RGB-D` `Depth-Free Inference` | [Paper](https://arxiv.org/abs/2109.03425) |
| <b>RGBD-SOD</b><br>🟧🟧🟧 | 2021/Jan | arXiv | RGB-D Salient Object Detection via 3D Convolutional Neural Networks | `RGB-D` `3D-CNN` | [Paper](https://arxiv.org/abs/2101.10241) / [Code](https://github.com/PPOLYpubki/RD3D) |
| <b>RGBD-SOD</b><br>🟧🟧🟧 | 2020/Jul | ECCV | Cross-Modal Weighting Network for RGB-D Salient Object Detection | `RGB-D` `Fusion` | [Paper](https://arxiv.org/abs/2007.04901) |
| <b>RGBD-SOD</b><br>🟧🟧🟧 | 2020/Jun | CVPR | UC-Net: Uncertainty Inspired RGB-D Saliency Detection via Conditional Variational Autoencoders | `RGB-D` `Uncertainty` | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_UC-Net_Uncertainty_Inspired_RGB-D_Saliency_Detection_via_Conditional_Variational_Autoencoders_CVPR_2020_paper.html) |
| <b>RGBD-SOD</b><br>🟧🟧🟧 | TODO | TODO | RGB-D SOD with SAM fine-tuning | `RGB-D` `SAM` `PEFT` | Paper / Code |

## Camouflaged Object Detection

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| <b>COD</b><br>🟦🟦🟦 | 2026/Jun | CVPR | Beyond Appearance: Camouflaged Object Detection via Geometric Structure | `Geometry` `DepthSAM` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Han_Beyond_Appearance_Camouflaged_Object_Detection_via_Geometric_Structure_CVPR_2026_paper.html) |
| <b>COD</b><br>🟦🟦🟦 | 2022/May | MIR | Deep Gradient Learning for Efficient Camouflaged Object Detection | `DGNet` `Gradient` `Efficient` | [Paper](https://arxiv.org/abs/2205.12853) / [Code](https://github.com/GewelsJI/DGNet) |
| <b>COD</b><br>🟦🟦🟦 | 2022/Mar | CVPR | Zoom In and Out: A Mixed-scale Triplet Network for Camouflaged Object Detection | `ZoomNet` `Scale` | [Paper](https://arxiv.org/abs/2203.02688) / [Code](https://github.com/lartpang/ZoomNet) |
| <b>COD</b><br>🟦🟦🟦 | 2020/Jun | CVPR | Camouflaged Object Detection | `COD10K` `SINet` | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Fan_Camouflaged_Object_Detection_CVPR_2020_paper.html) / [Code](https://github.com/DengPingFan/SINet/) |

## Weak / Semi / Unsupervised COD

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| <b>COD</b><br>🟦🟦🟦 | 2026/Jun | CVPR | EReCu: Pseudo-label Evolution Fusion and Refinement with Multi-Cue Learning for Unsupervised Camouflage Detection | `Unsupervised` `Pseudo-Label` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Jiang_EReCu_Pseudo-label_Evolution_Fusion_and_Refinement_with_Multi-Cue_Learning_for_CVPR_2026_paper.html) |
| <b>COD</b><br>🟦🟦🟦 | 2026/Jun | CVPR | Beyond Weak Supervision: MLLMs-Guided Graded Knowledge Distillation for Unsupervised Camouflaged Object Detection | `Unsupervised` `MLLM` `Distillation` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Chen_Beyond_Weak_Supervision_MLLMs-Guided_Graded_Knowledge_Distillation_for_Unsupervised_Camouflaged_CVPR_2026_paper.html) |
| <b>COD</b><br>🟦🟦🟦 | 2024/Aug | arXiv | SAM-COD: SAM-guided Unified Framework for Weakly-Supervised Camouflaged Object Detection | `Weak` `SAM` | [Paper](https://arxiv.org/abs/2408.10760) |

## Open-Vocabulary / Referring COD

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| <b>COD</b><br>🟦🟦🟦 | 2026/Jun | CVPR | SDDF: Specificity-Driven Dynamic Focusing for Open-Vocabulary Camouflaged Object Detection | `Open-Vocab` `Text` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Liang_SDDF_Specificity-Driven_Dynamic_Focusing_for_Open-Vocabulary_Camouflaged_Object_Detection_CVPR_2026_paper.html) / [Code](https://github.com/Zh1fen/SDDF) |
| <b>COD</b><br>🟦🟦🟦 | 2026/Jun | CVPR | Seeing Both Sides: Towards Bidirectional Semantic Alignment for Open-Vocabulary Camouflaged Object Segmentation | `Open-Vocab` `CLIP` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Zhang_Seeing_Both_Sides_Towards_Bidirectional_Semantic_Alignment_for_Open-Vocabulary_Camouflaged_CVPR_2026_paper.html) / [Code](https://github.com/okmaybach/BaCLIP-CVPR2026) |
| <b>COD</b><br>🟦🟦🟦 | 2026/Jun | CVPR | Training-Free Open-Vocabulary Camouflaged Object Segmentation via Fine-Grained Object Binding and Adaptive Hybrid Prompt | `Open-Vocab` `Training-Free` `Prompt` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Ren_Training-Free_Open-Vocabulary_Camouflaged_Object_Segmentation_via_Fine-Grained_Object_Binding_and_CVPR_2026_paper.html) |

## SAM and Foundation Models

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| <b>RGBD-SOD</b><br>🟧🟧🟧 | 2025/Nov | AAAI | SAM-DAQ: Segment Anything Model with Depth-guided Adaptive Queries for RGB-D Video Salient Object Detection | `RGB-D` `Video` `SAM2` | [Paper](https://arxiv.org/abs/2511.09870) |
| <b>COD</b><br>🟦🟦🟦 | 2025/Sep | ACM MM | SAM-TTT: Segment Anything Model via Reverse Parameter Configuration and Test-Time Training for Camouflaged Object Detection | `SAM` `TTA` | [Paper](https://arxiv.org/abs/2509.11884) / [Code](https://github.com/guobaoxiao/SAM-TTT) |
| <b>VIDEO</b><br>🟨🟨🟨 | 2024/Aug | arXiv | SAM 2: Segment Anything in Images and Videos | `SAM2` `Video` | [Paper](https://arxiv.org/abs/2408.00714) |
| <b>SOD</b><br>🟩🟩🟩 | 2024/Aug | ACM MM | Multi-Scale and Detail-Enhanced Segment Anything Model for Salient Object Detection | `SAM` `Adapter` | [Paper](https://arxiv.org/abs/2408.04326) / [Code](https://github.com/BellyBeauty/MDSAM) |
| <b>SOD-COD</b><br>🟪🟪🟪 | 2023/Apr | ICCV | Segment Anything | `SAM` `Foundation` | [Paper](https://arxiv.org/abs/2304.02643) / [Project](https://segment-anything.com) |

## Joint SOD-COD / Universal Foreground

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| <b>SOD-COD</b><br>🟪🟪🟪 | 2023/Nov | arXiv | VSCode: General Visual Salient and Camouflaged Object Detection with 2D Prompt Learning | `Prompt` `Generalist` | [Paper](https://arxiv.org/abs/2311.15011) / [Code](https://github.com/Sssssuperior/VSCode) |
| <b>SOD-COD</b><br>🟪🟪🟪 | 2023/May | arXiv | Explicit Visual Prompting for Universal Foreground Segmentations | `Prompt` `PEFT` `Universal` | [Paper](https://arxiv.org/abs/2305.18476) / [Code](https://github.com/NiFangBaAGe/Explicit-Visual-Prompt) |
| <b>SOD-COD</b><br>🟪🟪🟪 | 2021/Apr | arXiv | Uncertainty-aware Joint Salient Object and Camouflaged Object Detection | `Joint` `Uncertainty` | [Paper](https://arxiv.org/abs/2104.02628) |
| <b>SOD-COD</b><br>🟪🟪🟪 | TODO | TODO | Joint RGB-D COD and SOD training | `RGB-D` `Multi-Task` | Paper / Code |

## Video and Instance-Level Tasks

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| <b>COD</b><br>🟦🟦🟦 | 2023/Aug | ACM MM | A Unified Query-based Paradigm for Camouflaged Instance Segmentation | `CIS` `Query` | [Paper](https://arxiv.org/abs/2308.07392) / [Code](https://github.com/dongbo811/UQFormer) |
| <b>VIDEO</b><br>🟨🟨🟨 | 2022/Mar | CVPR | Implicit Motion Handling for Video Camouflaged Object Detection | `VCOD` `MoCA-Mask` | [Paper](https://arxiv.org/abs/2203.07363) / [Project](https://xueliancheng.github.io/SLT-Net-project) |
| <b>COD</b><br>🟦🟦🟦 | 2021/Mar | CVPR | Camouflaged Instance Segmentation In-The-Wild: Dataset, Method, and Benchmark Suite | `CIS` `CAMO++` | [Paper](https://arxiv.org/abs/2103.17123) |

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
| <b>COD</b><br>🟦🟦🟦 | 2026/Jun | CVPR | Paper Title | `SAM` `Open-Vocab` | [Paper](url) / [Code](url) |
```

## Citation

If this repository is useful for your work, please consider starring it and citing the original papers listed here.
