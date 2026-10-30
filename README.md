<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=190&section=header&text=Arush%20Ugal&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=36" width="100%" alt="Arush Ugal" />

<a href="https://github.com/ARUSHUGAL">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=3000&pause=800&color=3FB950&center=true&vCenter=true&width=700&lines=Junior+SOC+Analyst+%40+ASU+Enterprise+Technology;I+build+AI+systems+%E2%80%94+then+look+for+how+they+break;Python+%C2%B7+TypeScript+%C2%B7+Security+Operations" alt="What I do" />
</a>

**Backend engineer with a blue-team seat.** I build AI systems — then go looking for the ways they break.

`CS @ Arizona State University '29` · `3.9 GPA` · `Data Science minor` · `Junior SOC Analyst @ ASU Enterprise Technology` · 📍 Tempe, AZ

[![Portfolio](https://img.shields.io/badge/Portfolio-arushugal.github.io-111827?style=for-the-badge&logo=githubpages&logoColor=white)](https://arushugal.github.io/portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Arush_Ugal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arushugal/)
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
`Python` · `Flask` · `transformers` · `PyTorch`

A journal that reads the entry back to you.

- A Hugging Face `sentiment-analysis` pipeline classifies each entry, then the app returns a supportive reply matched to that mood
- Flask app with per-mood response templates, run locally with `python run.py`
- [Source →](https://github.com/ARUSHUGAL/HearMeOut)

## 💼 Experience

**Junior SOC Analyst — ASU Enterprise Technology** · *2026 – present*

Selected for ASU's enterprise Security Operations Center work-and-learn program, run with industry partners including CrowdStrike and Google.

- Triage and document security alerts, working phishing, malware, and compromised-account investigations under senior analyst supervision
- Handle the email-security ticket queue; write incident reports and escalation documentation
- Progressing through a structured track: SOC fundamentals → live monitoring and triage → automation and SOAR → capstone
- Pursuing funded industry certifications alongside the program

**Software Engineer Intern — Paytm** · *Jul – Aug 2026*

- Traced user journeys across a **233-file** payments codebase and mapped where failure modes could reach production
- Wrote **174 tests** across payment services, HMAC/JWT authentication, and input validation
- Found a JWT check that accepted tokens with **no expiry** — a replay risk — and a refund path that allowed amounts **above the order total**
- Proposed 6 performance improvements, including a Redis caching strategy for hot read paths

**Data Analyst — Global Career Accelerator** · *Aug – Dec 2025*

- Built Python and SQL pipelines over Intel and Grammy Awards datasets
- Condensed raw data into trend summaries used for program decisions

## 🛠 Toolbox

<div align="center">

<img src="https://skillicons.dev/icons?i=py,ts,js,java,react,nodejs,express,firebase,docker,git,aws&theme=dark&perline=11" alt="Python, TypeScript, JavaScript, Java, React, Node.js, Express, Firebase, Docker, Git, AWS" />

</div>

| | |
|---|---|
| **Languages** | Python · TypeScript / JavaScript · Java · SQL · C++ |
| **Backend** | Node.js · Express · REST · Socket.io · Firebase (Firestore, Auth, Storage) |
| **Frontend** | React 18 · Tailwind CSS · Vite |
| **Data** | pandas · NumPy · matplotlib · time series · statistical analysis |
| **Infrastructure** | Git · Docker · Vercel · Railway · AWS fundamentals · CI/CD |
| **Security** | Authentication (JWT, HMAC, OAuth) · access control · vulnerability identification · alert triage · incident documentation |

## 📚 Right now

- Junior at ASU, graduating **May 2029** — looking for **Summer 2027 software engineering and security engineering internships**
- Taking **Information Assurance** this semester
- Going deeper on backend fundamentals: distributed systems, caching, testing in production
- Solving NeetCode in public → [neetcode-submissions](https://github.com/ARUSHUGAL/neetcode-submissions)

---

<sub>Open to backend, platform, AI-infrastructure, and security engineering roles · arushugal@gmail.com</sub>
