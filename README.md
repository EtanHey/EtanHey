# Hey, I'm Etan

Full stack developer in Israel building AI infrastructure. I design systems where multiple AI agents collaborate autonomously — persistent memory, voice I/O, terminal orchestration, and 50 reusable skills.

Currently freelancing as osek patur and exploring opportunities in the Israeli startup market.

---

## What I Build

### Core Infrastructure

| Project | What it is | Key numbers |
|---------|-----------|-------------|
| **[Golems](https://github.com/EtanHey/golems)** | AI agent ecosystem — domain-expert agents as reusable skill packages, multi-vendor (Claude, Codex, Cursor, Gemini, Kiro) | 50 skills, 11 packages, 756 tests |
| **[BrainLayer](https://github.com/EtanHey/brainlayer)** | Persistent memory for AI agents — semantic search, knowledge graph, entity extraction | 295K+ chunks, 10 MCP tools, 1,083 tests |
| **[VoiceLayer](https://github.com/EtanHey/voicelayer)** | Voice I/O daemon — TTS + STT with MCP interface, VoiceBar native macOS daemon | 314 tests, ~300ms latency |
| **[cmuxlayer](https://github.com/EtanHey/cmuxlayer)** | Terminal multiplexer MCP — multi-agent workspace orchestration | 278 tests, 21 MCP tools |

### How They Fit Together

```
You → Claude Code / Codex / Cursor / Gemini
       ↓
     Skills (50 reusable workflows)
       ↓
     BrainLayer (memory across sessions)
     VoiceLayer (voice I/O)
     cmuxlayer  (multi-agent orchestration)
       ↓
     Supabase + Railway (persistence + cloud)
```

Every AI session gets memory of past decisions, voice interaction capability, and the ability to spawn and coordinate other agents. The skills work across any AI CLI — not locked to one vendor.

### Other Active Projects

| Project | Stack | What |
|---------|-------|------|
| **[Cantaloupe AI](https://trycantaloupe.com)** | Next.js, React Native, Supabase | Automated hiring — AI conducts voice interviews 24/7 |
| **[SongScript](https://github.com/EtanHey/songscript)** | TanStack Start, Convex, React 19 | Learn languages through music with line-by-line transliteration |
| **[etanheyman.com](https://etanheyman.com)** | Next.js 15, React 19, Tailwind v4 | Portfolio + golems dashboard |

---

## Open Source Contributions

| PR | Repo | Status | What |
|----|------|--------|------|
| [#1096](https://github.com/pingdotgg/t3code/pull/1096) | pingdotgg/t3code | Merged | fix: tighten node engine range for node:sqlite compat |
| [#4749](https://github.com/zed-industries/extensions/pull/4749) | zed-industries/extensions | Merged | Add iTerm2 default theme |
| [#1609](https://github.com/manaflow-ai/cmux/pull/1609) | manaflow-ai/cmux | Open | fix: crash on launch from Auto Layout constraint cycle |
| [#1562](https://github.com/manaflow-ai/cmux/pull/1562) | manaflow-ai/cmux | Open | fix: main thread starvation from synchronous socket I/O |
| [#1522](https://github.com/manaflow-ai/cmux/pull/1522) | manaflow-ai/cmux | Open | fix: offscreen NSWindow for background workspace PTY init |
| [#181](https://github.com/lharries/whatsapp-mcp/pull/181) | lharries/whatsapp-mcp | Open | fix: Unicode-safe chat search + auto-detect business bridge |
| [#58](https://github.com/Harzu/iced_term/pull/58) | Harzu/iced_term | Open | feat: public backend module + async PTY shutdown |
| [#2218](https://github.com/punkpeye/awesome-mcp-servers/pull/2218) | punkpeye/awesome-mcp-servers | Open | Add BrainLayer to Knowledge & Memory |
| [#2217](https://github.com/punkpeye/awesome-mcp-servers/pull/2217) | punkpeye/awesome-mcp-servers | Open | Add VoiceLayer voice I/O MCP |
| [#29](https://github.com/T3-Content/quipslop/pull/29) | T3-Content/quipslop | Open | Add 8 community prompts |
| [#23](https://github.com/T3-Content/quipslop/pull/23) | T3-Content/quipslop | Open | perf: less deterministic AI — temperature + reasoning split |
| [#14](https://github.com/T3-Content/quipslop/pull/14) | T3-Content/quipslop | Open | feat: twitch chat integration + audience-aware AI |

---

## Stack

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat&logo=swift&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat&logo=react&logoColor=black)
![Claude API](https://img.shields.io/badge/Claude_API-111111?style=flat&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-5A67D8?style=flat)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?style=flat&logo=bun&logoColor=white)
![Convex](https://img.shields.io/badge/Convex-FF6B6B?style=flat)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=flat&logo=tailwind-css&logoColor=white)

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/etanheyman)
[![Email](https://img.shields.io/badge/Email-etan@heyman.net-blue?style=flat)](mailto:etan@heyman.net)
[![Website](https://img.shields.io/badge/Website-etanheyman.com-green?style=flat)](https://etanheyman.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat&logo=whatsapp&logoColor=white)](https://wa.me/972547589755)
