<div align="center">

<img src="./assets/header_deploy.svg" alt="Dechante Chang — Forward-Deployed AI & Systems Engineer" width="820" />

📍 **Central Florida** &nbsp;·&nbsp; 🤖 **Forward-Deployed AI & Systems Engineer** &nbsp;·&nbsp; 🎓 **CS @ UCF (Dec 2026)**

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/-Java-E76F00?style=flat-square&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude-000000?style=flat-square&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/-Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

![FFmpeg](https://img.shields.io/badge/-FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white)
![Twilio](https://img.shields.io/badge/-Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white)
![Telnyx](https://img.shields.io/badge/-Telnyx-00B26B?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</div>

> I design, deploy, and operate autonomous AI systems and production SaaS — multi-agent automation, media pipelines, and trading bots on one side; WebRTC voice platforms, power dialers, and CRMs on the other. I ship fast, automate everything, and let the work speak for itself.

---

## 🏆 Awards & Open Source

### 🥇 1st Place — Google Gemini Hackathon (BloomKnights)

Architected a **real-time sports prediction market**: edge-device camera feeds from **Ray-Ban Meta** glasses capture the live game, **Gemini** orchestration extracts team stats on the fly, and the system streams back **dynamic win probabilities** as the play unfolds.

`Gemini` `LLM Orchestration` `Ray-Ban Meta` `Real-Time Vision` `Prediction Markets`

### 🔓 Open Source Contributions

Contributing fixes to the data & AI infrastructure I build on every day — **1 merged upstream, more in review** across major projects:

| Project | Contribution | Status |
|---|---|---|
| [**streamlit**](https://github.com/streamlit/streamlit/pull/15949) | Fix `RuntimeError: reentrant call inside _io.BufferedWriter` on Ctrl+C | ✅ **Merged** |
| [**pandas**](https://github.com/pandas-dev/pandas/pull/66304) | Fix `loc`/`iloc` setitem with empty / boolean column indexer on EA dtypes | 🟢 Open |
| [**scikit-learn**](https://github.com/scikit-learn/scikit-learn/pull/34464) | Fix `OrdinalEncoder` crash on numeric transform data with object-dtype categories | 🟢 Open |
| [**dask**](https://github.com/dask/dask/pull/12502) | Skip rechunk in `to_zarr` when chunks already align with the target array | 🟢 Open |
| [**Chart.js**](https://github.com/chartjs/Chart.js/pull/12275) | Don't run tooltip content callbacks when all items are filtered out | 🟢 Open |
| [**cypress**](https://github.com/cypress-io/cypress/pull/34283) | Don't inject into commented-out `head`/`body`/`html` tags | 🟢 Open |

---

## 🤖 AI Automation & Agents

### 🎬 [ClipPro](https://github.com/chang-pro/clippro) — Free Opus Clip Alternative `Open Source`

> Turn long videos into viral clips — runs locally, no subscriptions, no cloud uploads.

Built with **Whisper (GPU)** + **Gemini AI** + **FFmpeg**. Transcribes your video, scores the highest-virality moments with AI hook ranking, then cuts 9:16 clips with karaoke captions and hook overlays. Includes a web UI and a clip combiner.

`Python` `Flask` `faster-whisper` `Gemini 2.5 Flash` `FFmpeg` `OpenCV`

### 🖼️ [Meta AI MCP](https://github.com/chang-pro/meta-ai-mcp) — Free image + video generation via Meta AI `Source Available`

> Generate AI videos from Claude Code for free — no API key, no subscription.

Reverse-engineered Meta AI Vibes to expose a working MCP tool and CLI. Browser-driven CDP automation because Meta sends prompts over protobuf WebSocket — no pure-HTTP client exists. Text→video and image→video both work. ~30-90s per clip.

`Python` `MCP` `Chrome CDP` `agent-browser` `FFmpeg` `Reverse Engineering`

### 🔗 [LinkedIn MCP](https://github.com/chang-pro/linkedin-mcp) — LinkedIn Browser Automation MCP `Source Available`

> Post, comment, like, and DM on LinkedIn from Claude Code — no official API, no $300/month tools.

Browser-driven CDP automation using your real logged-in Chrome session. Five MCP tools: post (with image), comment, like, DM, and session status check.

`Python` `MCP` `Chrome CDP` `LinkedIn`

## 📈 Algorithmic Trading

### 🎯 [no-backtest-drift](https://github.com/chang-pro/no-backtest-drift) — Live/Backtest Parity Pattern `Source Available`

> Stop your trading bot from lying to you. One pattern: live engine delegates to backtest engine. Zero drift.

The #1 silent killer in algo bots is live-vs-backtest divergence. This pattern fixes it structurally — the live engine has no entry logic of its own; it calls the backtest engine's exact `should_enter()`. One brain, used in both places. 10 tests document every config-default trap and verify parity on every bar.

`Python` `Algorithmic Trading` `IBKR` `Backtesting` `pytest`

## 📞 Voice, Telephony & SaaS

- 📟 **Ringora** — Multi-tenant SaaS CRM & power dialer: Telnyx WebRTC, Stripe billing, AI call analysis, Rust WASM

## 📊 Building in Public

- 🛠️ **[daily-builds](https://github.com/chang-pro/daily-builds)** — a public log of what I ship most days. Project repos stay private; the cadence is public.
- 🌱 **[openai-chart-data-analyzer](https://github.com/chang-pro/openai-chart-data-analyzer)** — one of my first builds (2022): a PyQt GUI querying GPT-3 on chart data. Kept as a marker of how far the work has come.

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=chang-pro&hide_border=true&theme=github-dark-blue" alt="contribution streak" />

</div>

<!-- Contribution snake (auto-generated every 12h by .github/workflows/snake.yml) -->
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/chang-pro/chang-pro/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/chang-pro/chang-pro/output/github-snake.svg" />
  <img alt="github contribution snake" src="https://raw.githubusercontent.com/chang-pro/chang-pro/output/github-snake.svg" />
</picture>

</div>

---

## What I'm About

- **Shipping production software** — SaaS platforms, telephony systems, AI pipelines, and trading bots running in prod
- **AI-native development** — building with Claude, Gemini, and custom multi-agent systems to move faster
- **Voice & telephony engineering** — WebRTC, Twilio, Telnyx, Vapi — browser-based calling is my thing
- **Automating everything** — if it can be automated, it should be

## Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/-dmchang.xyz-FF5722?style=flat-square&logo=google-chrome&logoColor=white)](https://www.dmchang.xyz)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/changweb)
[![TechHelpFL](https://img.shields.io/badge/-TechHelpFL.com-brightgreen?style=flat-square&logo=google-chrome&logoColor=white)](https://techhelpfl.com)
[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chang-pro)

</div>

---

> Most projects are **closed source** and in active development. If you're interested for hiring, collaboration, or licensing — reach out. Open source contributions are marked above.
