<h1 align="center">Romanus Ogolla</h1>
<p align="center"><b>AI, Machine Learning &amp; Full-Stack Systems Engineer</b></p>
<p align="center">
  Building and shipping production digital systems end to end — predictive time-series models,
  LLM-powered analytics &amp; insight engines, data pipelines, REST APIs, cloud deployment,
  security hardening and SMS/WhatsApp alerting.
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white">
  <img alt="OpenAI" src="https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white">
  <img alt="Claude" src="https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white">
</p>

<p align="center">
  📧 golaromanus@gmail.com &nbsp;·&nbsp; 📍 Nairobi, Kenya &nbsp;·&nbsp;
  💻 <a href="https://github.com/golaromanus">github.com/golaromanus</a>
</p>

<blockquote align="center">
  <b>Source code is in private/production repositories — full walkthrough and code review available on request.</b><br>
  The projects below are live production systems. This page is a showcase of that work.
</blockquote>

---

## Selected Projects

<table>
<tr>
<td width="50%" valign="top">

### 🧠 AI Analytics &amp; Insights Platform
A production **AI insight engine** with a **multi-provider LLM integration** (OpenAI + Claude)
behind a clean provider-abstraction layer. Generates deep-analysis explanations with an
**anti-hallucination validation layer** that grounds every AI output against source data, plus a
**hybrid rules-engine + AI pipeline** with confidence-tiered outputs.

`TypeScript` · `NestJS` · `OpenAI` · `Claude` · `PostgreSQL`

</td>
<td width="50%" valign="top">

### 📈 Real-Time Time-Series Forecasting Engine
An end-to-end **predictive ML system**: a 15-feature engineering pipeline, scikit-learn / XGBoost
models with a deep-learning upgrade path, an **offline validation harness** (calibration &amp;
back-testing) and a **deployed FastAPI inference service** that learns continuously from live data.

`Python` · `scikit-learn` · `XGBoost` · `FastAPI` · `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏢 Qartit — Multi-Tenant Platform
A **multi-tenant SaaS platform** with isolated master + per-tenant databases and migrations,
served through an `api / web / worker` architecture with a **full observability stack**
(Grafana · Loki · Promtail · pgBouncer).

`Next.js` · `Prisma` · `PostgreSQL` · `Redis` · `Grafana`

</td>
<td width="50%" valign="top">

### 🔐 UnikQR — Hardened System with AI Insights
An `api / web / worker` system with a background **AI-insights worker** (Claude), and a
security-hardened deployment: **UFW + Cloudflare firewall**, automatic TLS via Caddy, and
**automated backup &amp; restore runbooks**.

`TypeScript` · `Docker` · `Caddy` · `UFW` · `Claude`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💳 Payliper — Payments Platform
A payments platform spanning **web + Android + api/worker** in a single monorepo, with
**SMS / WhatsApp notification integration** (Twilio · Africa's Talking) and a containerised deploy.

`Turborepo` · `Android` · `Twilio` · `Docker`

</td>
<td width="50%" valign="top">

### ⚙️ Cloud, CI/CD &amp; Delivery
Reproducible releases across all projects: **GitHub Actions → immutable GHCR images → SSH deploy**
with Docker Compose and Caddy (auto-TLS), non-root service users, secrets management and
monitoring via Sentry + the Grafana/Loki stack.

`GitHub Actions` · `GHCR` · `Docker Compose` · `Caddy` · `Sentry`

</td>
</tr>
</table>

---

## How the AI Insight Engine Works

```mermaid
flowchart LR
    A[Source Data<br/>records & live feeds] --> B[Rules Engine<br/>deterministic outcome]
    B --> C[LLM Layer<br/>OpenAI + Claude<br/>provider abstraction]
    C --> D[Validation<br/>grounded vs source<br/>anti-hallucination]
    D --> E[Insight Out<br/>confidence-tiered<br/>explainable]
```

*The LLM never invents facts — it explains what the rules engine already decided, and every explanation is validated against the source data before it reaches the user.*

---

## Experience Timeline

```mermaid
timeline
    2021 - 2022 : Engineering Simulation & Data Collection (UoN, AMREF) : Python/CFD modelling; led a 35-person data team
    2023 : Research Assistant, GIS & Spatial Analysis (ORIECO) : County-level suitability mapping across 5 counties
    2023 - 2024 : Generative AI & ML Trainee (UoN & Reaktor, Helsinki) : Supervised-learning classification models
    2025 : Member Analytics & Data Analyst (Dudu Sacco) : Arrears segmentation, survey & recruitment analytics
    2026 - Present : Chief Technology Officer (Elevika) : AI platforms, forecasting engine, cloud, security & alerting
```

---

## Core Skills

**AI / ML** — LLM integration · AI insights &amp; explainability · grounded / anti-hallucination validation · time-series forecasting · feature engineering &amp; model validation · scikit-learn · XGBoost

**Backend / Data** — Python · FastAPI · TypeScript · NestJS · REST APIs · PostgreSQL · Prisma · Redis · data pipelines &amp; systems architecture · multi-tenant design

**Cloud / DevOps / Security** — Docker · CI/CD · GHCR · Caddy · cloud deployment &amp; system administration · security hardening (UFW · Cloudflare · TLS) · backup/restore runbooks · monitoring (Grafana · Loki · Sentry)

**Integrations** — SMS / WhatsApp / email alerting (Twilio · Africa's Talking · Nodemailer)

**Other** — GIS &amp; spatial suitability analysis · Full-stack (Next.js) · Linux · C++ · CAD (AutoCAD · SolidWorks · ANSYS)

---

<p align="center"><sub>
  © Romanus Ogolla · Full source code and live demos available on request.
</sub></p>
