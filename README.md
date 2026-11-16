<p align="right">
  <img src="https://komarev.com/ghpvc/?username=byteKumar&color=blue">
</p>

<div align="center">
  <h1>Hi, I'm Chaman Kumar 👋</h1>
  <h3>Software Engineer · MS Computer Science at Northeastern (graduating December 2026)</h3>
  <p>Former AWS intern on Amazon Redshift · 2 years full-time at AKQA · backend, systems and full-stack</p>
  <p>
    <a href="https://chamankumar.vercel.app/">Portfolio</a> •
    <a href="https://www.linkedin.com/in/chamankumar5/">LinkedIn</a> •
    <a href="mailto:kumar.cham@northeastern.edu">Email</a>
  </p>
</div>

---

## 🔎 What I'm looking for

**Full-time, new-grad software engineering roles**, starting after I graduate in **December 2026**.

- **Roles:** backend, full-stack, infrastructure and platform, database and systems, data engineering, ML engineering
- **Location:** anywhere in the US, open to relocation
- **Education:** MS in Computer Science, Northeastern University, graduating **December 2026** (GPA 3.8/4.0)

If your team is hiring, I'd love to hear from you: [LinkedIn](https://www.linkedin.com/in/chamankumar5/) or [email](mailto:kumar.cham@northeastern.edu).

---

## 💼 Experience

**Amazon Web Services: Software Development Engineer Intern, Amazon Redshift** · *Jun 2026 to Sep 2026*
- Built server-side WHERE filtering in C++ for Redshift's SHOW TABLES / COLUMNS / SCHEMAS / GRANTS by reusing PostgreSQL's analyzer and executor (13 SQL operators).
- Cut exact-name catalog lookups on 30K tables from 2.7 s to 127 ms (21×); kept filter memory constant per row; tested 14 edge cases behind a feature flag.

**Hydrow: Software Engineering Co-op** · *Jan 2026 to May 2026*
- Built a diagnostics tool used by the firmware team: NestJS endpoint, S3 log fetch and a dependency-free TypeScript protobuf decoder charting 7 signals per handle.
- Shipped workout-history, interval-stats and 1RM REST APIs (NestJS, TypeORM, PostgreSQL) with 15 end-to-end tests.

**AKQA: Software Engineer** · *Jul 2022 to Aug 2024*
- Built React features for IWC Schaffhausen's global e-commerce site on Adobe Experience Manager; a React/Redux watch-strap configurator cut page load from 11 s to 4 s.
- Cut deployment errors 30% with Jenkins CI/CD and fixed 30+ browser and WCAG accessibility issues. Received AKQA's Q3 award for the IWC project.

**Northeastern University: Graduate Teaching Assistant** · *Jan 2025 to present*

*Earlier:* Full-Stack Developer, Aspiring Product Managers Club at Northeastern · Software Engineering Intern, BluePi · Teaching Assistant, Coding Ninjas

---

## 🚀 Featured projects

Every number below is measured and documented in the repo's `RESULTS.md`, and each repo runs its tests in GitHub Actions.

