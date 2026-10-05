# Federico Garzón

**AI & Growth leader in fintech, mortgages and rental housing.** I build AI agents, put them in production and stay on the hook for what they do to the numbers.

- **Now:** Head of AI & Growth at [LQN Hipotecas](https://lqnhipotecas.com), a VC-backed mortgage platform in Colombia. I designed and run the agents the company uses every day: an operations agent with 5,100+ sessions, a WhatsApp CRM with a voice agent, a broker copilot, an MCP plugin for ChatGPT and Claude, and a gamified dashboard that turns the loan pipeline into daily goals for 30+ people.
- **Before:** Co-founder and CEO of DORA, a rental guarantee company that replaced the co-signer requirement in Colombian leases. 2,000 tenants, USD 8.4M in annualized guaranteed rent, 0.8% default rate. Acquired.
- **Based in:** Bogotá. Open to remote work or relocation to the US or Mexico.

## Start here

| | |
|---|---|
| 📂 **[ai-systems-in-production](https://github.com/fechegarzon/ai-systems-in-production)** | Case studies of every system I built at LQN and DORA: architecture, decisions, results and what broke |
| 🔐 **[mcp-readonly-gateway](https://github.com/fechegarzon/mcp-readonly-gateway)** | How I give agents tool access without giving them the keys: an MCP server with allowlists, limits, human confirmation and an audit log |
| 💬 **[whatsapp-agent-kit](https://github.com/fechegarzon/whatsapp-agent-kit)** | Running an agent on the WhatsApp Cloud API safely: signed webhooks, idempotency, the 24-hour window and dry-run switches |
| 🧪 **[agent-evals](https://github.com/fechegarzon/agent-evals)** | How I test agents before and after a change: eval suites, a pinned LLM judge, cost tracking and a regression gate in CI |
| ⚖️ **[inmolawyer](https://github.com/fechegarzon/inmolawyer)** | AI review of Colombian residential leases (Law 820) with a 0–100 risk score |

## Numbers I can stand behind

| | |
|---|---|
| 5,100+ | agent sessions in production (43 users, 75K tool calls) |
| USD 51K/yr | saved by an AI agent that took over an operations coordinator role, at USD 274–400/month to run |
| 8–9x | growth in daily Google impressions in three weeks |
| 286 | merged pull requests across 7 repositories in six months |
| USD 8.4M | annualized rent guaranteed at DORA |

Most of my work code belongs to my employer and lives in private repositories. The case studies above explain what each system does and how it is built. I'm happy to walk through any of them on a call.

## How I work

I lead a small team and a fleet of coding agents. I run Claude Code and Codex in parallel on isolated branches, treat `AGENTS.md` as the contract every agent reads first, and let CI and tests decide what ships. I separate what is measured from what is estimated, and I write down every decision that matters.

**Stack:** Python (FastAPI) · TypeScript (Hono, XState, BullMQ, Zod) · PostgreSQL · Redis · Claude, GPT and Gemini APIs · MCP · Pipecat · WhatsApp Cloud API · Metabase · DigitalOcean · Cloudflare · GitHub Actions

## Contact

fechegarzon@gmail.com · [LinkedIn](https://www.linkedin.com/in/feche1101) · [feche.xyz](https://feche.xyz)
