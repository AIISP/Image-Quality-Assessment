# 图像质量评估（IQA）算法整理

本文档按方法论和应用场景对图像质量评估算法进行分类整理，涵盖无参考（NR）、有参考（FR）及多模态等方向。所有条目均标注论文链接、实现代码及引用信息。

---

## 1. ROI-based IQA（兴趣区域质量评估）  
**核心目标：** 专注于图像特定区域的质量评价  
**代表性方法：**  
| 论文链接 | 方法 | 类型 | 发表年份 | 代码 | BibTeX | 关键词 |  
|----------|------|------|----------|------|--------|--------|  
| [arXiv](https://arxiv.org/abs/2411.10161) | SEAGULL | 无参考 | 2024 | [GitHub](https://github.com/chencn2020/SEAGULL) | [Bibtex](./iqa_ref.bib#L1081-L1089) | 视觉语言指令调优 |  

---

## 2. Unified IQA（统一质量评估模型）  
**核心目标：** 单一模型处理所有IQA类型  
**代表性方法：**  
| 论文链接 | 方法 | 类型 | 发表年份 | 代码 | BibTeX | 关键词 |  
|----------|------|------|----------|------|--------|--------|  
| [arXiv](https://arxiv.org/abs/2403.04993) | PromptIQA | 无参考/有参考 | ECCV2024 | 无 | [Bibtex](./iqa_ref.bib#L931-L938) | 提示增强跨域适配 |  
| [arXiv](https://arxiv.org/abs/2312.17090) | Q-Align | 无参考/有参考 | ICML2024 | [GitHub](https://github.com/TianheWu/MLLMs-for-IQA) | [Bibtex](./iqa_ref.bib#L867-L874) | 文本定义的离散评分层级 |  

---

## 3. Explainable IQA（可解释质量评估）  
**核心目标：** 通过多模态模型生成人类可理解的评估结果  
**代表性方法：**  
| 论文链接 | 方法 | 类型 | 发表年份 | 代码 | BibTeX | 关键词 |  
|----------|------|------|----------|------|--------|--------|  
| [arXiv](https://arxiv.org/pdf/2503.22679) | Q-Insight | 无参考 | 2025 | [GitHub](https://github.com/lwq20020127/Q-Insight) | [Bibtex](./iqa_ref.bib#L1107-L1112) | 可视化强化学习 |  
| [arXiv](https://arxiv.org/abs/2407.17035) | Q-Ground | 无参考 | ACM MM2024 | [GitHub](https://github.com/Q-Future/Q-Ground) | [Bibtex](./iqa_ref.bib#L1002-L1007) | 质量定位与多模态基准 |  

---

## 4. AIGC IQA（AI生成内容质量评估）  
**核心目标：** 针对AI生成图像的特殊质量需求设计  
**代表性方法：**  
| 论文链接 | 方法 | 类型 | 发表年份 | 代码 | BibTeX | 关键词 |  
|----------|------|------|----------|------|--------|--------|  
| [arXiv](https://arxiv.org/abs/2312.10240) | 丰富人类反馈 | 无参考 | CVPR2024（最佳论文） | [GitHub](https://github.com/google-research-datasets/richhf-18k) | [Bibtex](./iqa_ref.bib#L1067-L1072) | 文本-图像生成偏好建模 |  
| [arXiv](https://arxiv.org/abs/2304.05977) | ImageReward | 有参考 | NeurIPS2023 | [GitHub](https://github.com/THUDM/ImageReward) | [Bibtex](./iqa_ref.bib#L817-L822) | 人类偏好对齐 |  

---

## 5. 无参考质量评估（NR-IQA）  
**核心目标：** 不依赖原始参考图像的盲质量评估  
**代表性方法：**  
| 论文链接 | 方法 | 类型 | 发表年份 | 代码 | BibTeX | 关键词 |  
|----------|------|------|----------|------|--------|--------|  
| [arXiv](https://arxiv.org/abs/2406.09546) | Q-Mamba | 无参考 | 2024 | 无 | [Bibtex](./iqa_ref.bib#L980-L986) | 视觉Mamba架构 |  
| [arXiv](https://arxiv.org/abs/2403.11176) | QualiCLIP | 无参考 | 2024 | [GitHub](https://github.com/miccunifi/QualiCLIP) | [Bibtex](./iqa_ref.bib#L950-L955) | 质量文本对齐 |  
| [arXiv](https://arxiv.org/abs/2108.07948) | CKDN | 无参考 | ICCV2021 | [GitHub](https://github.com/researchmm/CKDN) | [Bibtex](./iqa_ref.bib#L752-L761) | 退化参考蒸馏 |  

---

## 6. 有参考质量评估（FR-IQA）  
**核心目标：** 基于原始参考图像的精细质量对比  
**代表性方法：**  
| 论文链接 | 方法 | 类型 | 发表年份 | 代码 | BibTeX | 关键词 |  
|----------|------|------|----------|------|--------|--------|  
| [arXiv](https://arxiv.org/abs/2211.05215) | Shift-tolerant LPIPS | 有参考 | ECCV2022 | [GitHub](https://github.com/abhijay9/ShiftTolerant-LPIPS) | [Bibtex](./iqa_ref.bib#L931-L938) | 位移容忍感知相似性 |  
| [arXiv](https://arxiv.org/abs/2104.14730) | IQT | 有参考 | CVPRW2021 | [GitHub](https://github.com/anse3832/IQT) | [Bibtex](./iqa_ref.bib#L713-L721) | 变换器结构 |  

---

## 7. 其他专门领域  
### 色彩质量评估  
| 论文链接 | 方法 | 类型 | 发表年份 | 代码 | BibTeX | 关键词 |  
|----------|------|------|----------|------|--------|--------|  
| [arXiv](https://arxiv.org/abs/2407.10181) | 多尺度沃瑟斯坦距离 | N/A | 2024 | [GitHub](https://github.com/real-hjq/MS-SWD) | [Bibtex](./iqa_ref.bib#L1051-L1058) | 色彩差异感知模型 |  

### 面部图像质量评估  
| 论文链接 | 方法 | 类型 | 发表年份 | 代码 | BibTeX | 关键词 |  
|----------|------|------|----------|------|--------|--------|  
| [arXiv](https://arxiv.org/abs/2406.09622) | DSL-FIQA | 无参考 | CVPR2024 | [Project](https://dsl-fiqa.github.io/) | [Bibtex](./iqa_ref.bib#L973-L978) | 双集退化学习、关键点引导 |  

---

