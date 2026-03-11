<div align="center">

<!-- Animated Header -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Mohammad%20Seraj&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=AI%20%2F%20ML%20Engineer%20%7C%20NLP%20%7C%20GenAI%20%7C%20Computational%20Biology&descAlignY=58&descSize=18&animation=fadeIn" />

<!-- Typing Animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=38BDF8&center=true&vCenter=true&multiline=false&repeat=true&width=700&lines=Building+AI+that+actually+works+in+production+%F0%9F%9A%80;NLP+%7C+RAG+%7C+LLMs+%7C+Biomedical+AI+%F0%9F%A7%AC;From+model+training+to+HIPAA-compliant+deployment+%E2%98%81%EF%B8%8F" alt="Typing SVG" />
</a>

<br/>

<!-- Social Badges -->
[![Email](https://img.shields.io/badge/mail.serajansari%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mail.serajansari@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ansariserajmd/)
[![GitHub](https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mohammadserajansari)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=firefox&logoColor=white)](https://github.com/mohammadserajansari)

<br/>

<!-- Profile Views Counter -->
![Profile Views](https://komarev.com/ghpvc/?username=mohammadserajansari&label=Profile+Views&color=38BDF8&style=flat-square)

</div>

---

## 👨‍💻 About Me

```python
class MohammadSeraj:
    def __init__(self):
        self.name        = "Mohammad Seraj"
        self.role        = "AI / ML Engineer"
        self.experience  = "1.5+ years in industry"
        self.education   = "M.Tech Computational Biology @ IIIT Delhi"
        self.location    = "Varanasi, Uttar Pradesh, India 🇮🇳"
        self.focus       = ["NLP", "Generative AI", "Biomedical AI", "RAG Systems"]
        self.achievement = "AIR 133 in DBT GAT-B (2022) 🏆"

    def current_mission(self):
        return "Building production-ready AI systems that solve real clinical & healthcare problems."
```

---

## 🏢 Work Experience

<details open>
<summary><b>🔬 Anervea Data Labs — AI Developer</b> &nbsp;|&nbsp; <i>April 2025 – October 2025</i></summary>

<br/>

> Designed and deployed an AI-powered **clinical trial patient recruitment platform** processing real-world claims and EHR data at scale.

| What I Built | Tech Used |
|---|---|
| 🏥 NLP pipelines for automated protocol ingestion (inclusion/exclusion criteria) | AWS Textract + Bedrock (Claude Sonnet) |
| 🔍 RAG system for ICD-10, CPT & LOINC code retrieval | PGVector + LangChain |
| 🤖 Fine-tuned BioBERT for clinical NLP classification | PEFT (QLoRA), 4-bit quantization, bitsandbytes |
| ☁️ HIPAA-compliant patient matching services | AWS EC2, S3, Snowflake |
| 🐳 Containerized GenAI microservices | Docker, FastAPI, Jenkins CI/CD |

**Impact:** Reduced enrolment timelines and accelerated time-to-market for novel therapies.

</details>

<details open>
<summary><b>🧪 NeuroCare-eLab — Research Assistant</b> &nbsp;|&nbsp; <i>June 2024 – April 2025</i></summary>

<br/>

> Led AI/ML research in **computational drug discovery** — LogP prediction & solubility estimation using classical + quantum descriptors.

| Model | Metric | Result |
|---|---|---|
| GNN | R² | **0.959** 🥇 |
| XGBoost Regressor | R² | 0.932 |
| ExtraTrees (+ QMPSA, ΔG) | R² | 0.849 |

**Approach:** Rigorous 5-fold cross-validation · Classical & Quantum Descriptors · GNN + Tree-based ensembles

</details>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🎙️ Autonomous Voice-Enabled Dealership Agent
Multi-agent AI system for customer service automation and test-drive scheduling.

- **Multi-agent orchestration** with CrewAI + Llama 3.3
- **Real-time voice pipeline** — Deepgram Nova-2 (STT) + Aura (TTS)
- **Custom guardrails** eliminating hallucinations in booking logic
- **Async FastAPI** backend with session-based chat history

`Python` `CrewAI` `LangChain` `Llama 3.3` `Deepgram` `FastAPI` `Docker`

</td>
<td width="50%" valign="top">

### 🧠 GenAI Document Intelligence Platform
End-to-end GenAI pipeline for document understanding and semantic search.

- **LLM + RAG pipeline** for document Q&A
- **Vector database integration** for semantic retrieval
- **Prompt optimization** for accuracy & hallucination reduction
- **Containerized** FastAPI services for scalable inference

`Python` `LangChain` `HuggingFace` `FastAPI` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧬 Alzheimer's Diagnostics via Deep Learning *(M.Tech Thesis)*
3D MRI-based Alzheimer's detection achieving 64% improvement in diagnostic accuracy.

- **3D volumetric analysis** using `.nii` format MRI files
- **YOLOv8n** outperforming VGG16 across all MRI sections
- Axial: 71% · Sagittal: 78.1% · Coronal: **80.5%**

`Python` `TensorFlow` `PyTorch` `OpenCV` `NumPy`
[![Demo](https://img.shields.io/badge/▶_Watch_Demo-green?style=flat-square)](https://drive.google.com/file/d/1EKDIsHLkLoA0w_0jGkaA0g-2UfU4z-q5/view?usp=drive_link)

</td>
<td width="50%" valign="top">

### 💊 Blood-Brain Barrier Permeability Predictor
ML/DL model for predicting BBB permeability — deployed as a live web app.

- Feature engineering on molecular descriptors
- Benchmarked Random Forest, XGBoost, deep learning
- **Live deployed model** on Streamlit

`Python` `scikit-learn` `Random Forest` `Streamlit`
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://bbbpredict.streamlit.app/)

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

### 🤖 AI / LLM / GenAI
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![RAG](https://img.shields.io/badge/RAG-7C3AED?style=for-the-badge)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-0EA5E9?style=for-the-badge)
![CrewAI](https://img.shields.io/badge/CrewAI-EF4444?style=for-the-badge)
![BioBERT](https://img.shields.io/badge/BioBERT-16A34A?style=for-the-badge)

### 🧠 ML / DL Frameworks
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=for-the-badge)

### ☁️ MLOps & Cloud
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2563EB?style=for-the-badge&logo=github-actions&logoColor=white)

### 💻 Languages & Tools
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=mohammadserajansari&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mohammadserajansari&layout=compact&langs_count=8&theme=tokyonight&hide_border=true"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=mohammadserajansari&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

## 🎓 Education & Achievement

| Degree | Institution | Score |
|---|---|---|
| 🎓 M.Tech Computational Biology | IIIT Delhi | CGPA: 7.96/10 |
| 🔬 B.Tech Biotechnology | Hindustan College of Science & Technology | CGPA: 7.8/10 |

🏆 **DBT GAT-B (2022)** — All India Rank **133**

---

## 🌱 What I'm Focused On

```
🔭 Building production-grade LLM + RAG systems for healthcare
🧬 Applying Agentic AI to accelerate clinical research
📚 Exploring multimodal models for biomedical imaging
⚡ Optimizing LLM inference with quantization (QLoRA, 4-bit)
```

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer"/>

**💬 Open to AI/ML roles in healthcare, biomedical AI, and GenAI engineering.**  
*Let's build something impactful together.*

</div>
