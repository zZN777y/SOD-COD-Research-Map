<h1 align="center">SOD-COD Research Map</h1>

<p align="center">
  <b>A curated paper map for SOD, COD, RGB-D perception, SAM adaptation, and unified foreground segmentation.</b>
</p>

<p align="center">
  <a href="#latest-work">Latest Work</a> |
  <a href="#rgb-d-salient-object-detection">RGB-D SOD</a> |
  <a href="#camouflaged-object-detection">COD</a> |
  <a href="#sam-and-foundation-models">SAM</a> |
  <a href="#datasets">Datasets</a>
</p>

---

## About

I use this repository to keep track of papers and resources related to SOD and COD, especially RGB-D SOD, RGB-D COD, SAM-based adaptation, and joint SOD-COD learning.

Each topic section is sorted by release date, newest first. Recent top-conference, top-journal, and high-signal preprint papers are prioritized.

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
| &#x1F7E9;<br><b>SOD</b> | Salient object detection |
| &#x1F7E6;<br><b>COD</b> | Camouflaged object detection / segmentation |
| &#x1F7EA;<br><b>SOD-COD</b> | Joint SOD-COD or general foreground segmentation |
| &#x1F7E7;<br><b>RGB-D SOD</b> | RGB-D salient object detection |
| &#x1F7E5;<br><b>RGB-D COD</b> | RGB-D camouflaged object detection |
| &#x1F7E8;<br><b>VIDEO</b> | Video SOD / COD |
| &#x2B1B;<br><b>SURVEY</b> | Survey, benchmark, or dataset paper |

## Latest Work

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| &#x1F7E6;<br><b>COD</b> | 2026/Jun | CVPR | SDDF: Specificity-Driven Dynamic Focusing for Open-Vocabulary Camouflaged Object Detection | `Open-Vocab` `Text` `Detection` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Liang_SDDF_Specificity-Driven_Dynamic_Focusing_for_Open-Vocabulary_Camouflaged_Object_Detection_CVPR_2026_paper.html) / [Code](https://github.com/Zh1fen/SDDF) |
| &#x1F7E6;<br><b>COD</b> | 2026/Jun | CVPR | Seeing Both Sides: Towards Bidirectional Semantic Alignment for Open-Vocabulary Camouflaged Object Segmentation | `Open-Vocab` `Text` `CLIP` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Zhang_Seeing_Both_Sides_Towards_Bidirectional_Semantic_Alignment_for_Open-Vocabulary_Camouflaged_CVPR_2026_paper.html) / [Code](https://github.com/okmaybach/BaCLIP-CVPR2026) |
| &#x1F7E6;<br><b>COD</b> | 2026/Jun | CVPR | EReCu: Pseudo-label Evolution Fusion and Refinement with Multi-Cue Learning for Unsupervised Camouflage Detection | `Unsupervised` `Pseudo-Label` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Jiang_EReCu_Pseudo-label_Evolution_Fusion_and_Refinement_with_Multi-Cue_Learning_for_CVPR_2026_paper.html) / [arXiv](https://arxiv.org/abs/2603.11521) |
| &#x1F7E7;<br><b>RGB-D SOD</b> | 2026/Jun | CVPR | M4-SAM: Multi-Modal Mixture-of-Experts with Memory-Augmented SAM for RGB-D Video Salient Object Detection | `RGB-D` `Video` `SAM2` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Liu_M4-SAM_Multi-Modal_Mixture-of-Experts_with_Memory-Augmented_SAM_for_RGB-D_Video_Salient_CVPR_2026_paper.html) |
| &#x1F7E7;<br><b>RGB-D SOD</b> | 2025/Sep | ACM MM | LEAF-Mamba: Local Emphatic and Adaptive Fusion State Space Model for RGB-D Salient Object Detection | `RGB-D` `Mamba` `Fusion` | [Paper](https://arxiv.org/abs/2509.18683) |
| &#x1F7E8;<br><b>VIDEO</b> | 2025/Mar | arXiv | CamSAM2: Segment Anything Accurately in Camouflaged Videos | `VCOS` `SAM2` `Video` | [Paper](https://arxiv.org/abs/2503.19730) / [Code](https://github.com/zhoustan/CamSAM2) |

