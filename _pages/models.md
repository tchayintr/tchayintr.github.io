---
title: "Models"
permalink: /models/
date: 2026-08-13
---

# Open models

Models my team and I have released, free to download and run. Most live on
[open.iapp.co.th](https://open.iapp.co.th); weights are on Hugging Face.

- **OpenThai 2.0 27B** — general-purpose Thai LLM on Qwen3.8-27B, Apache-2.0. Beats its base on 14 of
  16 benchmarks; Thai document reading error falls 66% (0.126 vs 0.370 CER).
  [Weights](https://huggingface.co/iapp/openthai2.0-qwen3.8-27b)
- **OpenThai 2.0 Legal** — Thai legal LLM on Nemotron-3-Nano-30B, built with NVIDIA, BDI,
  and AIEAT; selected for the national TH-AI Passport programme. [Weights](https://huggingface.co/iapp/openthai2.0-legal-thaillm-nemotron-3-nano-30b-a3b)
- **OpenThaiGPT 1.6 & R1** — Thai-centric open-source and reasoning LLMs. R1 (32B) beats
  DeepSeek-R1-70B on Thai reasoning benchmarks at half the size.
  [Paper](https://arxiv.org/abs/2504.01789) · [1.6-72B](https://huggingface.co/openthaigpt/openthaigpt-1.6-72b-instruct) · [R1-32B](https://huggingface.co/openthaigpt/openthaigpt-r1-32b-instruct)
- **ChindaMT** — Thai–English translation that follows your rules on terminology, tone, and
  format, at 4B, 2B, and 0.8B, with the training data and evals open too. Also a
  [hosted API](https://iapp.co.th/docs/nlp/translation/chindamt).
  [Models](https://open.iapp.co.th/models/chindamt/) · [Paper](https://arxiv.org/abs/2609.34770), AACL-IJCNLP 2026.
- **Chinda LLM 4B** — compact Thai LLM under Apache-2.0. [open.iapp.co.th](https://open.iapp.co.th)
- **LATTE word segmentation models** — pre-trained character-based segmenters for
  [Chinese](https://huggingface.co/yacht/latte-mc-bert-base-chinese-ws) and
  [Thai](https://huggingface.co/yacht/latte-mc-bert-base-thai-ws), from my doctoral work.

For the commercial APIs (speech, vision, OCR, and the full Chinda platform), see
[one.iapp.co.th](https://one.iapp.co.th).
