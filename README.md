<!-- Header banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=180&section=header&text=Abdul%20Muhaimin%20Khan&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AI%20Engineer%20%C2%B7%20LLM%20Systems%20%26%20Evals&descAlignY=58&descSize=18" width="100%"/>

<div align="center">

<!-- Typing animation -->
<a href="https://github.com/AbdulMuhaiminKhan">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=800&color=36BCF7&center=true&vCenter=true&width=600&lines=I+build+LLM+systems...;...and+the+evals+that+prove+they+work.;RAG+%C2%B7+Agents+%C2%B7+MCP+%C2%B7+Text-to-SQL;Open+to+AI+Engineering+Werkstudent+roles" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdulmuhaiminkhan)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abdul.muhaimin.khan.official@gmail.com)
![Berlin](https://img.shields.io/badge/Berlin-Germany-000000?style=for-the-badge&logo=googlemaps&logoColor=white)

</div>

---

### 👋 About me

```python
class Abdul:
    role       = "AI Engineer · ex Software Integration & Deployment Intern @ Think3DDD"
    studying   = "B.Sc. Computer Science @ SRH Berlin"
    also       = ["AI consultant", "AI/ML · Python tutor (high school → postgrad)"]
    speaks     = ["English", "Urdu", "Hindi", "German (learning)"]
    philosophy = "If it isn't measured, it isn't done."
    looking_for = "AI Engineering Werkstudent / intern roles — Berlin or remote"
```

---

### 🚀 AI Engineering Portfolio

> One rule across every project: every system ships with an evaluation harness. Click a project to expand.

<details>
<summary><b>🤖 Agentic Code Reviewer</b> — multi-agent PR reviewer, backtested on real CVEs</summary>
<br/>

- **What:** Specialist agents review pull requests for security, error handling and test coverage, then post a PR comment
- **Eval:** Backtested on 79 real vulnerabilities from GitHub Security Advisories, with a held-out test set, patched-code controls and human labels
- **Cost:** $0, runs fully on a local model
- **Stack:** Python · LangGraph · Ollama (`qwen2.5-coder:7b`) · Streamlit · GitHub API

👉 [**View repo**](https://github.com/AbdulMuhaiminKhan/Agentic-Code-Reviewer) · [**Live demo PRs**](https://github.com/AbdulMuhaiminKhan/acr-demo-shop/pulls)
</details>

<details>
<summary><b>📚 RAG with Eval Harness</b> — retrieval QA you can actually trust</summary>
<br/>

- **What:** RAG over the Kubernetes docs with a full evaluation harness
- **Eval:** 24-config ablation, bootstrap confidence intervals, a calibrated LLM judge and a CI regression gate
- **Why it matters:** Most RAG demos never measure if answers are grounded. This one does.
- **Stack:** Python · BM25 · dense retrieval · reranking · runs locally

👉 [**View repo**](https://github.com/AbdulMuhaiminKhan/rag-eval-harness)
</details>

<details>
<summary><b>🔌 MCP Server + Tool-Selection Evals</b> — does the model pick the right tool?</summary>
<br/>

- **What:** A read-only GitHub MCP server plus a tool-selection benchmark
- **Result:** 63% → 95% tool-selection accuracy on a local 7B model, with an ablation of where the gain came from
- **Stack:** Python · MCP SDK · Ollama · Docker

👉 [**View repo**](https://github.com/AbdulMuhaiminKhan/github-mcp) · [**Project page**](https://abdulmuhaiminkhan.github.io/github-mcp/)
</details>

<details>
<summary><b>🔒 Privacy-First LLM Eval</b> — fully offline, zero data leaves the machine</summary>
<br/>

- **What:** Controlled offline experiment comparing plain text vs JSON mode vs schema-constrained output from small local LLMs
- **Scale:** 540 answers across 3 models, with calibration and latency analysis
- **Why it matters:** Structured output reliability is what breaks LLM apps in production
- **Stack:** Python · Ollama · Pydantic · Streamlit

👉 [**View repo**](https://github.com/AbdulMuhaiminKhan/privacy-first-llm-eval) · [**Project page**](https://abdulmuhaiminkhan.github.io/privacy-first-llm-eval/)
</details>

<details>
<summary><b>🗄️ Text-to-SQL Clarification Engine</b> — asks before it guesses</summary>
<br/>

- **What:** Turns natural-language questions into SQL, and asks a targeted clarifying question when a query is ambiguous instead of guessing
- **Stack:** Python · Pydantic · SQLAlchemy · MySQL · Groq · Docker

👉 [**View repo**](https://github.com/AbdulMuhaiminKhan/text2sql-clarification-engine)
</details>

<details>
<summary><b>🎓 Study Helper Agent</b> — RAG study assistant that refuses to make things up</summary>
<br/>

- **What:** Autonomous agent that ingests lecture PDFs/notes and answers questions grounded in them, with citations
- **How:** PDF parsing + chunking → semantic retrieval → cited prompts → ReAct-style CLI agent loop
- **Guardrail:** Refuses ungrounded answers to avoid hallucination
- **Stack:** Node.js · Google Gemini · Redis vector store · Docker Compose

👉 [**View repo**](https://github.com/AbdulMuhaiminKhan/study-helper-agent)
</details>

<details>
<summary><b>🎤 SmartSpeaking</b> — a free, private AI public-speaking coach</summary>
<br/>

- **What:** Record a talk and get pace, pauses, filler words, voice, eye contact and posture feedback, each marked at the moment it happened, with drills to fix it
- **Privacy:** Runs entirely on your own computer with free open-source models
- **Languages:** English · Deutsch · Urdu
- **Stack:** React · FastAPI · Whisper · MediaPipe · Ollama · Docker

👉 [**View repo**](https://github.com/AbdulMuhaiminKhan/smart-speaking)
</details>

<details>
<summary><b>🥦 The Fridge Graveyard</b> — rescue your groceries before they become a cold case</summary>
<br/>

- **What:** Food-waste app for students and shared flats: expiry-first fridge, receipt scanning, rescue recipes, a weekly meal planner and shared households
- **Stack:** Python · FastAPI · React · Tailwind · SQLite · pytest

👉 [**View repo**](https://github.com/AbdulMuhaiminKhan/fridge-graveyard)
</details>

<br/>

**More builds:** [🔖 Bookmark Manager](https://github.com/AbdulMuhaiminKhan/bookmark-manager) (Django · Docker · Kubernetes) · [📡 FTP Server & Client](https://github.com/AbdulMuhaiminKhan/FTP-server-and-client) (Python networking) · [🚀 Spaceship Game](https://github.com/AbdulMuhaiminKhan/Spaceship-game) (Pygame)

---

### 🧰 Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,java,nodejs,react,fastapi,django,postgres,mysql,redis,docker,kubernetes,nginx,flutter,linux,git&theme=dark" />

<br/><br/>

![RAG](https://img.shields.io/badge/RAG-1f2937?style=flat-square)
![Agents](https://img.shields.io/badge/AI_Agents-1f2937?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-1f2937?style=flat-square)
![Evals](https://img.shields.io/badge/LLM_Evals-1f2937?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-1f2937?style=flat-square)
![Groq](https://img.shields.io/badge/Groq-1f2937?style=flat-square)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)

</div>

---

### 📊 GitHub Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=AbdulMuhaiminKhan&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AbdulMuhaiminKhan&layout=compact&theme=tokyonight&hide_border=true" />

<img src="https://streak-stats.demolab.com?user=AbdulMuhaiminKhan&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=AbdulMuhaiminKhan&theme=tokyo-night&hide_border=true&area=true" width="100%"/>

</div>

---

<div align="center">

**💬 Ask me about:** building RAG that doesn't hallucinate, evaluating LLM outputs, MCP, local LLMs, or learning Python.

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%"/>
