# Financial LLM Agents

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Stars](https://img.shields.io/github/stars/acac-yep/awesome-financial-llm-agents?color=yellow)](https://github.com/acac-yep/awesome-financial-llm-agents)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)

[English](#english) | [中文](#中文)

---

# English

> A curated list of papers on LLM-based agents in finance.

## Table of Contents

- [Surveys](#surveys)
- [Datasets & Benchmarks](#datasets--benchmarks)
- [Financial LLMs](#financial-llms)
- [Agent Systems](#agent-systems)

---

## Surveys

| Title | Venue | Year | Links |
|-------|:-----:|:----:|:-----:|
| Large Language Model Agents in Finance | EMNLP Findings | 2025 | [paper](https://arxiv.org/abs/2502.XXXXX) |

---

## Datasets & Benchmarks

### Sentiment Analysis

| Dataset | Venue | Description | Links |
|---------|:-----:|-------------|:-----:|
| **StockEmotions** | AAAI Bridge'23 | 10K posts, 12 emotions | [paper](https://arxiv.org/abs/2301.09279) |
| **FOMC** | ACL'23 | Monetary policy stance (1996-2022) | [paper](https://arxiv.org/abs/2305.07972) |

### Information Extraction

| Dataset | Venue | Description | Links |
|---------|:-----:|-------------|:-----:|
| **FiNER-ORD** | arXiv'23 | NER, 4.7K sentences | [paper](https://arxiv.org/abs/2302.11157) |
| **FinRED** | WWW'23 | Relation extraction, 29 types | [paper](https://arxiv.org/abs/2306.03736) |

### Question Answering

| Dataset | Venue | Description | Links |
|---------|:-----:|-------------|:-----:|
| **FinQA** | EMNLP'21 | Numerical reasoning, 8K QA pairs | [paper](https://arxiv.org/abs/2109.00122) |
| **ConvFinQA** | EMNLP'22 | Multi-turn QA, 14K questions | [paper](https://arxiv.org/abs/2210.03849) |

### Comprehensive Benchmarks

| Benchmark | Venue | Description | Links |
|-----------|:-----:|-------------|:-----:|
| **PIXIU/FinMA** | NeurIPS'23 | Multi-task evaluation framework | [paper](https://arxiv.org/abs/2306.05443) |
| **FinBen** | NeurIPS'24 | 7 categories, 24 tasks | [paper](https://arxiv.org/abs/2402.12659) |
| **FinTSB** | arXiv'25 | Time series forecasting benchmark | [paper](https://arxiv.org/abs/2502.18834) |

---

## Financial LLMs

| Model | Venue | Description | Links |
|-------|:-----:|-------------|:-----:|
| **BloombergGPT** | arXiv'23 | 50B, financial pre-training | [paper](https://arxiv.org/abs/2303.17564) |
| **FinMA** | NeurIPS'23 | Instruction-tuned, open-source | [paper](https://arxiv.org/abs/2306.05443) |
| **FinTral** | ACL'24 | Multimodal (text+table+chart) | [paper](https://arxiv.org/abs/2402.10986) |
| **FinLLaMA** | ICAIF'24 | LLaMA-2 + LoRA for trading | [paper](https://arxiv.org/abs/2403.12285) |

---

## Agent Systems

### Trading Agents

| System | Venue | Key Feature | Links |
|--------|:-----:|-------------|:-----:|
| **FinMEM** | IEEE TBD'24 | Layered memory (daily/quarterly/annual) | [paper](https://arxiv.org/abs/2311.13743) |

### Investment Research

| System | Venue | Key Feature | Links |
|--------|:-----:|-------------|:-----:|
| **AlphaFin** | COLING'24 | RAG + Stock-Chain framework | [paper](https://arxiv.org/abs/2403.12582) |

### Risk Management

| System | Venue | Key Feature | Links |
|--------|:-----:|-------------|:-----:|
| **FinPT** | arXiv'23 | Profile tuning for risk prediction | [paper](https://arxiv.org/abs/2308.00065) |
| **CALM** | arXiv'23 | Credit scoring with bias analysis | [paper](https://arxiv.org/abs/2310.00566) |

### Multi-Agent Systems

| System | Venue | Key Feature | Links |
|--------|:-----:|-------------|:-----:|
| **FinCon** | NeurIPS'24 | Manager-Analyst hierarchy + verbal RL | [paper](https://arxiv.org/abs/2407.06567) |


---

# 中文

> 金融领域 LLM Agent 论文精选列表

## 目录

- [综述](#综述)
- [数据集与基准](#数据集与基准)
- [金融大模型](#金融大模型)
- [Agent系统](#agent系统)

---

## 综述

| 标题 | 会议 | 年份 | 链接 |
|-----|:----:|:----:|:----:|
| Large Language Model Agents in Finance | EMNLP Findings | 2025 | [论文](https://arxiv.org/abs/2502.XXXXX) |

---

## 数据集与基准

### 情感分析

| 数据集 | 会议 | 说明 | 链接 |
|-------|:----:|-----|:----:|
| **StockEmotions** | AAAI Bridge'23 | 1万条推文，12种情绪 | [论文](https://arxiv.org/abs/2301.09279) |
| **FOMC** | ACL'23 | 美联储货币政策立场（1996-2022） | [论文](https://arxiv.org/abs/2305.07972) |

### 信息抽取

| 数据集 | 会议 | 说明 | 链接 |
|-------|:----:|-----|:----:|
| **FiNER-ORD** | arXiv'23 | 命名实体识别，4739句 | [论文](https://arxiv.org/abs/2302.11157) |
| **FinRED** | WWW'23 | 关系抽取，29种关系 | [论文](https://arxiv.org/abs/2306.03736) |

### 问答与数值推理

| 数据集 | 会议 | 说明 | 链接 |
|-------|:----:|-----|:----:|
| **FinQA** | EMNLP'21 | 数值推理，8281对 | [论文](https://arxiv.org/abs/2109.00122) |
| **ConvFinQA** | EMNLP'22 | 多轮对话QA，14115问题 | [论文](https://arxiv.org/abs/2210.03849) |

### 综合基准

| 基准 | 会议 | 说明 | 链接 |
|-----|:----:|-----|:----:|
| **PIXIU/FinMA** | NeurIPS'23 | 首个开源金融指令微调模型+多任务评测 | [论文](https://arxiv.org/abs/2306.05443) |
| **FinBen** | NeurIPS'24 | 7大类24任务，最全面的金融LLM评测 | [论文](https://arxiv.org/abs/2402.12659) |
| **FinTSB** | arXiv'25 | 时序预测基准，含真实交易约束 | [论文](https://arxiv.org/abs/2502.18834) |

---

## 金融大模型

| 模型 | 会议 | 说明 | 链接 |
|-----|:----:|-----|:----:|
| **BloombergGPT** | arXiv'23 | 500亿参数，金融预训练（未开源） | [论文](https://arxiv.org/abs/2303.17564) |
| **FinMA** | NeurIPS'23 | 首个开源金融指令微调模型 | [论文](https://arxiv.org/abs/2306.05443) |
| **FinTral** | ACL'24 | 多模态（文本+表格+图表） | [论文](https://arxiv.org/abs/2402.10986) |
| **FinLLaMA** | ICAIF'24 | LLaMA-2 + LoRA，单卡可训 | [论文](https://arxiv.org/abs/2403.12285) |

---

## Agent系统

### 交易Agent

| 系统 | 会议 | 核心创新 | 链接 |
|-----|:----:|---------|:----:|
| **FinMEM** | IEEE TBD'24 | 分层记忆（日/季/年），时间敏感性 | [论文](https://arxiv.org/abs/2311.13743) |

### 投研Agent

| 系统 | 会议 | 核心创新 | 链接 |
|-----|:----:|---------|:----:|
| **AlphaFin** | COLING'24 | RAG + Stock-Chain，A股30.8%年化 | [论文](https://arxiv.org/abs/2403.12582) |

### 风控Agent

| 系统 | 会议 | 核心创新 | 链接 |
|-----|:----:|---------|:----:|
| **FinPT** | arXiv'23 | Profile Tuning，表格转自然语言 | [论文](https://arxiv.org/abs/2308.00065) |
| **CALM** | arXiv'23 | 信用评分，发现显著偏见风险 | [论文](https://arxiv.org/abs/2310.00566) |

### 多Agent系统

| 系统 | 会议 | 核心创新 | 链接 |
|-----|:----:|---------|:----:|
| **FinCon** | NeurIPS'24 | Manager-Analyst层级 + 双层风险控制 | [论文](https://arxiv.org/abs/2407.06567) |


---

*Last Updated: February 2026 | 最后更新：2026年2月*
