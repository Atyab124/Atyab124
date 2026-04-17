<!-- Hero Header -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,6,20&height=260&section=header&text=Atyab%20Tosif&fontSize=72&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=AI%20Solutions%20Engineer%20%7C%20Dubai%20%F0%9F%87%A6%F0%9F%87%AA&descSize=20&descAlignY=55" width="100%" alt="Header" />
</div>

<!-- Typing animation -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=1000&color=6DD5FA&center=true&vCenter=true&width=760&lines=AI+Solutions+Engineer;Enterprise-Grade+Product+Builder;Machine+Learning+Engineer;Real+Estate+Tech+Innovator;Automation+Enthusiast" alt="Typing Animation" />
</p>

<!-- Profile Views -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Atyab124&color=blueviolet&style=for-the-badge&label=PROFILE+VIEWS&base=160" alt="Profile Views" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,6,20&height=3" width="100%" alt="divider" />

## 🧠 About Me  
- 🎓 **B.Tech in Computer Science (AI)** — GPA 9.3, SRM Institute of Science and Technology  
- 💼 **AI Solutions Engineer at Fortes Investment** — building LLM agents and **enterprise-grade products** (most recently, **TaskIt**)  
- 🔬 **Ex-ML R&D Intern at OneOrigin** (Letter of Recommendation for excellence)  
- 🌍 Based in **Dubai, UAE**  
- 🌱 Currently exploring **LLM applications, automation, and scalable deployments**  

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,6,20&height=3" width="100%" alt="divider" />

