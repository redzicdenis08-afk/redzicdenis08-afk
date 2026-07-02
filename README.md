# Denis Redzic

**Founder and AI Systems Engineer.** I build voice-AI agents, automated workflows, and production systems that run reliably while businesses sleep.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

I am self-taught and I work solo, end to end. I handle the design, code, cloud infrastructure, and the unglamorous part where you keep it alive and functioning in production. Most of what I build talks to real customers in production, not sitting in a local demo.

## Why follow

I turn messy production AI problems into small public reference engines you can inspect. The open repos show reusable parts: parsers, schedulers, scoring, routing, audit trails, dry-run gates, and fictional examples.

Start here:

| Need | Repo |
|---|---|
| Score AI voice transcripts | [callscope](https://github.com/redzicdenis08-afk/callscope) |
| Audit broken voice agents with receipts | [dialproof](https://github.com/redzicdenis08-afk/dialproof) |
| Build missed-call AI receptionist workflows | [core-dispatch](https://github.com/redzicdenis08-afk/core-dispatch) |
| Generate local SEO lead-gen pages | [local-leadgen](https://github.com/redzicdenis08-afk/local-leadgen) |
| Analyze competitor ad creative | [adoracle](https://github.com/redzicdenis08-afk/adoracle) |

Public GitHub growth plan: [docs/GITHUB_GROWTH_PLAYBOOK.md](docs/GITHUB_GROWTH_PLAYBOOK.md).

---

## Flagship Open Source Tools

### 🔍 [callscope](https://github.com/redzicdenis08-afk/callscope)
**Outcome analytics and quality scoring for AI voice-agent call transcripts.**
*   A clean CLI and Python API to parse raw VAPI, Retell, Twilio, or plain text transcripts.
*   Categorizes calls into `human_reached`, `voicemail`, `ivr`, or `no_answer` instantly.
*   Detects high-signal customer events (objections, do-not-call requests, pricing discussion, bookings).
*   Applies offline, deterministic scoring to map conversation quality.
*   *Zero runtime dependencies. Pure Python standard library.*

### 📞 [core-dispatch](https://github.com/redzicdenis08-afk/core-dispatch)
**An open-source framework for AI voice-dispatch workflows.**
*   A clean qualify-and-schedule state machine for inbound and outbound operations.
*   Enforces calling windows, attempt limits, and custom backoff periods.
*   Includes signatures verification and defensive parsing for webhook ingestion.
*   *Zero runtime dependencies. Swap-ready provider protocols.*

---

## Featured Work

Each repository below is a clean, dependency-light **open reference implementation** of the engine behind one of my production systems. The live deployments stay private; the open part is the engine you can inspect, run, and test.

| Project | What it is | Stack |
|---|---|---|
| [**callscope**](https://github.com/redzicdenis08-afk/callscope) | Transcript outcome and quality analytics: CLI/API for VAPI/Retell/Twilio, offline scoring and signal detection. | Python |
| [**core-dispatch**](https://github.com/redzicdenis08-afk/core-dispatch) | AI voice-dispatch framework: missed-call intake, qualifying callbacks, booking, follow-up, on swappable adapters. | Python |
| [**adoracle**](https://github.com/redzicdenis08-afk/adoracle) | Ad-intelligence engine: normalize competitor ads, detect hooks and angles, score creative. | TypeScript |
| [**database-reactivation**](https://github.com/redzicdenis08-afk/database-reactivation) | Rank a business's dead leads by win-back potential and schedule compliant outreach. | Python |
| [**wc-leadgen**](https://github.com/redzicdenis08-afk/wc-leadgen) | Lead scoring plus a fail-closed CAN-SPAM and eligibility compliance engine. | Python |
| [**local-leadgen**](https://github.com/redzicdenis08-afk/local-leadgen) | Programmatic local-SEO page generator with schema.org markup and sitemaps. | TypeScript |
| [**dialproof**](https://github.com/redzicdenis08-afk/dialproof) | Voice-agent QA: audit calls, receipt-backed reports, dry-run-by-default action gate. | Python |

Every project ships with tests and CI. The bar I care about is simple: does it still work when nobody is watching.

---

## Tech Stack

```text
AI & Voice     LLMs (GPT, Claude) · Prompt engineering · VAPI · ElevenLabs · Deepgram
Languages      Python · TypeScript · JavaScript · SQL · Bash
Web            Next.js · React · Node · REST APIs · Webhooks
Automation     n8n · Playwright · Web scraping · Cron & systemd
Cloud & Data   AWS · Cloudflare · Linux · Docker · Google Sheets · SQLite · Supabase
```

---

## Activity

![Denis's GitHub stats](https://github-readme-stats.vercel.app/api?username=redzicdenis08-afk&show_icons=true&hide=stars&hide_title=true&theme=graywhite&hide_border=true&count_private=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=redzicdenis08-afk&layout=compact&theme=graywhite&hide_border=true&langs_count=6)

---

## Contact

*   **Portfolio** · https://denis.denisai.online
*   **LinkedIn** · https://www.linkedin.com/in/denis-redzic-118183419/
*   **Email** · hello@denisai.online
