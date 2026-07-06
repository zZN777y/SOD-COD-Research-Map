# SOD-COD Research Map

Papers, datasets, and notes on **Salient Object Detection (SOD)**, **Camouflaged Object Detection (COD)**, RGB-D perception, SAM adaptation, and unified foreground segmentation.

Last updated: 2026-07-06

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## About

I use this repository to keep track of papers and resources related to SOD and COD, especially the topics that connect to my own research: RGB-D SOD, RGB-D COD, SAM-based adaptation, and joint SOD-COD learning.

The list is organized by research direction rather than only by year. I will keep adding papers that I have read or found useful.

Pull requests and paper suggestions are welcome.

## Contents

- [Research Map](#research-map)
- [Legend](#legend)
- [Latest Additions](#latest-additions)
- [Survey and Benchmark Papers](#survey-and-benchmark-papers)
- [RGB-D Salient Object Detection](#rgb-d-salient-object-detection)
- [RGB-D Camouflaged Object Detection](#rgb-d-camouflaged-object-detection)
- [Joint SOD-COD and Universal Foreground Segmentation](#joint-sod-cod-and-universal-foreground-segmentation)
- [Foundation Models and SAM Adaptation](#foundation-models-and-sam-adaptation)
- [Learning Settings](#learning-settings)
- [Datasets](#datasets)
- [Reading Notes](#reading-notes)
- [Contributing](#contributing)

## Research Map

The current structure is:

| Track | Focus | Example Topics |
| --- | --- | --- |
| **SOD** | Detecting visually salient objects | RGB SOD, RGB-D SOD, VSOD, light-field SOD |
| **COD** | Detecting objects hidden in similar backgrounds | COD, COS, VCOD, RGB-D COD |
| **SOD-COD** | Learning common foreground representations across SOD and COD | joint training, universal foreground segmentation, task prompts |
| **Foundation Models** | Adapting SAM and related foundation models | SAM fine-tuning, visual prompts, PEFT, open vocabulary |
| **Cross-Modal Fusion** | Using RGB, depth, motion, text, or frequency cues together | RGB-D fusion, depth reliability, frequency-domain fusion |
| **Efficient Learning** | Reducing annotation or computation cost | weak supervision, semi-supervision, test-time adaptation |

## Legend

I use the following tags to keep the tables short.

| Field | Tags |
| --- | --- |
| Task | `SOD`, `COD`, `SOD-COD`, `RGBD-SOD`, `RGBD-COD`, `VSOD`, `VCOD`, `COS` |
| Modality | `RGB`, `Depth`, `RGB-D`, `Video`, `Text`, `Prompt`, `Thermal`, `LightField` |
| Setting | `Full`, `Survey`, `Weak`, `Semi`, `Unsupervised`, `Zero-Shot`, `Open-Vocab`, `PEFT`, `TTA` |
| Method | `SAM`, `Prompt`, `Fusion`, `Multi-Task`, `Transformer`, `Mamba`, `Diffusion`, `Frequency`, `Boundary`, `Depth-Reliability`, `Benchmark`, `Efficient`, `3D-CNN` |

## Latest Additions

Newly read papers will be added here first, then moved into the corresponding sections.

| Date | Year | Venue | Tags | Paper | Links | Note |
| --- | --- | --- | --- | --- | --- | --- |
| 2026-07-06 | TODO | TODO | `RGBD-SOD` `SAM` `PEFT` | RGB-D SOD with SAM fine-tuning | Paper / Code | To be updated after release |
| 2026-07-06 | TODO | TODO | `SOD-COD` `RGB-D` `Multi-Task` | Joint RGB-D COD and SOD training | Paper / Code | To be updated after release |

## Survey and Benchmark Papers

| Year | Venue | Tags | Paper | Links | Why Read |
| --- | --- | --- | --- | --- | --- |
| 2020 | arXiv | `RGBD-SOD` `Survey` `Benchmark` | RGB-D Salient Object Detection: A Survey | [Paper](https://arxiv.org/abs/2008.00230) / [Project](https://github.com/taozh2017/RGBDSODsurvey) | Good entry point for RGB-D SOD methods, datasets, and evaluation |

## RGB-D Salient Object Detection

| Year | Venue | Tags | Paper | Links | Why Read |
| --- | --- | --- | --- | --- | --- |
| 2020 | arXiv | `RGBD-SOD` `Fusion` `Efficient` | A Unified Structure for Efficient RGB and RGB-D Salient Object Detection | [Paper](https://arxiv.org/abs/2012.00437) | Useful for thinking about unified RGB/RGB-D architectures |
| 2021 | arXiv | `RGBD-SOD` `3D-CNN` `Fusion` | RGB-D Salient Object Detection via 3D Convolutional Neural Networks | [Paper](https://arxiv.org/abs/2101.10241) / [Code](https://github.com/PPOLYpubki/RD3D) | Shows encoder and decoder fusion with 3D convolutions |
| 2023 | arXiv | `RGBD-SOD` `VSOD` `Benchmark` | Salient Object Detection in RGB-D Videos | [Paper](https://arxiv.org/abs/2310.15482) / [Code](https://github.com/kerenfu/RDVS/) | Useful for temporal RGB-D saliency and dataset design |

## RGB-D Camouflaged Object Detection

| Year | Venue | Tags | Paper | Links | Why Read |
| --- | --- | --- | --- | --- | --- |
| TODO | TODO | `RGBD-COD` `Fusion` | Depth-assisted COD papers | Paper / Code | Focus on depth reliability and cross-modal fusion |

## Joint SOD-COD and Universal Foreground Segmentation

| Year | Venue | Tags | Paper | Links | Why Read |
| --- | --- | --- | --- | --- | --- |
| TODO | TODO | `SOD-COD` `Multi-Task` | Joint SOD-COD papers | Paper / Code | Core track for unified salient and concealed foreground learning |
| TODO | TODO | `SOD-COD` `Universal` `Prompt` | Universal foreground segmentation papers | Paper / Code | Useful for task prompts and foreground generalization |

## Foundation Models and SAM Adaptation

| Year | Venue | Tags | Paper | Links | Why Read |
| --- | --- | --- | --- | --- | --- |
| TODO | TODO | `SAM` `RGBD-SOD` `PEFT` | SAM adaptation for RGB-D SOD | Paper / Code | Closely related to RGB-D SOD with foundation models |
| TODO | TODO | `SAM` `COD` `Prompt` | SAM adaptation for COD/COS | Paper / Code | Good place for prompt, mask, and adapter methods |
| TODO | TODO | `VLM` `Open-Vocab` `SOD-COD` | Vision-language models for foreground segmentation | Paper / Code | Track open-vocabulary and language-guided methods |

## Learning Settings

| Setting | What to Collect |
| --- | --- |
| Fully supervised | Strong baselines and high-performance architectures |
| Weakly supervised | Scribble, point, box, text, pseudo-mask, and SAM-assisted supervision |
| Semi-supervised | Teacher-student, consistency, pseudo-label refinement |
| Unsupervised | Discovery, clustering, self-training, generative priors |
| Zero-shot / open-vocabulary | Prompting, VLM/MLLM priors, class-text interaction |
| Test-time adaptation | Online adaptation, domain shift, reliability-aware inference |

## Datasets

Dataset entries live in [`data/datasets.yaml`](data/datasets.yaml). Useful fields include:

- task and modality;
- train/test split if available;
- annotation type;
- project link;
- license or usage note when known.

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
| Year | Venue | Tags | Paper | Links | Why Read |
| --- | --- | --- | --- | --- | --- |
| 2026 | CVPR | `SOD-COD` `SAM` `Prompt` | Paper Title | [Paper](url) / [Code](url) | One short reason |
```

## Citation

If this repository is useful for your work, please consider starring it and citing the original papers listed here.
