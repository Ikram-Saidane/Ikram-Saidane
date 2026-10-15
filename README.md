<p align="center">
  <img src="header.svg" alt="Ikram Saidane · Master IASD, Paris Dauphine – PSL · GenAI, RAG, Agentic AI, Machine Learning" width="100%">
</p>

<p align="center">
  <a href="https://ikram-saidane.github.io"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=3000&pause=900&color=D2042D&center=true&vCenter=true&width=680&lines=Building+RAG+pipelines+evaluated+with+RAGAS;Designing+multi-agent+systems+with+LangGraph;Shipping+ML+models+as+APIs+(FastAPI+%2B+Docker);Open+to+a+6-month+internship+%C2%B7+Feb+2027+%F0%9F%8D%92" alt="Typing intro"></a>
</p>

<p align="center">
  <a href="https://ikram-saidane.github.io"><img src="https://img.shields.io/badge/Portfolio-ikram--saidane.github.io-6C1026?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="https://linkedin.com/in/ikram-saidane"><img src="https://img.shields.io/badge/LinkedIn-ikram--saidane-D2042D?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:ikram.saidane@dauphine.eu"><img src="https://img.shields.io/badge/Email-ikram.saidane%40dauphine.eu-2B0A13?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <br>
  <img src="https://komarev.com/ghpvc/?username=Ikram-Saidane&color=d2042d&style=flat-square&label=profile+views" alt="Profile views">
  <img src="https://img.shields.io/github/followers/Ikram-Saidane?style=flat-square&color=6C1026&label=followers" alt="Followers">
  <img src="https://img.shields.io/badge/status-open%20to%20PFE%20internship-2f7d4a?style=flat-square" alt="Open to internship">
</p>

---

### 🍒 About me

```python
class IkramSaidane:
    studies   = "M2 AI, Data Science & Agentic AI · Université Paris Dauphine – PSL (Master IASD)"
    focus     = ["GenAI", "RAG", "Multi-agent systems", "Machine Learning", "MLOps"]
    building  = "Agora · multi-agent assistant for EU regulation"
    previously = "GenAI / RAG intern @ Capgemini Engineering (18/20)"
    languages = ["Arabic", "French", "English", "German (beginner)"]
    looking_for = "6-month end-of-studies internship (PFE) · from February 2027 · France"
```

---

### ⭐ Featured · [Agora](https://github.com/Ikram-Saidane/Agora)

**Multi-agent regulatory watch on the EUR-Lex corpus** (AI Act, GDPR, DSA, DMA).
Four LangGraph agents pass the question along, and every answer cites the exact articles it relies on.

```mermaid
flowchart LR
    Q([Question]) --> A1[Query agent<br/>rewrites the question]
    A1 --> A2[Retrieval agent<br/>bge-m3 + Qdrant]
    A2 --> A3[Analysis agent<br/>LLaMA 3.3-70B · Groq]
    A3 --> A4[Citation agent<br/>links EUR-Lex articles]
    A4 --> R([Cited answer])
    style A1 fill:#6C1026,color:#fff,stroke:#6C1026
    style A2 fill:#D2042D,color:#fff,stroke:#D2042D
    style A3 fill:#6C1026,color:#fff,stroke:#6C1026
    style A4 fill:#D2042D,color:#fff,stroke:#D2042D
```

<p>
  <img src="https://img.shields.io/badge/context_recall-0.93-D2042D?style=flat-square" alt="context recall 0.93">
  <img src="https://img.shields.io/badge/faithfulness-0.75-6C1026?style=flat-square" alt="faithfulness 0.75">
  <img src="https://img.shields.io/badge/context_precision-0.74-6C1026?style=flat-square" alt="context precision 0.74">
  <img src="https://img.shields.io/badge/answer_relevancy-0.71-6C1026?style=flat-square" alt="answer relevancy 0.71">
  <img src="https://img.shields.io/github/last-commit/Ikram-Saidane/Agora?style=flat-square&color=2B0A13&label=last+commit" alt="Last commit on Agora">
</p>

---

### 🧪 Projects

<details open>
<summary><b>GenAI & Agentic AI</b></summary>
<br>