## Surveys and Benchmarks

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| &#x2B1B;<br><b>SURVEY</b> | 2024/Aug | arXiv | A Survey of Camouflaged Object Detection and Beyond | `COD` `Survey` | [Paper](https://arxiv.org/abs/2408.14562) |
| &#x2B1B;<br><b>SURVEY</b> | 2024/Jun | arXiv | ViDSOD-100: A New Dataset and A Baseline Model for RGB-D Video Salient Object Detection | `RGB-D` `Video` `Dataset` | [Paper](https://arxiv.org/abs/2406.12536) / [Code](https://github.com/jhl-Det/RGBD_Video_SOD) |
| &#x2B1B;<br><b>SURVEY</b> | 2023/Apr | arXiv | Advances in Deep Concealed Scene Understanding | `COD` `Survey` `Benchmark` | [Paper](https://arxiv.org/abs/2304.11234) / [Project](https://github.com/DengPingFan/CSU) |
| &#x2B1B;<br><b>SURVEY</b> | 2020/Aug | arXiv | RGB-D Salient Object Detection: A Survey | `RGBD-SOD` `Survey` `Benchmark` | [Paper](https://arxiv.org/abs/2008.00230) / [Project](https://github.com/taozh2017/RGBDSODsurvey) |
| &#x2B1B;<br><b>SURVEY</b> | 2020/Jun | CVPR | Camouflaged Object Detection | `COD10K` `SINet` `Benchmark` | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Fan_Camouflaged_Object_Detection_CVPR_2020_paper.html) / [Code](https://github.com/DengPingFan/SINet/) |

## Salient Object Detection

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| &#x1F7E9;<br><b>SOD</b> | 2024/Aug | ACM MM | Multi-Scale and Detail-Enhanced Segment Anything Model for Salient Object Detection | `SAM` `Adapter` | [Paper](https://arxiv.org/abs/2408.04326) / [Code](https://github.com/BellyBeauty/MDSAM) |

## RGB-D Salient Object Detection

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| &#x1F7E7;<br><b>RGB-D SOD</b> | 2026/Jun | CVPR | M4-SAM: Multi-Modal Mixture-of-Experts with Memory-Augmented SAM for RGB-D Video Salient Object Detection | `RGB-D` `Video` `SAM2` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Liu_M4-SAM_Multi-Modal_Mixture-of-Experts_with_Memory-Augmented_SAM_for_RGB-D_Video_Salient_CVPR_2026_paper.html) |
| &#x1F7E7;<br><b>RGB-D SOD</b> | 2025/Nov | AAAI | SAM-DAQ: Segment Anything Model with Depth-guided Adaptive Queries for RGB-D Video Salient Object Detection | `RGB-D` `Video` `SAM2` | [Paper](https://arxiv.org/abs/2511.09870) |
| &#x1F7E7;<br><b>RGB-D SOD</b> | 2025/Sep | ACM MM | LEAF-Mamba: Local Emphatic and Adaptive Fusion State Space Model for RGB-D Salient Object Detection | `RGB-D` `Mamba` `Fusion` | [Paper](https://arxiv.org/abs/2509.18683) |
| &#x1F7E7;<br><b>RGB-D SOD</b> | 2024/Oct | arXiv | MambaSOD: Dual Mamba-Driven Cross-Modal Fusion Network for RGB-D Salient Object Detection | `RGB-D` `Mamba` `Fusion` | [Paper](https://arxiv.org/abs/2410.15015) / [Code](https://github.com/YueZhan721/MambaSOD) |
| &#x1F7E7;<br><b>RGB-D SOD</b> | 2024/Jun | arXiv | ViDSOD-100: A New Dataset and A Baseline Model for RGB-D Video Salient Object Detection | `RGB-D` `Video` `Dataset` | [Paper](https://arxiv.org/abs/2406.12536) / [Code](https://github.com/jhl-Det/RGBD_Video_SOD) |
| &#x1F7E7;<br><b>RGB-D SOD</b> | TODO | TODO | RGB-D SOD with SAM fine-tuning | `RGB-D` `SAM` `PEFT` | Paper / Code |

