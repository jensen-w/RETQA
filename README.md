# RETQA
A Large-Scale Open-Domain Tabular Question Answering Dataset for the Real Estate Sector


This repository contains the dataset and code released for the paper "RETQA: A Large-Scale Open-Domain Tabular Question Answering Dataset for Real Estate Sector".

![Pipeline](https://github.com/jensenw1/RETQA/blob/main/figures/pipeline.png)

RETQA is the first large-scale open-domain Chinese Tabular Question Answering (TQA) dataset focused on the real estate domain. It comprises 4,932 tables and 20,762 question-answer pairs across 16 sub-fields within three major domains: property information, real estate company finance information, and land auction information.

This dataset poses unique challenges for tabular question answering due to its long-table structures, open-domain retrieval requirements, and multi-domain queries. To address these challenges, the paper also introduces the SLUTQA framework, which integrates large language models with spoken language understanding tasks to enhance retrieval and answering accuracy.

### The repository includes:
1.The RETQA dataset in JSON format

2.The source code for the SLUTQA framework

3.Pre-trained SLUTQA model checkpoints

4.Detailed instructions for dataset usage and model training/evaluation

This resource is intended to advance tabular question answering research in the real estate domain and address critical challenges in open-domain and long-table question-answering. We hope it will be a valuable contribution to the research community.


The acquisition of real estate data is supported by [Elmleaf Ltd.](https://www.elmleaf.com.cn/home) (Shanghai).






# Citation
If you found this work useful for you, please consider citing it.
```
@inproceedings{
anonymous2024retqa,
title={{RETQA}: A Large-Scale Open-Domain Tabular Question Answering Dataset for Real Estate Sector},
author={Anonymous},
booktitle={The 39th Annual AAAI Conference on Artificial Intelligence},
year={2024},
url={https://openreview.net/forum?id=WQrikNyXug}
}
```
