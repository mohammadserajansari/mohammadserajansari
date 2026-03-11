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
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=firefox&logoColor=white)](https://mohammadserajansari.github.io/)

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

## 🛠️ Technical Skills

### 💻 Programming Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

---

### 🤖 AI & Machine Learning
![Machine Learning](https://img.shields.io/badge/Machine_Learning-FF6F00?style=for-the-badge)
![Deep Learning](https://img.shields.io/badge/Deep_Learning-C2410C?style=for-the-badge)
![Model Evaluation](https://img.shields.io/badge/Model_Evaluation-0369A1?style=for-the-badge)
![Error Analysis](https://img.shields.io/badge/Error_Analysis-7C3AED?style=for-the-badge)
![Cross-Validation](https://img.shields.io/badge/Cross--Validation-059669?style=for-the-badge)
![Feature Engineering](https://img.shields.io/badge/Feature_Engineering-D97706?style=for-the-badge)

---

### 🧠 LLMs & Agentic AI
![LLMs](https://img.shields.io/badge/Large_Language_Models-1C3C3C?style=for-the-badge&logo=openai&logoColor=white)
![Agentic AI](https://img.shields.io/badge/Agentic_AI-EF4444?style=for-the-badge)
![LangChain Agents](https://img.shields.io/badge/LangChain_Agents-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/Retrieval--Augmented_Generation-7C3AED?style=for-the-badge)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-0EA5E9?style=for-the-badge)
![Prompt Iteration](https://img.shields.io/badge/Prompt_Iteration-0284C7?style=for-the-badge)
![Tool Calling](https://img.shields.io/badge/Tool_Calling-16A34A?style=for-the-badge)
![PGVector](https://img.shields.io/badge/PGVector-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC2626?style=for-the-badge)
![Embeddings](https://img.shields.io/badge/Embeddings-8B5CF6?style=for-the-badge)

---

### 📚 Frameworks & Libraries
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow_Keras-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace_Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-3B4D2E?style=for-the-badge)

---

### 📊 Data Visualization
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

---

### ☁️ MLOps & Deployment
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazon-s3&logoColor=white)
![AWS Bedrock](https://img.shields.io/badge/AWS_Bedrock-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Model Serving](https://img.shields.io/badge/Model_Serving-0F172A?style=for-the-badge)
![Production ML Pipelines](https://img.shields.io/badge/Production_ML_Pipelines-1D4ED8?style=for-the-badge)
![Monitoring & Logging](https://img.shields.io/badge/Monitoring_%26_Logging-7C3AED?style=for-the-badge)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2563EB?style=for-the-badge&logo=github-actions&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white)

---

### 🔧 Developer Tools
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=pycharm&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=google-colab&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=mohammadserajansari&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&cache_seconds=1800"/>
&nbsp;
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mohammadserajansari&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&cache_seconds=1800"/>

</div>

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=mohammadserajansari&theme=tokyonight" width="100%"/>

</div>

---
## 🎓 Education & Achievement

| Degree | Institution |
|---|---|
| 🎓 M.Tech Computational Biology | IIIT Delhi |
| 🔬 B.Tech Biotechnology | Hindustan College of Science & Technology |

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
