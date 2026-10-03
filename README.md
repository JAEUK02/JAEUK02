# Hi, I'm Jaeuk Lee

I work across technical product planning and hands-on implementation, turning user needs into multilingual tools, Python applications, and applied machine learning prototypes. My academic background combines International Studies and Information Systems at Hanyang University.

**[LinkedIn](https://www.linkedin.com/in/jaeuk-lee-4723a9305) · [Email](mailto:dlwodnr0223@gmail.com)**

## Start with School Buddy

[School Buddy](https://github.com/JAEUK02/schoolbuddy) is a team hackathon prototype for multicultural families navigating Korean school notices. It explores the gap between translating a term and explaining what a parent needs to do.

- **Representative implementation:** [`test_jaeuk.py` on `model_optimization`](https://github.com/JAEUK02/schoolbuddy/blob/model_optimization/test_jaeuk.py) connects Gemini image OCR, PDF text extraction, S3 notice JSON, multilingual summaries, Titan embeddings, and PostgreSQL/pgvector retrieval.
- **My public contribution record:** [commit `ab3f202`](https://github.com/JAEUK02/schoolbuddy/commit/ab3f202c9e1f62416e17991163bf95d8fd2b82e3), adding the integrated experiment to this team fork. Shared implementation and contributor histories are explained in the project README.
- **Review route:** start with the repository README for the architecture and branch map. `main/app.py` is an earlier Nova Lite FAQ variant; the integrated OCR/RAG experiment is on a separate branch.
- **Reliability follow-up:** [merged PR #1](https://github.com/JAEUK02/schoolbuddy/pull/1) adds notice validation, accurate indexing status, and DB cleanup. The [setup and offline test guide](https://github.com/JAEUK02/schoolbuddy/blob/model_optimization/docs/notice-development.md) records **23 offline tests and 40 subtests passed** with mocks; live integration remains unverified.

The project implements four language choices and document-context Q&A. It remains a prototype: retrieval quality, translation accuracy, and production operation are separate evaluation tasks.

## Other public work

| Project | What to inspect | Scope |
| --- | --- | --- |
| [SecurityProject-IDS-](https://github.com/JAEUK02/SecurityProject-IDS-) | CIC-IDS2017 preprocessing, Logistic Regression / Random Forest / LightGBM / GRU autoencoder comparisons, and archived evaluation outputs | Course project notebooks; results have reproducibility limits described in the README |
| [RT-IoT2022](https://github.com/JAEUK02/RT-IoT2022) | Random Forest multiclass classification, per-class metrics, feature importance, and PCA plots | Offline notebook study of IoT traffic |
| [Django2025](https://github.com/JAEUK02/Django2025) | Content models, list/detail views, signup/login, and comment-flow code | Web coursework; comment-flow regression tests and limitations are documented |
| [Andorid2025](https://github.com/JAEUK02/Andorid2025) | Java Android number-memory game, dynamic layouts, touch events, and UI-thread updates | Android coursework |

## Product work in international education

- **[UNIE website](docs/unie-website.md):** I handled the homepage design and Bubble implementation with custom HTML/CSS, aligning the direction with the planning team in meetings. The case study includes selected interface and implementation evidence. [Public website](https://unie.kr/) · [FAQ](https://unie.kr/faq).
- **[Scholarship exploration tool](docs/scholarship-tool.md):** Conversations with students during school visits in Mongolia led me to build a quiz prototype around scholarship interest. I designed the route into company consultation, student-response recording in Google Sheets, and GA4 behavior tracking. The prototype uses rule-based example candidates; scholarship awards are determined by universities.

This work grew from AWS study and the School Buddy hackathon into practical use of S3 hosting, lead collection, and GA4 behavior analysis.

These case studies describe the public interfaces, my role, and the implementation approach. Selected implementation evidence is included with approval; full application sources, operational settings, and individual student data are excluded.

## Technologies in these projects

**Python · Streamlit · AWS Bedrock / S3 · Gemini · PostgreSQL / pgvector · pandas · scikit-learn · LightGBM · TensorFlow · Django · Java / Android · React / Vite / Tailwind · Bubble · Google Sheets · GA4**

The project links show where each technology is used. Team prototypes, notebook studies, and coursework are identified in their READMEs so that implementation and limitations can be reviewed together.

## Background

- Hanyang University: International Studies and Information Systems.
- Exchange-study background: University of Sheffield and Waseda University.
- Deloitte Data Analytics Job Simulation through Forage: a training simulation.

日本語サマリー：Python、機械学習、多言語情報ツールの実装と検証に取り組んでいます。各リポジトリのREADMEから、実装例・貢献履歴・プロジェクトの範囲を確認できます。