| Project | What it does | Result | Stack |
|---|---|---|---|
| **[Agora](https://github.com/Ikram-Saidane/Agora)** | Multi-agent RAG over EU regulation | Context recall **0.93** | LangGraph · Qdrant · LLaMA 3.3 · RAGAS |
| **RAG pipeline · Capgemini** | Document Q&A, fully local (no cloud API) | Context precision **0.85** | LangChain · ChromaDB · LLaMA 3.1 · Ollama |
| **PRIMIA** · EY × Dauphine hackathon | An LLM reads financial PDF reports, a model scores risk on 7 indicators | SaaS prototype | Gemini · Random Forest · XGBoost |

</details>

<details open>
<summary><b>Machine Learning & MLOps</b></summary>
<br>

| Project | What it does | Result | Stack |
|---|---|---|---|
| **[Churn Prediction API](https://github.com/Ikram-Saidane/churn-prediction-api)** | End-to-end MLOps on IBM Telco (7,043 customers) | AUC **0.840** | FastAPI · Docker · GitHub Actions · Railway |
| **[House Prices](https://github.com/Ikram-Saidane/house-prices-kaggle)** | Kaggle Ames Housing, stacking ensemble | **58th / 5,235** · RMSLE 0.11464 | XGBoost · LightGBM · CatBoost |
| **[Tunisia Tourism Forecasting](https://github.com/Ikram-Saidane/tunisia-tourism-forecasting)** | Monthly tourism flows, 24 governorates (2017–2025) | Forecasts + maps | Random Forest · MLP · LSTM · GeoPandas |
| **Hotel cancellations** | Booking cancellation prediction with explainability | AUC **0.915** | SMOTE · SHAP · LIME |
| **[Bayesian Network](https://github.com/Ikram-Saidane/R-seau-Bay-sien)** | Course project in probabilistic modelling | | Bayesian networks |

</details>

---

### 🛠️ Tech stack

<p>
  <b>GenAI & Agentic AI</b><br>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white">
  <img src="https://img.shields.io/badge/LangGraph-6C1026?style=flat-square&logo=langchain&logoColor=white">
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black">
  <img src="https://img.shields.io/badge/Qdrant-D2042D?style=flat-square">
  <img src="https://img.shields.io/badge/ChromaDB-6C1026?style=flat-square">
  <img src="https://img.shields.io/badge/Groq-F55036?style=flat-square">
  <img src="https://img.shields.io/badge/RAGAS-2B0A13?style=flat-square">
</p>
<p>
  <b>Machine Learning</b><br>
  <img src="https://skillicons.dev/icons?i=python,sklearn" alt="Python, scikit-learn">
  <img src="https://img.shields.io/badge/SQL-2B0A13?style=flat-square&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/XGBoost-6C1026?style=flat-square">
  <img src="https://img.shields.io/badge/LightGBM-D2042D?style=flat-square">
  <img src="https://img.shields.io/badge/CatBoost-6C1026?style=flat-square">
  <img src="https://img.shields.io/badge/SHAP%20%2F%20LIME-2B0A13?style=flat-square">
</p>
<p>
  <b>MLOps & tools</b><br>
  <img src="https://skillicons.dev/icons?i=fastapi,docker,githubactions,git" alt="FastAPI, Docker, GitHub Actions, Git">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white">
  <img src="https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white">
</p>

---

### 📊 GitHub in real time

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Ikram-Saidane&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&border_radius=14&bg_color=6C1026&title_color=FFFFFF&icon_color=FF8FA6&text_color=FFE1E7&ring_color=FF8FA6" alt="GitHub stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ikram-Saidane&layout=compact&hide_border=true&border_radius=14&bg_color=6C1026&title_color=FFFFFF&text_color=FFE1E7" alt="Top languages">
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=Ikram-Saidane&hide_border=true&border_radius=14&background=6C1026&ring=FF8FA6&fire=FF8FA6&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=FFE1E7&sideLabels=FFE1E7&dates=FFD6DE&stroke=8A1530" alt="Contribution streak">
</p>
<p align="center">
  <img width="100%" src="https://raw.githubusercontent.com/Ikram-Saidane/Ikram-Saidane/output/contrib-graph.svg" alt="Contribution graph">
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ikram-Saidane/Ikram-Saidane/output/github-snake-dark.svg">
    <img alt="A cherry-red snake eating my contribution graph" src="https://raw.githubusercontent.com/Ikram-Saidane/Ikram-Saidane/output/github-snake.svg">
  </picture>
</p>

---

### ⚡ Recent activity

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

---

### 🎓 Journey

| When | What |
|---|---|
| 2025 → now | **M2 AI, Data Science & Agentic AI** · Université Paris Dauphine – PSL |
| 2025 → now | **IT & training lead** · DataIn club · co-organiser of the EY × Dauphine hackathon |
| Dec 2025 | **PRIMIA** · AI / InsurTech hackathon (Dauphine & EY) |
| Jan – May 2025 | **GenAI / RAG intern** · Capgemini Engineering · grade 18/20 |
| 2023 – 2024 | **Web development intern** · Dreamtek Consulting |
| 2021 – 2025 | **BSc Computer Science, Software Engineering** · ISTIC |

---

<p align="center">
  <b>Hiring a GenAI / ML intern from February 2027?</b><br>
  Let's talk: <a href="mailto:ikram.saidane@dauphine.eu">ikram.saidane@dauphine.eu</a> · <a href="https://ikram-saidane.github.io">ikram-saidane.github.io</a>
  <br><br>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:D2042D,100:6C1026&height=110&section=footer" width="100%" alt="">
</p>
