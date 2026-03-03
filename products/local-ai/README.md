# Lab-in-a-Box: Local AI (CPU-first)

This is a reproducible **Local AI** demo stack for home labs and mini PCs.

**Stack:** Ollama + Open WebUI  
**Goal:** Working local chat UI + a deterministic “it works” proof in under 60 minutes.

---

## What you get
- Pinned-version `docker-compose.yml`
- A quickstart that gets to **LOCAL UI OK**
- A troubleshooting section (symptom → cause → fix)
- Bonus: icons/wallpaper assets (optional)

---

## Prerequisites
- Linux host with Docker + Docker Compose v2  
- Recommended: **16 GB+ RAM** (32 GB is comfortable)
- Disk: **10–20 GB** free for a small model demo

---

## Quickstart

### 1) Get the stack files
From the repo root:

```bash
cd products/local-ai/stack
cp .env.example .env
