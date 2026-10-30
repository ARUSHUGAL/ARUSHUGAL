<div align="center">

# Arush Ugal

**Backend-leaning software engineer — I build AI systems and take them the whole way.**

`CS @ Arizona State University '27` · `3.9 GPA` · `Data Science minor` · 📍 Tempe, AZ

[![Portfolio](https://img.shields.io/badge/Portfolio-arushugal.github.io-111827?style=for-the-badge&logo=githubpages&logoColor=white)](https://arushugal.github.io/portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Arush_Ugal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arush-ugal-b1a8a625a/)
[![Email](https://img.shields.io/badge/Email-arushugal@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arushugal@gmail.com)

</div>

---

I like the part of engineering where something stops being a demo. My projects all end in the same place: a real user can open it, break it, and still get a working answer back.

## 🚀 What I've built

### HireMeNow — AI recruitment platform
`React 18` · `TypeScript` · `Node/Express` · `Firebase` · `Socket.io` · `Twilio`
**Winner — DevLabs Dev Hacks**

Candidates upload one PDF instead of filling out a form; recruiters search them by skills, experience, salary, and location.

- Extracts **40+ structured fields** from unstructured resume PDFs, including malformed and scanned files
- Real-time compatibility scoring over **Socket.io**, filtered across five dimensions
- Browser-based video interviews via **Twilio**, with separate candidate and recruiter access
- Firebase Auth, Firestore, and Storage with role-based security rules
- [Source →](https://github.com/ARUSHUGAL/hiremenow-recruitment-platform)

### resume-claude — ATS-scored resume pipeline
`Python` · `LaTeX` · `XeLaTeX`

Every application wants a different resume, and hand-editing LaTeX for each one wastes an evening. This takes one master resume plus a job posting and emits a tailored PDF — selecting relevant experience, rebuilding the LaTeX, compiling it, and scoring the result against the posting's keywords.

- Used for **20+ internship applications** this cycle
- Deterministic: the same posting always produces the same resume
- [Source →](https://github.com/ARUSHUGAL/resume-claude)

### Oil price analysis — quantitative pipeline
`Python` · `pandas` · `NumPy` · `matplotlib` · `yfinance`

A reproducible ETL over **10 years of daily Brent Crude prices** (~2,500 trading days), end to end in under a minute.

- Rolling 30-day mean and standard deviation with **3σ anomaly flagging** for volatility spikes
- Correlates flagged moves against macro events — the 2020 demand collapse, the 2022 supply shock
- Multi-panel dashboard: price trend, 90-day moving average, 30-day rolling volatility, annotated events
- [Source →](https://github.com/ARUSHUGAL/oilbrentanalysis)

### HearMeOut — AI mood journal
`Python` · `Flask` · `PyTorch` · `transformers` · `VaderSentiment`

A journal that reads the entry back to you.

- Transformer sentiment scoring with a VaderSentiment lexicon baseline
- Flask app, runs locally from `python run.py`
- [Source →](https://github.com/ARUSHUGAL/HearMeOut)

## 💼 Experience

**Software Engineer Intern — Paytm** · *Jul – Aug 2026*

- Traced user journeys across a **233-file** payments codebase and mapped where failure modes could reach production
- Wrote **174 unit tests**, surfacing an authentication bypass and several input-validation gaps before release
- Proposed 6 performance improvements, including a Redis caching strategy for hot read paths

**Data Analyst — Global Career Accelerator** · *Aug – Dec 2025*

- Built Python and SQL pipelines over Intel and Grammy Awards datasets
- Condensed raw data into trend summaries used for program decisions

## 🛠 Toolbox

| | |
|---|---|
| **Languages** | Python · TypeScript / JavaScript · Java · SQL · C++ |
| **Backend** | Node.js · Express · REST · Socket.io · Firebase (Firestore, Auth, Storage) |
| **Frontend** | React 18 · Tailwind CSS · Vite |
| **Data** | pandas · NumPy · matplotlib · time series · statistical analysis |
| **Infrastructure** | Git · Docker · Vercel · Railway · AWS fundamentals · CI/CD |

## 📚 Right now

- Junior at ASU, graduating **May 2027** — looking for **Summer 2027 software engineering internships**
- Going deeper on backend fundamentals: distributed systems, caching, testing in production
- Solving NeetCode in public → [neetcode-submissions](https://github.com/ARUSHUGAL/neetcode-submissions)

---

<sub>Open to backend, platform, and AI-infrastructure roles · arushugal@gmail.com</sub>
