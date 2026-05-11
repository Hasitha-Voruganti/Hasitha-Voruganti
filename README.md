<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1f35,100:0d3b8c&height=200&section=header&text=HASITHA%20VORUGANTI&fontSize=52&fontColor=58a6ff&fontAlignY=38&desc=AI%20Engineer%20%E2%80%A2%20Data%20Scientist%20%E2%80%A2%20Full%20Stack%20Developer&descAlignY=60&descColor=8b949e&animation=fadeIn" />

### `Building intelligent systems. Turning raw data into real decisions.`

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hasitha-voruganti-a7168a2b8)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hasithavoruganti@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Hasitha-Voruganti)

</div>

---

<div align="center">

```python
class Hasitha:
    location     = "Hyderabad, India 🇮🇳"
    education    = "B.Tech Computer Science"
    focus        = ["AI/ML", "Data Science", "Data Analytics", "Full Stack Dev"]
    currently    = "Deepening expertise in advanced Machine Learning & LLM systems"
    open_to      = "Open-source collaborations & innovative AI projects"
    philosophy   = "Don't just analyze data — build systems that act on it"
```

</div>

---

## 👨‍💻 About Me

I'm a Computer Science student from Hyderabad with a genuine passion for building **end-to-end intelligent systems** — not just notebooks, but production-ready platforms that ingest raw data, reason over it, and deliver real decisions.

My work spans the full AI pipeline: designing **agentic RAG architectures** with hybrid search and self-correcting reasoning loops, building ML models with SHAP explainability, shipping interactive analytics dashboards, and developing full-stack AI-powered web applications.

What drives me is the intersection of **intelligence and utility** — AI that doesn't just impress on paper, but genuinely solves problems people face.

- 🤖 **AI/ML** — RAG systems, LLM integration, classification, NLP, explainability
- 📊 **Data Science** — end-to-end pipelines, feature engineering, model evaluation
- 📈 **Analytics** — advanced SQL, Power BI dashboards, business intelligence
- 🌐 **Full Stack** — React + FastAPI, Docker deployments, REST APIs

---

## 🚀 Featured Projects

---

### 🧠 [Corporate Brain — Agentic RAG Knowledge Assistant](https://github.com/Hasitha-Voruganti)
> *Enterprise AI that reads your company's documents — and actually understands them*

Most enterprise search is dumb keyword matching. Corporate Brain is different: a **self-correcting AI agent** that plans its retrieval strategy, fuses semantic and keyword search, verifies its own confidence, and rewrites queries when uncertain — all enforced with role-based access controls per employee.

| Layer | What it does |
|-------|-------------|
| 🔍 **Search** | Hybrid: Qdrant semantic vectors + Elasticsearch BM25, fused with RRF |
| 🎯 **Reranking** | ms-marco-MiniLM cross-encoder for precision scoring |
| 🤖 **Agent Loop** | Plan → Act → Verify with query rewriting and self-reflection |
| 🔐 **Security** | JWT auth + RBAC enforced at the vector database level |
| ⚡ **Performance** | Redis caching for instant repeat query responses |
| 📄 **Ingestion** | PDF, DOCX, XLSX, PPTX, TXT + OCR fallback via Tesseract |

`FastAPI` `React` `Qdrant` `Elasticsearch` `PostgreSQL` `Redis` `Groq LLaMA 3.1` `Docker`

---

### 📊 [DataMind — AI Data Analyst](https://github.com/Hasitha-Voruganti)
> *Upload any dataset. Ask questions. Get intelligence. No data science degree required.*

DataMind democratizes data analysis. Upload a messy real-world file in any format, ask questions in plain English, and watch an AI-powered analyst automatically clean, visualize, and explain your data — all in one platform.

- 📁 **Universal ingestion** — CSV, Excel, JSON, TSV, Parquet all supported
- 🧹 **One-click cleaning** — intelligently resolves nulls, duplicates, and outliers
- 📈 **6 interactive chart types** + correlation heatmap with drill-down controls
- 🤖 **Conversational AI** — LLaMA 3.1-powered chat for natural language analysis queries
- ⚡ **6 quick-action prompts** for instant common insights
- 💾 **Export** cleaned datasets as ready-to-use CSV

`FastAPI` `Pandas` `NumPy` `React 18` `Vite` `Chart.js` `Framer Motion` `Groq AI`

---

### 📚 [AI Study Assistant](https://github.com/Hasitha-Voruganti)
> *Your intelligent exam companion — upload, ask, quiz, master*

Transforms static PDFs into an active, adaptive learning experience. The AI doesn't just answer questions — it identifies your weak spots and drills you on them before your exam does.

- 🤖 **Contextual Q&A** — context-aware answers sourced directly from your documents
- 📝 **Smart quiz engine** — auto-generated MCQs at Easy / Medium / Hard / Mixed difficulty
- 🃏 **Flashcard system** — AI-created cards with Mastered vs Needs Revision tracking
- 🎯 **Weakness detection** — automatically flags topics where performance drops below 60%
- 📊 **Progress dashboard** — score trends, subject distribution, and streak tracking

`React` `Node.js` `MongoDB` `Express` `TailwindCSS` `Groq LLaMA 3`

