# 📚 Henry Zhang's Paper Reading Logs

Welcome to my personal repository for recording and summarizing research papers I've read.  
My focus areas include:
- **Vision-Language Models (VLMs)**
- **Reinforcement Learning for Multimodal Reasoning**
- **Mixture-of-Experts (MoE)**

---

## 🗂️ Table of Contents
- [Why Reading Log?](#why-reading-log)
- [📅 Reading Log](#-reading-log)
- [🧱 Template for New Logs](#-template-for-new-logs)
- [🧩 Legend](#-legend)

---

## Why Reading Log?

As mentioned in [this insightful post](https://www.xiaohongshu.com/discovery/item/68fc7fa90000000003035c7e?source=webshare):  
> “**Scientific research begins with reading papers.**”  
> Typically, each research area has **10–20 core papers** that should be studied thoroughly,  
> and around **40–50 important papers** that deserve focused reading.  

Following this philosophy — and guided by GPT-5’s recommendations —  
I maintain this structured log to record my progress across different stages of research reading and exploration.

What's more, I hope these reading records can serve as a useful reference and help fellow newcomers navigate the landscape of research reading more effectively 🚀 🚀 🚀 .

---

## 📅 Reading Log

| No. | Paper | Year | Keywords / Main Contribution | Status |
|:---:|:------|:----:|:-----------------------------|:--------|
| 1 | **Attention Is All You Need**🔑 | 2017 | Proposed the <mark>Transformer architecture<mark> | ✅ Done · 2025-10-29  |
| 2 | **BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding**🔑 Core | 2018 | Introduced bidirectional masked language modeling and the <mark>pre-training + fine-tuning paradigm<mark>. | ✅ Done · 2025-10-30 |
| 3 | **RoBERTa: A Robustly Optimized BERT Pretraining Approach** | 2019 | Demonstrated that <mark>“more data and better recipes”<mark> can significantly improve BERT’s performance. | ✅ Done · 2025-10-30 |
| 4 | **ALBERT: A Lite BERT for Self-supervised Learning of Language Representations** | 2019 | Achieved lightweight scalability through <mark>parameter sharing and embedding factorization<mark>. | ✅ Done · 2025-10-30 |
| 5 | **BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation** | 2019 | BERT+GPT的结构，并在encoder端尝试多种noise｜[知乎回答｜潘小小](https://zhuanlan.zhihu.com/p/173858031) | ✅ Done · 2025-10-31 |
| 6 | **T5: Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer**🔑 | 2020 | 将所有 NLP 任务都可转化成 Text-to-Text 通用框架（即为T5:文本到文本）任务，prompt 先驱｜[知乎回答｜Andy Yang](https://zhuanlan.zhihu.com/) | ✅ Done · 2025-10-31 |
| 7 | **GPT-3: Language Models are Few-Shot Learners**🔑 | 2020 | 从 GPT2 的 zeroshot 到 GPT3 的 fewshot，泛化能力（应用潜力）｜[李沐读 GPT 论文的精简笔记](https://blog.csdn.net/qq_45276194/article/details/136530979) | ✅ Done · 2025-11-03 |
| 8 | **Scaling Laws for Neural Language Models**🔑 | 2020 | scaling law——模型/数据/算力的幂律规律；最优策略是大模型配中等数据集——不完全拟合 | ✅ Done · 2025-11-03 |
| 9 | **Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism** | 2020 | 英伟达开发的基于 pytorch，模型数据同时并行，超大 LLM 可训练的架构 | ✅ Done · 2025-11-05 |
| 10 | **Switch Transformer: Scaling to Trillion Parameter Models with Simple and Efficient Sparsity** | 2021 | 新单专家激活，高训练效率的MoE架构 | ✅ Done · 2025-11-05 |
| 11 | **Chinchilla: Training Compute-Optimal Large Language Models** | 2022 | data scaling law——大模型配更大数据是最优策略 | ✅ Done · 2025-11-05 |
| 12 | **PaLM: Scaling Language Modeling with Pathways** | 2022 | Google 在自家 TPU 上训出的 540B 超大 Transformer 语言模型 | ✅ Done · 2025-11-05 |
| 13 | **InstructGPT: Training Language Models to Follow Instructions with Human Feedback** | 2022 |  | 📖 Planned |
| 14 | **FLAN / Flan-T5: Scaling Instruction-Finetuned Language Models** | 2022 |  | 📖 Planned |
| 15 | **Chain-of-Thought Prompting Elicits Reasoning in Large Language Models** | 2022 |  | 📖 Planned |
| 16 | **Constitutional AI: Harmlessness from AI Feedback** | 2022 |  |  |
| 17 | **GPT-4 Technical Report** | 2023 |  |  |
| 18 | **LLaMA / LLaMA 2: Open and Efficient Foundation Language Models** | 2023 |  |  |
| 19 | **Mixtral: Sparse Mixture-of-Experts Model** | 2024 |  |  |
| 20 | **LLaMA 3 Series** | 2024 |  |  |

---

## 🧱 Template for New Logs

| No. | Paper | Year | Keywords / Main Contribution | Status |
|:---:|:------|:----:|:-----------------------------|:--------|
| XX | **[Paper Title]** | [Year] | [Brief summary, <mark>core ideas<mark>, or keywords] | ✅ Done / 📖 Planned / 🕒 Reading + Date |

```
# how to highlight
<mark>highlight text<mark>
```

## 🧩 Legend

| Symbol | Meaning |
|:-------|:---------|
| ✅ Done | Fully read and summarized |
| 📖 Planned | Planned for future reading |
| 🔑 Core | Foundational or highly influential paper |