| Project | What it shows | Highlights |
|---|---|---|
| [**pg-durable-queue**](https://github.com/byteKumar/pg-durable-queue) | Backend, PostgreSQL, reliability | Durable job queue in TypeScript with SKIP LOCKED claims, leases and dead-lettering. 0 lost jobs across 1M jobs and 530 worker crashes; 12,632 jobs/s. |
| [**ledger-service**](https://github.com/byteKumar/ledger-service) | Java, Spring Boot, Kafka | Double-entry ledger with idempotent transfers and a transactional outbox. 2M concurrent transfers with 0 invariant violations; 0 of 30,000 events lost after a relay crash. |
| [**lsm-kv-store**](https://github.com/byteKumar/lsm-kv-store) | C++20, storage engines | LSM-tree key-value store with WAL, Bloom filters and compaction. 525K writes/s; 23× faster missing-key reads; 0 acknowledged writes lost in 100 crash tests. |
| [**timeseries-viewer**](https://github.com/byteKumar/timeseries-viewer) | React, performance, accessibility | Canvas + Web Worker chart for millions of points. 5M-point render 4,522 → 72 ms; 2.8 → 60 fps; Lighthouse 100. |
| [**movement-classifier**](https://github.com/byteKumar/movement-classifier) | ML engineering | PyTorch 1D-CNN vs. gradient boosting on wearable sensor data, served as ONNX via FastAPI (0.45 ms per prediction), with a drift monitor (0/200 false alarms). |
| [**news-intelligence-studio**](https://github.com/byteKumar/news-intelligence-studio) | NLP (team project) | Fake-news classification (97.85% test accuracy), LDA/NMF/KMeans topic modeling (my part), summarization and claim verification. |
| [**taxi-lakehouse**](https://github.com/byteKumar/taxi-lakehouse) | Data engineering | DuckDB + dbt + Dagster pipeline over 98.3M NYC taxi trips with 45 data-quality tests and incremental loads. |
| [**job-match-ranker**](https://github.com/byteKumar/job-match-ranker) | NLP retrieval | Sentence-transformer + FAISS resume-to-job retrieval: +54% nDCG@10 over BM25; 23 ms p99 over 10K jobs. |

<details>
<summary>Earlier projects</summary>

- [PepperUni](https://github.com/byteKumar/pepperuni): MERN app that uses GPT-4 Turbo to tailor a resume to a job description ([live demo](https://pepperuni.onrender.com/))
- [LeetCode Power-Up](https://github.com/byteKumar/LeetCode-Power-Up): Chrome extension that adds solution videos and a per-problem scratchpad to LeetCode
- [DesignCraft](https://github.com/byteKumar/systemdesign): OOP, SOLID and design-patterns course with 50+ Java examples, used by 500+ students
- [Advanced Image Manipulation](https://github.com/byteKumar/advanced_image_manipulation_and_enhancement_application): Java MVC image app with Strategy, Factory and Command patterns
- [Google Slides Generator](https://github.com/byteKumar/google_slide_generator) · [RecipeHub](https://github.com/byteKumar/RecipeHub)

</details>

---

## 🛠️ Skills

**Languages:** C++, Java, TypeScript, Python, SQL, JavaScript

**Backend and data:** Spring Boot, Node.js, NestJS, Fastify, Express, Kafka, PostgreSQL (internals), Amazon Redshift, MySQL, MongoDB, DuckDB, dbt, Dagster

**Frontend:** React, Next.js, Redux, Canvas, Web Workers, Vite, Playwright, Lighthouse CI

**ML:** PyTorch, scikit-learn, sentence-transformers, FAISS, ONNX Runtime, FastAPI, MLflow, pandas, NumPy

**Cloud and tools:** AWS (S3, EC2, IAM), Docker, GitHub Actions, Jenkins, Prometheus, Grafana, k6, Testcontainers, GoogleTest, sanitizers, Linux, Git

**Certifications:** AWS Certified Developer (Associate), AWS Certified Cloud Practitioner

---

## 📚 Publications

- Co-author, ["Evaluation of Tracking System using Facial Recognition and Location"](https://ieeexplore.ieee.org/document/10541414), IEEE ICAC3N-23, December 2023
- Co-author, ["Understanding Factors Affecting Trust and Satisfaction with Banking in India"](https://ieeexplore.ieee.org/document/10541439), IEEE ICAC3N-23, December 2023

---

## 🌱 Beyond code

- Open-source contributor, GirlScript Summer of Code (ML/AI)
- Two years volunteering with the Welfare Association for the Handicapped: food distribution and teaching
- Usually found reading non-fiction, on a trail, or out on a run

---

<div align="center">
  <a href="https://chamankumar.vercel.app/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-chamankumar.vercel.app-darkblue?style=for-the-badge"></a>
  <a href="https://www.linkedin.com/in/chamankumar5/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Chaman%20Kumar-blue?style=for-the-badge&logo=linkedin"></a>
  <a href="mailto:kumar.cham@northeastern.edu"><img alt="Email" src="https://img.shields.io/badge/Email-kumar.cham%40northeastern.edu-red?style=for-the-badge&logo=gmail"></a>
</div>
