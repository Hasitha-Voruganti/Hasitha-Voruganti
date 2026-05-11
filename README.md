<div align="center">

```
██╗  ██╗ █████╗ ███████╗██╗████████╗██╗  ██╗ █████╗
██║  ██║██╔══██╗██╔════╝██║╚══██╔══╝██║  ██║██╔══██╗
███████║███████║███████╗██║   ██║   ███████║███████║
██╔══██║██╔══██║╚════██║██║   ██║   ██╔══██║██╔══██║
██║  ██║██║  ██║███████║██║   ██║   ██║  ██║██║  ██║
╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚═╝   ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═╝
```

### `Building intelligent systems. Turning raw data into real decisions.`

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hasitha-voruganti-a7168a2b8)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hasithavoruganti@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Hasitha-Voruganti)

---

```python
class Hasitha:
    location     = "Hyderabad, India 🇮🇳"
    focus        = ["AI/ML", "Data Science", "Data Analytics", "Full Stack"]
    currently    = "Learning advanced Machine Learning concepts"
    open_to      = "Open-source collaborations & innovative projects"
    superpower   = "Turning messy data into meaningful decisions"
```

</div>

---

## 🧠 What I Build

> End-to-end systems — from raw data ingestion to intelligent interfaces. I don't just train models. I build complete platforms.

---

## 🚀 Featured Projects

### 🏢 [Corporate Brain — Agentic RAG Knowledge Assistant](https://github.com/Hasitha-Voruganti/Agentic-RAG-Corporate-Brain)
> *Enterprise-grade AI knowledge retrieval with role-based access control*

An intelligent document query system for enterprises, built with a self-correcting **Plan → Act → Verify** agentic loop.

| Component | Technology |
|-----------|------------|
| 🔍 Search | Hybrid: Qdrant vector search + Elasticsearch BM25 |
| 🎯 Reranking | ms-marco-MiniLM cross-encoder |
| 🤖 LLM | Groq LLaMA 3.1 (free-tier powered) |
| 🔐 Security | JWT + Role-Based Access Control at vector DB level |
| ⚡ Caching | Redis for instant repeat query responses |
| 📄 Ingestion | PDF, DOCX, XLSX, PPTX, TXT + OCR fallback via Tesseract |

`FastAPI` `React` `Qdrant` `Elasticsearch` `PostgreSQL` `Redis` `Docker`

---

### 📚 [AI Study Assistant](https://github.com/Hasitha-Voruganti/AI-Study-Assistant)
> *Your intelligent exam companion — upload, ask, quiz, master*

AI-powered learning platform that transforms PDFs into an interactive study experience.

- 🤖 **AI Chat Q&A** — context-aware answers from your documents
- 📝 **Quiz Generator** — auto-MCQs at Easy / Medium / Hard / Mixed difficulty
- 🃏 **Smart Flashcards** — Mastered vs Needs Revision tracking
- 🎯 **Weak Topic Detection** — flags topics where quiz scores fall below 60%
- 📊 **Progress Dashboard** — score trends, subject distribution, streak tracking

`React` `Node.js` `MongoDB` `Express` `TailwindCSS` `Groq LLaMA 3`

---

### 📉 [Employee Attrition Intelligence System](https://github.com/Hasitha-Voruganti/Employee-Attrition-Intelligence-System)
> *Production-grade ML platform — predict who's leaving before they do*

End-to-end ML platform trained on the **IBM HR Analytics dataset (1,470 employees)**.

| Rank | Model | ROC-AUC | F1 Score | Accuracy |
|------|-------|---------|----------|----------|
| 🥇 | XGBoost | **0.7860** | **0.4375** | 82.6% |
| 🥈 | RandomForest | 0.7858 | 0.3333 | 82.3% |
| 🥉 | LightGBM | 0.7821 | 0.4337 | **84.0%** |

