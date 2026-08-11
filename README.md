# Hi, I'm Erez Gartsman 👋

I'm a Data/AI Engineer and Product Manager. I love turning messy data into intelligent, automated products.

Having just graduated with a Dual-Degree in Information Science & Communication and Product Management from Bar-Ilan University, my daily focus is at the intersection of data engineering and Generative AI. 

By day, I lead AI product evaluation and data pipelines for **ScribeMD** at ARC Sheba Medical Center — ensuring clinical LLMs perform flawlessly in high-stakes environments. By night, I’m a builder. After managing a digital community of 75K+ followers for six years, I got tired of manual workflows and started building my own AI agents and data pipelines to automate them. 

I care about taking an idea from a raw problem → data pipeline → AI prototype → production, and making it survive contact with real users.

## 🔧 What I've Built

### 🧠 Nexus AI 
A RAG-based backend ecosystem and NL2SQL analytics engine. It lets content creators (like me) ask questions in plain language and get real-time insights extracted directly from their own data and internal documents.
*   **Stack:** FastAPI · SQL/DuckDB · Gemini · React
*   **Why I built it:** With a community of 75K+ followers, I needed a way to query my own performance metrics intuitively. The tool didn't exist, so I built it.
*   **What was hard:** Building deterministic, schema-grounded prompts to prevent LLM hallucinations, while keeping query latency low enough for the experience to feel like a real-time search engine rather than a batch job.
*   **Engineering reality:** When I discovered the initial codebase had been silently corrupted mid-project, I chose to rewrite it end-to-end instead of patching around the problem.
*   ➡️ [Repo] · [2-min demo]

### 🏥 ScribeMD — Clinical LLM Evaluation Pipeline
As the PM/Data lead for an AI ambient clinical scribe, I deal with live doctor–patient encounters. The users are senior physicians with zero tolerance for hallucinations or latency.
*   **The Challenge:** We needed to migrate away from a legacy model without guessing which foundational model should replace it.
*   **The Solution:** I architected the team's data-driven protocol for evaluating and grading LLMs in production.
*   **Highlights:** Built a local 1,500-encounter "Gold Standard" dataset, implemented an **LLM-as-a-Judge** scoring stack, and established strict deterministic testing gates (Temperature = 0) to ensure zero Sev-1 medical hallucinations.

### 📊 Instagram Analytics Semantic Model (Power BI)
Audited and refactored a large-scale Power BI semantic model to handle complex creator metrics.
*   Repaired star schemas and fixed referential-integrity issues.
*   Introduced a unified `dim_users` dimension and standardized the DAX layer to drastically improve the model's consistency and maintainability.

## 🛠 Tools I Actually Work With

**AI / LLM Engineering:**
RAG Architecture · AI Agents · Prompt Engineering · Structured Outputs · LLM Evaluation (LLM-as-a-Judge) · Gemini · OpenAI APIs · Claude Code · Cursor 

**Backend & Data:**
Python (FastAPI, Pandas) · SQL · DuckDB · Power BI · DAX · ETL/ELT pipelines

**Product & Frontend:**
React · JavaScript · HTML/CSS · PRDs · Product Strategy · Rapid Prototyping

## 📫 Let's Connect
I'm always open to talking about data architecture, AI products, or building cool tools.
*   **LinkedIn:** [Your Link]
*   **Email:** erezkim1234@gmail.com
