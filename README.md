# Hey, I'm Dechante 👋

📍 **Central Florida** | 🤖 **AI Automation Engineer** | 📞 **Voice/Telephony + Full-Stack SaaS**

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Claude](https://img.shields.io/badge/-Claude-000000?style=flat-square&logo=anthropic&logoColor=white)
![FFmpeg](https://img.shields.io/badge/-FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white)
![Twilio](https://img.shields.io/badge/-Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white)
![Telnyx](https://img.shields.io/badge/-Telnyx-00B26B?style=flat-square)
![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Stripe](https://img.shields.io/badge/-Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)

> I design, deploy, and operate autonomous AI systems and production SaaS — multi-agent automation, media pipelines, and trading bots on one side; WebRTC voice platforms, power dialers, and CRMs on the other. I ship fast, automate everything, and let the work speak for itself.

---

## 🤖 AI Automation & Agents

### 🎬 [ClipPro](https://github.com/chang-pro/clippro) — Free Opus Clip Alternative `Open Source`

> Turn long videos into viral clips — runs locally, no subscriptions, no cloud uploads.

Built with **Whisper (GPU)** + **Gemini AI** + **FFmpeg**. Transcribes your video, scores the highest-virality moments with AI hook ranking, then cuts 9:16 clips with karaoke captions and hook overlays. Includes a web UI and a clip combiner.

`Python` `Flask` `faster-whisper` `Gemini 2.5 Flash` `FFmpeg` `OpenCV`

### 🖼️ [Meta AI MCP](https://github.com/chang-pro/meta-ai-mcp) — Free image generation + AI prompting via Meta AI `Source Available`

> Generate AI videos from Claude Code for free — no API key, no subscription.

Reverse-engineered Meta AI Vibes to expose a working MCP tool and CLI. Browser-driven CDP automation because Meta sends prompts over protobuf WebSocket — no pure-HTTP client exists. Text→video and image→video both work. ~30-90s per clip.

`Python` `MCP` `Chrome CDP` `agent-browser` `FFmpeg` `Reverse Engineering`

### 🔗 [LinkedIn MCP](https://github.com/chang-pro/linkedin-mcp) — LinkedIn Browser Automation MCP `Source Available`

> Post, comment, like, and DM on LinkedIn from Claude Code — no official API, no $300/month tools.

Browser-driven CDP automation using your real logged-in Chrome session. No partner-program approval, no PhantomBuster subscription. Five MCP tools: post (with image), comment, like, DM, and session status check.

`Python` `MCP` `Chrome CDP` `LinkedIn`


## 📈 Algorithmic Trading

### 🎯 [no-backtest-drift](https://github.com/chang-pro/no-backtest-drift) — Live/Backtest Parity Pattern `Source Available`

> Stop your trading bot from lying to you. One pattern: live engine delegates to backtest engine. Zero drift.

The #1 silent killer in algo bots is live-vs-backtest divergence. Separate entry logic in two places means they drift. This pattern fixes it structurally — the live engine has no entry logic of its own. It calls the backtest engine's exact `should_enter()` function. One brain, used in both places. 10 tests document every config-default trap and verify parity on every bar.

`Python` `Algorithmic Trading` `IBKR` `Backtesting` `pytest`

## 📞 Voice, Telephony & SaaS

- 📟 **Ringora** — Multi-tenant SaaS CRM & power dialer: Telnyx WebRTC, Stripe billing, AI call analysis, Rust WASM

## 🌐 Web & Product


## 📊 Building in Public

- 🛠️ **[daily-builds](https://github.com/chang-pro/daily-builds)** — a public log of what I ship most days. Project repos stay private; the cadence is public.
- 🌱 **[openai-chart-data-analyzer](https://github.com/chang-pro/openai-chart-data-analyzer)** — one of my first builds (2022): a PyQt GUI querying GPT-3 on chart data. Kept as a marker of how far the work has come.

---

## What I'm About

- **Shipping production software** — SaaS platforms, telephony systems, AI pipelines, and trading bots running in prod
- **AI-native development** — building with Claude, Codex, and custom multi-agent systems to move faster
- **Voice & telephony engineering** — WebRTC, Twilio, Telnyx, Vapi — browser-based calling is my thing
- **Automating everything** — if it can be automated, it should be

## Connect

[![Portfolio](https://img.shields.io/badge/-dmchang.xyz-FF5722?style=flat-square&logo=google-chrome&logoColor=white)](https://www.dmchang.xyz)
[![TechHelpFL](https://img.shields.io/badge/-TechHelpFL.com-brightgreen?style=flat-square&logo=google-chrome&logoColor=white)](https://techhelpfl.com)
[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chang-pro)

---

> Most projects are **closed source** and in active development. If you're interested for hiring, collaboration, or licensing — reach out. Open source contributions are marked above.

