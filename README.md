# SOD-COD Research Map

Papers, datasets, and notes on **Salient Object Detection (SOD)**, **Camouflaged Object Detection (COD)**, RGB-D perception, SAM adaptation, and unified foreground segmentation.

Last updated: 2026-07-06

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## About

I use this repository to keep track of papers and resources related to SOD and COD, especially the topics that connect to my own research: RGB-D SOD, RGB-D COD, SAM-based adaptation, and joint SOD-COD learning.

To avoid repeating the same paper in many sections, each paper is assigned one **primary task color**. Extra information such as `RGB-D`, `SAM`, `Open-Vocab`, or `Unsupervised` is kept in the tag column.

Pull requests and paper suggestions are welcome.

## Contents

- [Color Labels](#color-labels)
- [CVPR 2026](#cvpr-2026)
- [Paper List](#paper-list)
- [Surveys and Datasets](#surveys-and-datasets)
- [Reading Notes](#reading-notes)
- [Contributing](#contributing)

## Color Labels

| Label | Scope |
| --- | --- |
| ![SOD](https://img.shields.io/badge/-SOD-2EA44F?style=flat-square) | Salient object detection |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | Camouflaged object detection / segmentation |
| ![SOD-COD](https://img.shields.io/badge/-SOD--COD-8E44AD?style=flat-square) | Joint or unified SOD-COD learning |
| ![RGBD-SOD](https://img.shields.io/badge/-RGBD--SOD-F2994A?style=flat-square) | RGB-D salient object detection |
| ![RGBD-COD](https://img.shields.io/badge/-RGBD--COD-D35400?style=flat-square) | RGB-D camouflaged object detection |
| ![SURVEY](https://img.shields.io/badge/-SURVEY-6C757D?style=flat-square) | Survey, benchmark, or dataset paper |

## CVPR 2026

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2026/Jun | CVPR | SDDF: Specificity-Driven Dynamic Focusing for Open-Vocabulary Camouflaged Object Detection | `Open-Vocab` `Text` `Detection` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Liang_SDDF_Specificity-Driven_Dynamic_Focusing_for_Open-Vocabulary_Camouflaged_Object_Detection_CVPR_2026_paper.html) / [Code](https://github.com/Zh1fen/SDDF) |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2026/Jun | CVPR | Seeing Both Sides: Towards Bidirectional Semantic Alignment for Open-Vocabulary Camouflaged Object Segmentation | `Open-Vocab` `Text` `SAM` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Zhang_Seeing_Both_Sides_Towards_Bidirectional_Semantic_Alignment_for_Open-Vocabulary_Camouflaged_CVPR_2026_paper.html) / [Code](https://github.com/okmaybach/BaCLIP-CVPR2026) |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2026/Jun | CVPR | Beyond Appearance: Camouflaged Object Detection via Geometric Structure | `Depth` `SAM` `Geometry` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Han_Beyond_Appearance_Camouflaged_Object_Detection_via_Geometric_Structure_CVPR_2026_paper.html) |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2026/Jun | CVPR | Training-Free Open-Vocabulary Camouflaged Object Segmentation via Fine-Grained Object Binding and Adaptive Hybrid Prompt | `Open-Vocab` `Training-Free` `SAM` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Ren_Training-Free_Open-Vocabulary_Camouflaged_Object_Segmentation_via_Fine-Grained_Object_Binding_and_CVPR_2026_paper.html) |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2026/Jun | CVPR | Beyond Weak Supervision: MLLMs-Guided Graded Knowledge Distillation for Unsupervised Camouflaged Object Detection | `Unsupervised` `MLLM` `SAM` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Chen_Beyond_Weak_Supervision_MLLMs-Guided_Graded_Knowledge_Distillation_for_Unsupervised_Camouflaged_CVPR_2026_paper.html) |
| ![RGBD-SOD](https://img.shields.io/badge/-RGBD--SOD-F2994A?style=flat-square) | 2026/Jun | CVPR | M4-SAM: Multi-Modal Mixture-of-Experts with Memory-Augmented SAM for RGB-D Video Salient Object Detection | `RGB-D` `Video` `SAM2` `PEFT` | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Liu_M4-SAM_Multi-Modal_Mixture-of-Experts_with_Memory-Augmented_SAM_for_RGB-D_Video_Salient_CVPR_2026_paper.html) |

## Paper List

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| ![RGBD-SOD](https://img.shields.io/badge/-RGBD--SOD-F2994A?style=flat-square) | 2023/Oct | arXiv | Salient Object Detection in RGB-D Videos | `RGB-D` `Video` `Benchmark` | [Paper](https://arxiv.org/abs/2310.15482) / [Code](https://github.com/kerenfu/RDVS/) |
| ![RGBD-SOD](https://img.shields.io/badge/-RGBD--SOD-F2994A?style=flat-square) | 2021/Jan | arXiv | RGB-D Salient Object Detection via 3D Convolutional Neural Networks | `RGB-D` `3D-CNN` `Fusion` | [Paper](https://arxiv.org/abs/2101.10241) / [Code](https://github.com/PPOLYpubki/RD3D) |
| ![RGBD-SOD](https://img.shields.io/badge/-RGBD--SOD-F2994A?style=flat-square) | 2020/Dec | arXiv | A Unified Structure for Efficient RGB and RGB-D Salient Object Detection | `RGB-D` `RGB` `Efficient` | [Paper](https://arxiv.org/abs/2012.00437) |
| ![SOD-COD](https://img.shields.io/badge/-SOD--COD-8E44AD?style=flat-square) | TODO | TODO | Joint RGB-D COD and SOD training | `RGB-D` `Multi-Task` | Paper / Code |
| ![RGBD-SOD](https://img.shields.io/badge/-RGBD--SOD-F2994A?style=flat-square) | TODO | TODO | RGB-D SOD with SAM fine-tuning | `RGB-D` `SAM` `PEFT` | Paper / Code |

## Surveys and Datasets

| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| ![SURVEY](https://img.shields.io/badge/-SURVEY-6C757D?style=flat-square) | 2020/Aug | arXiv | RGB-D Salient Object Detection: A Survey | `RGBD-SOD` `Survey` `Benchmark` | [Paper](https://arxiv.org/abs/2008.00230) / [Project](https://github.com/taozh2017/RGBDSODsurvey) |
| ![SURVEY](https://img.shields.io/badge/-SURVEY-6C757D?style=flat-square) | 2023/Oct | arXiv | Salient Object Detection in RGB-D Videos | `RGB-D` `Video` `Dataset` | [Paper](https://arxiv.org/abs/2310.15482) / [Code](https://github.com/kerenfu/RDVS/) |

Dataset entries are also kept in [`data/datasets.yaml`](data/datasets.yaml).

## Reading Notes

For papers that are worth reading carefully, I use [`docs/reading-note-template.md`](docs/reading-note-template.md). A note usually records:

- the paper's core problem;
- its main idea in one sentence;
- what it teaches for SOD, COD, or SOD-COD;
- limitations or possible follow-up ideas;
- whether code, data, or pretrained weights are available.

## Contributing

Contributions are welcome. Please read [`CONTRIBUTING.md`](CONTRIBUTING.md) before opening a pull request.

Recommended entry format:

```markdown
| Task | Release | Pub. | Title | Tags | Links |
| --- | --- | --- | --- | --- | --- |
| ![COD](https://img.shields.io/badge/-COD-2F80ED?style=flat-square) | 2026/Jun | CVPR | Paper Title | `SAM` `Open-Vocab` | [Paper](url) / [Code](url) |
```

## Citation

If this repository is useful for your work, please consider starring it and citing the original papers listed here.
