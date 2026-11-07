# Hi, I'm Jeffrey 👋

**AI Engineer · I build LLM systems that are grounded in data, tested and easy to run.**

I'm an AI engineer with a background in backend and cloud engineering — Python, Go and Java
on AWS and Kubernetes. I work across the whole life of an LLM feature: designing the agent,
giving it the right tools and data, checking that it answers well, and running it in
production.

## 🔬 Selected project

**[Mawta](https://github.com/amaru-one/mawta)** — an open-source gradebook for Peruvian
schools, where AI drafts and the teacher decides. One Python service per school: agents draft
term plans and descriptive conclusions for teachers to review, and a LangGraph chat answers
school directors' questions through read-only SQL tools, on open models.

- **A boundary the model cannot cross:** the chat's tools run as a Postgres role that can read
  only a set of views, entered with `SET LOCAL ROLE` inside the transaction.
- **Schema as code:** typed SQLAlchemy models, SQLAlchemy Core queries and Alembic migrations
  checked in CI, with one database per school.
- **Rules as tested code:** the national promotion rules and "at risk" definitions live in the
  tools, each with its own test case.

## 🛠️ Toolbox

**AI**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-30A2FF?style=for-the-badge)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6566F1?style=for-the-badge&logo=openrouter&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-0F172A?style=for-the-badge)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)

**Backend, data and cloud**

[![Python, Go, Java, TypeScript, Svelte, PostgreSQL, Redis, Kafka, Docker, Kubernetes, AWS, Terraform](https://skillicons.dev/icons?i=python,go,java,ts,svelte,postgres,redis,kafka,docker,kubernetes,aws,terraform&perline=12)](https://skillicons.dev)

## 📫 Let's talk

I'm always happy to talk about agents, RAG, evaluation and open models.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jeffrey_Orihuela-0A66C2?style=for-the-badge)](https://linkedin.com/in/jeffrey-orihuela)
