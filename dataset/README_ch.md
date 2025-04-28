# IQA 数据集信息

IQA分为全参考(full reference,FR)，半参考( reduced-reference,RR)，无参考(no-reference)。

**全参考FR**：在FR问题中除了给出失真图像，还给出了无失真的参考图像。

**半参考RR**：在RR问题中给出了失真图像，没有参考图像，但是给了参考图像的部分信息。至于是哪种信息取决于你的算法。RR算法在实时系统中很有用。

**无参考NR**：在NR问题中仅给出了失真图像。NR是最难的图像质量评价方法。


## 无参考（NR）数据集
| 数据集名称       | 类型           | 发表年份       | 官网链接                                | 图像数量                          | 标注信息               | 
|------------------|----------------|----------------|-----------------------------------------|------------------------------------|-----------------------|
| **BRISQUE**      | 无参考（NR）   | IEEE TIP 2012  | [项目链接](https://live.ece.utexas.edu/research/Quality/index_algorithms.htm) | 10,000张（来自YFCC100M） | 120万条评分               |
| **IL-NIQE**      | 无参考（NR）   | IEEE TIP 2015  | [项目链接](http://www4.comp.polyu.edu.hk/~cslzhang/paper/IL-NIQE.pdf)     | 15张原始图像            | 传统特征方法              |
| **FRIQUEE**      | 无参考（NR）   | JoV 2017       | [项目链接](https://live.ece.utexas.edu/research/Quality/index_algorithms.htm) | 14万张原始图像          | 特征包方法                |
| **HIQA**         | 无参考（NR）   | IEEE CVPR 2018 | [项目链接](https://kwanyeelin.github.io/projects/HIQA/HIQA.html)          | 1万张退化图像            | 对抗学习生成参考          |
| **LIVEMD**       | 无参考（NR）   | ACSSC 2012     | [项目链接](https://live.ece.utexas.edu/research/Quality/live_multidistortedimage.html) | 15张原始图像          | 双重退化序列              |
| **ADB**          | 无参考美学（NR） | ECCV 2016     | [GitHub](https://github.com/aimerykong/deepImageAestheticsAnalysis)       | 1万张图像（8500/500/1000） | 11个美学属性             |
| **AV**           | 无参考美学（NR） | CVPR 2012     | [项目链接](https://live.ece.utexas.edu/research/ChallengeDB/index.html)    | 25万张（60类）          | ---                       |
| **CLIVE**        | 无参考（NR）   | TIP 2016       | [项目链接](https://live.ece.utexas.edu/research/ChallengeDB/index.html)    | 1200张图像              | 35万条评分                |
| **KonIQ-10k**    | 无参考（NR）   | TIP 2020       | [项目链接](http://database.mmsp-kn.de/koniq-10k-database.html)           | 10,000张（来自YFCC100M） | 120万标注信息             |
| **SPAQ**         | 无参考（NR）   | CVPR 2020      | [GitHub](https://github.com/h4nwei/SPAQ)                                | 1.1万张智能手机图像     | ---                       |
| **PaQ-2-PiQ**    | 无参考（NR）   | CVPR 2020      | [GitHub](https://github.com/baidut/PaQ-2-PiQ)                           | 4万张图像，12万块补丁   | 400万条评分               |
| **UHD-IQA**      | 无参考（NR）   | ECCVW 2024     | [项目链接](https://database.mmsp-kn.de/uhd-iqa-benchmark-database.html)  | 6000张（3840×2160）     | 每张20条评分              |

## 全参考（FR）数据集
| 数据集名称       | 类型           | 发表年份       | 官网链接                                | 图像数量                          | 标注信息               | 
|------------------|----------------|----------------|-----------------------------------------|------------------------------------|-----------------------|
| **LIVE IQA**     | 全参考（FR）   | TIP 2006       | [项目链接](https://live.ece.utexas.edu/research/Quality/subjective.htm) | 29原始图像，780个退化版本 | 主观人类评分             |
| **TID2008**      | 全参考（FR）   | 2009           | [项目链接](http://www.ponomarenko.info/tid2008.htm)                     | 10原始图像，185个退化版本 | 1700个退化图像           |
| **CSIQ**         | 全参考（FR）   | 2010           | [项目链接](http://vision.eng.shizuoka.ac.jp/mod/page/view.php?id=23)     | 30原始图像，866个退化版本 | 人类评分                 |
| **TID2013**      | 全参考（FR）   | SP 2015        | [项目链接](http://www.ponomarenko.info/tid2013.htm)                     | 25原始图像，3000个退化版本 | MOS/DMOS评分标准         |
| **LIVEMD**       | 全参考（FR）   | ACSSC 2012     | [项目链接](https://live.ece.utexas.edu/research/Quality/live_multidistortedimage.html) | 15原始图像          | 双重退化序列              |
| **MDID**         | 全参考（FR）   | PR 2017        | ---                                     | 20原始图像                        | 1600个退化版本         |
| **KADID-10k**    | 全参考（FR）   | QoMEX 2019     | [项目链接](http://database.mmsp-kn.de/kadid-10k-database.html)         | 81原始图像，10,000个退化版本 | 每张30条评分            |
| **KADIS-700k**   | 全参考（FR）   | arXiv          | [项目链接](http://database.mmsp-kn.de/kadid-10k-database.html)         | 14万原始图像，70万退化版本 | 每张30条评分            |
| **Waterloo-Exp** | 全参考（FR）   | TIP 2017       | [项目链接](https://ece.uwaterloo.ca/~k29ma/exploration/)                | 4,744原始图像            | 94,000个退化版本         |
| **BAPPS(LPIPS)** | 全参考（FR）   | CVPR 2018      | [项目链接](https://richzhang.github.io/PerceptualSimilarity/)           | 18.77万张图像            | 484,000对偏好标注        |
| **PieAPP**       | 全参考（FR）   | CVPR 2018      | [项目链接](http://civc.ucsb.edu/graphics/Papers/CVPR2018_PieAPP/)       | 200张图像                | 230万对偏好标注          |
| **PIPAL**        | 全参考（FR）   | ECCV 2020      | [项目链接](https://www.jasongt.com/projectpages/pipal.html)             | 250原始图像              | 113万退化版本            |
| **A-DISTS**      | 全参考（FR）   | ACMM 2021      | [项目链接](https://github.com/dingkeyan93/A-DISTS)                       | ---                      | ---                       |
| **DISTS**        | 全参考（FR）   | TPAMI 2021     | [项目链接](https://github.com/dingkeyan93/DISTS)                         | ---                      | ---                       |
| **IQT**          | 全参考（FR）   | CVPRW 2021     | [项目链接](https://github.com/anse3832/IQT)                             | ---                      | Transformer架构          |
| **JSPL**         | 全参考（FR）   | AAAI 2022      | [项目链接](https://github.com/happycaoyue/JSPL)                          | ---                      | 半监督学习与PU学习       |
| **AHIQ**         | 全参考（FR）   | CVPR 2022      | [项目链接](https://github.com/IIGROUP/AHIQ)                              | ---                      | 注意力/Transformer       |