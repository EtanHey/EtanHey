# Hey, I'm Etan

Full stack developer in Israel. I build products and occasionally let AI build them for me.

---

## What I'm Building

### [Golems](https://github.com/EtanHey/golems) — AI Agent Ecosystem

A Bun workspace monorepo of domain-expert AI agents — not locked to any single AI platform. Each agent is a self-contained **skill package** that works across Claude Code, Codex, Cursor, Gemini, and Kiro.

**5 domain golems** + orchestrator + 3 infrastructure daemons:

| Golem | Domain |
|-------|--------|
| **RecruiterGolem** | Outreach campaigns, contact discovery, 7 interview practice modes with Elo tracking |
| **TellerGolem** | Transaction categorization for tax, payment alerts, expense reports |
| **CoachGolem** | Calendar management, daily plans, cross-golem status |
| **JobGolem** | Board scraping (Indeed, SecretTLV, Drushim, Goozali), LLM scoring, auto-outreach |
| **ContentGolem** | LinkedIn posts, Hebrew tech ghostwriting |

**Also includes:**
- **[Ralph](https://github.com/EtanHey/golems/tree/master/packages/ralph)** — Autonomous coding loop. PRD in, shipped code out. Smart model routing, cost tracking, worktree isolation.
- **[BrainLayer](https://etanheyman.com/projects/brainlayer)** — Memory layer. 312K+ indexed chunks, knowledge graph, 8 MCP tools, BrainBar daemon (209KB native macOS binary). [Source](https://github.com/EtanHey/brainlayer) · [Docs](https://etanheyman.com/projects/brainlayer)
- **[VoiceLayer](https://etanheyman.com/projects/voicelayer)** — Voice I/O MCP daemon with dual-protocol (NDJSON + MCP Content-Length). TTS + STT, voice cloning, ~300ms latency. [Source](https://github.com/EtanHey/voicelayer) · [Docs](https://etanhey.github.io/voicelayer/)
- **[cmuxlayer](https://github.com/EtanHey/cmuxlayer)** — Terminal multiplexer MCP. 221 tests, 1,423x socket speedup, native MCP in cmux Swift fork.
- **45+ skills** with AI-agnostic adapter layer (Claude, Cursor, Gemini, Codex, Kiro), 6 MCP servers, 7 agent profiles
- **3 singleton daemons** built: BrainBar, VoiceBar MCP, cmux native MCP

Mac runs the brain (Telegram bot, Night Shift, memory). Railway runs the body (email polling, job scraping, briefings).

**[Live docs](https://etanheyman.com/golems/)**

### Active Projects

| Project | Stack | What it does |
|---------|-------|--------------|
| **[Golems](https://github.com/EtanHey/golems)** | TypeScript, Bun, Python | AI agent ecosystem — 16 packages, 5 domain golems, 45+ AI-agnostic skills |
| **[BrainLayer](https://etanheyman.com/projects/brainlayer)** | Python, SQLite, MCP | Persistent memory for AI agents — 312K+ chunks, 8 MCP tools, BrainBar daemon |
| **[VoiceLayer](https://etanheyman.com/projects/voicelayer)** | TypeScript, Bun, MCP | Voice I/O MCP daemon — dual-protocol, TTS + STT, voice cloning, ~300ms |
| **[cmuxlayer](https://github.com/EtanHey/cmuxlayer)** | Swift, TypeScript, MCP | Terminal multiplexer MCP — 221 tests, 1,423x socket speedup |
| **[Cantaloupe AI](https://trycantaloupe.com)** | Next.js, React Native, Supabase | Automated hiring platform — AI conducts voice interviews 24/7 |
| **Private** | Next.js, Expo, Supabase | Property platform (stealth) |
| **[SongScript](https://github.com/EtanHey/songscript)** | TanStack Start, Convex, React 19 | Learn languages through music with line-by-line transliteration |

---

## Open Source

### My Repos

| Repo | License | What |
|------|---------|------|
| **[Golems](https://github.com/EtanHey/golems)** | Apache 2.0 | AI agent ecosystem — domain-expert golems as skill packages, autonomous coding loop, semantic memory |
| **[BrainLayer](https://github.com/EtanHey/brainlayer)** | Apache 2.0 | Persistent memory for AI agents — 312K+ chunks, 8 MCP tools, 846 Python + 28 Swift tests, BrainBar daemon |
| **[VoiceLayer](https://github.com/EtanHey/voicelayer)** | Apache 2.0 | Voice I/O MCP daemon — dual-protocol (NDJSON + MCP Content-Length), TTS + STT, voice cloning |
| **[cmuxlayer](https://github.com/EtanHey/cmuxlayer)** | Apache 2.0 | Terminal multiplexer MCP — multi-agent workspace orchestration |
| **[SongScript](https://github.com/EtanHey/songscript)** | Apache 2.0 | Language learning through music — synchronized lyrics, word breakdowns |
| **[etanheyman.com](https://github.com/EtanHey/etanheyman.com)** | Apache 2.0 | Portfolio site (Next.js 15, React 19, Tailwind v4) |

### Contributions to Other Projects

| PR | Repo | Status | What |
|----|------|--------|------|
| [#1096](https://github.com/pingdotgg/t3code/pull/1096) | pingdotgg/t3code | Merged | fix: tighten node engine range for node:sqlite compat (#206) |
| [#4749](https://github.com/zed-industries/extensions/pull/4749) | zed-industries/extensions | Merged | Add iTerm2 default theme |
| [#1609](https://github.com/manaflow-ai/cmux/pull/1609) | manaflow-ai/cmux | Open | fix: crash on launch from Auto Layout constraint cycle |
| [#1522](https://github.com/manaflow-ai/cmux/pull/1522) | manaflow-ai/cmux | Open | fix: create offscreen NSWindow for background workspace P... |
| [#1562](https://github.com/manaflow-ai/cmux/pull/1562) | manaflow-ai/cmux | Open | fix: avoid main thread starvation from synchronous socket... |
| [#181](https://github.com/lharries/whatsapp-mcp/pull/181) | lharries/whatsapp-mcp | Open | fix: Unicode-safe chat search + auto-detect business brid... |
| [#58](https://github.com/Harzu/iced_term/pull/58) | Harzu/iced_term | Open | feat: make backend module public + async PTY shutdown |
| [#29](https://github.com/T3-Content/quipslop/pull/29) | T3-Content/quipslop | Open | Add 8 community prompts |
| [#23](https://github.com/T3-Content/quipslop/pull/23) | T3-Content/quipslop | Open | perf: less deterministic AI — add temperature + split rea... |
| [#14](https://github.com/T3-Content/quipslop/pull/14) | T3-Content/quipslop | Open | feat: twitch chat integration + audience-aware AI |

----|------|--------|------|
| [#1096](https://github.com/pingdotgg/t3code/pull/1096) | pingdotgg/t3code | Merged | fix: tighten node engine range for node:sqlite compat (#206) |
| [#4749](https://github.com/zed-industries/extensions/pull/4749) | zed-industries/extensions | Merged | Add iTerm2 default theme |
| [#2217](https://github.com/punkpeye/awesome-mcp-servers/pull/2217) | punkpeye/awesome-mcp-servers | Open | Add VoiceLayer — Voice I/O layer for Claude Code |
| [#2218](https://github.com/punkpeye/awesome-mcp-servers/pull/2218) | punkpeye/awesome-mcp-servers | Open | Add EtanHey/brainlayer to Knowledge & Memory |
| [#1609](https://github.com/manaflow-ai/cmux/pull/1609) | manaflow-ai/cmux | Open | fix: crash on launch from Auto Layout constraint cycle |
| [#1562](https://github.com/manaflow-ai/cmux/pull/1562) | manaflow-ai/cmux | Open | fix: avoid main thread starvation from synchronous socket... |
| [#1522](https://github.com/manaflow-ai/cmux/pull/1522) | manaflow-ai/cmux | Open | fix: create offscreen NSWindow for background workspace P... |
| [#181](https://github.com/lharries/whatsapp-mcp/pull/181) | lharries/whatsapp-mcp | Open | fix: Unicode-safe chat search + auto-detect business brid... |
| [#58](https://github.com/Harzu/iced_term/pull/58) | Harzu/iced_term | Open | feat: make backend module public + async PTY shutdown |
| [#29](https://github.com/T3-Content/quipslop/pull/29) | T3-Content/quipslop | Open | Add 8 community prompts |
| [#23](https://github.com/T3-Content/quipslop/pull/23) | T3-Content/quipslop | Open | perf: less deterministic AI — add temperature + split rea... |
| [#14](https://github.com/T3-Content/quipslop/pull/14) | T3-Content/quipslop | Open | feat: twitch chat integration + audience-aware AI |

----|------|--------|------|
| [#1096](https://github.com/pingdotgg/t3code/pull/1096) | pingdotgg/t3code | Merged | fix: tighten node engine range for node:sqlite compat (#206) |
| [#4749](https://github.com/zed-industries/extensions/pull/4749) | zed-industries/extensions | Merged | Add iTerm2 default theme |
| [#2217](https://github.com/punkpeye/awesome-mcp-servers/pull/2217) | punkpeye/awesome-mcp-servers | Open | Add VoiceLayer — Voice I/O layer for Claude Code |
| [#2218](https://github.com/punkpeye/awesome-mcp-servers/pull/2218) | punkpeye/awesome-mcp-servers | Open | Add EtanHey/brainlayer to Knowledge & Memory |
| [#1522](https://github.com/manaflow-ai/cmux/pull/1522) | manaflow-ai/cmux | Open | fix: create offscreen NSWindow for background workspace P... |
| [#1562](https://github.com/manaflow-ai/cmux/pull/1562) | manaflow-ai/cmux | Open | fix: avoid main thread starvation from synchronous socket... |
| [#1609](https://github.com/manaflow-ai/cmux/pull/1609) | manaflow-ai/cmux | Open | fix: crash on launch from Auto Layout constraint cycle |
| [#181](https://github.com/lharries/whatsapp-mcp/pull/181) | lharries/whatsapp-mcp | Open | fix: Unicode-safe chat search + auto-detect business brid... |
| [#58](https://github.com/Harzu/iced_term/pull/58) | Harzu/iced_term | Open | feat: make backend module public + async PTY shutdown |
| [#29](https://github.com/T3-Content/quipslop/pull/29) | T3-Content/quipslop | Open | Add 8 community prompts |
| [#23](https://github.com/T3-Content/quipslop/pull/23) | T3-Content/quipslop | Open | perf: less deterministic AI — add temperature + split rea... |
| [#14](https://github.com/T3-Content/quipslop/pull/14) | T3-Content/quipslop | Open | feat: twitch chat integration + audience-aware AI |

----|------|--------|------|
| [#1096](https://github.com/pingdotgg/t3code/pull/1096) | pingdotgg/t3code | Merged | fix: tighten node engine range for node:sqlite compat (#206) |
| [#4749](https://github.com/zed-industries/extensions/pull/4749) | zed-industries/extensions | Merged | Add iTerm2 default theme |
| [#2218](https://github.com/punkpeye/awesome-mcp-servers/pull/2218) | punkpeye/awesome-mcp-servers | Open | Add EtanHey/brainlayer to Knowledge & Memory |
| [#1609](https://github.com/manaflow-ai/cmux/pull/1609) | manaflow-ai/cmux | Open | fix: crash on launch from Auto Layout constraint cycle |
| [#1562](https://github.com/manaflow-ai/cmux/pull/1562) | manaflow-ai/cmux | Open | fix: avoid main thread starvation from synchronous socket... |
| [#1522](https://github.com/manaflow-ai/cmux/pull/1522) | manaflow-ai/cmux | Open | fix: create offscreen NSWindow for background workspace P... |
| [#181](https://github.com/lharries/whatsapp-mcp/pull/181) | lharries/whatsapp-mcp | Open | fix: Unicode-safe chat search + auto-detect business brid... |
| [#58](https://github.com/Harzu/iced_term/pull/58) | Harzu/iced_term | Open | feat: make backend module public + async PTY shutdown |
| [#2217](https://github.com/punkpeye/awesome-mcp-servers/pull/2217) | punkpeye/awesome-mcp-servers | Open | Add VoiceLayer — Voice I/O layer for Claude Code |
| [#29](https://github.com/T3-Content/quipslop/pull/29) | T3-Content/quipslop | Open | Add 8 community prompts |
| [#23](https://github.com/T3-Content/quipslop/pull/23) | T3-Content/quipslop | Open | perf: less deterministic AI — add temperature + split rea... |
| [#14](https://github.com/T3-Content/quipslop/pull/14) | T3-Content/quipslop | Open | feat: twitch chat integration + audience-aware AI |

----|------|--------|------|
| [#1096](https://github.com/pingdotgg/t3code/pull/1096) | pingdotgg/t3code | Merged | fix: tighten node engine range for node:sqlite compat (#206) |
| [#4749](https://github.com/zed-industries/extensions/pull/4749) | zed-industries/extensions | Merged | Add iTerm2 default theme |
| [#2218](https://github.com/punkpeye/awesome-mcp-servers/pull/2218) | punkpeye/awesome-mcp-servers | Open | Add EtanHey/brainlayer to Knowledge & Memory |
| [#1609](https://github.com/manaflow-ai/cmux/pull/1609) | manaflow-ai/cmux | Open | fix: crash on launch from Auto Layout constraint cycle |
| [#1562](https://github.com/manaflow-ai/cmux/pull/1562) | manaflow-ai/cmux | Open | fix: avoid main thread starvation from synchronous socket... |
| [#1522](https://github.com/manaflow-ai/cmux/pull/1522) | manaflow-ai/cmux | Open | fix: create offscreen NSWindow for background workspace P... |
| [#181](https://github.com/lharries/whatsapp-mcp/pull/181) | lharries/whatsapp-mcp | Open | fix: Unicode-safe chat search + auto-detect business brid... |
| [#58](https://github.com/Harzu/iced_term/pull/58) | Harzu/iced_term | Open | feat: make backend module public + async PTY shutdown |
| [#2217](https://github.com/punkpeye/awesome-mcp-servers/pull/2217) | punkpeye/awesome-mcp-servers | Open | Add VoiceLayer — Voice I/O layer for Claude Code |
| [#29](https://github.com/T3-Content/quipslop/pull/29) | T3-Content/quipslop | Open | Add 8 community prompts |
| [#23](https://github.com/T3-Content/quipslop/pull/23) | T3-Content/quipslop | Open | perf: less deterministic AI — add temperature + split rea... |
| [#14](https://github.com/T3-Content/quipslop/pull/14) | T3-Content/quipslop | Open | feat: twitch chat integration + audience-aware AI |

----|------|--------|------|
| [#1096](https://github.com/pingdotgg/t3code/pull/1096) | pingdotgg/t3code | Merged | fix: tighten node engine range for node:sqlite compat (#206) |
| [#4749](https://github.com/zed-industries/extensions/pull/4749) | zed-industries/extensions | Merged | Add iTerm2 default theme |
| [#1609](https://github.com/manaflow-ai/cmux/pull/1609) | manaflow-ai/cmux | Open | fix: crash on launch from Auto Layout constraint cycle |
| [#1562](https://github.com/manaflow-ai/cmux/pull/1562) | manaflow-ai/cmux | Open | fix: avoid main thread starvation from synchronous socket... |
| [#1522](https://github.com/manaflow-ai/cmux/pull/1522) | manaflow-ai/cmux | Open | fix: create offscreen NSWindow for background workspace P... |
| [#181](https://github.com/lharries/whatsapp-mcp/pull/181) | lharries/whatsapp-mcp | Open | fix: Unicode-safe chat search + auto-detect business brid... |
| [#2218](https://github.com/punkpeye/awesome-mcp-servers/pull/2218) | punkpeye/awesome-mcp-servers | Open | Add EtanHey/brainlayer to Knowledge & Memory |
| [#58](https://github.com/Harzu/iced_term/pull/58) | Harzu/iced_term | Open | feat: make backend module public + async PTY shutdown |
| [#2217](https://github.com/punkpeye/awesome-mcp-servers/pull/2217) | punkpeye/awesome-mcp-servers | Open | Add VoiceLayer — Voice I/O layer for Claude Code |
| [#29](https://github.com/T3-Content/quipslop/pull/29) | T3-Content/quipslop | Open | Add 8 community prompts |
| [#23](https://github.com/T3-Content/quipslop/pull/23) | T3-Content/quipslop | Open | perf: less deterministic AI — add temperature + split rea... |
| [#14](https://github.com/T3-Content/quipslop/pull/14) | T3-Content/quipslop | Open | feat: twitch chat integration + audience-aware AI |

----|------|--------|------|
| [#1096](https://github.com/pingdotgg/t3code/pull/1096) | pingdotgg/t3code | Merged | fix: tighten node engine range for node:sqlite compat (#206) |
| [#4749](https://github.com/zed-industries/extensions/pull/4749) | zed-industries/extensions | Merged | Add iTerm2 default theme |
| [#1609](https://github.com/manaflow-ai/cmux/pull/1609) | manaflow-ai/cmux | Open | fix: crash on launch from Auto Layout constraint cycle |
| [#1562](https://github.com/manaflow-ai/cmux/pull/1562) | manaflow-ai/cmux | Open | fix: avoid main thread starvation from synchronous socket... |
| [#1522](https://github.com/manaflow-ai/cmux/pull/1522) | manaflow-ai/cmux | Open | fix: create offscreen NSWindow for background workspace P... |
| [#181](https://github.com/lharries/whatsapp-mcp/pull/181) | lharries/whatsapp-mcp | Open | fix: Unicode-safe chat search + auto-detect business brid... |
| [#2218](https://github.com/punkpeye/awesome-mcp-servers/pull/2218) | punkpeye/awesome-mcp-servers | Open | Add EtanHey/brainlayer to Knowledge & Memory |
| [#58](https://github.com/Harzu/iced_term/pull/58) | Harzu/iced_term | Open | feat: make backend module public + async PTY shutdown |
| [#2217](https://github.com/punkpeye/awesome-mcp-servers/pull/2217) | punkpeye/awesome-mcp-servers | Open | Add VoiceLayer — Voice I/O layer for Claude Code |
| [#29](https://github.com/T3-Content/quipslop/pull/29) | T3-Content/quipslop | Open | Add 8 community prompts |
| [#23](https://github.com/T3-Content/quipslop/pull/23) | T3-Content/quipslop | Open | perf: less deterministic AI — add temperature + split rea... |
| [#14](https://github.com/T3-Content/quipslop/pull/14) | T3-Content/quipslop | Open | feat: twitch chat integration + audience-aware AI |

----|------|--------|------|
| [#1096](https://github.com/pingdotgg/t3code/pull/1096) | pingdotgg/t3code | Merged | fix: tighten node engine range for node:sqlite compat (#206) |
| [#4749](https://github.com/zed-industries/extensions/pull/4749) | zed-industries/extensions | Merged | Add iTerm2 default theme |
| [#1609](https://github.com/manaflow-ai/cmux/pull/1609) | manaflow-ai/cmux | Open | fix: crash on launch from Auto Layout constraint cycle |
| [#1562](https://github.com/manaflow-ai/cmux/pull/1562) | manaflow-ai/cmux | Open | fix: avoid main thread starvation from synchronous socket... |
| [#1522](https://github.com/manaflow-ai/cmux/pull/1522) | manaflow-ai/cmux | Open | fix: create offscreen NSWindow for background workspace P... |
| [#181](https://github.com/lharries/whatsapp-mcp/pull/181) | lharries/whatsapp-mcp | Open | fix: Unicode-safe chat search + auto-detect business brid... |
| [#2218](https://github.com/punkpeye/awesome-mcp-servers/pull/2218) | punkpeye/awesome-mcp-servers | Open | Add EtanHey/brainlayer to Knowledge & Memory |
| [#58](https://github.com/Harzu/iced_term/pull/58) | Harzu/iced_term | Open | feat: make backend module public + async PTY shutdown |
| [#2217](https://github.com/punkpeye/awesome-mcp-servers/pull/2217) | punkpeye/awesome-mcp-servers | Open | Add VoiceLayer — Voice I/O layer for Claude Code |
| [#29](https://github.com/T3-Content/quipslop/pull/29) | T3-Content/quipslop | Open | Add 8 community prompts |
| [#23](https://github.com/T3-Content/quipslop/pull/23) | T3-Content/quipslop | Open | perf: less deterministic AI — add temperature + split rea... |
| [#14](https://github.com/T3-Content/quipslop/pull/14) | T3-Content/quipslop | Open | feat: twitch chat integration + audience-aware AI |

----|------|--------|------|
| [#1096](https://github.com/pingdotgg/t3code/pull/1096) | pingdotgg/t3code | Merged | fix: tighten node engine range for node:sqlite compat (#206) |
| [#4749](https://github.com/zed-industries/extensions/pull/4749) | zed-industries/extensions | Merged | Add iTerm2 default theme |
| [#1609](https://github.com/manaflow-ai/cmux/pull/1609) | manaflow-ai/cmux | Open | fix: crash on launch from Auto Layout constraint cycle |
| [#1562](https://github.com/manaflow-ai/cmux/pull/1562) | manaflow-ai/cmux | Open | fix: avoid main thread starvation from synchronous socket... |
| [#1522](https://github.com/manaflow-ai/cmux/pull/1522) | manaflow-ai/cmux | Open | fix: create offscreen NSWindow for background workspace P... |
| [#181](https://github.com/lharries/whatsapp-mcp/pull/181) | lharries/whatsapp-mcp | Open | fix: Unicode-safe chat search + auto-detect business brid... |
| [#2218](https://github.com/punkpeye/awesome-mcp-servers/pull/2218) | punkpeye/awesome-mcp-servers | Open | Add EtanHey/brainlayer to Knowledge & Memory |
| [#58](https://github.com/Harzu/iced_term/pull/58) | Harzu/iced_term | Open | feat: make backend module public + async PTY shutdown |
| [#2217](https://github.com/punkpeye/awesome-mcp-servers/pull/2217) | punkpeye/awesome-mcp-servers | Open | Add VoiceLayer — Voice I/O layer for Claude Code |
| [#29](https://github.com/T3-Content/quipslop/pull/29) | T3-Content/quipslop | Open | Add 8 community prompts |
| [#23](https://github.com/T3-Content/quipslop/pull/23) | T3-Content/quipslop | Open | perf: less deterministic AI — add temperature + split rea... |
| [#14](https://github.com/T3-Content/quipslop/pull/14) | T3-Content/quipslop | Open | feat: twitch chat integration + audience-aware AI |

----|------|--------|------|
| [#206](https://github.com/pingdotgg/t3code/pull/206) | pingdotgg/t3code | Merged | Fix: tighten node engine range for node:sqlite compat |
| [#181](https://github.com/lharries/whatsapp-mcp/pull/181) | lharries/whatsapp-mcp | Open | Fix: Unicode-safe chat search + auto-detect business bridge DB |
| [#4749](https://github.com/zed-industries/extensions/pull/4749) | zed-industries/extensions | Merged | Add iTerm2 default theme |
| [#1522](https://github.com/manaflow-ai/cmux/pull/1522) | manaflow-ai/cmux | Open | Fix: background workspace PTY initialization |
| [#1562](https://github.com/manaflow-ai/cmux/pull/1562) | manaflow-ai/cmux | Open | Fix: thread starvation in MCP server |
| [#58](https://github.com/Harzu/iced_term/pull/58) | Harzu/iced_term | Open | Feat: public backend module + async PTY shutdown |
| [#2218](https://github.com/punkpeye/awesome-mcp-servers/pull/2218) | punkpeye/awesome-mcp-servers | Open | Add BrainLayer to Knowledge & Memory |
| [#2217](https://github.com/punkpeye/awesome-mcp-servers/pull/2217) | punkpeye/awesome-mcp-servers | Open | Add VoiceLayer voice I/O MCP |

---

## Stack

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat&logo=expo&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![Convex](https://img.shields.io/badge/Convex-FF6B6B?style=flat)
![Claude API](https://img.shields.io/badge/Claude_API-111111?style=flat&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-5A67D8?style=flat)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![Zsh](https://img.shields.io/badge/Zsh-F15A24?style=flat&logo=gnu-bash&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?style=flat&logo=bun&logoColor=white)

---

## About the Contribution Graph

The green squares mostly come from:
- **[Cantaloupe AI](https://trycantaloupe.com)** — Automated hiring with AI voice interviews
- **Private project** — Active development (stealth)
- **Golems** — The AI agent ecosystem
- **Client work** — Various private repos

Most of the interesting work lives in private repos. Happy to discuss in conversation.

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/etanheyman)
[![Email](https://img.shields.io/badge/Email-etan@heyman.net-blue?style=flat)](mailto:etan@heyman.net)
[![Website](https://img.shields.io/badge/Website-etanheyman.com-green?style=flat)](https://etanheyman.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat&logo=whatsapp&logoColor=white)](https://wa.me/972547589755)
