<h1 align="center">Hi, I'm Navya </h1>
<p align="center">Backend and infrastructure engineer, recent CS graduate (CGPA 9.83), building reliable systems and AI agent tooling. Interested in backend, SRE, and AI infra roles at fast moving product teams.</p>

<div align="center">
  <a href="https://navyabijoy.github.io/cv/">Portfolio</a> •
  <a href="mailto:navyabijoy14@gmail.com">Email</a> •
  <a href="https://www.linkedin.com/in/navya-bijoy-883a35249">LinkedIn</a> •
  <a href="https://leetcode.com/navyaaaa13">LeetCode</a>
</div>

<br>

## About Me

- CS graduate from SRM Institute of Science and Technology, CGPA 9.83, class of 2026
- Two internship rotations at Guidewire Software, shipping Java backend services for a production application with 5,000+ daily active users
- Backend and platform engineering, with growing focus on AI agent infrastructure and self-healing systems
- 10+ merged PRs across Aden (YC W20) and other open source ML projects
- Top 25 at the Google DeepMind Bangalore Hackathon 2026 (from 4,000+ applicants)
- LeetCode Knight (1909 rating, top 4% globally across 800k+ participants)
- Based in Bengaluru, India, open to remote-first roles

---

## ⚒️ Skills & Tools

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,java,go,js,ts,cpp" alt="languages"/>
  <img src="https://skillicons.dev/icons?i=spring,nodejs,express,react,nextjs,tailwind" alt="backend+frontend"/>
  <img src="https://skillicons.dev/icons?i=postgres,redis,mongodb,supabase,firebase,prisma" alt="databases"/>
  <img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,terraform,grafana,githubactions,postman" alt="cloud+devops"/>
</div>

---

## 🔭 Selected Projects

**Foresight — ML-Driven Predictive Self-Healing Platform**

Built a Kafka-streamed metrics pipeline feeding a PyTorch LSTM anomaly predictor that forecasts incidents 3-5 minutes ahead of a threshold breach, cutting MTTR from 5+ minutes to under 60 seconds. Tracked model versions and automated weekly retraining and drift detection with MLflow, with self-healing infra provisioned across 3 availability zones using Terraform-managed autoscaling (2 to 10 replicas).
`FastAPI` `Next.js` `Python` `Kubernetes` `Prometheus` `Docker` `LSTM Neural Networks`

**Fleet — Multi-Tenant Model Serving Gateway**

Streamed inference requests through Kafka into a PyFlink job computing rolling per-tenant and per-model error and latency windows, served via Feast to drive live canary promote and rollback decisions. Nightly Evidently AI drift detection via Airflow flags degrading tenant-model pairs, while the gateway enforces Redis-backed rate limiting and PostgreSQL cost attribution across 10+ tenants on Kubernetes.
`Go` `Apache Kafka` `PyFlink` `Feast` `Redis` `MLflow` `BentoML` `Airflow` `Evidently AI`

**CodeMap — Local-First Codebase Onboarding AI Agent**

A local-first RAG pipeline that indexes repos into Supabase via pgvector, chunking by function and class boundaries and grounding Llama 3.2 answers in cited file and line context. Ships with a Clerk-gated chat interface for per-team repo access, with the vector database and LLM service containerized via Docker Compose for single-command deployment.
`Next.js` `TypeScript` `FastAPI` `Python` `Ollama` `Llama 3.2` `Clerk` `Supabase`

**Conduit — SaaS Integration Gateway**

A Go based gateway for connecting to third-party SaaS APIs, with AES-256-GCM encrypted credential storage, automatic OpenAPI spec generation, and built-in Prometheus observability.
`Go` `OpenAPI` `Prometheus`

**Anchorpoint — Real-Time Geospatial Facility Siting Tool**

A real-time tool for facility siting decisions, built with FastAPI and WebSockets. Runs a two-stage ETL pipeline and uses a SQLite coordinate cache for fast geospatial lookups.
`Python` `FastAPI` `WebSockets` `SQLite`

---

## 🏆 Achievements

- LeetCode Knight (1909), top 4% globally across 800k+ participants. Rank 63 in Weekly Contest 509.
- Top 25 at Google DeepMind Bangalore Hackathon 2026, selected from 250 finalists out of 4,000+ applicants.
- "Best Scalable Idea" at Hack Summit 5.0, among 200+ participants.
- Academic Excellence Award: 10/10 SGPA in semesters III, V, and VIII. 3rd rank for academic performance at SRM.
- AWS Cloud Foundations Certified and AWS Machine Learning Foundations Certified.

---

## ⭐ GitHub Activity & Stats

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=navyabijoy&radius=16&theme=github-dark&area=true&order=5" height="200" alt="activity graph"/>
  <p>
    <img src="https://github-readme-stats.vercel.app/api?username=navyabijoy&show_icons=true&locale=en&theme=dark" alt="GitHub stats" />
  </p>
  <p>
    <img src="https://komarev.com/ghpvc/?username=navyabijoy&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />
  </p>
</div>

---

## 📫 Contact

- Portfolio: [Link](https://navyabijoy.github.io/cv/)
- Email: navyabijoy14@gmail.com
- LinkedIn: [Link](https://www.linkedin.com/in/navya-bijoy-883a35249)

<p align="center">Open to backend, SRE, and AI infra roles or even hackathons ! Feel free to reach out or open a PR.</p>
