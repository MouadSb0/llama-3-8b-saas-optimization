# Llama-3-8B Fine-Tuning for SaaS Rationalization

## 📌 Project Overview
This repository contains a fine-tuned **Llama-3-8B** model designed to extract software names, usage patterns, and overlapping subscription data from unstructured business text. 

The goal of this project is to support **SaaS Rationalization** by providing intelligent analysis that helps businesses identify unnecessary software costs and optimize their SaaS stack.

## 🎯 Why This Project? (Alignment with SaaS Rationalization)
This project was built to demonstrate the intersection of **Python backend engineering** and **practical AI/ML integration** required for modern SaaS platforms. It specifically addresses the need for intelligent recommendation systems and data processing in a B2B environment.

## 🛠️ Tech Stack & Tools
- **Model:** Llama-3-8B (Meta)
- **Fine-Tuning Framework:** Unsloth (for 2x faster training and 60% less memory usage)
- **Format:** GGUF (Q4_K_M quantization)
- **Environment:** Google Colab (NVIDIA T4 GPU)
- **Libraries:** PyTorch, Hugging Face `transformers`, `trl`
- **Deployment Target:** AWS (SageMaker / EC2) or local inference via Ollama/LM Studio

## 🚀 Key Achievements
1. **Efficient Fine-Tuning:** Utilized Unsloth to fine-tune the 8B parameter model efficiently on a single GPU.
2. **Cost-Effective Deployment:** Converted the model to **GGUF Q4_K_M** format, reducing the model size to ~4.9GB. This allows for cost-effective deployment on AWS (or local infrastructure) without needing expensive enterprise-grade GPUs.
3. **Production Readiness:** The model is uploaded to Hugging Face and ready for integration into a Python backend (FastAPI/Flask) as an AI API.

## 🔗 Model Access
- **Hugging Face Model:** [mouadS0/llama-3-8b-saas-optimization](https://huggingface.co/mouadS0/llama-3-8b-saas-optimization)
- **Notebook:** [llama-3-8b-fine-tune.ipynb](./llama-3-8b-fine-tune.ipynb)

---
*Built by Mouad Saber as a demonstration of AI/ML backend integration for SaaS optimization.*
