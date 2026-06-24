## J. Nicolas LL.M.: building payment infra for agents.

Founder of **[OneShot](https://oneshotagent.com)** and **[Freway](https://freway.ai)**.
I build AI agents that do real work and get paid for it.

- **[OneShot](https://oneshotagent.com)**: the commercial action layer for AI agents. 26+ tools, x402 pay-per-call in USDC on Base, signed receipts, MCP. `240★`
- **[oneshot-gtm](https://github.com/oneshot-agent/oneshot-gtm)**: open-source GTM agent built on OneShot. `453★`
- **[Freway](https://freway.ai)**: conversational-commerce agent "Janine" that closes the sale at checkout. $10.2M revenue closed.
- **[SoulHunt](https://soulhunt.ai)**: judgement-cloning. AI "souls" that do a person's work autonomously.

Previously: consumer products past 500K users (Butter.us, Video.io), ML & data @ Erste Group ($300B+ assets), PM @ Cloudflare, earlier @ PayPal.

`TypeScript` · `Python` · `LLM agents` · `model training / fine-tuning` · `x402 / on-chain` · `MCP`

[LinkedIn](https://linkedin.com/in/legendjerry) · [@nclsjrry](https://x.com/nclsjrry)

---

### 商 OneShot — the agent commerce stack
The action layer that lets AI agents pay for and run real-world tasks via x402 (USDC on Base).

- **[OneShot core](https://oneshotagent.com)** — email, SMS, voice, research, enrichment, commerce, browser automation, signed receipts.
- **[oneshot-sdk](https://github.com/oneshot-agent/sdk)** — `@oneshot-agent/sdk`, the TypeScript SDK with built-in x402 payments. _(open source)_
- **[oneshot-gtm](https://github.com/oneshot-agent/oneshot-gtm)** — terminal CLI + local dashboard; a pay-per-result GTM agent for technical founders. _(open source)_
- **[agent-skills](https://github.com/oneshot-agent/agent-skills)** — teach 70+ coding agents (Claude Code, Cursor, Codex) to use OneShot. _(open source)_

### 話 Freebot — customer-service & outbound AI
Voice/SMS/email agents that handle support and outbound for businesses.

- **[Freebot](https://freebot.ai)** — core platform (Remix, Supabase, Stripe, Twilio, FreeSWITCH, LangChain, Typesense).
- **[Freebot Outbound](https://app.freebot.ai)** — outbound across email/SMS/voice (FreeSWITCH + Twilio + OpenRouter).
- **[Freebot Tasks](https://task-manager.freebot.ai)** — Bun task-runner backend with Docker deploy.
- **[Freebot Ads](https://freebot.ai)** — automated Google Ads campaign creation/management.
- **[Freebot for Business](https://app.freebot.ai)** — Firebase + FreeSWITCH business edition with customer portals.
- **[FreeShop](https://freeshop.ai)** — AI-avatar live-shopping: photorealistic lip-sync (LatentSync) + ElevenLabs TTS on GPU.
- **[FreeButter Agents](https://freebutter.ai)** — multi-agent framework (Python, multi-provider LLM, Docker-isolated tool execution).

### 品 Products & consumer apps
- **[Freway](https://freway.ai)** — conversational-commerce site & agent (Next.js 15 / React 19).
- **[Based Mini Apps](https://basedminiapps.xyz)** — Bun + Nx monorepo of Base mini-apps (Prisma, Docker).
- **[Blabla](https://blablalanguage.ai)** — language-learning iOS app (Swift/Obj-C).
- **[1message](https://1message.app)** — unified messaging experiment.

### 払 Payments & Network Token Orchestration
- **[NTO Optimizer](https://ntooptimizer.com)** — network-token routing optimizer; Shopify embedded app + orchestrator backend (Drizzle, Nx).
- **[NTO Synthetic Data](https://synthetic.ntooptimizer.com)** — synthetic transaction generator for routing research (6 merchant archetypes, BigQuery, Terraform).
- **[Merchant Enrichment](https://merchants.ntooptimizer.com)** — Apollo/Shopify lead enrichment pipeline.

### 脳 Personal AI & content tooling
- **[Brain](https://nclsjrry.com)** — Obsidian + Bun content engine driving four Twitter voices, LinkedIn, blog, and video scripts.
- **[Message Concierge](https://hermes.app)** — drafts replies in your voice across iMessage/WhatsApp/Instagram with human approval (MCP).
- **[LegendJerry Video](https://legendjerry.com)** — portrait → vertical lip-synced music-video pipeline (Fal AI + Gemini/Veo).
- **[Resume Optimizer](https://resume-optimizer.app)** — ATS-tailored resume rewriter (Gemini 2.5 + spaCy + ReportLab).
- **[Real Podcast](https://realpodcast.app)** — open NotebookLM-style podcast generator from documents.
- **[Theme Generator](https://generatethemes.com)** — LLM theme generator from Reddit, evaluated + stored in Chroma.
- **[MidJourney Client](https://mj.legendjerry.com)** — unofficial MidJourney API client/server (WebSocket).
- **[Situations Rank](https://situations.app)** — Flask service ranking situational content (Firestore, Cloud Run).

### 球 European Handball Federation (client work)
SSO, auth, fan engagement, and data migrations for the EHF ecosystem.

- **[EHF SSO](https://sso.eurohandball.com)** — production OIDC provider (Next.js 15, Prisma, NextAuth, tRPC).
- **[EHF Auth](https://auth.eurohandball.com)** — Authentik OIDC identity infra (Docker, Postgres, Redis).
- **[EHF Fan Engagement](https://eurohandball.com)** — fan-engagement platform (Remix, PostHog).
- **[EHF Bot](https://bot.eurohandball.com)** — document-aware chatbot (Remix, Pinecone, OpenRouter).
- **[EHF AI Chatbot](https://chat.eurohandball.com)** — multi-LLM RAG chatbot (Next.js, Vercel AI SDK, Pinecone).
- **[EHF TV](https://ehftv.com)** — HLS streaming API client (10,000+ handball videos).
- **[IDCS → Authentik migration](https://eurohandball.com)** — Oracle IDCS → Authentik user/group/app ETL, plus Eloqua/Iubenda consent (11.7M+ records) and PhotoShelter integration.
- **[Login load-test suite](https://eurohandball.com)** — Playwright load tests for eurohandball.com login.

### 集 Scrapers & automation
- **[Crexi Scraper](https://crexi-scrape.app)** — Crexi real-estate scraper → BigQuery.
- **[Maps Lead Scraper](https://maps-leads.app)** — landscaping-lead scraper enriched with Gemini + weather.
- **[Review Scraper](https://review-scraper.app)** — multi-source review scraper + TF-IDF/ML theme extraction.
- **[LinkedIn Auto-Apply](https://autoapply.app)** — LinkedIn auto-apply bot (Selenium + multi-LLM).
- **[Browser Job Agent](https://browser-jobs.app)** — Gradio UI for browser agents (Playwright, multi-LLM, persistent sessions).
- **[Phone Verification](https://phone-verify.app)** — verifies org phone numbers with Vertex AI → Supabase (Cloud Run).

### 基 Models, infra & research
Models I've trained, plus the serving and infra around them.

- **[GPT from scratch](https://colab.research.google.com/drive/10tVTAmNDq1XMiBPH7Tg7eNIOdBJn189F)** — a transformer implemented and trained end-to-end in raw PyTorch: multi-head self-attention, residual blocks, custom training loop. _(private notebook)_
- **[DistilBERT classifier ensemble](https://colab.research.google.com/drive/1oWLmGByKqFuMpD9iyRM3kpbRD27jjvmS)** — fine-tuned via HuggingFace Trainer into a 4-model majority-vote ensemble, with a BigQuery-backed labeling + disagreement pipeline. _(private notebook)_
- **[Llama-2-7B fine-tuning](https://colab.research.google.com/drive/1wIBMCL9qzjxkO43q6K8BOSTBtY-Ot1R-)** — full fine-tuning pipeline (HF Trainer, mixed precision, gradient accumulation, custom structural tokens). _(private notebook)_
- **[vLLM serving](https://colab.research.google.com/drive/1S5Ff9xN2sH95iV-8HsYojTN1MZZqgAyZ)** — self-hosted vLLM (Llama-3-8B-Instruct) driving production prompt generation. _(private notebook)_
- **[Typesense HA](https://github.com/tormine/typesense)** — high-availability Typesense deploy on GKE (Docker + Cloud Build).
- **[LiteLLM Proxy](https://github.com/tormine/litellm)** — proxy routing Claude/Gemini for Cursor (OpenRouter / Vertex AI, ngrok).
- **[iOS Location Spoofer](https://github.com/tormine/ios-location-spoofer)** — no-jailbreak iOS location spoofing via on-device VPN/MITM (Swift + Go).
- **[macOS Keylogger PoC](https://github.com/tormine/keylogger)** — Event-Tap keylogger for security research (Objective-C).

### 芸 Music & creative
Before software I worked in music, direction, and film — the thread behind the lyrics models, the AI music-video pipeline, and the LegendJerry handle. Reel on [Vimeo](https://vimeo.com/315299303) · music on [SoundCloud](https://soundcloud.com/legendjerry) · more at [legendjerry.com](https://legendjerry.com).

> Many of these are private, research-only, or not yet live.