## 📌 Now  
- 🚀 Shipping **[TaskIt](#-latest-build--taskit)** — a multi-tenant task + chat platform (Next.js 16, Supabase, Drizzle)
- 🧩 Deep-diving into **Crew AI** and multi-agent orchestration patterns  
- 🏢 Building production LLM agents for real estate ops at **Fortes Investment**  
- ✍️ Documenting what I learn — one commit at a time  

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,6,20&height=3" width="100%" alt="divider" />

## 🌟 Latest Build — TaskIt  

> **Multi-tenant task + chat platform for organizations.** Auth-hardened, realtime, optimistic-first.  

- ⚙️ **Stack:** Next.js 16 App Router (`cacheComponents`), Vercel serverless, Supabase (Postgres + Auth + Realtime + Storage), Drizzle ORM, shadcn/ui, TanStack Table, Zustand, Zod, Sentry  
- 🔐 **Auth proxy** validates JWTs via local JWKS (<1ms, 10s cache), strips inbound identity headers, writes trusted `x-auth-*` downstream — zero network calls in request path  
- 🏢 **Tenancy & RLS:** org-scoped Postgres RLS as a safety net; business rules (visibility, privilege gates) enforced in TypeScript — `admin / director / hod / manager / member` role hierarchy  
- 💬 **Realtime chat:** 1:1 + group, reactions, mentions, attachments (25 MB), unread badges, fulltext search — all over Supabase WebSockets with unique per-mount channels  
- ⚡ **Optimistic everywhere:** `useOptimistic` for inline edits, temp-ID pattern for message sends, rollback + toast on error  
- 🧱 **60+ migrations**, batch-CTE RPCs, compound-cursor pagination, cache-tag invalidation (no `router.refresh()` after mutations)  

## 🚀 Projects  

| Project | Description | Tech Stack |
|---------|-------------|------------|
| 🧩 **TaskIt** *(Private)* | Multi-tenant task + chat platform with realtime collaboration, role-based visibility, and optimistic UI. | Next.js 16, TypeScript, Supabase, Drizzle, shadcn/ui, Zustand |
| 🎮 [**Miscrits Game Automation Bot**](https://github.com/Atyab124/Miscrits-Farming-Bot) | Automated gameplay with Python, OpenCV, OCR & fuzzy logic. | Python, OpenCV, PyAutoGUI |
| 📚 [**Local RAG Assistant**](https://github.com/Atyab124/Semantic-RAG) | Private RAG pipeline with semantic chunking & vector search. | Python, Ollama, Supabase, n8n |
| 💬 **Crew AI Multi-Agent WhatsApp Summarizer** *(Private)* | Converts real estate WhatsApp chats to structured property data. | Python, Crew AI, MongoDB |
| ✍️ [**Full Page Handwriting OCR**](https://github.com/Atyab124/Full-page-docker-TrOCR-Completebuild-v2) | TrOCR + PaddleOCR hybrid for CUDA-based full-page OCR. | Python, PyTorch, Docker |

### ⭐ Featured Repositories  

<p align="center">
  <a href="https://github.com/Atyab124/Miscrits-Farming-Bot">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Atyab124&repo=Miscrits-Farming-Bot&theme=tokyonight&hide_border=true" alt="Miscrits Farming Bot" />
  </a>
</p>
<p align="center">
  <a href="https://github.com/Atyab124/Semantic-RAG">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Atyab124&repo=Semantic-RAG&theme=tokyonight&hide_border=true" alt="Semantic RAG" />
  </a>
</p>
<p align="center">
  <a href="https://github.com/Atyab124/Full-page-docker-TrOCR-Completebuild-v2">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Atyab124&repo=Full-page-docker-TrOCR-Completebuild-v2&theme=tokyonight&hide_border=true" alt="Full Page OCR" />
  </a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,6,20&height=3" width="100%" alt="divider" />

## ⚙️ Tech Stack  

**Languages:** Python, TypeScript, SQL.  
**Full-Stack:** Next.js 16 (App Router), React, Node.js, Drizzle ORM, Zod, TanStack Table, shadcn/ui, Zustand.  
**Cloud & Data:** Supabase (Postgres + Auth + Realtime + Storage), Vercel, Docker, AWS EC2, Sentry.  
**AI / ML Frameworks:** PyTorch, TensorFlow, LangChain, HuggingFace, Crew AI, Flask.  
**AI / ML Libraries:** Transformers, Scikit-learn, OpenCV, Pandas.  
**Tools:** Git, Apollo, Instantly, n8n.  

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,6,20&height=3" width="100%" alt="divider" />

## 📊 GitHub Stats  

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Atyab124&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&hide_rank=true&hide=issues,contribs&card_width=800" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Atyab124&theme=tokyonight&hide_border=true&card_width=800" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Atyab124&layout=compact&theme=tokyonight&hide_border=true&card_width=800&langs_count=8" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Atyab124&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Graph" />
</p>

### 🐍 Contribution Snake  

<p align="center">
  <img src="https://raw.githubusercontent.com/Atyab124/Atyab124/output/github-contribution-grid-snake-dark.svg" alt="Contribution Snake" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,6,20&height=3" width="100%" alt="divider" />

## 💬 Dev Quote  

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Dev Quote" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,6,20&height=3" width="100%" alt="divider" />

## 🎯 Fun Facts  
- 🏃 Early riser & daily runner (5 AM club 🌅)  
- 📚 Love blending **AI** with **real-world business problems**  
- ✈️ Moved to Dubai chasing big dreams & bigger deals  
- ⚡ Can turn chaotic WhatsApp group chats into clean databases in minutes  

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,6,20&height=3" width="100%" alt="divider" />

## 📫 Connect With Me  
<p align="center">
  <a href="https://www.linkedin.com/in/atyab-tosif-1b6224249/"><img src="https://img.shields.io/badge/LinkedIn-Atyab%20Tosif-blue?style=for-the-badge&logo=linkedin" /></a>
  <a href="mailto:atyabbusiness@gmail.com"><img src="https://img.shields.io/badge/Email-atyabbusiness%40gmail.com-red?style=for-the-badge&logo=gmail" /></a>
  <a href="https://github.com/Atyab124"><img src="https://img.shields.io/badge/GitHub-Atyab124-lightgrey?style=for-the-badge&logo=github" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,6,20&height=120&section=footer" width="100%" alt="footer" />

<p align="center">
  💡 <i>"AI should not just be intelligent — it should be useful."</i>
</p>
