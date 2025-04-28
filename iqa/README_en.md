# Image Quality Assessment (IQA) Algorithms Overview

This document categorizes IQA algorithms based on their methodologies and application domains. All entries are organized by their reference type (NR/FR) and specialized subfields. Code and Bibtex links are provided where available.

---

## 1. ROI-based IQA  
**Focus:** Quality assessment for specific regions of interest (ROI).  
**Key Methods:**  
| Paper Link | Method       | Type | Conference/Journal | Code          | Bibtex Link               | Keywords                |
|------------|--------------|------|---------------------|---------------|--------------------------|-------------------------|
| [arXiv](https://arxiv.org/abs/2411.10161) | SEAGULL | NR | Arxiv 2024 | [GitHub](https://github.com/chencn2020/SEAGULL) | [Bibtex](./iqa_ref.bib#L1081-L1089) | Vision-Language, ROI Scoring |

---

## 2. Unified IQA  
**Focus:** Single model architectures for all IQA types (NR/FR/RR).  
**Key Methods:**  
| Paper Link | Method       | Type | Conference/Journal | Code          | Bibtex Link               | Keywords                |
|------------|--------------|------|---------------------|---------------|--------------------------|-------------------------|
| [arXiv](https://arxiv.org/abs/2403.04993) | PromptIQA | NR/FR | ECCV 2024 | N/A | [Bibtex](./iqa_ref.bib#L931-L938) | Prompt-based, Cross-domain Adaptation |
| [arXiv](https://arxiv.org/abs/2312.17090) | Q-Align | NR/FR | ICML 2024 | [GitHub](https://github.com/TianheWu/MLLMs-for-IQA) | [Bibtex](./iqa_ref.bib#L867-L874) | Multimodal LLMs, Discrete Level Scoring |

---

## 3. Explainable IQA  
**Focus:** Human-interpretable quality assessment using LLMs.  
**Key Methods:**  
| Paper Link | Method       | Type | Conference/Journal | Code          | Bibtex Link               | Keywords                |
|------------|--------------|------|---------------------|---------------|--------------------------|-------------------------|
| [arXiv](https://arxiv.org/pdf/2503.22679) | Q-Insight | NR | TPAMI 2025 | [GitHub](https://github.com/lwq20020127/Q-Insight) | [Bibtex](./iqa_ref.bib#L1107-L1112) | Reinforcement Learning, Visual Explanation |
| [arXiv](https://arxiv.org/abs/2407.17035) | Q-Ground | NR | ACM MM2024 | [GitHub](https://github.com/Q-Future/Q-Ground) | [Bibtex](./iqa_ref.bib#L1002-L1007) | Grounding Mechanism, Quality Localization |
| [arXiv](https://arxiv.org/abs/2312.08962) | Depicting Beyond Scores | NR | ECCV 2024 | [Project](https://depictqa.github.io/) | [Bibtex](./iqa_ref.bib#L885-L890) | Multimodal Language Grounding |

---

## 4. AIGC IQA  
**Focus:** Quality assessment for AI-generated content.  
**Key Methods:**  
| Paper Link | Method       | Type | Conference/Journal | Code          | Bibtex Link               | Keywords                |
|------------|--------------|------|---------------------|---------------|--------------------------|-------------------------|
| [arXiv](https://arxiv.org/abs/2312.10240) | Rich Human Feedback | NR | CVPR 2024 (Best Paper) | [GitHub](https://github.com/google-research-datasets/richhf-18k) | [Bibtex](./iqa_ref.bib#L1067-L1072) | Human-in-the-loop, Text-to-Image Evaluation |
| [arXiv](https://arxiv.org/abs/2303.11897) | TIFA | NR | ICCV 2023 | [GitHub](https://github.com/Yushi-Hu/tifa) | [Bibtex](./iqa_ref.bib#L840-L846) | Faithfulness Measurement via QA |
| [arXiv](https://arxiv.org/abs/2304.05977) | ImageReward | FR | NeurIPS 2023 | [GitHub](https://github.com/THUDM/ImageReward) | [Bibtex](./iqa_ref.bib#L817-L822) | Perceptual Preference Learning |

---

## 5. No Reference (NR) IQA  
**Focus:** Quality assessment without access to reference images.  
**Key Methods:**  
| Paper Link | Method       | Type | Conference/Journal | Code          | Bibtex Link               | Keywords                |
|------------|--------------|------|---------------------|---------------|--------------------------|-------------------------|
| [arXiv](https://arxiv.org/abs/2406.09546) | Q-Mamba | NR | Arxiv 2024 | N/A | [Bibtex](./iqa_ref.bib#L980-L986) | Vision Mamba Architecture |
| [arXiv](https://arxiv.org/abs/2405.19298) | Adaptive IQA | NR | Arxiv 2024 | N/A | [Bibtex](./iqa_ref.bib#L964-L971) | LLM-based Comparative Learning |
| [arXiv](https://arxiv.org/abs/2403.11176) | QualiCLIP | NR | Arxiv 2024 | [GitHub](https://github.com/miccunifi/QualiCLIP) | [Bibtex](./iqa_ref.bib#L950-L955) | Quality-aware Image-Text Alignment |
| [arXiv](https://arxiv.org/abs/2406.01020) | ATTIQA | NR | ACCV 2024 | N/A | [Bibtex](./iqa_ref.bib#L1091-L1098) | Attribute-aware Pretraining |
| [arXiv](https://arxiv.org/abs/2405.04167) | BSA (Blind Super-Resolution Adaptation) | NR | CVPR 2024 | N/A | [Bibtex](./iqa_ref.bib#L956-L961) | Domain Adaptation for SR |
| [arXiv](https://arxiv.org/abs/2308.12001) | LFE-Transformer | NR | CVPR 2024 | N/A | [Bibtex](./iqa_ref.bib#L915-L920) | Local Feature Enhancement |
| [arXiv](https://arxiv.org/abs/2310.14918) | ARNIQA | NR | WACV 2024 | [GitHub](https://github.com/miccunifi/ARNIQA) | [Bibtex](./iqa_ref.bib#L858-L865) | Distortion Manifold Learning |

---

## 6. Full Reference (FR) IQA  
**Focus:** Quality assessment using pristine reference images.  
**Key Methods:**  
| Paper Link | Method       | Type | Conference/Journal | Code          | Bibtex Link               | Keywords                |
|------------|--------------|------|---------------------|---------------|--------------------------|-------------------------|
| [arXiv](https://arxiv.org/abs/2211.05215) | Shift-tolerant LPIPS | FR | ECCV 2022 | [GitHub](https://github.com/abhijay9/ShiftTolerant-LPIPS) | [Bibtex](./iqa_ref.bib#L931-L938) | Robust Perceptual Similarity |
| [arXiv](https://arxiv.org/abs/2207.08689) | SRIF | FR | ACM MM2022 | [GitHub](https://github.com/weizhou-geek/SRIF) | [Bibtex](./iqa_ref.bib#L709-L714) | Super-Resolution Fidelity |
| [arXiv](https://arxiv.org/abs/2104.14730) | IQT | FR | CVPRW2021 | [GitHub](https://github.com/anse3832/IQT) | [Bibtex](./iqa_ref.bib#L713-L721) | Transformer-based Metric |
| [arXiv](https://arxiv.org/abs/1801.03924) | LPIPS | FR | CVPR 2018 | [Project](https://richzhang.github.io/PerceptualSimilarity/) | [Bibtex](./iqa_ref.bib#L142-L149) | Perceptual Similarity Loss |

---

## 7. Image Aesthetic Assessment  
**Focus:** Evaluating artistic/aesthetic merits of images.  
**Key Methods:**  
| Paper Link | Method       | Type | Conference/Journal | Code          | Bibtex Link               | Keywords                |
|------------|--------------|------|---------------------|---------------|--------------------------|-------------------------|
| [arXiv](https://arxiv.org/abs/2504.02522) | Charm | NR | CVPR2025 | [GitHub](https://github.com/FBehrad/Charm) | [Bibtex](./iqa_ref.bib#L1114-L1119) | Vision Transformer Fine-tuning |
| [arXiv](https://arxiv.org/abs/2303.14302) | VILA | NR | CVPR2023 | N/A | [Bibtex](./iqa_ref.bib#L784-L789) | Vision-Language Pretraining |

---

## 8. Specialized Domains & Techniques  
### Color IQA  
| Paper Link | Method       | Type | Conference/Journal | Code          | Bibtex Link               | Keywords                |
|------------|--------------|------|---------------------|---------------|--------------------------|-------------------------|
| [arXiv](https://arxiv.org/abs/2407.10181) | MS-SWD | N/A | ECCV 2024 | [GitHub](https://github.com/real-hjq/MS-SWD) | [Bibtex](./iqa_ref.bib#L1051-L1058) | Color Difference Metrics |

### Face IQA  
| Paper Link | Method       | Type | Conference/Journal | Code          | Bibtex Link               | Keywords                |
|------------|--------------|------|---------------------|---------------|--------------------------|-------------------------|
| [arXiv](https://arxiv.org/abs/2406.09622) | DSL-FIQA | NR | CVPR2024 | [Project](https://dsl-fiqa.github.io/) | [Bibtex](./iqa_ref.bib#L973-L978) | Facial Landmark Guidance |

### 360° Image IQA  
| Paper Link | Method       | Type | Conference/Journal | Code          | Bibtex Link               | Keywords                |
|------------|--------------|------|---------------------|---------------|--------------------------|-------------------------|
| [arXiv](https://arxiv.org/abs/2305.10983) | Assessor360 | NR | NeurIPS2023 | [GitHub](https://github.com/TianheWu/Assessor360) | [Bibtex](./iqa_ref.bib#L995-L1000) | Omnidirectional Quality |

### Adversarial Defense  
| Paper Link | Method       | Type | Conference/Journal | Code          | Bibtex Link               | Keywords                |
|------------|--------------|------|---------------------|---------------|--------------------------|-------------------------|
| [arXiv](https://arxiv.org/abs/2408.01541) | IQ Guardians | N/A | Arxiv2024 | [GitHub](https://github.com/msu-video-group/adversarial-defenses-for-iqa) | [Bibtex](./iqa_ref.bib#L1027-L1035) | Adversarial Attack Defense |

### Loss Functions  
| Paper Link | Method       | Conference/Journal | Code          | Keywords                |
|------------|--------------|---------------------|---------------|-------------------------|
| [arXiv](https://arxiv.org/abs/2008.03889) | NiNLoss | AAAI2020 | [GitHub](https://github.com/lidq92/LinearityIQA) | Norm-in-Norm Regularization |

---
