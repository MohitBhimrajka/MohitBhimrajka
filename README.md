# Hey, I'm Mohit 👋

I'm a **Senior Forward Deployed AI Engineer** who's slightly obsessed with making AI systems that actually work in production (you know, the hard part).

Currently at [Supervity](https://supervity.ai), where I get paid to argue with LLMs and occasionally win.

[![Portfolio](https://img.shields.io/badge/mohitbhimrajka.com-4285F4?style=flat-square&logo=google-chrome&logoColor=white)](https://mohitbhimrajka.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohit-bhimrajka)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mohitbhimrajka5@gmail.com)

---

## The Short Version

I build AI systems for enterprises and teach developers how to do the same. The best compliment I've received? *"Your code actually works in production."* (The bar is low, I know.)

**Some numbers I'm proud of:**
- Helped close **$3M+** in enterprise deals (turns out, working demos > slide decks)
- Mentored **1000+ developers** through Google Cloud community programs
- Shipped **50+ AI agents** to production (and only mass-deprecated 3 of them)
- Cut idea-to-production time by **4x** (my PM still doesn't believe me)

---

## What I've Been Building

### [Visual Commerce](https://github.com/MohitBhimrajka/visual-commerce-gemini-3-alloydb) — Teaching AI to Count Boxes

What if your supply chain could *see*? Not the "I think there are approximately some bolts" kind of seeing — the "there are exactly 47 M8 hex bolts in bin 3" kind.

Visual Commerce is a **multi-agent supply chain system** where a Vision Agent (Gemini 3 Flash), Supplier Agent (AlloyDB AI), and Control Tower coordinate autonomously to count inventory and find replacement parts.

**The cool parts:**
- Gemini 3 Flash with Code Execution for *deterministic* vision (no more "approximately")
- AlloyDB ScaNN for vector search (10x faster than HNSW — Google Research wasn't kidding)
- A2A Protocol for agent discovery (the future of multi-agent communication)
- Complete 30-minute codelab: `./setup.sh` → `./run.sh` → done

[View the project & tutorial →](https://github.com/MohitBhimrajka/visual-commerce-gemini-3-alloydb)

---

### [Project Agora](https://github.com/MohitBhimrajka/project-agora) — When One Agent Isn't Enough

I got tired of explaining why a single chatbot can't replace an engineering team. So I built a system that actually tries to.

Project Agora is a **multi-agent framework** on Google ADK where specialized agents (analyst, researcher, architect, coder, reviewer) collaborate like a tiny autonomous dev shop. The code reviewer agent is ruthless — exactly like that one senior engineer we all know.

**The interesting bits:**
- Orchestrator treats agents as function calls in a DAG (determinism > vibes)
- BigQuery Vector Search for memory (because why add another database?)
- Human-in-the-loop checkpoints (AI writes code, humans approve it — for now)

[Read the deep dive →](https://mohitbhimrajka.com/blog/project-agora)

---

### [AIVA](https://github.com/MohitBhimrajka/aiva) — An AI That Interviews You (Nicely)

Ever had an interview where the silence felt eternal? That 3-second AI thinking pause? Yeah, I fixed that.

AIVA is a real-time AI interview coach with **<500ms latency**. It listens, thinks in parallel, and responds with lip-synced video — fast enough that you forget it's not human. Almost.

**What made it work:**
- Gemini 2.5 with native JSON mode (no more regex parsing prayer circles)
- Cloud Run Session Affinity (the WebSocket trick no one talks about)
- Safety Settings API (because an AI interviewer shouldn't roast candidates)

[Read the architecture breakdown →](https://mohitbhimrajka.com/blog/aiva-architecture)

---

### [AlgoArena 3D](https://github.com/MohitBhimrajka) — Settling the "Is Python Slow?" Debate

Instead of arguing about language performance on Twitter, I built a system where you can *watch* C++, Java, and Python race in real-time.

Spoiler: C++ wins. But Python has better snacks at the finish line.

**What I learned:**
- P99 latency doesn't lie (C++ at 5ms, Python at 25ms — sorry not sorry)
- Structured logging to Cloud Logging turns opinions into data
- Visualization teaches better than documentation ever will

[Read the writeup →](https://mohitbhimrajka.com/blog/algoarena-3d)

---

### [Full-Stack Template](https://github.com/MohitBhimrajka/template) — Ship Faster, Configure Less

Got tired of spending the first week of every project configuring boilerplate. So I built a template I actually want to use.

**FastAPI + Next.js + PostgreSQL** — all containerized with Docker. One command to start, zero environment debugging nightmares.

**What's included:**
- Python 3.11 backend with FastAPI, Pydantic, SQLAlchemy
- Next.js 15 frontend with React 19 and TypeScript
- PostgreSQL 15 with Alembic migrations pre-configured
- Docker Compose for consistent dev environments across any OS
- Code quality tools (Black, isort, ESLint, Prettier) ready to go

```bash
git clone https://github.com/MohitBhimrajka/template
cd template && cp .env.example .env
docker-compose up --build
# → Frontend at :3001, Backend at :8001/docs
```

[View the template →](https://mohitbhimrajka.com/template)

---

## Tech I Actually Use

**The Google Cloud stuff:**
Vertex AI, Cloud Run, BigQuery, ADK, AlloyDB AI, A2A Protocol, Secret Manager, Cloud Logging
*(Yes, I drink the Kool-Aid. It's pretty good Kool-Aid.)*

**The AI/ML stuff:**
Gemini 3 Flash, Gemini 2.5, LangChain, RAG pipelines, PyTorch, TensorFlow

**The "I can also do this" stuff:**
Python, TypeScript, C++, Java, FastAPI, React, Docker, Postgres

---

## Writing

I write about the stuff that doesn't fit in a README — architectural decisions, production war stories, and occasionally, opinions:

- [**Autonomous Supply Chain with Gemini 3 Flash & AlloyDB AI**](https://github.com/MohitBhimrajka/visual-commerce-gemini-3-alloydb) — Multi-agent vision meets vector search
- [**Building an Autonomous Software Agency**](https://mohitbhimrajka.com/blog/project-agora) — Multi-agent systems on ADK
- [**Architecting a "Human" AI Interviewer**](https://mohitbhimrajka.com/blog/aiva-architecture) — Latency, WebSockets, and controlled generation
- [**Polyglot Microservices on Cloud Run**](https://mohitbhimrajka.com/blog/algoarena-3d) — When you need proof, not opinions

---

## Community Stuff

I believe you don't really understand something until you can teach it.

**Lead, Code Vipassana (Google Cloud)** — Helped 1000+ developers at Google's "Build and Blog" Marathon in Bangalore. Turns out, the best way to learn cloud architecture is to explain it to someone at 2 AM during a hackathon.

**President, Technical Student Council** — Ran hackathons and tech events at ATLAS SkillTech. Mostly involved convincing sponsors that students can, in fact, build cool things.

---

## Let's Chat

I'm always down to talk about:
- Why your RAG pipeline isn't working (it's probably the chunking)
- Multi-agent architectures (and why most of them are overkill)
- How to make AI demos that actually impress enterprise clients
- The eternal Python vs. compiled languages debate

**Currently exploring:** Forward Deployed AI roles where I can build *and* ship.

---

<p align="center">
<i>"The future of development isn't AI assistance — it's AI collaboration."</i>
<br><br>
</p>
