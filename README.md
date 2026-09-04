<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,50:06b6d4,100:8b5cf6&height=200&section=header&text=Mohammed%20Muneeb%20PT&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=B.Tech%20CSE%20%40%20KMEA%20%C2%B7%20Building%20Software%2C%20Systems%20%26%20AI-assisted%20Products&descAlignY=58&descSize=16" width="100%"/>

<a href="https://readme-typing-svg.demolab.com">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=3000&pause=900&color=06B6D4&center=true&vCenter=true&width=750&lines=Second-year+CSE+student+%40+KMEA+Engineering+College;Minor+in+Electronics+(EC)+%C2%B7+KTU+Autonomous;Currently%3A+JavaFX+%2B+MySQL+%C2%B7+NPTEL+Cloud+Computing;Open+to+Software+Engineering+Internships" alt="Typing SVG"/>
</a>

<p>
  <a href="https://github.com/Muneeb-PT"><img src="https://img.shields.io/badge/GitHub-Muneeb--PT-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="https://www.linkedin.com/in/mohammed-muneeb-pt"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <img src="https://img.shields.io/badge/Status-Open%20to%20SDE%20Internships-2ea043?style=for-the-badge" alt="Open to internships"/>
  <img src="https://komarev.com/ghpvc/?username=Muneeb-PT&style=for-the-badge&color=6366f1&label=Profile+Views" alt="Profile views"/>
</p>

<sub><a href="#-about-me">About</a> &nbsp;·&nbsp; <a href="#-currently">Currently</a> &nbsp;·&nbsp; <a href="#-featured-builds">Featured Builds</a> &nbsp;·&nbsp; <a href="#-other-projects">Other Projects</a> &nbsp;·&nbsp; <a href="#%EF%B8%8F-tech-stack">Tech Stack</a> &nbsp;·&nbsp; <a href="#-github-analytics">Analytics</a> &nbsp;·&nbsp; <a href="#-lets-connect">Connect</a></sub>

</div>

<br/>

## 🧑‍💻 About Me

I'm a second-year **B.Tech CSE** student at **KMEA Engineering College (Autonomous)**, Aluva — affiliated to KTU — currently in **S3**, also pursuing a **minor in Electronics (EC)**.

