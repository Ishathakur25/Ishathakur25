<!-- Replace every YOUR_USERNAME with your GitHub username -->

<h1 align="center">Hey, I'm Isha Thakur 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=00F5A0&center=true&vCenter=true&width=700&lines=Backend+%7C+AI+Applications+%7C+Software+Engineer;Building+reliable%2C+scalable+services;LLMs+%2B+RAG+%2B+Multi-Agent+Systems;FastAPI+%7C+Node.js+%7C+PostgreSQL+%7C+Redis" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Based_in-Pune%2C_India-0d1117?style=for-the-badge&logo=googlemaps&logoColor=00F5A0" />
  <img src="https://img.shields.io/badge/Associate_SWE-Synechron-0d1117?style=for-the-badge&logo=azuredevops&logoColor=00F5A0" />
  <img src="https://img.shields.io/badge/Open_to-Collaboration-0d1117?style=for-the-badge&logo=github&logoColor=00F5A0" />
</p>

<p align="center">
  <a href="https://github.com/YOUR_USERNAME"><img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&label=Profile+Views&color=00f5a0&style=flat-square" /></a>
  <a href="mailto:ishathakur2504@gmail.com"><img src="https://img.shields.io/badge/Email-ishathakur2504%40gmail.com-0d1117?style=flat-square&logo=gmail&logoColor=white" /></a>
</p>

---

## ⚡ About Me

```python
class IshaThakur:
    role      = "Software Engineer"
    focus     = ["Backend Development", "AI-Powered Applications"]
    based_in  = "Pune, India"
    education = "B.Tech Computer Engineering, MIT Academy of Engineering (CGPA 8.56)"

    def currently(self):
        return [
            "Working on data pipelines & AI-assisted data mapping @ Synechron",
            "Building a multi-agent AI customer support system (LangGraph + OpenAI)",
        ]

    def i_care_about(self):
        return ["Reliable systems", "Clean APIs", "Concurrency done right", "Production-ready code"]
```

I build backend services and AI-powered apps: REST APIs, async/event-driven workflows, database optimization, and LLM/RAG integrations.

---

## 🛠️ Tech Stack

**Languages**

<p>
  <img src="https://skillicons.dev/icons?i=py,js,ts,cpp,postgres&theme=dark" />
</p>

**Backend & Databases**

<p>
  <img src="https://skillicons.dev/icons?i=fastapi,django,nodejs,express,postgres,redis,sqlite&theme=dark" />
</p>

**Cloud & DevOps**

<p>
  <img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,githubactions,linux,git&theme=dark" />
</p>

**Frontend**

<p>
  <img src="https://skillicons.dev/icons?i=react,ts,html,css&theme=dark" />
</p>

**AI / LLM**

<p>
  <img src="https://img.shields.io/badge/OpenAI-0d1117?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-0d1117?style=for-the-badge&logo=langchain&logoColor=00F5A0" />
  <img src="https://img.shields.io/badge/LangGraph-0d1117?style=for-the-badge&logoColor=00F5A0" />
  <img src="https://img.shields.io/badge/AWS_Bedrock-0d1117?style=for-the-badge&logo=amazonaws&logoColor=FF9900" />
  <img src="https://img.shields.io/badge/pgvector-0d1117?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/ChromaDB-0d1117?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP-0d1117?style=for-the-badge&logoColor=00F5A0" />
</p>

<details>
<summary><b>📚 Full skill list</b></summary>

| Area | Skills |
|------|--------|
| **Backend** | FastAPI, Django, Node.js, Express.js, REST APIs, Pydantic, SQLAlchemy, Async Programming, Celery |
| **Engineering** | JWT Auth, RBAC, API Security, Caching, Rate Limiting, Concurrent Processing, Distributed Task Queues, Event-Driven Workflows |
| **Data** | PostgreSQL, Redis, SQLite, pgvector, ChromaDB |
| **AI/LLM** | RAG, Embeddings, Vector Search, Prompt Engineering, LangGraph, LangChain, OpenAI, AWS Bedrock, MCP |
| **Cloud/DevOps** | AWS (S3, Lambda), Docker, Kubernetes, GitHub Actions, CI/CD |
| **Frontend/Realtime** | React, TypeScript, WebSockets, Server-Sent Events |

</details>

---

## 🚀 Featured Projects

### 🤖 AI Customer Support Resolution Agent  `🚧 In progress`
> A multi-agent system that triages, researches, and resolves support tickets, with humans in the loop for sensitive actions.

- **Agents:** specialized LangGraph agents for triage, knowledge retrieval, troubleshooting, policy validation, resolution & escalation
- **RAG:** ChromaDB-backed retrieval over docs, FAQs, and policies to ground responses and cut unsupported LLM output
- **Stateful routing:** shared context between agents, confidence scoring, dynamic routing to resolution or human escalation
- **Realtime:** FastAPI + PostgreSQL + Redis, streaming agent execution via WebSockets/SSE
- **Dashboard:** React + TypeScript with human-in-the-loop approvals and reasoning/context inspection

`Python` `FastAPI` `LangGraph` `OpenAI` `ChromaDB` `Redis` `PostgreSQL` `React` `TypeScript` `WebSockets` `SSE`

---

### 🏟️ Sports Facility Management Platform  [`🌐 Live`](https://akolasportsarena.vercel.app/)
> Production-grade booking platform with real-time reservations and notifications.

- 🔐 Secure **JWT auth + RBAC**, with Redis-backed **API rate limiting**
- ⚡ **45% fewer repeated DB reads** via Redis caching layers and query batching
- 🔒 **Double-booking prevention** under concurrent requests using PostgreSQL transactional locking
- 📲 **WhatsApp Cloud API + email** notifications (confirmations, reminders, alerts) via async event-driven workflows

`TypeScript` `Node.js` `Express` `PostgreSQL` `Redis` `React`

---

## 💼 Experience

**Associate Software Engineer @ Synechron** · *Jun 2025 – Present* · Pune

- Built data pipelines to ingest raw source files, apply business filtering/transformation rules, and prepare data for downstream systems
- Supported data mapping and lineage: traced source-to-target flows across ingestion, transformation, and matching stages
- Developed rule-based attribute matching across source systems with differing names and structures
- Applied **Azure AI + semantic matching** to automate attribute mapping and reduce manual effort, combined with business rules and conditional validations

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00F5A0&icon_color=00F5A0" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ishathakur25&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00F5A0" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=Ishathakur25&theme=tokyonight&hide_border=true&background=0d1117&ring=00F5A0&fire=00F5A0&currStreakLabel=00F5A0" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Ishathakur25&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=00F5A0&line=00F5A0&point=ffffff" />
</p>

---

## 🤝 Let's Connect

<p align="center">
  <a href="mailto:ishathakur457@gmail.com"><img src="https://img.shields.io/badge/Gmail-0d1117?style=for-the-badge&logo=gmail&logoColor=00F5A0" /></a>
  <a href="https://ishathakur.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0d1117?style=for-the-badge&logo=googlechrome&logoColor=00F5A0" /></a>
  <a href="https://www.linkedin.com/in/isha-thakur2504"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=00F5A0" /></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F5A0,100:0d1117&height=100&section=footer" />
</p>
