<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:4c1d95,100:7c3aed&height=200&section=header&text=Jaeuk%20Lee&fontColor=ffffff&fontSize=54&fontAlignY=32&desc=Software%20Engineer%20·%20AI%20/%20ML%20·%20Product&descAlignY=52&descSize=18&animation=fadeIn" />

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=A78BFA&center=true&vCenter=true&width=680&lines=Building+AI+systems+that+remove+language+barriers;Cloud-native+engineering+on+AWS;Data+%26+Security+driven+problem+solving;International+Studies+%2B+Information+Systems" />

<br/>

![Hanyang University](https://img.shields.io/badge/Hanyang_University-Information_Systems_·_International_Studies-4C1D95?style=for-the-badge&labelColor=1a1a2e)
![Waseda University](https://img.shields.io/badge/Waseda_University-Computer_Science_(Exchange)-5B21B6?style=for-the-badge&labelColor=1a1a2e)
![University of Sheffield](https://img.shields.io/badge/Univ._of_Sheffield-International_Relations_(Exchange)-6D28D9?style=for-the-badge&labelColor=1a1a2e)

![Location](https://img.shields.io/badge/📍_Tokyo,_Japan-1a1a2e?style=for-the-badge&labelColor=1a1a2e&color=312e81)

<br/>

<a href="https://www.linkedin.com/in/jaeuk-lee-4723a9305">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=1a1a2e" />
</a>
<a href="mailto:dlwodnr0223@gmail.com">
  <img src="https://img.shields.io/badge/Email-Reach_Out-8B5CF6?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1a1a2e" />
</a>
<a href="https://github.com/JAEUK02">
  <img src="https://img.shields.io/badge/GitHub-Follow-A78BFA?style=for-the-badge&logo=github&logoColor=white&labelColor=1a1a2e" />
</a>

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=JAEUK02&style=flat-square&color=7C3AED&label=Profile+Views)
![Followers](https://img.shields.io/github/followers/JAEUK02?style=flat-square&color=7C3AED&labelColor=1a1a2e&label=Followers)
![Stars](https://img.shields.io/github/stars/JAEUK02?style=flat-square&color=7C3AED&labelColor=1a1a2e&label=Stars)

</div>

---

## About

Software engineer working across **AI/ML, cloud infrastructure, and product** — with a background that spans International Studies and Information Systems at Hanyang University, and exchange programs at the University of Sheffield and Waseda University.

I build systems where the hard part is not the model, but the **problem definition**. At Global ENS I own products end to end: scoping the real user need, shipping a minimal version fast, and instrumenting it to learn. My AWS Hackathon project *School Buddy* came out of that mindset — multicultural parents in Korea don't need better translation, they need **interpretation** of cultural context that literal translation destroys.

- **AI / ML** — RAG pipelines, vector search, LLM prompt design, NLP clustering, anomaly detection
- **Full Stack** — Python, Java (Spring), Django, Android, Streamlit
- **Cloud & Data** — AWS (S3, Bedrock, RDS), PostgreSQL + pgvector, data pipelines
- **Product Engineering** — MVP scoping, GA4 instrumentation, cross-functional delivery with design and planning teams

**Open to** — Software Engineering / AI Engineering / Data roles · Internships & new grad (2027) · Korea 🇰🇷 · Japan 🇯🇵 · Remote

---

## Tech Stack

<div align="center">

**Languages**

![Skills](https://skillicons.dev/icons?i=python,java,js,html,css,mysql&theme=dark)

**Frontend**

![Skills](https://skillicons.dev/icons?i=react,html,css,bootstrap&theme=dark)

**Backend & Databases**

![Skills](https://skillicons.dev/icons?i=django,spring,postgres,mysql,sqlite&theme=dark)

**Cloud, DevOps & Tooling**

![Skills](https://skillicons.dev/icons?i=aws,git,github,docker,linux,vscode&theme=dark)

</div>

---

## AI / ML Expertise

| Domain | Proficiency | Details |
| :--- | :---: | :--- |
| **Retrieval-Augmented Generation** | ⬤⬤⬤⬤⬤ | Chunking strategy (1000 chars / 200 overlap), 1536-dim Titan embeddings, cosine top-K retrieval, strict grounding — no source, no answer |
| **Vector Search & Embeddings** | ⬤⬤⬤⬤◯ | PostgreSQL + pgvector, AWS Bedrock Titan Embeddings, similarity tuning for multilingual corpora |
| **LLM Application Engineering** | ⬤⬤⬤⬤◯ | Gemini 2.5 Flash (Vision OCR + generation), LG EXAONE, 3-step explanation prompt design, 4-language output control |
| **Anomaly Detection / Security ML** | ⬤⬤⬤⬤◯ | CIC-IDS2017 (1.56M instances, 52 features), LightGBM / Random Forest / GRU Autoencoder benchmarking, precision–recall trade-off analysis |
| **NLP & Clustering** | ⬤⬤⬤◯◯ | Comparative technology-strategy analysis of Japanese, Korean, and global tech firms via NLP-based clustering |
| **Data Analytics** | ⬤⬤⬤◯◯ | Python analytics pipelines, GA4 funnel & drop-off tracking, Excel / Tableau (Deloitte simulation) |

---

## Featured Projects

<details open>
<summary><b>&nbsp;🎓&nbsp;&nbsp;School Buddy — AI Assistant for Multicultural Families</b></summary>

<br/>

> An AI school-notice assistant that *interprets* Korean school notices for multicultural families — OCR, four-language delivery, and RAG-based Q&A grounded in official government guides.

| | |
| :--- | :--- |
| **Stack** | AWS Bedrock (Titan Embeddings) · Google Gemini 2.5 Flash · PostgreSQL + pgvector · Amazon S3 · Streamlit |
| **Scale** | 4 languages (KO / EN / VI / ZH) · 1536-dim vectors · serverless pipeline on `us-west-2` |
| **Performance** | Vision OCR → structured JSON (title / summary / dates) → chunked embeddings → cosine top-K retrieval |
| **Security** | Strict grounding rule — the model answers **only** from retrieved documents; no source, no generated answer |
| **Impact** | Targets the 68% of multicultural families reporting difficulty with Korean-only notices, and the 45% unaware of support programs |
| **Repository** | [JAEUK02/schoolbuddy](https://github.com/JAEUK02/schoolbuddy) |

Team project for the AWS Hackathon (2026). I proposed the core concept of **"interpretation, not translation"** — the insight that Korean school terms such as *School Banking* translate literally but stay meaningless without cultural context. I built the Bedrock-based chatbot prototype with a Streamlit frontend, designing a three-step explanation prompt (definition → why it matters → what the parent should do), and designed a category-based FAQ flow (school, medical, administrative, welfare, legal) to lower the barrier for parents unsure how to phrase a question.

</details>

<details>
<summary><b>&nbsp;🛡️&nbsp;&nbsp;Anomaly-Based Intrusion Detection Using Machine Learning</b></summary>

<br/>

> A comparative study of four ML models for anomaly-based intrusion detection, evaluating the trade-off between detection performance and real-time viability.

| | |
| :--- | :--- |
| **Stack** | Python · LightGBM · scikit-learn (Random Forest, Logistic Regression) · TensorFlow (GRU Autoencoder) |
| **Scale** | CIC-IDS2017 — 1.56M instances, 52 numerical features · 70/30 stratified split (1,093,197 / 468,513) |
| **Performance** | LightGBM — **F1 0.9965**, recall 0.9996, 3.03s inference · Random Forest — F1 0.9956, 7.02s · GRU AE — precision 0.9838 but recall 0.3148 |
| **Security** | Analysis of adversarial evasion, data poisoning, privacy leakage, and XAI/regulatory compliance (GDPR Art. 22) |
| **Impact** | Concluded LightGBM offers the best performance/efficiency trade-off for deployment; GRU AE is best used in hybrid systems for zero-day coverage |
| **Repository** | [JAEUK02/SecurityProject-IDS-](https://github.com/JAEUK02/SecurityProject-IDS-) |

Course paper written with a team of four. Beyond raw accuracy, the paper argues that **F1 and inference latency — not accuracy — are the decision metrics** for IDS on imbalanced traffic, and pairs the benchmark with deployment guidance for constrained environments where explainability is a regulatory requirement, not a nice-to-have.

</details>

<details>
<summary><b>&nbsp;📡&nbsp;&nbsp;RT-IoT2022 — IoT Network Traffic Analysis</b></summary>

<br/>

> Machine learning analysis over the RT-IoT2022 dataset, extending intrusion-detection work from enterprise traffic to resource-constrained IoT environments.

| | |
| :--- | :--- |
| **Stack** | Python · Jupyter · scikit-learn · pandas |
| **Scale** | RT-IoT2022 real-time IoT traffic dataset |
| **Performance** | Model comparison with attention to lightweight inference on low-power devices |
| **Security** | Anomaly detection for IoT-specific attack surfaces |
| **Impact** | Complements the CIC-IDS2017 study — validates whether the LightGBM efficiency advantage generalizes to IoT traffic |
| **Repository** | [JAEUK02/RT-IoT2022](https://github.com/JAEUK02/RT-IoT2022) |

</details>

<details>
<summary><b>&nbsp;🤖&nbsp;&nbsp;LG Aimers — Korea–Japan Business Communication Assistant</b></summary>

<br/>

> A RAG prototype built on LG EXAONE to support business communication between Korean and Japanese teams.

| | |
| :--- | :--- |
| **Stack** | LG EXAONE · RAG · Python |
| **Scale** | Bilingual (KO / JA) business-context corpus |
| **Performance** | Retrieval-grounded generation to reduce hallucination in high-stakes business phrasing |
| **Security** | Grounded responses over a curated document set rather than open generation |
| **Impact** | Addresses the register and etiquette gap that generic translation tools miss in Korea–Japan business contexts |
| **Repository** | *Private — available on request* |

</details>

<details>
<summary><b>&nbsp;📊&nbsp;&nbsp;Tech Strategy Analysis — NLP Clustering</b></summary>

<br/>

> Comparative analysis of the technology strategies of Japanese, Korean, and global tech firms using NLP-based clustering.

| | |
| :--- | :--- |
| **Stack** | Python · NLP · clustering · pandas |
| **Scale** | Multi-region corpus across Japanese, Korean, and global firms |
| **Performance** | Unsupervised clustering to surface strategic groupings without predefined categories |
| **Security** | Public-source corpus only |
| **Impact** | Turns qualitative strategy discourse into a quantitative, comparable structure |
| **Repository** | *Coursework — available on request* |

</details>

---

## Experience

### Project Manager &nbsp;·&nbsp; Global ENS, Seoul
`Jan 2026 – Present`

Product ownership across web platforms for international education, working directly with design and planning teams from problem definition through launch and measurement.

- Built UNIE's main site on Bubble, collaborating with the design and planning teams
- Proposed and shipped a scholarship-estimate quiz site on AWS S3 after a business trip to Mongolia revealed that scholarships were students' primary concern — kept the build deliberately minimal, storing responses in Google Sheets and tracking funnel drop-off with GA4
- Launched the MVP of a multilingual (KO / EN / JA / ZH / VI) information platform for Hanyang University's International Education Institute
- Cut an initial AI auto-update plan after determining that tuition and visa details require staff verification regardless — redesigned the system to answer strictly from uploaded documents with sources shown

`Product Strategy` `AWS S3` `GA4` `Bubble` `Multilingual Systems` `MVP Scoping` `Cross-functional Delivery`

### Defensive Captain &nbsp;·&nbsp; LIONS, Hanyang University American Football Club
`Mar 2021 – Present` &nbsp;·&nbsp; Also with Big Bears, Waseda University AFC (`Mar 2026 – Present`)

Lead the defensive unit — game-plan installation, in-game adjustments, and player development across a multi-year roster.

`Leadership` `Team Coordination` `Performance Under Pressure`

### Republic of Korea Marine Corps
`Feb 2022 – Aug 2023`

Completed military service. Received the **Outstanding Trainee Award** from the Commander, U.S. Marine Corps Forces, Pacific.

`Discipline` `Joint Operations` `Resilience`

---

## Achievements

<div align="center">

| Recognition | Details |
| :--- | :--- |
| 🏅 **Outstanding Trainee Award** | Commander, U.S. Marine Corps Forces, Pacific — Republic of Korea Marine Corps |
| ☁️ **AWS Hackathon** | School Buddy — original concept, chatbot prototype, and UX flow (2026) |
| 🤖 **LG Aimers** | Selected participant — built an EXAONE + RAG prototype for Korea–Japan business communication |
| 🎓 **GPA 4.1 / 4.5** | Hanyang University — International Studies (BA) & Information Systems (BA, double major) |
| 🌏 **Dual Exchange Programs** | University of Sheffield, UK (2024) · Waseda University, Tokyo (2026) |
| 🏈 **Defensive Captain** | Hanyang University LIONS American Football Club |

</div>

---

## Certifications & Programs

<div align="center">

**Professional Programs**

![Deloitte](https://img.shields.io/badge/Deloitte-Data_Analytics_Job_Simulation_(Jul_2025)-86BC25?style=for-the-badge&logo=deloitte&logoColor=white&labelColor=1a1a2e)
![LG Aimers](https://img.shields.io/badge/LG_Aimers-AI_Program_·_EXAONE-A50034?style=for-the-badge&logo=lg&logoColor=white&labelColor=1a1a2e)
![AWS](https://img.shields.io/badge/AWS-Hanyang_Bootcamp_·_Hackathon-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white&labelColor=1a1a2e)

**Language Proficiency**

![TOEIC](https://img.shields.io/badge/TOEIC-935_(Jul_2025)-4C1D95?style=for-the-badge&labelColor=1a1a2e)
![JLPT](https://img.shields.io/badge/JLPT-N2_(Jan_2026)-5B21B6?style=for-the-badge&labelColor=1a1a2e)
![Korean](https://img.shields.io/badge/Korean-Native-6D28D9?style=for-the-badge&labelColor=1a1a2e)

</div>

---

## GitHub Analytics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=JAEUK02&show_icons=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=A78BFA&icon_color=7C3AED&text_color=c9d1d9&border_radius=10" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JAEUK02&layout=compact&hide_border=true&bg_color=0d1117&title_color=A78BFA&text_color=c9d1d9&border_radius=10&langs_count=8" />

<br/>

<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=JAEUK02&hide_border=true&background=0d1117&stroke=4c1d95&ring=7C3AED&fire=A78BFA&currStreakLabel=A78BFA&sideLabels=c9d1d9&currStreakNum=ffffff&sideNums=ffffff&dates=8b949e&border_radius=10" />

</div>

---

## GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=JAEUK02&theme=discord&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" />

</div>

---

## Contribution Activity

<div align="center">

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=JAEUK02&bg_color=0d1117&color=c9d1d9&line=7C3AED&point=A78BFA&area_color=4c1d95&area=true&hide_border=true&radius=10" />

</div>

---

## Contribution Snake

<div align="center">

<img width="100%" src="https://raw.githubusercontent.com/JAEUK02/JAEUK02/output/snake.svg" alt="Contribution snake animation" />

</div>

---

## Current Focus

```yaml
learning:
  - Distributed systems & cloud architecture (AWS Solutions Architect track)
  - Computer Science coursework at Waseda University, Tokyo
  - Production-grade RAG: evaluation, retrieval quality, hallucination control

building:
  - School Buddy — push notifications, calendar integration, additional languages
  - Multilingual information platforms for international students

exploring:
  - Security ML — adversarial robustness and explainability in IDS
  - Agentic LLM systems and tool-use architectures
  - Cross-border product design (KO / JA / EN)

open_to:
  - Software Engineering · AI Engineering · Data roles
  - Internships and new-grad opportunities (graduating Feb 2027)
  - Korea · Japan · Remote
```

---

## Connect

<div align="center">

<a href="mailto:dlwodnr0223@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-dlwodnr0223@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1a1a2e" />
</a>
<a href="https://www.linkedin.com/in/jaeuk-lee-4723a9305">
  <img src="https://img.shields.io/badge/LinkedIn-jaeuk--lee-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=1a1a2e" />
</a>
<a href="https://github.com/JAEUK02">
  <img src="https://img.shields.io/badge/GitHub-JAEUK02-7C3AED?style=for-the-badge&logo=github&logoColor=white&labelColor=1a1a2e" />
</a>

</div>

---

<div align="center">

*"The hard part was never the model — it was defining the problem worth solving."*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,50:4c1d95,100:1a1a2e&height=140&section=footer" />

</div>