## Camouflaged Object Detection

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| &#x1F7E6;<br><b>COD</b> | 2026/Jun | CVPR | Beyond Appearance: Camouflaged Object Detection via Geometric Structure | `Geometry` `DepthSAM` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Han_Beyond_Appearance_Camouflaged_Object_Detection_via_Geometric_Structure_CVPR_2026_paper.html) |
| &#x1F7E6;<br><b>COD</b> | 2025/Aug | arXiv | ArgusCogito: Chain-of-Thought for Cross-Modal Synergy and Omnidirectional Reasoning in Camouflaged Object Segmentation | `VLM` `CoT` `Zero-Shot` | [Paper](https://arxiv.org/abs/2508.18050) |

## Weak / Semi / Unsupervised COD

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| &#x1F7E6;<br><b>COD</b> | 2026/Jun | CVPR | EReCu: Pseudo-label Evolution Fusion and Refinement with Multi-Cue Learning for Unsupervised Camouflage Detection | `Unsupervised` `Pseudo-Label` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Jiang_EReCu_Pseudo-label_Evolution_Fusion_and_Refinement_with_Multi-Cue_Learning_for_CVPR_2026_paper.html) |
| &#x1F7E6;<br><b>COD</b> | 2026/Jun | CVPR | Beyond Weak Supervision: MLLMs-Guided Graded Knowledge Distillation for Unsupervised Camouflaged Object Detection | `Unsupervised` `MLLM` `Distillation` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Chen_Beyond_Weak_Supervision_MLLMs-Guided_Graded_Knowledge_Distillation_for_Unsupervised_Camouflaged_CVPR_2026_paper.html) |
| &#x1F7E6;<br><b>COD</b> | 2024/Aug | arXiv | SAM-COD: SAM-guided Unified Framework for Weakly-Supervised Camouflaged Object Detection | `Weak` `SAM` | [Paper](https://arxiv.org/abs/2408.10760) |

## Open-Vocabulary / Referring COD

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| &#x1F7E6;<br><b>COD</b> | 2026/Jun | CVPR | SDDF: Specificity-Driven Dynamic Focusing for Open-Vocabulary Camouflaged Object Detection | `Open-Vocab` `Text` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Liang_SDDF_Specificity-Driven_Dynamic_Focusing_for_Open-Vocabulary_Camouflaged_Object_Detection_CVPR_2026_paper.html) / [Code](https://github.com/Zh1fen/SDDF) |
| &#x1F7E6;<br><b>COD</b> | 2026/Jun | CVPR | Seeing Both Sides: Towards Bidirectional Semantic Alignment for Open-Vocabulary Camouflaged Object Segmentation | `Open-Vocab` `CLIP` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Zhang_Seeing_Both_Sides_Towards_Bidirectional_Semantic_Alignment_for_Open-Vocabulary_Camouflaged_CVPR_2026_paper.html) / [Code](https://github.com/okmaybach/BaCLIP-CVPR2026) |
| &#x1F7E6;<br><b>COD</b> | 2026/Jun | CVPR | Training-Free Open-Vocabulary Camouflaged Object Segmentation via Fine-Grained Object Binding and Adaptive Hybrid Prompt | `Open-Vocab` `Training-Free` `Prompt` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Ren_Training-Free_Open-Vocabulary_Camouflaged_Object_Segmentation_via_Fine-Grained_Object_Binding_and_CVPR_2026_paper.html) |
| &#x1F7E6;<br><b>COD</b> | 2025/Aug | arXiv | A Simple yet Powerful Instance-Aware Prompting Framework for Training-free Camouflaged Object Segmentation | `Training-Free` `Prompt` `SAM` | [Paper](https://arxiv.org/abs/2508.06904) |
| &#x1F7E6;<br><b>COD</b> | 2025/Jun | arXiv | Open-Vocabulary Camouflaged Object Segmentation with Cascaded Vision Language Models | `Open-Vocab` `VLM` `SAM` | [Paper](https://arxiv.org/abs/2506.19300) |

