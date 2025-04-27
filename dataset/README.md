# Awesome Image Quality Assessment 


## 1、IQA dataset
| Dataset Name       | Type | Published | Website                                                                 | Images       | Annotations                   |
|---------------------|------|-----------|-------------------------------------------------------------------------|--------------|-------------------------------|
| UHD-IQA            | NR   | 2024      | [Project](https://database.mmsp-kn.de/uhd-iqa-benchmark-database.html) | 6k (4K)      | 20 ratings per image          |
| AGIQA-3k           | NR   | 2023      | [GitHub](https://github.com/lcysyzxdxc/AGIQA-3k-Database)              | 3k           | Multi-dimensional annotations|
| SPAQ               | NR   | 2020      | [GitHub](https://github.com/h4nwei/SPAQ)                                | 11k          | Smartphone photography metrics|
| KonIQ-10k          | NR   | 2020      | [Project](http://database.mmsp-kn.de/koniq-10k-database.html)         | 10k          | 1.2M MOS ratings              |
| PIPAL              | FR   | 2020      | [Project](https://www.jasongt.com/projectpages/pipal.html)             | 250 ref      | 1.13M pairwise comparisons    |
| KADID-10k          | FR   | 2019      | [Project](http://database.mmsp-kn.de/kadid-10k-database.html)          | 81 ref       | 10k distortions               |
| LIVE IQA           | FR   | 2006      | [Project](https://live.ece.utexas.edu/research/Quality/subjective.htm)| 29 ref       | 780 distortions               |


---

## 2、dataset

| Dataset Name       | Type | Published | Website                                                                 | Images       | Annotations       |
|---------------------|------|-----------|-------------------------------------------------------------------------|--------------|-------------------|
| BAPPS (LPIPS)      | FR   | 2018      | [Project](https://richzhang.github.io/PerceptualSimilarity/)           | 187.7k       | 484k comparisons  |
| PieAPP             | FR   | 2018      | [Project](http://civc.ucsb.edu/graphics/Papers/CVPR2018_PieAPP/)       | 200 ref      | 2.3M rankings     |


---

## 3、medical dataset

| Dataset Name       | Type | Published | Description                                                                 |
|---------------------|------|-----------|-----------------------------------------------------------------------------|
| FOCUS-MUSE DWI     | NR   | 2025      | MRI直肠癌影像质量评估，含深度学习重建技术验证数据 [10](@ref)                     |


---

## 4、other dataset

| Dataset Name       | Type | Published | Highlights                                                                 |
|---------------------|------|-----------|-----------------------------------------------------------------------------|
| ESIQA              | NR   | 2024      | 苹果Vision Pro头显空间影像质量评估 [13](@ref)                                    |
| RichHF-18k         | NR   | 2024      | 包含18K图文对的多维度人类反馈数据 (CVPR 2024最佳论文) [5](@ref)                  |


# IQA数据集分类整理

## 一、IQA 核心数据集

| 数据集名称         | 类型 | 发布时间 | 网址                                                                   | 图像数量     | 标注信息                     |
|---------------------|------|----------|-------------------------------------------------------------------------|--------------|-----------------------------|
| UHD-IQA            | 无参考 | 2024    | [项目页](https://database.mmsp-kn.de/uhd-iqa-benchmark-database.html)  | 6千 (4K)     | 每图20次主观评分            |
| AGIQA-3k           | 无参考 | 2023    | [代码库](https://github.com/lcysyzxdxc/AGIQA-3k-Database)              | 3千          | 多维质量标注                |
| SPAQ               | 无参考 | 2020    | [代码库](https://github.com/h4nwei/SPAQ)                                | 1.1万        | 智能手机摄影质量指标        |
| KonIQ-10k          | 无参考 | 2020    | [项目页](http://database.mmsp-kn.de/koniq-3k-database.html)            | 1万          | 120万平均主观评分(MOS)      |
| PIPAL              | 全参考 | 2020    | [项目页](https://www.jasongt.com/projectpages/pipal.html)              | 250参考图    | 113万成对比较数据           |
| KADID-10k          | 全参考 | 2019    | [项目页](http://database.mmsp-kn.de/kadid-10k-database.html)           | 81参考图     | 1万种失真类型               |
| LIVE IQA           | 全参考 | 2006    | [项目页](https://live.ece.utexas.edu/research/Quality/subjective.htm)  | 29参考图     | 780种合成失真               |

---

## 二、感知相似性数据集


| 数据集名称         | 类型 | 发布时间 | 网址                                                                   | 图像数量     | 标注信息           |
|---------------------|------|----------|-------------------------------------------------------------------------|--------------|-------------------|
| BAPPS (LPIPS)      | 全参考 | 2018    | [项目页](https://richzhang.github.io/PerceptualSimilarity/)            | 18.77万      | 48.4万成对比较     |
| PieAPP             | 全参考 | 2018    | [项目页](http://civc.ucsb.edu/graphics/Papers/CVPR2018_PieAPP/)        | 200参考图    | 230万排名数据      |

---

## 三、医学影像数据集


| 数据集名称         | 类型 | 发布时间 | 描述                                                                       |
|---------------------|------|----------|-----------------------------------------------------------------------------|
| FOCUS-MUSE DWI     | 无参考 | 2025    | 直肠癌MRI影像质量评估，含深度学习重建验证数据 [10](@ref)                         |

---

## 四、其他专项数据集

| 数据集名称         | 类型 | 发布时间 | 亮点                                                                       |
|---------------------|------|----------|-----------------------------------------------------------------------------|
| ESIQA              | 无参考 | 2024    | 针对苹果Vision Pro空间影像的感知质量评估 [13](@ref)                              |
| RichHF-18k         | 无参考 | 2024    | 多维度人类反馈数据集，含18K图文对 (CVPR 2024最佳论文) [5](@ref)                 |

---

### 引用说明
[5](@ref): CVPR 2024最佳论文数据集  
[10](@ref): 医学影像质量评估研究  
[13](@ref): 空间影像质量评估新方法  

[参考文档](https://github.com/chaofengc/Awesome-Image-Quality-Assessment)



