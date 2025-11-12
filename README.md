# Modern AI with Unsloth.ai - Fine-tuning Assignment

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org)
[![Colab](https://img.shields.io/badge/Platform-Google%20Colab-orange.svg)](https://colab.research.google.com)
[![Unsloth](https://img.shields.io/badge/Library-Unsloth-green.svg)](https://unsloth.ai)

## 📌 Assignment Overview

This repository contains all materials for the Modern AI assignment focusing on fine-tuning Large Language Models using Unsloth.ai. The assignment demonstrates 5 different training methodologies on the SmolLM2-135M model.

## 🔗 Quick Links

- **Medium Article Link:** https://medium.com/@prachigupta2610/fine-tuning-llms-5-training-methods-with-unsloth-ai-80dc17a05508
- **Demo Video Link:**  colab1_full_finetuning - https://drive.google.com/file/d/1G7houDvYA22Z13FYUna5o7d2xRY1OWPD/view?usp=sharing
                        colab2_lora_finetuning - https://drive.google.com/file/d/1i0rK4mphLLqtwHTDphDw_bAR0Ed1wR8o/view?usp=sharing
                        colab3_dpo_reinforcement_learning - https://drive.google.com/file/d/1CfGr90yQFuKUS6g3t2dU7xOQ29WZa0jZ/view?usp=sharing
                        colab4_grpo_reasoning_model - https://drive.google.com/file/d/11zG6CAB67CEc818iUyehKsGY1Y1G3aA5/view?usp=sharing
                        colab5_continued_pretraining - https://drive.google.com/file/d/15JRC32NIlPq_YFwzicqEJPdRj_x0m-7q/view?usp=sharing

## 🎯 Objectives

- **Colab 1:** Full Fine-tuning on SQL generation task
- **Colab 2:** LoRA Fine-tuning on SQL generation task
- **Colab 3:** DPO Reinforcement Learning with preference data
- **Colab 4:** GRPO Reinforcement Learning for reasoning
- **Colab 5:** Continued Pretraining for French language

## 📂 Repository Structure

```
modern-ai-unsloth-assignment/
│
├── README.md
├── .gitignore
│
├── notebooks/
│   ├── colab1_full_finetuning.ipynb
│   ├── colab2_lora_finetuning.ipynb
│   ├── colab3_dpo_reinforcement_learning.ipynb
│   ├── colab4_grpo_reasoning_model.ipynb
│   └── colab5_continued_pretraining.ipynb
│
└── VideoURL/
    └── URL.txt

```
## 🚀 Quick Start

### Prerequisites
- Google Colab account (free tier works)
- HuggingFace account

### Running the Notebooks

1. **Colab 1 - Full Fine-tuning:**
   ```
   Open: notebooks/colab1_full_finetuning.ipynb
   Dataset: Clinton/Text-to-sql-v1
   Training Steps: 60
   Expected Duration: ~10 minutes
   ```

2. **Colab 2 - LoRA Fine-tuning:**
   ```
   Open: notebooks/colab2_lora_finetuning.ipynb
   Dataset: Clinton/Text-to-sql-v1 (same as Colab 1)
   Training Steps: 200
   Expected Duration: ~20 minutes
   ```

3. **Colab 3 - DPO RL:**
   ```
   Open: notebooks/colab3_dpo_reinforcement_learning.ipynb
   Dataset: argilla/distilabel-capybara-dpo-7k-binarized
   Training Steps: 100
   Expected Duration: ~15 minutes
   ```

4. **Colab 4 - GRPO Reasoning:**
   ```
   Open: notebooks/colab4_grpo_reasoning_model.ipynb
   Dataset: openai/gsm8k
   Training Steps: 50
   Expected Duration: ~20 minutes
   ```

5. **Colab 5 - Continued Pretraining:**
   ```
   Open: notebooks/colab5_continued_pretraining.ipynb
   Dataset: Custom French sentences
   Training Steps: 100
   Expected Duration: ~12 minutes
   ```

## 📊 Results Summary

| Colab | Method | Dataset | Steps | Output Quality |
|-------|--------|---------|-------|----------------|
| 1 | Full Fine-tuning | SQL | 60 | Poor (baseline) |
| 2 | LoRA | SQL | 200 | Good (improved) |
| 3 | DPO | Preferences | 100 | Excellent |
| 4 | GRPO | Math | 50 | Moderate |
| 5 | Continued PT | French | 100 | Basic learning |

## 🎥 Video Demonstrations

All videos demonstrate cell-by-cell code walkthrough, training process, and results analysis.

- colab1_full_finetuning - https://drive.google.com/file/d/1G7houDvYA22Z13FYUna5o7d2xRY1OWPD/view?usp=sharing
- colab2_lora_finetuning - https://drive.google.com/file/d/1i0rK4mphLLqtwHTDphDw_bAR0Ed1wR8o/view?usp=sharing
- colab3_dpo_reinforcement_learning - https://drive.google.com/file/d/1CfGr90yQFuKUS6g3t2dU7xOQ29WZa0jZ/view?usp=sharing
- colab4_grpo_reasoning_model - https://drive.google.com/file/d/11zG6CAB67CEc818iUyehKsGY1Y1G3aA5/view?usp=sharing
- colab5_continued_pretraining - https://drive.google.com/file/d/15JRC32NIlPq_YFwzicqEJPdRj_x0m-7q/view?usp=sharing

## 🛠️ Technologies Used

- **Model:** SmolLM2-135M (HuggingFaceTB)
- **Library:** Unsloth.ai
- **Framework:** PyTorch
- **Training:** TRL (Transformer Reinforcement Learning)
- **Platform:** Google Colab (Free T4 GPU)
- **Optimization:** 4-bit quantization, LoRA, gradient checkpointing

## 📈 Key Learnings

1. **Full vs LoRA Fine-tuning:** LoRA is more efficient with comparable results
2. **Reinforcement Learning:** DPO effectively teaches preferences
3. **GRPO for Reasoning:** Requires larger models for complex math
4. **Language Learning:** Continued pretraining enables multilingual capabilities
5. **Optimization:** 4-bit quantization crucial for free GPU training

## 🤝 Acknowledgments

- **Unsloth Team** - For the amazing optimization library
- **HuggingFace** - For model hosting and datasets
- **Assignment Instructor** - For the comprehensive learning opportunity

## 👤 Author

**Prachi Gupta**
- Student ID: 019106594
- Course: CMPE255-Data Mining
- Email: prachi.gupta01@sjsu.edu
