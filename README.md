<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&duration=3000&pause=800&color=00D4FF&center=true&vCenter=true&multiline=false&width=700&lines=Mohammed+%22Silva%22+Sedeg;Senior+AI+Engineer+%7C+LLM+Systems;Edge+Computer+Vision+%7C+MLOps;Founder+of+SAiR+%7C+Building+AI+for+Sudan" alt="Typing SVG" />

<br/>

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-0D1117?style=for-the-badge&logo=google-chrome&logoColor=00D4FF)](https://silvaxxx1.github.io/MyWebsite/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=0A66C2)](https://www.linkedin.com/in/mohammed-sedeg-67444b307/)
[![Email](https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=EA4335)](mailto:silvapi1994@gmail.com)
[![GitHub](https://img.shields.io/github/followers/silvaxxx1?style=for-the-badge&logo=github&label=Follow&color=0D1117&labelColor=0D1117&logoColor=white)](https://github.com/silvaxxx1)

<br/>

![Location](https://img.shields.io/badge/📍_Turkey-0D1117?style=flat-square&logoColor=white)
![Remote](https://img.shields.io/badge/🌍_Remote_Ready-0D1117?style=flat-square&logoColor=white)
![PhD](https://img.shields.io/badge/🎓_PhD_Candidate-0D1117?style=flat-square&logoColor=white)
![Views](https://komarev.com/ghpvc/?username=silvaxxx1&color=00D4FF&style=flat-square&label=Profile+Views)

</div>

---

## ⚡ Who I Am

I'm an **AI Engineer & Researcher** with **5+ years in LLM systems, MLOps, and edge computer vision** — backed by **9 years of broader engineering experience** in automation, embedded systems, and renewable energy. I bridge research depth with production delivery.

As **Founder of SAiR (Sudanese AI Research Organization)**, I'm building Sudan's AI ecosystem from the ground up — running a free, open-source AI engineering program that has trained **300+ learners** across Sudan and Africa.

> *"I don't just build AI systems — I build the infrastructure and the people around them."*

---

## 🎯 Production Impact at a Glance

```
🚀 3×  faster LLM inference        via GGUF + ExLlamaV2 quantization
💸 70%  reduction in fine-tuning    via LoRA / QLoRA on custom instruction datasets
⚡ 40%  lower RAG query latency     via optimized retrieval pipeline architecture
📦 40-60% smaller CV models        via quantization + pruning on edge hardware
⏱️ 60-80ms inference on Jetson     real-time edge AI on devices with <4GB RAM
👥 300+ learners trained            6-module AI engineering curriculum, 65% completion rate
```

---

## 💼 Experience

### 🤖 AI Engineer & LLM Consultant · Independent / Contract `2023 – Present`

- Architected **enterprise RAG systems** with multi-provider LLM stack (OpenAI, Cohere, HuggingFace, Ollama) using modular retriever-generator design — FastAPI + pgvector + Qdrant + MongoDB — cutting query latency by ~**40%**
- Reduced LLM fine-tuning costs by **70%** via LoRA/QLoRA; accelerated distributed training **20–30%** with DeepSpeed, PyTorch DDP, and AMP
- Deployed GGUF and ExLlamaV2 quantized models achieving **~3× faster inference**; built full observability stack (Prometheus + Grafana) and ML pipelines with Prefect, cutting deployment cycle time by **35%**
- Improved reasoning accuracy **20%** via Chain-of-Thought and Tree-of-Thought prompting
- Built **fintech KYC OCR pipeline** using Mistral OCR — reduced manual document processing by **60%**

### 👁️ AI Engineer – Computer Vision Specialist · VisionCore `2024 – 2025`

- Deployed **low-latency edge AI** (TFLite, ONNX) on constrained hardware achieving **60–80ms end-to-end inference** on devices with <4GB RAM
- Built real-time **PPE detection system** using YOLOv8, reaching **85–90% mAP** in production
- Automated annotation and augmentation via Roboflow + VLM augmentation — cut labeling effort by **25%**, accelerated dataset iteration **2×**
- Reduced overfitting by **15%** via Random Forest Isolation augmentation techniques

### 🔬 R&D Engineer – AI & Deep Learning · Karabük University `2021 – 2023`

- Designed a **multimodal deep learning system** for solar power forecasting — fusing LSTM, Transformer, and CNN branches with cross-modal attention over NOAA GOES-16/17 satellite imagery — achieving **state-of-the-art accuracy** across all benchmark metrics (RMSE, MAE, R²)
- Built **V2G microgrid optimization pipeline** using Improved Antlion Optimizer and PSO with Monte Carlo simulation — full techno-economic benchmarking (COE, NPC, LPSP, REF); results published in research paper

### ⚙️ Industrial Automation & Renewable Energy `2017 – 2021`

- Managed 24/7 industrial control systems (PLC, HMI, SCADA) — improved uptime by **~18%**
- Designed and deployed solar systems including a dual-axis tracker achieving **+35% energy capture**
- Contributed to hybrid solar-EV R&D from concept to prototype

---

## 🔬 Research

> PhD Candidate · Karabük University · Focus: Vision-Language Models, Edge AI, African AI Applications

| Project | Method | Result |
|---|---|---|
| Solar Irradiance Forecasting | LSTM + Transformer + CNN fusion · NOAA GOES-16/17 | SOTA on RMSE, MAE, R² |
| V2G Microgrid Optimization | Improved Antlion Optimizer + PSO + Monte Carlo | Published paper |
| Edge VLM Deployment | Quantization + pruning for constrained hardware | 60–80ms inference |

---

## 🏗️ Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🧠 [MyLLM101](https://github.com/silvaxxx1/MyLLM101)
**End-to-End LLM Research Framework**

Modular PyTorch framework covering the full LLM lifecycle:
- GPT-2 & LLaMA pretraining from scratch
- SFT → RLHF → DPO → PPO alignment pipeline
- Quantization: GGUF, AWQ, GPTQ
- Memory-efficient distributed training (DeepSpeed, FSDP)
- Notebooks bridging math foundations → production

*Used to train **300+ SAiR students***

`PyTorch` `Transformers` `RLHF` `DeepSpeed` `FSDP`

</td>
<td width="50%" valign="top">

### 🔍 [RagApp](https://github.com/silvaxxx1/RagApp)
**Production-Ready RAG Platform**

Enterprise RAG framework with real production usage:
- Multi-provider LLM orchestration
- Modular retriever-generator design
- FastAPI + Docker · CI/CD via GitHub Actions
- Scalable vector backends: pgvector, MongoDB, Qdrant
- Observability: Prometheus + Grafana

*Powers **client solutions** and SAiR demos*

`FastAPI` `PostgreSQL` `Qdrant` `LangChain` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌍 [SAiR Courses](https://github.com/SAIR-Org/SAIR_Courses)
**Free AI Curriculum for African Learners**

6-module AI engineering program, built from scratch:
- Python → ML → Deep Learning → MLOps pipeline
- Student projects: healthcare diagnostics, crop disease CNN, Arabic NLP
- **300+ learners** · 5 African countries · 65% completion rate

`Python` `ML` `DL` `MLOps` `Education`

</td>
<td width="50%" valign="top">

### 🧮 [SilvaXNet](https://github.com/silvaxxx1/SilvaNet)
**Deep Learning From Scratch**

Educational DL framework built from first principles:
- Pure NumPy/CuPy implementations
- Custom autograd engine
- Mathematical foundations → working neural nets

`NumPy` `CuPy` `Autograd` `Education`

</td>
</tr>
</table>

**More:** [PAPER2CODE](https://github.com/silvaxxx1/PAPER2CODE) · [TF2 Object Detection Pipeline](https://github.com/silvaxxx1/Automated-Pipeline-for-Inference-and-Fine-Tuning-Using-TensorFlow-2-Object-Detection-API) . [HandsOnLLMs](https://github.com/silvaxxx1/HandsOnLLMs)

---

## 🛠️ Technical Skills

| Domain | Stack |
|---|---|
| **LLMs & GenAI** | Hugging Face Transformers · LangChain · LoRA · QLoRA · RLHF · DPO · RAG · FAISS · OpenAI API · Ollama · Mistral |
| **MLOps & Deployment** | Docker · FastAPI · AWS SageMaker · MLflow · GitHub Actions · Prometheus · Grafana · Prefect · TensorRT · GGUF · ExLlamaV2 |
| **Training Infrastructure** | DeepSpeed · PyTorch DDP · FSDP · AMP · ZeRO Optimization |
| **Computer Vision** | YOLOv8 · OpenCV · Roboflow · ONNX · TFLite · Detectron2 · SAM · Jetson / Raspberry Pi |
| **ML & Deep Learning** | PyTorch · TensorFlow · JAX · LSTM · CNN · Transformers · Multimodal · scikit-learn · XGBoost |
| **Data & Vector Stores** | PostgreSQL + pgvector · MongoDB · Qdrant · SQLAlchemy · Redis |
| **Programming** | Python (advanced) · C/C++ · R · Bash/Shell |

---

## 🇸🇩 SAiR — Building Sudan's AI Future

<div align="center">

**Founder & Lead Instructor · Sudanese Artificial Intelligence Research Organization**

*Free · Open-source · Built from scratch*

```
👥 300+ Learners    📚 6 Modules    🌍 5 African Countries
🚀 Production Projects Shipped    💯 100% Free Access    ✅ 65% Completion Rate
```

</div>

Student teams have shipped production systems in:
- 🏥 Healthcare diagnostics
- 🌾 Crop disease detection (CNN)
- 🔤 Arabic NLP

**🔗 Join:** [SAiR GitHub](https://github.com/SAIR-Org) · [Telegram Community](https://t.me/+jPPlO6ZFDbtlYzU0)

---

## 🔭 Currently

- 📖 **PhD research** — Vision-Language Models for edge deployment in low-resource African contexts
- 🏗️ **Building** — Next SAiR module: LLM Engineering end-to-end
- 🤝 **Open to** — Full-time AI Engineering · Consulting · Research Collaboration

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=silvaxxx1&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=silvaxxx1&layout=compact&theme=tokyonight&hide_border=true&langs_count=8"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=silvaxxx1&theme=tokyonight&hide_border=true" width="49%"/>
<img src="https://github-profile-trophy.vercel.app/?username=silvaxxx1&theme=tokyonight&column=4&margin-w=15&margin-h=15&no-frame=true" width="49%"/>

</div>

---

## 🎓 Education

| Degree | Institution | Year |
|---|---|---|
| 🎓 **PhD Candidate** — Mechatronics & AI *(Vision-Language Models, Edge AI)* | Karabük University, Turkey | 2024 – Present |
| 🎓 **M.Sc.** — Mechatronics *(Computer Vision specialization)* | Karabük University, Turkey | 2023 |
| 🎓 **B.Sc.** — Electrical Engineering *(Control Systems)* | Sudan University of Science and Technology | 2016 |

📜 **Certifications:** [View All](https://drive.google.com/drive/folders/1_jptrFFIlA3uZUXjhCKuEX6JztPal1u1?usp=sharing)

**Languages:** Arabic (Native) · English (C1 Fluent) · Turkish (B2 Intermediate)

---

## 📬 Let's Connect

<div align="center">

*5+ years in LLM systems + 9 years engineering background. I bridge research depth with production delivery.*

[![Email](https://img.shields.io/badge/✉️_silvapi1994@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:silvapi1994@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammed-sedeg-67444b307/)
[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-Visit-0D1117?style=for-the-badge)](https://silvaxxx1.github.io/MyWebsite/)
[![SAiR](https://img.shields.io/badge/🚀_Join_SAiR-Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/+jPPlO6ZFDbtlYzU0)

<br/>

*🇸🇩 Founder of SAiR · Senior AI Engineer · Building AI for Everyone*

</div>
