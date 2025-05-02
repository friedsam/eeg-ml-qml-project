# Research Notes and Blog Learnings

## 🧠 Concepts

### LoRA (Low-Rank Adaptation)
**Source**: [Hugging Face PEFT Blog](https://huggingface.co/blog/peft)

- LoRA reduces training cost by injecting small, trainable rank-decomposition matrices into transformer layers.
- It enables efficient fine-tuning of large models (like LLaMA, Mistral) with fewer parameters and less memory.
- Used widely in personal LLMs (Alpaca, Vicuna), and becoming a default for resource-efficient model tuning.

**Follow-Up: PEFT (Parameter-Efficient Fine-Tuning)**
- PEFT is a general strategy (includes LoRA, Prefix Tuning, Prompt Tuning).
- Hugging Face’s `peft` library supports these techniques directly.
- Modular tuning like this could inspire ideas for EEGNet variant layers or hybrid QML modules.

**Action Idea**: Try a LoRA-inspired bottleneck layer in EEGNet or use `peft` for downstream experimentation if you explore transformer-based EEG modeling.

---

## 🔧 Tools & Infrastructure

_TBD_

## 🧪 Case Studies / Policy

_TBD_