---

### 📉 [Employee Attrition Intelligence System](https://github.com/Hasitha-Voruganti)
> *Know who's about to quit — before they hand in their notice*

A full production-grade ML platform that predicts employee attrition with automated model selection, SHAP explainability, and a 7-page React analytics dashboard. Trained and evaluated on the real **IBM HR Analytics dataset (1,470 employees)**.

| Rank | Model | ROC-AUC | F1 Score | Accuracy |
|------|-------|---------|----------|----------|
| 🥇 Best | XGBoost | **0.7860** | **0.4375** | 82.6% |
| 🥈 | RandomForest | 0.7858 | 0.3333 | 82.3% |
| 🥉 | LightGBM | 0.7821 | 0.4337 | **84.0%** |

> Best model auto-selected by composite score: `0.6 × ROC-AUC + 0.4 × F1`

**11 engineered features** — TenureRatio, SatisfactionScore, PromotionLag, JobHopper, IncomePerYearExp & more  
**SHAP explainability** — global feature importance + per-employee waterfall charts  
**16 FastAPI endpoints** | **7-page React SPA** | Real-time attrition gauge & HR risk recommendations

`XGBoost` `LightGBM` `SHAP` `FastAPI` `React` `Scikit-learn`

---

### ❤️ [Heart Disease Prediction App](https://github.com/Hasitha-Voruganti)
> *Clinical-grade risk scoring — interactive and deployed*

An SVM-powered web application that assesses heart disease likelihood from patient vitals, with a live visual risk gauge for clear, actionable output — accessible to non-specialists.

- SVM classifier on Kaggle Heart Failure dataset (Age, Cholesterol, ECG, ST Slope & more)
- Dynamic **Low / Medium / High** risk gauge updating in real time
- Full clinical label descriptions — usable without a medical background

`Python` `Scikit-learn (SVM)` `Streamlit` `Plotly` `Pandas`

---

### 🏥 [AI Obesity Level Prediction System](https://github.com/Hasitha-Voruganti)
> *Preventive healthcare intelligence — built in R, deployed to the cloud*

An R-based ML web app that assesses obesity risk from lifestyle habits in real time. Deployed on **ShinyApps.io** for zero-install access anywhere.

- Naive Bayes classifier on eating habits, activity levels, and physical metrics
- Real-time BMI calculation with personalised health recommendations
- Fully interactive Shiny dashboard with live prediction updates

`R` `Shiny` `Naive Bayes` `ShinyApps.io`

---

### 🛍️ [Customer Shopping Behavior Analysis](https://github.com/Hasitha-Voruganti)
> *From raw transactions to boardroom-ready insights*

A three-stage analytics pipeline across ~3,900 customer records — uncovering spending patterns, customer segments, and subscription behavior.

`Python (Pandas)` → data cleaning & feature engineering → `MySQL` → SQL business analysis → `Power BI` → interactive dashboard

`Pandas` `MySQL` `Power BI` `Data Storytelling`

---

### 👥 [HR Attrition Analytics Dashboard](https://github.com/Hasitha-Voruganti)
> *Power BI deep-dive: who's leaving, why, and what to do about it*

| Metric | Value |
|--------|-------|
| 👥 Total Employees | 961 |
| 🚪 Attrition Rate | **13.84%** |
| 💡 Key Finding | 110 of 133 leavers earn ≤ 5K — **low pay is the #1 retention lever** |
| 📅 Risk Window | Year 1 attrition spike — critical onboarding gap identified |

`Power BI` `DAX` `HR Analytics`

---

### 🔍 [Customer Review Analytics — Pure SQL](https://github.com/Hasitha-Voruganti)
> *100K+ Amazon reviews → product intelligence — entirely inside MySQL*

Proves a well-architected SQL schema can handle the full lifecycle of sentiment analysis and fraud detection — no Python, no ML frameworks. Just SQL, done seriously.

- **Custom 50-word sentiment lexicon** (-3 to +3 tiered scoring)
- **Fake review detection** via star-rating vs. text-sentiment mismatch flagging
- **5 analytical views** forming a complete business reporting layer
- **12 insight queries** — rolling 3-month averages, YoY sentiment shifts, category health

`MySQL 8.0` `Window Functions` `CTEs` `Sentiment Analysis` `Fraud Detection`

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**AI / ML / Data**

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

**Backend & Databases**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)

**Frontend & DevOps**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Hasitha-Voruganti&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Hasitha-Voruganti&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9)

![GitHub Streak](https://streak-stats.demolab.com?user=Hasitha-Voruganti&theme=tokyonight&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff)

</div>

---

## 📫 Let's Connect

<div align="center">

Always open to interesting problems, research discussions, and open-source collaborations.  
If you're building something ambitious in AI/ML — let's talk.

<br/>

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hasitha-voruganti-a7168a2b8)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hasithavoruganti@gmail.com)

<br/>

---

*"Data is the raw material. Intelligence is what you build with it."*

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Hasitha-Voruganti&style=for-the-badge&color=58a6ff&label=PROFILE+VIEWS)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d3b8c,50:1a1f35,100:0d1117&height=100&section=footer" />
