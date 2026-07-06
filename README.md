# SOD-COD Research Map

Curated papers, datasets, and resources for **Salient Object Detection (SOD)**, **Camouflaged Object Detection (COD)**, RGB-D perception, SAM adaptation, and unified foreground segmentation.

Last updated: 2026-07-06

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Why This List

Most existing lists are either SOD-centric or COD-centric. This repository is designed as a bridge:

- **SOD side:** salient object detection, RGB-D SOD, video SOD, light-field SOD.
- **COD side:** camouflaged object detection, camouflaged segmentation, RGB-D COD, video COD.
- **Bridge side:** joint SOD-COD training, universal foreground segmentation, SAM/Segment Anything adaptation, prompt tuning, multi-task learning, and open-vocabulary settings.

The goal is not to be a duplicate paper dump. Each entry should help readers answer: *what problem does this paper study, what modality does it use, and why is it useful for SOD-COD research?*

Suggested repository description:

> Curated papers, datasets, and resources for SOD, COD, RGB-D perception, SAM adaptation, and unified foreground segmentation.

Suggested GitHub topics:

`awesome-list`, `salient-object-detection`, `camouflaged-object-detection`, `rgb-d`, `sod`, `cod`, `sam`, `segment-anything`, `computer-vision`, `paper-list`

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

This repository uses a taxonomy-first structure so that papers can be found by research intent, not only by publication year.

| Track | Typical Questions | Example Topics |
| --- | --- | --- |
| **SOD** | What makes an object visually salient? | RGB SOD, RGB-D SOD, VSOD, light-field SOD |
| **COD** | How can hidden or camouflaged targets be separated from background? | COD, COS, VCOD, RGB-D COD |
| **SOD-COD Bridge** | Can one model handle both salient and concealed foregrounds? | joint training, universal foreground segmentation, task prompting |
| **Foundation Models** | How can SAM/VLM/MLLM priors be adapted? | SAM fine-tuning, visual prompts, PEFT, open vocabulary |
| **Cross-Modal Fusion** | When and how should RGB, depth, text, motion, or frequency cues interact? | RGB-D fusion, depth reliability, frequency-domain fusion |
| **Efficient Learning** | How can we reduce annotation or compute cost? | weak/semi/unsupervised learning, test-time adaptation, lightweight models |

## Legend

Use compact tags to make entries easy to scan.

| Field | Tags |
| --- | --- |
| Task | `SOD`, `COD`, `SOD-COD`, `RGBD-SOD`, `RGBD-COD`, `VSOD`, `VCOD`, `COS` |
| Modality | `RGB`, `Depth`, `RGB-D`, `Video`, `Text`, `Prompt`, `Thermal`, `LightField` |
| Setting | `Full`, `Survey`, `Weak`, `Semi`, `Unsupervised`, `Zero-Shot`, `Open-Vocab`, `PEFT`, `TTA` |
| Method | `SAM`, `Prompt`, `Fusion`, `Multi-Task`, `Transformer`, `Mamba`, `Diffusion`, `Frequency`, `Boundary`, `Depth-Reliability`, `Benchmark`, `Efficient`, `3D-CNN` |

## Latest Additions

Add newly read papers here first, then move them into the stable sections below.

| Date | Year | Venue | Tags | Paper | Links | Note |
| --- | --- | --- | --- | --- | --- | --- |
| 2026-07-06 | TODO | TODO | `RGBD-SOD` `SAM` `PEFT` | Your first paper: RGB-D SOD with SAM fine-tuning | Paper / Code | Add after public release |
| 2026-07-06 | TODO | TODO | `SOD-COD` `RGB-D` `Multi-Task` | Your second paper: joint RGB-D COD and SOD training | Paper / Code | Add after public release |

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
| TODO | TODO | `RGBD-COD` `Fusion` | Add depth-assisted COD papers here | Paper / Code | Focus on depth reliability and cross-modal fusion |

## Joint SOD-COD and Universal Foreground Segmentation

| Year | Venue | Tags | Paper | Links | Why Read |
| --- | --- | --- | --- | --- | --- |
| TODO | TODO | `SOD-COD` `Multi-Task` | Add joint SOD-COD papers here | Paper / Code | Core track for unified salient and concealed foreground learning |
| TODO | TODO | `SOD-COD` `Universal` `Prompt` | Add universal foreground segmentation papers here | Paper / Code | Useful for task prompts and foreground generalization |

## Foundation Models and SAM Adaptation

| Year | Venue | Tags | Paper | Links | Why Read |
| --- | --- | --- | --- | --- | --- |
| TODO | TODO | `SAM` `RGBD-SOD` `PEFT` | SAM adaptation for RGB-D SOD | Paper / Code | Keep papers related to your first work here |
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

Dataset entries live in [`data/datasets.yaml`](data/datasets.yaml). Prefer adding:

- task and modality;
- train/test split if available;
- annotation type;
- project link;
- license or usage note when known.

## Reading Notes

Use [`docs/reading-note-template.md`](docs/reading-note-template.md) for papers you care about. A useful note should record:

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

If this repository helps your research, please consider starring it and citing the original papers listed here.