## SAM and Foundation Models

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| &#x1F7E7;<br><b>RGB-D SOD</b> | 2026/Jun | CVPR | M4-SAM: Multi-Modal Mixture-of-Experts with Memory-Augmented SAM for RGB-D Video Salient Object Detection | `RGB-D` `Video` `SAM2` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Liu_M4-SAM_Multi-Modal_Mixture-of-Experts_with_Memory-Augmented_SAM_for_RGB-D_Video_Salient_CVPR_2026_paper.html) |
| &#x1F7E7;<br><b>RGB-D SOD</b> | 2025/Nov | AAAI | SAM-DAQ: Segment Anything Model with Depth-guided Adaptive Queries for RGB-D Video Salient Object Detection | `RGB-D` `Video` `SAM2` | [Paper](https://arxiv.org/abs/2511.09870) |
| &#x1F7E6;<br><b>COD</b> | 2025/Sep | ACM MM | SAM-TTT: Segment Anything Model via Reverse Parameter Configuration and Test-Time Training for Camouflaged Object Detection | `SAM` `TTA` | [Paper](https://arxiv.org/abs/2509.11884) / [Code](https://github.com/guobaoxiao/SAM-TTT) |
| &#x1F7E8;<br><b>VIDEO</b> | 2025/Mar | arXiv | CamSAM2: Segment Anything Accurately in Camouflaged Videos | `VCOS` `SAM2` `Video` | [Paper](https://arxiv.org/abs/2503.19730) / [Code](https://github.com/zhoustan/CamSAM2) |
| &#x1F7E9;<br><b>SOD</b> | 2024/Aug | ACM MM | Multi-Scale and Detail-Enhanced Segment Anything Model for Salient Object Detection | `SAM` `Adapter` | [Paper](https://arxiv.org/abs/2408.04326) / [Code](https://github.com/BellyBeauty/MDSAM) |
| &#x1F7EA;<br><b>SOD-COD</b> | 2023/Apr | ICCV | Segment Anything | `SAM` `Foundation` | [Paper](https://arxiv.org/abs/2304.02643) / [Project](https://segment-anything.com) |

## Joint SOD-COD / Universal Foreground

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| &#x1F7EA;<br><b>SOD-COD</b> | 2023/Nov | arXiv | VSCode: General Visual Salient and Camouflaged Object Detection with 2D Prompt Learning | `Prompt` `Generalist` | [Paper](https://arxiv.org/abs/2311.15011) / [Code](https://github.com/Sssssuperior/VSCode) |
| &#x1F7EA;<br><b>SOD-COD</b> | TODO | TODO | Joint RGB-D COD and SOD training | `RGB-D` `Multi-Task` | Paper / Code |

## Video and Instance-Level Tasks

Sorted by release date, newest first.

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| &#x1F7E8;<br><b>VIDEO</b> | 2025/Mar | arXiv | CamSAM2: Segment Anything Accurately in Camouflaged Videos | `VCOS` `SAM2` `Video` | [Paper](https://arxiv.org/abs/2503.19730) / [Code](https://github.com/zhoustan/CamSAM2) |
| &#x1F7E6;<br><b>COD</b> | 2023/Aug | ACM MM | A Unified Query-based Paradigm for Camouflaged Instance Segmentation | `CIS` `Query` | [Paper](https://arxiv.org/abs/2308.07392) / [Code](https://github.com/dongbo811/UQFormer) |

## Datasets

| Dataset | Task | Link |
| --- | --- | --- |
| COD10K | COD / COS | [Project](http://mmcheng.net/cod) |
| CAMO / CAMO++ | COD / CIS | [Project](https://sites.google.com/view/ltnghia/research/camo_plus_plus) |
| MoCA-Mask | VCOD | [Project](https://xueliancheng.github.io/SLT-Net-project) |
| SIP | RGB-D SOD | [Project](https://github.com/DengPingFan/D3NetBenchmark) |
| RDVS | RGB-D VSOD | [Project](https://github.com/kerenfu/RDVS/) |
| ViDSOD-100 | RGB-D VSOD | [Code](https://github.com/jhl-Det/RGBD_Video_SOD) |

## Contributing

Contributions are welcome.

Recommended entry format:

```markdown
| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| &#x1F7E6;<br><b>COD</b> | 2026/Jun | CVPR | Paper Title | `SAM` `Open-Vocab` | [Paper](url) / [Code](url) |
```

## Citation

If this repository is useful for your work, please consider starring it and citing the original papers listed here.
