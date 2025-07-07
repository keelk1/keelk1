gYlt – README Collection

This file now contains three independent READMEs.
	1.	gylt‑proto‑v3 – functional MVP
	2.	gylt‑landing‑page – marketing site
	3.	keelk1/keelk1 – GitHub profile README (new)

⸻

1. gylt‑proto‑v3 – Switch & Save FinTech Prototype

✨ Overview

The gylt‑proto‑v3 repository hosts the functional MVP of gYlt – a “Spotify Wrapped”‑style assistant that analyses open‑banking transactions and recommends money‑saving switches (telco, energy, insurance).

🏗 Stack
	•	Next.js 14 + TypeScript (App Router, Server Actions)
	•	Tailwind CSS + Framer Motion animations
	•	Qdrant vector DB for semantic matching
	•	Google Apps Script webhook → click‑tracking in Google Sheets

🚀 Getting Started

git clone https://github.com/keelk1/gylt-proto-v3.git
cd gylt-proto-v3
pnpm install              # or npm / yarn
touch .env.local          # copy env.sample and fill variables
pnpm dev                  # runs on http://localhost:3000

🔑 Environment

Variable	Purpose
OPENAI_API_KEY	embeddings & prompts
QDRANT_URL / QDRANT_API_KEY	vector storage
WEBHOOK_URL	click‑tracking

📝 Scripts

Command	Action
pnpm dev	dev server with hot‑reload
pnpm build	static build (Next 13 ++)
pnpm lint	ESLint + Prettier

☁️ Deployment (Vercel)
	1.	Import repo, set env vars in dashboard.
	2.	Enable Edge Runtime for /api/embedding route (faster inference).
	3.	Assign prototype.gylt.space custom domain.

📄 Licence

MIT – feel free to fork, star and contribute.

⸻

2. gylt‑landing‑page – Marketing / Waitlist

✨ Overview

Single‑page marketing site generated with V0.dev, tweaked in Next.js 14. It captures e‑mails, forwards them to Google Sheets, and links to the prototype.

🏗 Stack

Tailwind CSS • React Server Components • Google Apps Script Webhook • Migadu DNS for MX records

🚀 Setup Quick‑Start

git clone https://github.com/keelk1/gylt-landing-page.git
cd gylt-landing-page
pnpm install
pnpm dev

☁️ Deploy

Deployed on Vercel – set env var WEBHOOK_URL and your domain gylt.space.

⸻

3. keelk1/keelk1 – GitHub Profile README

Copy the markdown below into a new public repository named exactly keelk1. GitHub will display it on your profile home page.

<h1 align="center">Hi, I'm Edgar (keelk1) 👋</h1>

<p align="center">
  FinTech builder · Aspiring VC analyst · TypeScript & Next.js enthusiast
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=keelk1&style=flat-square" alt="profile views" />
  <img src="https://img.shields.io/github/followers/keelk1?label=Follow&style=social" alt="followers" />
</p>

---

### 🔧 Tech Stack
![TypeScript](https://img.shields.io/badge/-TypeScript-black?style=flat-square&logo=typescript)
![Next.js](https://img.shields.io/badge/-Next.js-black?style=flat-square&logo=next.js)
![JavaScript](https://img.shields.io/badge/-JavaScript-black?style=flat-square&logo=javascript)
![Tailwind](https://img.shields.io/badge/-TailwindCSS-black?style=flat-square&logo=tailwind-css)
![Python](https://img.shields.io/badge/-Python-black?style=flat-square&logo=python)

### 📊 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=keelk1&show_icons=true&hide_border=true" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=keelk1&layout=compact&hide_border=true&hide=html,css" />
</p>

### 🔥 Streak
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=keelk1&hide_border=true" />
</p>

### 🚀 Current Focus
- ✨ Shipping **gYlt** v3 – a Switch & Save assistant for Gen Z.
- 🤝 Seeking a technical co‑founder & early advisors.
- 🎓 M1 Student @ SKEMA BS; January 2026 VC internship hunt.

### 📫 Contact
- **e‑mail**: edgar.tissot@skema.edu  
- **LinkedIn**: <https://www.linkedin.com/in/edgar‑tissot/>  
- **Prototype**: <https://prototype.gylt.space>

<!-- Proudly generated with ChatGPT & fine‑tuned tweaks 😊 -->

Tips before pushing
	1.	Pin your two public repos (gylt-landing-page, gylt-proto-v3) so they appear atop the profile.
	2.	Adjust the hide= list in the Top Langs card to exclude HTML/CSS if they dominate falsely.
	3.	Feel free to add fun badges (e.g., ![Code Time](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/keelk1/...)).

⸻

Need more bling?
	•	Add a GIF banner (max 4 MB) just under the H1.
	•	Use mermaid diagrams for quick architecture sketches.
	•	Enable GitHub Actions CI saying “README build ✓” for the geek touch.
