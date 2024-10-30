# Awesome-LLM4Ranking

A paper list on large language models for ranking. This list is currently maintained by [Qi Liu](https://liuqi6777.github.io) at Gaoling School of Artificial Intelligence, Renmin University of China.

## Contents

- [Basics](#basics)
- [Effectiveness](#effectiveness)
- [Efficiency](#efficiency)
- [Analysis](#analysis)

## Basics

- **Document Ranking with a Pretrained Sequence-to-Sequence Model.** *EMNLP 2020.*  ![](https://img.shields.io/badge/pointwise-blue) \
Rodrigo Nogueira, Zhiying Jiang, Ronak Pradeep, and Jimmy Lin. \
2020.5 [[pdf](https://arxiv.org/pdf/2003.06713)]

- **The expando-mono-duo design pattern for text ranking with pretrained sequence-to-sequence models.** *ArXiv.*  ![](https://img.shields.io/badge/pairwise-blue) \
Ronak Pradeep, Rodrigo Nogueira, Jimmy Lin. \
2021.1 [[pdf](https://arxiv.org/pdf/2101.05667)]

- **Improving Passage Retrieval with Zero-Shot Question Generation.** *EMNLP 2022.*  ![](https://img.shields.io/badge/pointwise-blue) \
Devendra Sachan, Mike Lewis, Mandar Joshi, Armen Aghajanyan, Wen-tau Yih, Joelle Pineau, and Luke Zettlemoyer. \
2022.4 [[pdf](https://arxiv.org/pdf/2204.07496)]

- **Is ChatGPT Good at Search? Investigating Large Language Models as Re-Ranking Agent.** *EMNLP 2023.*  ![](https://img.shields.io/badge/listwise-blue) \
Weiwei Sun, Lingyong Yan, Xinyu Ma, Pengjie Ren, Dawei Yin, and Zhaochun Ren. \
2023.4 [[pdf](http://arxiv.org/pdf/2304.09542)]

- **Large Language Models Are Effective Text Rankers with Pairwise Ranking Prompting.** *NAACL 2024.*  ![](https://img.shields.io/badge/pairwise-blue) \
Zhen Qin, Rolf Jagerman, Kai Hui, Honglei Zhuang, Junru Wu, Le Yan, Jiaming Shen, Tianqi Liu, Jialu Liu, Donald Metzler, Xuanhui Wang, Michael Bendersky. \
2023.6 [[pdf](https://arxiv.org/abs/2306.17563)]

- **Fine-Tuning LLaMA for Multi-Stage Text Retrieval.** *SIGIR 2024.* ![](https://img.shields.io/badge/pointwise-blue) \
Xueguang Ma, Liang Wang, Nan Yang, Furu Wei, Jimmy Lin. \
2023.10 [[pdf](https://arxiv.org/pdf/2310.08319)]

## Effectiveness

- **RankT5: Fine-Tuning T5 for Text Ranking with Ranking Losses.** *SIGIR 2023.* ![](https://img.shields.io/badge/pointwise-blue) \
Honglei Zhuang, Zhen Qin, Rolf Jagerman, Kai Hui, Ji Ma, Jing Lu, Jianmo Ni, Xuanhui Wang, and Michael Bendersky. \
2022.10 [[pdf](https://arxiv.org/pdf/2210.10634)]

- **Found in the Middle: Permutation Self-Consistency Improves Listwise Ranking in Large Language Models.** *NAACL 2024.* ![](https://img.shields.io/badge/listwise-blue) \
Raphael Tang, Xinyu Zhang, Xueguang Ma, Jimmy Lin, and Ferhan Ture. \
2023.10 [[pdf](http://arxiv.org/pdf/2310.07712)]

- **Beyond Yes and No: Improving Zero-Shot LLM Rankers via Scoring Fine-Grained Relevance Labels.** *NAACL 2024.* ![](https://img.shields.io/badge/pointwise-blue) \
Honglei Zhuang, Zhen Qin, Kai Hui, Junru Wu, Le Yan, Xuanhui Wang, and Michael Berdersky. \
2023.10 [[pdf](http://arxiv.org/pdf/2310.14122)]

- **PaRaDe: Passage Ranking Using Demonstrations with Large Language Models.** *EMNLP 2023.* ![](https://img.shields.io/badge/pointwise-blue) \
Andrew Drozdov, Honglei Zhuang, Zhuyun Dai, Zhen Qin, Razieh Rahimi, Xuanhui Wang, Dana Alon, Mohit Iyyer, Andrew McCallum, Donald Metzler, Kai Hui \
2023.10 [[pdf](https://arxiv.org/pdf/2310.14408)]

- **A Two-Stage Adaptation of Large Language Models for Text Ranking.** *ACL 2024.* ![](https://img.shields.io/badge/pointwise-blue) \
Longhui Zhang, Yanzhao Zhang, Dingkun Long, Pengjun Xie, Meishan Zhang, Min Zhang \
2023.11 [[pdf](http://arxiv.org/pdf/2311.16720)]

- **ListT5: Listwise Reranking with Fusion-in-Decoder Improves Zero-Shot Retrieval.** *ACL 2024.* ![](https://img.shields.io/badge/listwise-blue) \
Soyoung Yoon, Eunbi Choi, Jiyeon Kim, Hyeongu Yun, Yireun Kim, and Seung-won Hwang. \
2024.2 [[pdf](https://arXiv.org/pdf/2402.15838)]

- **Consolidating Ranking and Relevance Predictions of Large Language Models through Post-Processing.** *EMNLP 2024* ![](https://img.shields.io/badge/pairwise-blue) \
Le Yan, Zhen Qin, Honglei Zhuang, Rolf Jagerman, Xuanhui Wang, Michael Bendersky, and Harrie Oosterhuis. \
2024.4 [[pdf](http://arxiv.org/pdf/2404.11791)]

- **Generating Diverse Criteria On-the-Fly to Improve Point-Wise LLM Rankers.** *ArXiv* ![](https://img.shields.io/badge/pointwise-blue) \
Fang Guo, Wenyu Li, Honglei Zhuang, Yun Luo, Yafu Li, Le Yan, and Yue Zhang. \
2024.4 [[pdf](http://arxiv.org/pdf/2404.11960)]

- **LLM-RankFusion: Mitigating Intrinsic Inconsistency in LLM-Based Ranking.** *ArXiv* ![](https://img.shields.io/badge/pairwise-blue) \
Yifan Zeng, Ojas Tendolkar, Raymond Baartmans, Qingyun Wu, Huazheng Wang, and Lizhong Chen. \
2024.5 [[pdf](http://arxiv.org/pdf/2406.00231)]

- **TourRank: Utilizing Large Language Models for Documents Ranking with a Tournament-Inspired Strategy.**  *ArXiv* \
Yiqun Chen, Qi Liu, Yi Zhang, Weiwei Sun, Daiting Shi, Jiaxin Mao, and Dawei Yin. \
2024.6 [[pdf](http://arxiv.org/pdf/2406.11678)]

- **Improving Zero-Shot LLM Re-Ranker with Risk Minimization.** *EMNLP 2024* ![](https://img.shields.io/badge/pointwise-blue) \
Xiaowei Yuan, Zhao Yang, Yequan Wang, Jun Zhao, and Kang Liu. \
2024.6 [[pdf](http://arxiv.org/abs/2406.13331)]

- **APEER: Automatic Prompt Engineering Enhances Large Language Model Reranking.** *ArXiv.*  ![](https://img.shields.io/badge/listwise-blue) \
Can Jin, Hongwu Peng, Shiyu Zhao, Zhenting Wang, Wujiang Xu, Ligong Han, Jiahui Zhao, Kai Zhong, Sanguthevar Rajasekaran, and Dimitris N. Metaxas. \
2024.6 [[pdf](http://arxiv.org/pdf/2406.14449)]

- **DemoRank: Selecting Effective Demonstrations for Large Language Models in Ranking Task.** *ArXiv* \
Wenhan Liu, Yutao Zhu, and Zhicheng Dou. \
2024.6 [[pdf](http://arxiv.org/pdf/2406.16332)]

- **ReasoningRank: Teaching Student Models to Rank through Reasoning-Based Knowledge Distillation.** *ArXiv.*  ![](https://img.shields.io/badge/listwise-blue) \
Yuelyu Ji, Zhuochun Li, Rui Meng, and Daqing He. \
2024.10 [[pdf](http://arxiv.org/pdf/2410.05168)]

## Efficiency

- **A Setwise Approach for Effective and Highly Efficient Zero-Shot Ranking with Large Language Models.**  *SIGIR 2024.* \
Shengyao Zhuang, Honglei Zhuang, Bevan Koopman, and Guido Zuccon. \
2023.10 [[pdf](http://arxiv.org/pdf/2310.09497)]

- **Top-Down Partitioning for Efficient List-Wise Ranking.** *ArXiv.*  ![](https://img.shields.io/badge/listwise-blue) \
Andrew Parry, Sean MacAvaney, and Debasis Ganguly. \
2024.5 [[pdf](http://arxiv.org/pdf/2405.14589)]

- **Leveraging Passage Embeddings for Efficient Listwise Reranking with Large Language Models.** *ArXiv.* ![](https://img.shields.io/badge/listwise-blue) \
Qi Liu, Bo Wang, Nan Wang, and Jiaxin Mao. \
2024.6 [[pdf](http://arxiv.org/pdf/2406.14848)]

- **FIRST: Faster Improved Listwise Reranking with Single Token Decoding.** *EMNLP 2024.* ![](https://img.shields.io/badge/listwise-blue) \
Revanth Gangi Reddy, JaeHyeok Doo, Yifei Xu, Md Arafat Sultan, Deevya Swain, Avirup Sil, Heng Ji.
2024.6 [[pdf](http://arxiv.org/pdf/2406.15657)]

- **Attention in Large Language Models Yields Efficient Zero-Shot Re-Rankers.** *ArXiv.* ![](https://img.shields.io/badge/listwise-blue) \
Shijie Chen, Bernal Jiménez Gutiérrez, and Yu Su.
2024.10 [[pdf](http://arxiv.org/pdf/2410.02642)]

## Analysis

- **A Thorough Comparison of Cross-Encoders and LLMs for Reranking SPLADE.** *ArXiv.* \
Hervé Déjean, Stéphane Clinchant, and Thibault Formal. \
2024.3 [[pdf](http://arxiv.org/pdf/2403.10407)]

- **An Investigation of Prompt Variations for Zero-Shot LLM-Based Rankers.** *ArXiv.* \
Shuoqi Sun, Shengyao Zhuang, Shuai Wang, and Guido Zuccon. \
2024.6 [[pdf](http://arxiv.org/pdf/2406.14117)]

- **Ranked List Truncation for Large Language Model-Based Re-Ranking.** *SIGIR 2024.* \
Chuan Meng, Negar Arabzadeh, Arian Askari, Mohammad Aliannejadi, and Maarten de Rijke. \
2024.4 [[pdf](https://doi.org/10.1145/3626772.3657864)]

- **Probing Ranking LLMs: Mechanistic Interpretability in Information Retrieval.** *ArXiv.* ![](https://img.shields.io/badge/pointwise-blue) \
Tanya Chowdhury, and James Allan. \
2024.10 [[pdf](http://arxiv.org/pdf/2410.18527)]

## Distillation

- **RankVicuna: Zero-Shot Listwise Document Reranking with Open-Source Large Language Models.** *ArXiv.* ![](https://img.shields.io/badge/listwise-blue) \
Ronak Pradeep, Sahel Sharifymoghaddam, and Jimmy Lin.
2023.9 [[pdf](http://arxiv.org/pdf/2309.15088)]

- **RankZephyr: Effective and Robust Zero-Shot Listwise Reranking Is a Breeze!** *ArXiv.* ![](https://img.shields.io/badge/listwise-blue) \
Ronak Pradeep, Sahel Sharifymoghaddam, and Jimmy Lin.
2023.12 [[pdf](http://arxiv.org/pdf/2312.02724)]

- **Rank-without-GPT: Building GPT-Independent Listwise Rerankers on Open-Source Large Language Models.** *ArXiv.* ![](https://img.shields.io/badge/listwise-blue) \
Xinyu Zhang, Sebastian Hofstätter, Patrick Lewis, Raphael Tang, and Jimmy Lin.
2023.12 [[pdf](http://arxiv.org/pdf/2312.02969)]



<!-- 


-->


