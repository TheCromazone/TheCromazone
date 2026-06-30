# Hi, I'm Matthew 👋

I'm an MS Quantitative Economics grad (Cal Poly SLO '25; Reed College econ undergrad) based in San Francisco, building **agentic AI and data systems** as my main work right now. I'm looking for **data analyst, data scientist, or AI engineer** roles in the Bay Area. The projects below are some examples of what I've recently been working and iterating upon. 

## What I'm building (as of right now)

### Real-estate listings site — freelance: legacy WordPress → headless rebuild & live migration 🏙️
Ongoing client work for a San Francisco Compass real-estate agent (private repo — her photo and video assets stay off GitHub). The site *used to* run as a Nuxt frontend reading a JSON feed from a WordPress backend on aging GoDaddy shared hosting (PHP 5.6 / WP 5.0), with listings stored as ACF photo-repeater posts behind a ~2-minute cache bolted on to shield the fragile server. I've already migrated the frontend AWS → Vercel (static generate + deploy-hook publishing), and the next phase replaces the WordPress/PHP backend with a Postgres feed (Neon) so listings update on-click instead of on a timer. I also built a custom agentic CMS — a Next.js admin dashboard plus an LLM chatbot that edits the live site — so she can self-manage without touching code. Alongside the plumbing I keep shipping distinct frontend design concepts (30+ so far: cinematic, minimal black-and-white, Compass-style) and refining each against her feedback until she's satisfied.

**Stack:** Nuxt · Vue · Vercel · WordPress → Postgres (Neon) · Next.js · Playwright · GSAP · AI media (Imagen / Veo)

### [forgetmenote-ios](https://github.com/TheCromazone/forgetmenote-ios) — Native iOS visual-memory app with hybrid AI vision 🌸
Photograph rooms and shelves, then draw or freehand-trace nested sub-spaces directly on the photos — a recursive map of where your things live, searchable down to a single drawer. Object scanning runs on a two-tier vision pipeline: on-device Apple Vision segmentation fused with ML Kit (private, offline), with optional free-tier Gemini enhanced scans that auto-fall-back across the Flash model family when Google is overloaded. Full XCTest + Maestro E2E coverage, including a mocked-Gemini server that proves the cloud pipeline offline. iOS port of an open-source Android app, data-model compatible.

**Stack:** Swift · SwiftUI · SwiftData · Apple Vision · ML Kit · Gemini API · Maestro · XcodeGen

### [Personal-JobPilot](https://github.com/TheCromazone/Personal-JobPilot) — Local autonomous job-search agent
Scans Greenhouse / Lever / Ashby ATS APIs, scores every role with a local LLM against archetype-specific rubrics, tailors ATS-clean `.docx` resumes, and auto-applies through Playwright. FastAPI + SSE dashboard. 68 passing tests. Runs unattended on one laptop.

**Stack:** Python · FastAPI · Playwright · Ollama · SQLAlchemy · APScheduler

### [alpaca-paper-bot](https://github.com/TheCromazone/alpaca-paper-bot) — LLM tool-use trading agent
Runs Claude / GPT tool-use loops five times a week on Alpaca paper. Ingests news + congressional + 13F + market-regime signals, reads markdown "memory" files like a portfolio manager, places trades within hard-coded server-side caps the model can't evade. Next.js terminal dashboard.

**Stack:** Python · FastAPI · Next.js · TypeScript · Anthropic + OpenAI · Alpaca · SQLAlchemy · Playwright

## Stack

![Swift](https://img.shields.io/badge/-Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Anthropic](https://img.shields.io/badge/-Anthropic_Claude-191919?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/-Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/-SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![Postgres](https://img.shields.io/badge/-Postgres-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pandas](https://img.shields.io/badge/-pandas-150458?style=flat-square&logo=pandas&logoColor=white)

## Find me

- **Email** — [matthewcromaz37@gmail.com](mailto:matthewcromaz37@gmail.com)
- **LinkedIn** — [linkedin.com/in/matthew-cromaz](https://linkedin.com/in/matthew-cromaz)
- **GitHub** — you're already here
