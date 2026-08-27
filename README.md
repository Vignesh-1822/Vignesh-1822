<div align="center">

<!-- HEADER — animated SVG: matrix rain + typewriter. Save header.svg in repo root -->
<img src="./header.svg" width="100%" alt="Vignesh Gopal Rajendran"/>

### 📍 UW–Madison · MS Information Science (May 2026) · Open to Full-Time Roles

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vignesh-gopal-rajendran-6720211b2/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-3fb950?style=for-the-badge&logo=vercel&logoColor=white)](https://vignesh-portfolio-liard.vercel.app/)
[![Email](https://img.shields.io/badge/Gmail-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gopalrajend@wisc.edu)
[![LeetCode](https://img.shields.io/badge/LeetCode-Profile-f0a500?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/Vignesh_GR)

</div>

---

## 👋 About Me

Full-stack developer focused on building scalable applications, backend systems, and developer platforms.  

I enjoy working across the stack — from designing user interfaces to building APIs and distributed systems. Recently exploring **AI-driven workflows, LLM integrations, and cloud automation.**

---

## ⚠️ Previous GitHub

I previously used another GitHub account for several older projects but unfortunately lost access to it.  
You can still view that profile here:

👉 **Previous GitHub:**  https://github.com/Vignesh1002

---

## 💼 Experience

### 🔷 ABC Supply Co.
Built an AI-powered product image validation platform to automate catalog QA workflows across large product inventories. Developed full-stack applications, GraphQL APIs, and automation workflows for validating product images and processing SKU data at scale.

### 🔷 Space Science and Engineering Center (SSEC)
Worked on data-intensive applications for NOAA, building interactive dashboards and backend APIs to support real-time meteorological analysis. Focused on performance optimization, containerization, and cloud deployment using Kubernetes and AWS.

### 🔷 FindMe LLC
Developed a no-code portfolio platform enabling users to generate customizable websites. Contributed across frontend and backend, building real-time features and scalable data workflows.

### 🔷 Tekion Corp
Built and scaled an internal CRM system used for dealer operations. Worked on frontend architecture, CI/CD pipelines, testing systems, and backend data pipelines with distributed systems.

---

## 🚀 Projects

### 🖼️ AI Product Image Validation Platform
> React · TypeScript · FastAPI · GraphQL · PostgreSQL · OpenAI · n8n

- Built a full-stack web application to validate product images against catalog descriptions and automate manual QA workflows  
- Designed GraphQL APIs and backend services to process SKU data and support large-scale image validation pipelines  
- Built an automation workflow using n8n to automatically trigger image validation whenever new product data is added to the database

<p><a href="https://github.com/Vignesh-1822/image-analysis-tool">→ View Source Code</a></p>

---

### 📞 Aria — AI Voice Receptionist
> Retell AI · Next.js · FastAPI · Supabase · Google Calendar · HubSpot

- Built an AI voice receptionist that handles real-time patient conversations and automates appointment booking, rescheduling, and cancellation end-to-end  
- Integrated Google Calendar for live availability checks and HubSpot for automatic CRM contact and deal creation on every booking  
- Designed a FastAPI backend with Retell tool-call webhooks, a confirmation page with one-click "Add to Calendar", and a rate-limited password gate to prevent API abuse

<p>
  <a href="https://github.com/Vignesh-1822/ai-receptionist">→ View Source Code</a> &nbsp;·&nbsp;
  <a href="https://ai-receptionist-ten-plum.vercel.app/">→ Live Demo</a>
</p>

---

### 🌍 Worldseed — Procedural 3D World Generator
> Three.js WebGPU · React 19 · TypeScript · OpenAI · AWS Lambda · Vite

- Built a browser-based 3D world generator where every mountain, tree, ripple, and cloud is procedurally generated from a single seed — no assets, no textures, no models  
- Designed an AI layer using GPT-4o mini with strict structured outputs to translate natural language prompts (e.g. *"misty pine valley at dawn"*) into validated `WorldParams` that drive the rendering engine  
- Every generated world is a shareable URL — same seed, same world, on any machine

<p>
  <a href="https://github.com/Vignesh-1822/fable-3Dworld">→ View Source Code</a>
</p>

---

### 🗣️ EchoMe — AI Digital Twin
> FastAPI · React · Claude API · Whisper · Chroma · Pipecat · Ollama

- Built a config-driven AI digital twin — drop in a YAML profile, documents, and a voice clip, and visitors can have a spoken or text conversation with a clearly-labelled AI version of you  
- Implemented a RAG pipeline using sentence-transformers and Chroma so the twin answers only from real profile data, never hallucinating unknown facts  
- Built a spoken-consent gate and AudioSeal watermarking so all cloned-voice audio is provably AI-generated

<p><a href="https://github.com/Vignesh-1822/EchoMe">→ View Source Code</a></p>

---

### 🏋️ SyncFit — AI Fitness Coach
> OpenClaw · Telegram · GPT-5.1 · Markdown · Cron

- Built a personal AI fitness coach that runs entirely in Telegram — tracks nutrition through natural language, runs 9 scheduled cron jobs for meal nudges, water checks, and weigh-in reminders  
- Designed a silence protocol where meal nudges read the day's log before firing and emit a suppressed `HEARTBEAT_OK` when not needed, preventing notification fatigue  
- Documented model selection across 5 LLMs — only frontier models (GPT-5.1, Gemini 3.1 Pro) reliably read files before answering; smaller models silently skip reads while appearing to succeed

<p><a href="https://github.com/Vignesh-1822/fitness-ai-assistant">→ View Source Code</a></p>

---

### 📊 NOAA Dashboard
> React · Drag-and-Drop UI · PHP · Slim

- Built a drag-and-drop dashboard for LightningCast, allowing users to customize and arrange visualizations for locations like airports, stadiums, and fire incidents  
- Enabled real-time display of lightning probability predictions using dynamic, location-based graph components

<p><a href="https://cimss.ssec.wisc.edu/probsevere/lc/dashboard-staging/#/">→ View Project</a></p>

---

### 🧊 GOES-R Ice & Snow Dashboard
> React · Image Visualization · PHP · Slim

- Built an interactive dashboard for GOES-R ABI ice and snow validation data, visualizing variables like ice concentration, temperature, thickness, and motion  
- Enabled near real-time monitoring of GOES-18 and GOES-19 data with flexible hourly, daily, and weekly views

<p><a href="https://cimss.ssec.wisc.edu/goes-cryosphere-products/view/#/Oper_Ice_Concentration">→ View Project</a></p>

---

## 📖 Publications

<table>
<tr>
<td width="60%" valign="top">

**Secure Data Transmission in IoT Networks: A Machine Learning-Based Approach**
<br/>ML-based security framework for IoT data pipelines · IEEE

</td>
<td width="40%" align="right" valign="top">

[![IEEE](https://img.shields.io/badge/IEEE-View%20Paper-00629B?style=for-the-badge&logo=ieee&logoColor=white)](https://ieeexplore.ieee.org/document/10568602)

</td>
</tr>
<tr>
<td width="60%" valign="top">

**Identification of Improper Posture in Female Bharatanatyam Dancers — A Computational Approach**
<br/>Computer vision applied to classical dance biomechanics · IEEE

</td>
<td width="40%" align="right" valign="top">

[![IEEE](https://img.shields.io/badge/IEEE-View%20Paper-00629B?style=for-the-badge&logo=ieee&logoColor=white)](https://ieeexplore.ieee.org/document/10134062)

</td>
</tr>
</table>

---

## 📚 Currently Learning

| Course / Resource | Focus |
|------------------|------|
| *Principles of Designing AI Agents* by Sam Bhagwat | Agentic architectures, MCP servers, tool design |
| *AWS Certified Cloud Practitioner* | Cloud fundamentals, AWS services, architecture |

---

## 🛠️ Stack

**Languages**  
![JavaScript](https://img.shields.io/badge/JavaScript-yellow?style=flat-square&logo=javascript)
![TypeScript](https://img.shields.io/badge/TypeScript-blue?style=flat-square&logo=typescript)
![Python](https://img.shields.io/badge/Python-blue?style=flat-square&logo=python)
![Go](https://img.shields.io/badge/Go-cyan?style=flat-square&logo=go)
![SQL](https://img.shields.io/badge/SQL-orange?style=flat-square)

**Frontend**  
![React](https://img.shields.io/badge/React-blue?style=flat-square&logo=react)
![NextJS](https://img.shields.io/badge/NextJS-black?style=flat-square&logo=next.js)
![Tailwind](https://img.shields.io/badge/TailwindCSS-teal?style=flat-square&logo=tailwindcss)

**Backend**  
![Node](https://img.shields.io/badge/NodeJS-green?style=flat-square&logo=node.js)
![Express](https://img.shields.io/badge/Express-black?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-teal?style=flat-square)

**DevOps**  
![Docker](https://img.shields.io/badge/Docker-blue?style=flat-square&logo=docker)
![Kubernetes](https://img.shields.io/badge/Kubernetes-blue?style=flat-square&logo=kubernetes)
![AWS](https://img.shields.io/badge/AWS-orange?style=flat-square&logo=amazonaws)
![Terraform](https://img.shields.io/badge/Terraform-purple?style=flat-square&logo=terraform)

**AI / LLM Tools**  
![HuggingFace](https://img.shields.io/badge/HuggingFace-yellow?style=flat-square&logo=huggingface)
![LangGraph](https://img.shields.io/badge/LangGraph-black?style=flat-square)
![Claude](https://img.shields.io/badge/Claude-purple?style=flat-square)

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Vignesh-1822&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="155"/>
&nbsp;
<img src="https://streak-stats.demolab.com?user=Vignesh-1822&theme=tokyonight&hide_border=true" height="155"/>

</div>

---

## 🧠 LeetCode

<div align="center">

<img src="https://leetcard.jacoblin.cool/Vignesh_GR?theme=dark&font=baloo&ext=contest" height="200"/>
&nbsp;
<img src="https://streak-stats.demolab.com?user=Vignesh_GR&theme=dark&hide_border=true&background=1a1b27&ring=f0a500&fire=f0a500&currStreakLabel=f0a500" height="200"/>

</div>

---

## ⚡ Beyond Code

💃 Dancing · 📸 Photography · ⚽ Football

---

<div align="center">

*Building things at UW–Madison · Available May 2026 · Let's connect!*

<!-- FOOTER — animated SVG. Save footer.svg in repo root -->
<img src="./footer.svg" width="100%" alt="footer"/>

</div>
