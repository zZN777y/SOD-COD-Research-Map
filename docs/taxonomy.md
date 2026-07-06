# Taxonomy

This is the tag set used in this repository. A paper can have multiple tags.

## Task Tags

| Tag | Meaning |
| --- | --- |
| `SOD` | Salient Object Detection |
| `COD` | Camouflaged Object Detection |
| `COS` | Camouflaged Object Segmentation |
| `SOD-COD` | Joint or universal modeling of salient and camouflaged objects |
| `RGBD-SOD` | RGB-D Salient Object Detection |
| `RGBD-COD` | RGB-D Camouflaged Object Detection |
| `VSOD` | Video Salient Object Detection |
| `VCOD` | Video Camouflaged Object Detection |

## Modality Tags

| Tag | Meaning |
| --- | --- |
| `RGB` | RGB image input |
| `Depth` | Depth-only cue or depth supervision |
| `RGB-D` | RGB and depth input |
| `Video` | Temporal frames or motion cues |
| `Text` | Language or category text |
| `Prompt` | Points, boxes, masks, text prompts, or learned prompts |
| `Thermal` | Thermal/infrared input |
| `LightField` | Light-field input |

## Setting Tags

| Tag | Meaning |
| --- | --- |
| `Full` | Fully supervised training |
| `Survey` | Survey, review, or benchmark-summary paper |
| `Weak` | Weak labels such as scribbles, boxes, points, or image-level labels |
| `Semi` | Semi-supervised learning |
| `Unsupervised` | No manual object masks for the target task |
| `Zero-Shot` | No target-task training |
| `Open-Vocab` | Open-vocabulary or class-generalized inference |
| `PEFT` | Parameter-efficient fine-tuning |
| `TTA` | Test-time adaptation |
| `Training-Free` | No target-task training or fine-tuning |

## Method Tags

| Tag | Meaning |
| --- | --- |
| `SAM` | Segment Anything Model or SAM-style promptable segmentation |
| `SAM2` | Segment Anything Model 2 |
| `CLIP` | CLIP-style image-text alignment |
| `Foundation` | Foundation segmentation or vision-language model |
| `VLM` | Vision-language model |
| `MLLM` | Multimodal large language model |
| `Prompt` | Manual, visual, text, or learned prompt design |
| `Fusion` | Multi-modal or multi-level feature fusion |
| `Multi-Task` | Joint training across multiple tasks or datasets |
| `Efficient` | Lightweight, efficient, or resource-aware design |
| `Real-Time` | Real-time or speed-oriented design |
| `3D-CNN` | 3D convolutional modeling |
| `Detection` | Detection-oriented formulation or output |
| `Geometry` | Geometric structure, depth geometry, or shape priors |
| `Distillation` | Teacher-student or knowledge distillation |
| `Pseudo-Label` | Pseudo-label generation or refinement |
| `Uncertainty` | Uncertainty modeling |
| `Scale` | Multi-scale or scale-aware modeling |
| `Motion` | Motion modeling for video tasks |
| `Adapter` | Adapter-based tuning or lightweight adaptation |
| `Transformer` | Transformer-based architecture |
| `Mamba` | State-space model or Mamba-based architecture |
| `Diffusion` | Diffusion model or generative prior |
| `Frequency` | Frequency-domain modeling |
| `Boundary` | Boundary, contour, or structure-aware modeling |
| `Depth-Reliability` | Explicit depth quality or reliability estimation |
| `Benchmark` | Dataset, benchmark, evaluation protocol, or leaderboard resource |
| `Dataset` | Dataset paper or dataset resource |

## Recommended Placement

When one paper fits multiple sections, place it where it will be easiest to find.

Examples:

- A fully supervised RGB-D SOD paper should go under **RGB-D Salient Object Detection**.
- A SAM-based COD paper should go under **Foundation Models and SAM Adaptation**.
- A model trained jointly on SOD and COD should go under **Joint SOD-COD and Universal Foreground Segmentation** even if it uses SAM.
- A paper mainly introducing a dataset should also be listed in `data/datasets.yaml`.
