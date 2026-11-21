<div align="center">
# Hi, I'm Shivansh Gupta 👋
 
### CSE student @ LPU · building retrieval systems, multi-agent AI, and transformers from scratch
 
I learn AI by implementing it: measuring where it fails, fixing it, and writing down why.
 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shivansh-gupta12412482)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL_HERE)
 
</div>
---
 
## 🔭 Right now
 
- Looking for an **AI/ML engineering internship**
- Building retrieval (RAG) and agent systems, and evaluating them properly
- Practicing DSA in **Java** (Striver A2Z)
---
 
## ⭐ Featured Projects
 
### 🌿 [IP-Sakti](https://github.com/shivansh-arch/IP-Sakti): Prior-art retrieval for Ayurvedic patents
Hybrid retrieval over the **Charaka Samhita** (romanised Sanskrit) cross-referenced against **Indian herbal-medicine patents**. It flags possible prior art under Section 3(p) of the Patents Act. Based on SIH problem SIH26045.
 
- v1 embedded raw Sanskrit and got **5.6%** top-1 accuracy. v2 bridges Sanskrit and English with a curated lexicon (74 plants, 38 conditions) plus hybrid scoring.
- **v2: 94.4% top-1 · 81.1% precision@5 · 100% correct abstention** on off-topic queries
- Stack: Qdrant · FastAPI · ONNX embeddings (fastembed) · Docker · pytest
### 🛰️ [Orion](https://github.com/shivansh-arch/Orion): Multi-agent ReAct system
An orchestrator routes each query to a **Researcher** agent (web search plus extraction) or a **Coder** agent (Python execution). A Planner splits multi-step tasks into steps.
 
- I refactored a single-user CLI prototype into **stateless agents** so it can serve many users at once
- Python agent core (FastAPI) → Node/Express API (JWT auth) → MongoDB conversation memory with auto-summarization
- Stack: Groq · FastAPI · Express · MongoDB · Docker
### 🎯 [IntentClassifier-Pro](https://github.com/shivansh-arch/IntentClassifier-Pro): Small fine-tuned model vs. large LLM
**LoRA-fine-tuned DistilBERT** vs. a few-shot prompted **gpt-oss-120b** on BANKING77 (77 intents).
 
- Fine-tuned model: **89.0% vs 87.5% accuracy** and **3.2× lower latency** (24 ms vs 76 ms)
- Includes confusion-matrix analysis of the most-confused intents
- Stack: PyTorch · Hugging Face Transformers · PEFT · Streamlit
### 🧠 [minllm](https://github.com/shivansh-arch/minllm): GPT-style transformer from scratch
Every component written by hand in PyTorch: **multi-head causal attention, RoPE, RMSNorm, SwiGLU**, pre-norm blocks, and a training loop.
 
- Character-level model (d_model = 256). Training loss fell from **4.74 to 0.31** over 5,000 steps
- Streamlit app for text generation and loss curves
### 🔬 [transformer-internals](https://github.com/shivansh-arch/transformer-internals): Transformer visualizer
Interactive walkthrough of BPE tokenization, embeddings, positional encoding, and attention heatmaps.
 
<details>
<summary><b>Other projects</b></summary>
- [skin-disease-project](https://github.com/shivansh-arch/skin-disease-project): EfficientNet-B0 skin-condition classifier with a Flask API
- Virtual Memory Simulator · Hospital Management System
</details>
---
 
## 🛠 Tech I've actually shipped with
 
| Area | Tools |
|---|---|
| **Languages** | Python · Java · JavaScript · SQL |
| **ML / DL** | PyTorch · Hugging Face Transformers · PEFT/LoRA · scikit-learn · NumPy · Pandas |
| **LLM / RAG** | Qdrant · fastembed/ONNX · Groq · tool calling · ReAct agents |
| **Backend** | FastAPI · Flask · Node.js · Express · MongoDB |
| **Ops** | Docker · Git · Linux · Render · Streamlit |
 
---
 
<div align="center">
*Measure it, break it, fix it, write down why.*
 
</div>
 