**11 engineered features** — TenureRatio, SatisfactionScore, PromotionLag, JobHopper, IncomePerYearExp & more  
**SHAP explainability** — global importance + per-employee waterfall charts  
**16 FastAPI endpoints** | **7-page React SPA** | Real-time attrition gauge & risk badges

`XGBoost` `LightGBM` `SHAP` `FastAPI` `React` `Scikit-learn`

---

### ❤️ [Heart Disease Prediction App](https://github.com/Hasitha-Voruganti/Heart-disease-prediction)
> *SVM-powered clinical decision support — deployed on Streamlit*

Predicts heart disease likelihood from patient vitals using a **Support Vector Machine** trained on the Kaggle Heart Failure dataset.

- Interactive patient parameter inputs with full clinical descriptions
- Visual risk gauge — **Low / Medium / High** probability display
- StandardScaler preprocessing pipeline matching training distribution

`Python` `Scikit-learn (SVM)` `Streamlit` `Plotly` `Pandas`

---

### 🏥 [AI Obesity Level Prediction System](https://github.com/Hasitha-Voruganti/Obesity-level-prediction)
> *Naive Bayes + Shiny — real-time health assessment*

R-based ML web app that predicts obesity levels from lifestyle data — deployed on **ShinyApps.io**.

- Naive Bayes classifier on eating habits, activity levels & physical metrics
- Real-time BMI calculation + personalized health recommendations
- Interactive dashboard with live prediction updates

`R` `Shiny` `Naive Bayes` `ShinyApps.io`

---

### 🛍️ [Customer Shopping Behavior Analysis](https://github.com/Hasitha-Voruganti/Customer-Shopping-Behavior-Analysis)
> *End-to-end analytics pipeline — Python → SQL → Power BI*

Full analytics pipeline on ~3,900 transactional records uncovering spending patterns, segmentation, and subscription behavior.

`Python (Pandas)` → `MySQL` → `Power BI`

`Data Cleaning` `SQL Business Analysis` `Interactive Dashboard`

---

### 👥 [HR Analytics Dashboard](https://github.com/Hasitha-Voruganti/HR-Analytics-Dashboard)
> *Power BI attrition deep-dive across 961 employees*

| Metric | Value |
|--------|-------|
| 👥 Total Employees | 961 |
| 🚪 Attrition Rate | **13.84%** |
| 💰 Avg Salary | 6.3K |
| 🔑 Top Insight | 110/133 leavers earn ≤ 5K — **compensation is #1 driver** |

`Power BI` `DAX` `HR Analytics` `Data Storytelling`

---

### 🔍 [Customer Review Analytics System — Pure SQL](https://github.com/Hasitha-Voruganti/Customer-review-analytics-sql)
> *100K+ Amazon reviews → intelligence — entirely inside MySQL*

Full sentiment analysis & fake review detection pipeline using zero ML frameworks — just SQL.

- **Custom 50-word sentiment lexicon** (-3 to +3 tier scoring)
- **Fake review detection** — star-vs-text sentiment mismatch flagging
- **5 analytical views** + **12 insight queries** (rolling averages, YoY shifts, category health)
- SQL features: `WINDOW FUNCTIONS` `CTEs` `PIVOT-style CASE` `ROWS BETWEEN`

`MySQL 8.0` `Advanced SQL` `Sentiment Analysis` `Fraud Detection`

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
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logo=xgboost&logoColor=white)
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
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

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

I'm always open to interesting problems, open-source collaborations, and research discussions.

[![LinkedIn](https://img.shields.io/badge/Let's_connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hasitha-voruganti-a7168a2b8)
[![Email](https://img.shields.io/badge/Drop_me_an_email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hasithavoruganti@gmail.com)

---

*"Data is the raw material. Intelligence is what you build with it."*

![Profile Views](https://komarev.com/ghpvc/?username=Hasitha-Voruganti&style=for-the-badge&color=58a6ff&label=PROFILE+VIEWS)

</div>
