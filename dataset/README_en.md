# IQA Datasets Information

Image Quality Assessment (IQA) can be categorized into Full Reference (FR), Reduced Reference (RR), and No Reference (NR).

**Full Reference (FR)**: In FR problems, both the distorted image and the undistorted reference image are provided.

**Reduced Reference (RR)**: In RR problems, the distorted image is provided, but there is no reference image. However, partial information about the reference image is given, which depends on the algorithm you use. RR algorithms are useful in real-time systems. The working principle of RR is illustrated in the diagram below.

**No Reference (NR)**: In NR problems, only the distorted image is provided. NR is the most challenging method for image quality assessment.

## No Reference (NR) Datasets
| Dataset Name       | Type         | Published      | Website                                | Images                          | Annotations               | 
|--------------------|--------------|----------------|---------------------------------------|---------------------------------|--------------------------|
| **BRISQUE**        | NR           | IEEE TIP 2012  | [Project](https://live.ece.utexas.edu/research/Quality/index_algorithms.htm) | 10k from YFCC100M          | 1.2M ratings               |
| **IL-NIQE**        | NR           | IEEE TIP 2015  | [Project](http://www4.comp.polyu.edu.hk/~cslzhang/IQA/ILNIQE/ILNIQE.htm) | 20 pristine images           | Traditional feature-based  |
| **FRIQUEE**        | NR           | JoV 2017       | [Project](https://live.ece.utexas.edu/research/Quality/index_algorithms.htm) | 140k pristine               | Bag of Features approach   |
| **HIQA**           | NR           | IEEE CVPR 2018 | [Project](https://kwanyeelin.github.io/projects/HIQA/HIQA.html)         | 10k distorted               | Adversarial learning       |
| **LIVEMD**         | NR           | ACSSC 2012     | [Project](https://live.ece.utexas.edu/research/Quality/live_multidistortedimage.html) | 15 pristine                  | Two successive distortions |
| **ADB**            | NR/Aesthetic | ECCV 2016      | [GitHub](https://github.com/aimerykong/deepImageAestheticsAnalysis)      | 10k images (8500/500/1000)  | 11 attributes              |
| **AV**             | NR/Aesthetic | CVPR 2012      | [Project](https://live.ece.utexas.edu/research/ChallengeDB/index.html)   | 250k (60 categories)        | ---                        |
| **CLIVE**          | NR           | TIP 2016       | [Project](https://live.ece.utexas.edu/research/ChallengeDB/index.html)   | 1200 images                  | 350k ratings               |
| **KonIQ-10k**      | NR           | TIP 2020       | [Project](http://database.mmsp-kn.de/koniq-10k-database.html)           | 10k from YFCC100M           | 1.2M annotations           |
| **SPAQ**           | NR           | CVPR 2020      | [GitHub](https://github.com/h4nwei/SPAQ)                                | 11k smartphone images       | ---                        |
| **PaQ-2-PiQ**      | NR           | CVPR 2020      | [GitHub](https://github.com/baidut/PaQ-2-PiQ)                            | 40k images, 120k patches    | 4M ratings                 |
| **UHD-IQA**        | NR           | ECCVW 2024     | [Project](https://database.mmsp-kn.de/uhd-iqa-benchmark-database.html)  | 6k (3840x2160)              | 20 ratings per image       |

## Full Reference (FR) Datasets
| Dataset Name       | Type         | Published      | Website                                | Images                          | Annotations               | 
|--------------------|--------------|----------------|---------------------------------------|---------------------------------|--------------------------|
| **LIVE IQA**        | FR           | TIP 2006       | [Project](https://live.ece.utexas.edu/research/Quality/subjective.htm) | 29 pristine, 780 distortions | Human subjective scores   |
| **TID2008**         | FR           | 2009           | [Project](http://www.ponomarenko.info/tid2008.htm)                    | 10 pristine, 185 distortions | 1700 distortions          |
| **CSIQ**            | FR           | 2010           | [Project](http://vision.eng.shizuoka.ac.jp/mod/page/view.php?id=23)    | 30 pristine, 866 distortions | Human ratings              |
| **TID2013**         | FR           | SP 2015        | [Project](http://www.ponomarenko.info/tid2013.htm)                     | 25 pristine, 3000 distortions | MOS/DMOS scores           |
| **LIVEMD**          | FR           | ACSSC 2012     | [Project](https://live.ece.utexas.edu/research/Quality/live_multidistortedimage.html) | 15 pristine                  | Two successive distortions |
| **MDID**            | FR           | PR 2017        | ---                                   | 20 pristine                     | 1600 distortions          |
| **KADID-10k**       | FR           | QoMEX 2019     | [Project](http://database.mmsp-kn.de/kadid-10k-database.html)         | 81 pristine, 10k distortions | 30 ratings per image      |
| **KADIS-700k**      | FR           | arXiv          | [Project](http://database.mmsp-kn.de/kadid-10k-database.html)         | 140k pristine, 700k distortions | 30 ratings per image      |
| **Waterloo-Exp**    | FR           | TIP 2017       | [Project](https://ece.uwaterloo.ca/~k29ma/exploration/)                | 4744 pristine               | 94k distortions           |
| **BAPPS(LPIPS)**    | FR           | CVPR 2018      | [Project](https://richzhang.github.io/PerceptualSimilarity/)            | 187.7k images               | 484k pairwise preferences  |
| **PieAPP**          | FR           | CVPR 2018      | [Project](http://civc.ucsb.edu/graphics/Papers/CVPR2018_PieAPP/)       | 200 images                  | 2.3M pairwise preferences  |
| **PIPAL**           | FR           | ECCV 2020      | [Project](https://www.jasongt.com/projectpages/pipal.html)             | 250 pristine                | 1.13M distortions         |
| **A-DISTS**         | FR           | ACMM 2021      | [Project](https://github.com/dingkeyan93/A-DISTS)                       | ---                         | ---                        |
| **DISTS**           | FR           | TPAMI 2021     | [Project](https://github.com/dingkeyan93/DISTS)                         | ---                         | ---                        |
| **IQT**             | FR           | CVPRW 2021     | [Project](https://github.com/anse3832/IQT)                             | ---                         | Transformer-based          |
| **JSPL**            | FR           | AAAI 2022      | [Project](https://github.com/happycaoyue/JSPL)                          | ---                         | Semi-supervised learning   |
| **AHIQ**            | FR           | CVPR 2022      | [Project](https://github.com/IIGROUP/AHIQ)                              | ---                         | Attention/Transformer      |

---
