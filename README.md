# Denis Redzic

Self-taught builder from Bosnia. Voice AI, automation, and the engineering underneath it.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

## About

In 2026 I ran a small AI receptionist and dispatch operation for local service businesses, built on Vapi and n8n. That work taught me where voice agents actually break: callbacks outside legal hours, leads re-dialed forever, do-not-call requests ignored, broken bookings.

The repos here are the reusable parts of that work, rebuilt as small, tested, dependency-light reference implementations. They were built with heavy AI-assisted coding and are prototypes and learning projects, not production deployments. I say that upfront because I would rather be honest than impressive.

Right now I am going deep on fundamentals: Python, backend and APIs, testing, and AI agent reliability. Building in public, one project at a time.

## Featured

| Repo | What it does | Stack |
|---|---|---|
| [callscope](https://github.com/redzicdenis08-afk/callscope) | Offline outcome and quality scoring for AI voice-agent call transcripts, with a fictional benchmark | Python |
| [core-dispatch](https://github.com/redzicdenis08-afk/core-dispatch) | Qualify-and-schedule state machine for missed-call and callback workflows, with swappable provider adapters | Python |
| [dialproof](https://github.com/redzicdenis08-afk/dialproof) | Voice-agent QA: audit calls, receipt-backed reports, dry-run-by-default action gate | Python |

Every featured repo runs offline with in-memory adapters and ships with tests.

## Stack

```text
AI and voice   LLMs (Claude, GPT), Vapi, ElevenLabs, Deepgram
Languages      Python, TypeScript, JavaScript, SQL, Bash
Automation     n8n, webhooks, REST APIs, Playwright
Infra          Linux, Docker, Cloudflare, SQLite
```

## Contact

- Portfolio: https://denis.denisai.online
- LinkedIn: https://www.linkedin.com/in/denis-redzic-118183419/
- Email: hello@denisai.online

*Last updated: October 2026*
