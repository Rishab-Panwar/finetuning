# Fine-Tuning Portfolio

> **Rishab Panwar** | IIT Madras  

This repository currently contains branches demonstrating parameter-efficient fine-tuning of large language models across **text, vision-language, and reasoning domains**.

Each notebook includes detailed explanations covering: model architecture, LoRA/QLoRA implementation, memory optimization strategies, training dynamics, and inference best practices.

---

## Fine-Tuning Notebooks

- [**Qwen2.5-VL (7B)**](https://github.com/Rishab-Panwar/finetuning/tree/Qwen2.5-VL) — Vision-language model fine-tuning for multimodal understanding
- [**DeepSeek R1 (8B)**](https://github.com/Rishab-Panwar/finetuning/tree/deepseek_R1_8b) — Reasoning-optimized model with chain-of-thought fine-tuning
- [**LLaMA 3.2 (3B)**](https://github.com/Rishab-Panwar/finetuning/tree/llama_3.2_3b) — General-purpose instruction following on FineTome-100k

---

## Tech Stack

**Framework:** Unsloth (2× faster fine-tuning)  
**Method:** LoRA/QLoRA (parameter-efficient training)  
**Quantization:** 4-bit (reduces VRAM requirements)  
**Hardware:** Google Colab T4 GPU (15GB VRAM)

---

## Contact

**GitHub:** [@Rishab-Panwar](https://github.com/Rishab-Panwar)  
**Email:** 22f1000589@ds.study.iitm.ac.in