I like taking things past the tutorial stage: finishing a working app, writing down what it actually does (and doesn't do yet), and shipping the next version. Off the keyboard, I serve as **Class Representative** and **Junior Red Cross (JRC) Unit Leader**, and I'm active in **IEEE** and other technical communities on campus.

## 🌱 Currently

- 🏥 Building a **Smart Hospital Management System** — JavaFX + JDBC + MySQL, with a rule-based appointment-priority engine (Strategy/Observer patterns) — for my S3 OOP coursework *(in progress — repo coming soon)*
- ☁️ Working through **NPTEL Cloud Computing** (IIT Kharagpur, Prof. Soumya K. Ghosh) week by week
- 📈 Strengthening **DSA** and backend fundamentals ahead of internship applications
- 🎯 Targeting **software engineering internships**, with GATE CSE and MS-abroad kept open as longer-term tracks

## 🚀 Featured Builds

<table>
<tr>
<td width="100%">

### 🧠 Synapse — AI Career Intelligence Platform
**Team hackathon build · KAPRICIOUS'26, KMEA Engineering College — first hackathon, first year of college**

<p>
<img alt="status" src="https://img.shields.io/badge/status-hackathon_prototype-orange?style=flat-square"/>
<img alt="react" src="https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=white"/>
<img alt="typescript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img alt="supabase" src="https://img.shields.io/badge/Supabase-Postgres%20%2B%20Auth-3ECF8E?style=flat-square&logo=supabase&logoColor=white"/>
<img alt="tailwind" src="https://img.shields.io/badge/Tailwind-shadcn%2Fui-38BDF8?style=flat-square&logo=tailwindcss&logoColor=white"/>
</p>

Built in ~12 hours with a 4-person team. Instead of reducing a candidate to a resume, Synapse builds a living profile (skills, goals, strengths) paired with an AI mentor and a fit-based matching layer for recruiters.

```mermaid
flowchart LR
    U[User] -->|sign in| A[Supabase Auth]
    U -->|browse| F[React + Vite Frontend]
    F -->|profile & skills data| D[(Supabase Postgres + RLS)]
    F -->|chat message| E[Edge Function: ai-mentor]
    E -->|streamed request| G[Lovable AI Gateway]
    G -->|Gemini 3 Flash| E
    E -->|streamed tokens| F
```

**Genuinely working:** email/password auth, profile + skills/education/experience persisted to Postgres behind Row-Level Security, and a live AI mentor chat streamed from Gemini 3 Flash.
**Still prototype:** the dashboard, roadmap, and recruiter views currently render from mock data rather than live queries — called out here rather than left for someone to discover later.

📎 [Live demo](https://muneeb-pt.github.io/SYNAPSE-mindspark/) · [Source](https://github.com/Muneeb-PT/SYNAPSE-mindspark)

</td>
</tr>
<tr>
<td width="100%">

### 📄 AutoDoc AI — Product Concept & Landing Page
**Course project · Engineering Entrepreneurs & IPR**

<p>
<img src="https://img.shields.io/badge/Built_with-Lovable.ai-6366f1?style=flat-square"/>
<img src="https://img.shields.io/badge/React_%2B_Vite-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Status-Prototype-orange?style=flat-square"/>
</p>

A startup-style MVP exploring an AI-powered documentation generator: the problem, the pitch, feature set, and pricing tiers, built as a polished landing page and UI (React + TypeScript + Tailwind + shadcn/ui, scaffolded with Lovable). This project was the entrepreneurship exercise — validating the idea and the UI, not shipping the backend — so the "engine" describes a planned architecture (repo analysis → LLM pipeline → generated docs) rather than a deployed one.

📎 [Live demo](https://autodoc-ai.lovable.app) · [Source](https://github.com/Muneeb-PT/AutoDoc-AI)

</td>
</tr>
</table>

## 🧪 Other Projects

| Project | What it is | Built with | Link |
|---|---|---|---|
| 🌦️ Weather App | API-driven, location-based weather lookup | React · Vite · Weather API | [Live](https://muneeb-pt.github.io/Weather_App/) · [Code](https://github.com/Muneeb-PT/Weather_App) |
| 🧮 Calculator | Responsive arithmetic calculator | HTML · CSS · JavaScript | [Live](https://muneeb-pt.github.io/Calculator/) · [Code](https://github.com/Muneeb-PT/Calculator) |
| 🪔 Diwali — Festival of Lights | First-year "Foundations of Computing" project | HTML · CSS | [Code](https://github.com/Muneeb-PT/Diwali-Festival-of-Lights) |
| 🌐 My First HTML Project | Class-12 site — first steps into web dev | HTML | [Live](https://muneeb-pt.github.io/MyFirst-HTML-project/) · [Code](https://github.com/Muneeb-PT/MyFirst-HTML-project) |

## 🛠️ Tech Stack

<div align="center">

**Languages**
<img src="https://skillicons.dev/icons?i=java,python,cpp,c,js,ts" />

**Web & Frontend**
<img src="https://skillicons.dev/icons?i=html,css,react,vite,tailwind" />

**Backend & Data**
<img src="https://skillicons.dev/icons?i=mysql,supabase" />

**Tools**
<img src="https://skillicons.dev/icons?i=git,github,vscode,idea,linux" />

</div>

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Muneeb-PT&show_icons=true&hide_border=true&rank_icon=github&count_private=true&theme=tokyonight" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Muneeb-PT&layout=compact&hide_border=true&langs_count=8&theme=tokyonight" height="165"/>

<img src="https://streak-stats.demolab.com?user=Muneeb-PT&hide_border=true&theme=tokyonight" />

<img src="https://github-profile-trophy.vercel.app/?username=Muneeb-PT&theme=tokyonight&no-frame=true&margin-w=8&row=1" />

</div>

> These cards use the shared public instances of `github-readme-stats` / `github-profile-trophy`, which occasionally rate-limit under heavy traffic — if a card ever shows blank, refresh, or see the setup note below on self-hosting.

## 🐍 Contribution Graph

<div align="center">
<img src="https://raw.githubusercontent.com/Muneeb-PT/Muneeb-PT/output/github-contribution-grid-snake.svg" alt="GitHub contribution snake animation"/>
</div>

*(Renders once the snake workflow below is added to this repo — see setup note.)*

## 🎯 Roadmap

| Now | Next | Later |
|---|---|---|
| DSA fundamentals · Java/JavaFX backend work · finish SHMS | First public open-source PR · a full-stack project with a real backend | Internship-ready portfolio · GATE CSE / MS-abroad prep |

## 🤝 Let's Connect

<div align="center">

I'm interested in backend systems, full-stack builds, hackathons, and AI-assisted developer tools — open to internships, collaborations, and good first issues.

<a href="https://github.com/Muneeb-PT"><img src="https://img.shields.io/badge/GitHub-Muneeb--PT-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/mohammed-muneeb-pt"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,50:06b6d4,100:8b5cf6&height=150&section=footer" width="100%"/>

</div>
