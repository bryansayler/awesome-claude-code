<!--lint disable remark-lint:awesome-badge-->

#

<!-- [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) -->

<pre style="display: inline-block; text-align: left;">
 █████┐ ██┐    ██┐███████┐███████┐ ██████┐ ███┐   ███┐███████┐
██┌──██┐██│    ██│██┌────┘██┌────┘██┌───██┐████┐ ████│██┌────┘
███████│██│ █┐ ██│█████┐  ███████┐██│   ██│██┌████┌██│█████┐
██┌──██│██│███┐██│██┌──┘  └────██│██│   ██│██│└██┌┘██│██┌──┘
██│  ██│└███┌███┌┘███████┐███████│└██████┌┘██│ └─┘ ██│███████┐
└─┘  └─┘ └──┘└──┘ └──────┘└──────┘ └─────┘ └─┘     └─┘└──────┘

 ────────────────────────────────────────────────────────────────────────────────────

 ██████┐██┐      █████┐ ██┐   ██┐██████┐ ███████┐     ██████┐ ██████┐ ██████┐ ███████┐
██┌────┘██│     ██┌──██┐██│   ██│██┌──██┐██┌────┘    ██┌────┘██┌───██┐██┌──██┐██┌────┘
██│     ██│     ███████│██│   ██│██│  ██│█████┐      ██│     ██│   ██│██│  ██│█████┐
██│     ██│     ██┌──██│██│   ██│██│  ██│██┌──┘      ██│     ██│   ██│██│  ██│██┌──┘
└██████┐███████┐██│  ██│└██████┌┘██████┌┘███████┐    └██████┐└██████┌┘██████┌┘███████┐
 └─────┘└──────┘└─┘  └─┘ └─────┘ └─────┘ └──────┘     └─────┘ └─────┘ └─────┘ └──────┘
</pre>

<!--lint enable remark-lint:awesome-badge-->

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

<!--lint enable remark-lint:awesome-badge-->

<!--lint disable double-link-->

This is a curated list of slash-commands, `CLAUDE.md` files, CLI tools, and other resources and guides for enhancing your [Claude Code](https://docs.anthropic.com/en/docs/claude-code) workflow, productivity, and vibes.

<!--lint enable double-link-->

Claude Code is a cutting-edge CLI-based coding assistant and agent that you can access in your terminal or IDE. It is a rapidly evolving tool that offers a number of powerful capabilities, and allows for a lot of configuration, in a lot of different ways. Users are actively working out best practices and workflows. It is the hope that this repo will help the community share knowledge and understand how to get the most out of Claude Code.

### Announcements

- 2025-07-04: Added new section for Claude Code _hooks_!
- 2025-07-04: The new contribution system/CI/CD is under repair, if you want to submit something just put together a clear and tidy PR, if the CI messes things up a bit, I'll take care of it for now, should be back up and running by end of week.

<br>

## Contents

▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Documentation, Knowledge & Learning](#documentation-knowledge--learning)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Obsidian](#obsidian)  
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Research & Scientific Inquiry](#research--scientific-inquiry)  
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Providers, Runtime & Integration Infrastructure](#providers-runtime--integration-infrastructure)  
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Remote Control, Notifications & Voice I/O](#remote-control-notifications--voice-i/o)  
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Alternative Clients](#alternative-clients)  
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Status Lines](#status-lines)  
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Design & UI/UX](#design--ui/ux)  
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Writing & Prose Quality](#writing--prose-quality)  
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Creative Media](#creative-media)  
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Infrastructure & DevOps](#infrastructure--devops)  
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Security](#security)  
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Agent Orchestration](#agent-orchestration)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Ralph Wiggum](#ralph-wiggum)  
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Memory & Context Persistence](#memory--context-persistence)  
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Observability & Monitoring](#observability--monitoring)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Usage & Cost](#usage--cost)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Observability](#observability)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Session Monitors](#session-monitors)  
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Linting](#linting)  
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[From Anthropic](#from-anthropic)  
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Start Here](#start-here)  
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Skills](#skills)  

<br>

## Documentation, Knowledge & Learning

[`cxpak`](https://github.com/Barnett-Studios/cxpak) by [Barnett Studios](https://github.com/Barnett-Studios)  
A code-intelligence Claude Code plugin and MCP server (Rust, single binary, 43 languages) that builds a typed dependency graph and packs token-budgeted, annotated context bundles for any task. Exceptionally engineered and security-forward — 2,400+ tests, recorded ADRs, a sandboxed WASM plugin SDK, and cosign-signed, SBOM-attested release images.

[`NotebookLM MCP`](https://github.com/roomi-fields/notebooklm-mcp) by [Romain Peyrichou](https://github.com/roomi-fields)  
A mature MCP server (plus a 33-endpoint REST API) that drives Google NotebookLM for citation-backed Q&A and full Studio generation (audio, video, infographics, reports), with multi-account TOTP re-auth. Notably well-maintained and security-attentive — batch-tested on overnight 1,000-question runs, with a documented changelog that includes patching a transitive XSS advisory.

[`showreel`](https://github.com/HeyRenan/showreel) by [HeyRenan](https://github.com/HeyRenan)  
A Claude Code plugin that turns CSS selectors + text into finished visual documentation — annotated screenshots, flow GIFs/MP4s, terminal recordings, and before/after composites — placing every annotation deterministically and pixel-verifying each artifact (PASS/FAIL) before it is saved. Self-contained (bundles its own headless Chromium, no browser MCP, no telemetry); every image in its README is generated by the tool itself.

[`RAG Learning Academy`](https://github.com/TakaGoto/rag-learning-academy) by [Taka Goto](https://github.com/TakaGoto)  
A multi-agent Claude Code learning environment for mastering Retrieval-Augmented Generation, with 20 specialist agents, 22 slash commands, and a 9-module hands-on curriculum that runs zero-config inside Claude Code. Quality is evident — 616 tests, CI, and weekly/monthly content-freshness automation that opens issues for stale material.

[`claude-code-android`](https://github.com/ferrumclaudepilgrim/claude-code-android) by [ferrumclaudepilgrim](https://github.com/ferrumclaudepilgrim)  
A thorough, device-tested guide and toolkit for running Claude Code natively on Android via three paths (Termux, proot-Ubuntu, and the Android Virtualization Framework), with a verification harness and per-device results. Unusually security-aware for a setup guide — it ships a threat model, an SSRF-guard WebFetch hook, a biometric approval gate, and a permission matrix.

[`Bloom`](https://github.com/Li-Evan/Bloom) by [Li-Evan](https://github.com/Li-Evan)  
A self-contained Claude Code skill that turns Benjamin Bloom's "2-sigma" tutoring research into a personal AI tutor: it generates a structured syllabus, teaches one lesson at a time, and adapts each next lesson to the learner's annotations and feedback. The skill is dependency-free and makes no network calls beyond the configured LLM endpoint (an optional web app is also included).

[`MDXG Redline`](https://github.com/oubakiou/mdxg-redline) by [oubakiou](https://github.com/oubakiou)  
A Claude Code skill plus single-file HTML tool that closes the human-review loop on AI-written docs: a person leaves inline comments in the browser, which export as structured JSON keyed by heading path and line, and the skill polls for that file and applies each comment to the exact lines. Strongly privacy-respecting — the local/CLI build enforces a strict CSP (`connect-src 'none'`), so document text and comments never leave the machine.

[`cc-thinking-skills`](https://github.com/tjboudreaux/cc-thinking-skills) by [tjboudreaux](https://github.com/tjboudreaux)  
A collection of installable thinking-framework skills with a meta-router, notable for publishing a replication-gated evaluation instead of unsupported quality claims.

[`Dive into Claude Code`](https://github.com/VILA-Lab/Dive-into-Claude-Code) by [VILA-Lab](https://github.com/VILA-Lab)  
A research-lab systematic analysis of the Claude Code codebase whose headline finding — overwhelmingly infrastructure rather than model — reframes Claude Code as a harness.

[`claude-code-docs`](https://github.com/costiash/claude-code-docs) by [Constantin Shafranski](https://github.com/costiash)  
A mirror of the Anthropic&copy; PBC documentation site for Claude/Code, but with bonus features like full-text search and query-time updates - up-to-the-minute, fully-indexed information so that Claude Code can read about itself.

[`Agentic Workflow Patterns`](https://github.com/ThibautMelen/agentic-workflow-patterns) by [ThibautMelen](https://github.com/ThibautMelen)  
A comprehensive and well-documented collection of agentic patterns from Anthropic docs, with colorful Mermaid diagrams and code examples for each pattern. Covers Subagent Orchestration, Progressive Skills, Parallel Tool Calling, Master-Clone Architecture, Wizard Workflows, and more. Also compatible with other providers.

[`Claude Code Handbook`](https://nikiforovall.blog/claude-code-rules/) by [nikiforovall](https://github.com/nikiforovall)  
Collection of best practices, tips, and techniques for Claude Code development workflows, enhanced with distributable plugins

[`Claude Code Repos Index`](https://github.com/danielrosehill/Claude-Code-Repos-Index) by [Daniel Rosehill](https://github.com/danielrosehill)  
This is either the work of a prolific genius, or a very clever bot (or both), although it hardly matters because the quality is so good - an index of 75+ Claude Code repositories published by the author - and I'm not talking about slop. CMS, system design, deep research, IoT, agentic workflows, server management, personal health... If you spot the lie, let me know, otherwise please check these out.

[`Claude Code System Prompts`](https://github.com/Piebald-AI/claude-code-system-prompts) by [Piebald AI](https://github.com/Piebald-AI)  
All parts of Claude Code's system prompt, including builtin tool descriptions, sub agent prompts (Plan/Explore/Task), utility prompts (CLAUDE.md, compact, Bash cmd, security review, agent creation, etc.). Updated for each Claude Code version.

[`Encyclopedia of Agentic Coding Patterns`](https://aipatternbook.com) by [Wolf McNally](https://github.com/wolfmcnally)  
A freely available reference covering 190+ patterns for AI-assisted software development (and actually a whole bunch of related technical topics) from foundational concepts through agentic construction patterns, governance, testing, and socio-technical systems. Each entry follows a consistent pattern-language format with Context, Problem, Forces, Solution, Consequences, and Related Patterns. Opinionated and erudiate, which is actually good for an "encyclopedia" in some ways.

[`learn-faster-kit`](https://github.com/cheukyin175/learn-faster-kit) by [Hugo Lau](https://github.com/cheukyin175)  
A creative educational framework for Claude Code, inspired by the "FASTER" approach to self-teaching. Ships with a variety of agents, slash commands, and tools that enable Claude Code to help you progress at your own pace, employing well-established pedagogical techniques like active learning and spaced repetition.

### Obsidian

[`Librarian`](https://github.com/ngmeyer/librarian-mcp) by [ngmeyer](https://github.com/ngmeyer)  
A standalone MCP server that gives Claude a markdown second-brain over any Obsidian vault or folder of `.md` files, with trigram search, auto-wikilinks on write, and real graph analytics (Louvain communities, PageRank, shortest-path, D3 visualization). Runs entirely locally with no network calls or telemetry, productionizing the "LLM wiki" pattern.

[`Bedrock`](https://github.com/iurykrieger/claude-bedrock) by [Iury Krieger](https://github.com/iurykrieger)  
A Claude Code plugin that turns an Obsidian vault into a structured second brain via 8 skills, building an entity-typed (actors/people/teams/topics…) Zettelkasten graph with bidirectional wikilinks and ingesting Confluence, Google Docs, GitHub, and docling-supported files. Operates only on local markdown, with conscientious, opt-out error reporting that explicitly never transmits vault content or paths.

[`agentcairn`](https://github.com/ccf/agentcairn) by [ccf](https://github.com/ccf)  
Long-term, cross-project memory for AI coding agents. Your own Obsidian vault as the source of truth. Daemonless and without opaque databases, your memory belongs to you.

[`claude-obsidian`](https://github.com/AgriciDaniel/claude-obsidian) by [Agrici Daniel](https://github.com/AgriciDaniel)  
Self-organizing AI second brain for Obsidian + Claude Code. Claude reads any source, links it, and files it into one connected knowledge graph of plain Markdown. Based on Karpathy's LLM Wiki pattern.

<br>

## Research & Scientific Inquiry

[`AI Research Skills`](https://github.com/WenyuChiou/ai-research-skills) by [Wenyu Chiou](https://github.com/WenyuChiou)  
A catalog of 15 Claude Code skills mapped to 8 research-workflow stages (literature → gap analysis → design → drafting → reviewer response), where each stage emits an explicit YAML/Markdown deliverable the next stage consumes. Thoughtfully designed around anti-hallucination — schemas force "gap" status on unsupported claims, and downstream skills refuse malformed, overconfident handoffs.

[`My Claude Code Setup`](https://github.com/pedrohcgs/claude-code-my-workflow) by [Pedro H. C. Sant'Anna](https://github.com/pedrohcgs)  
A ready-to-fork Claude Code template for academics using LaTeX/Beamer + R. Multi-agent review, quality gates, adversarial QA, and replication protocols. Great use of orchestration patterns and great documentation.

<br>

## Providers, Runtime & Integration Infrastructure

[`llm-router`](https://github.com/ypollak2/llm-router) by [Yali Pollak](https://github.com/ypollak2)  
A local-first router that sits under Claude Code (and Codex/Gemini CLI) and sends each prompt to the cheapest capable model, with three-layer token compression and automatic provider fallback — protecting your premium quota and cutting cost with zero config on a Claude subscription. Credibly engineered: 1,900+ tests, an independent RouterArena benchmark placement, and an honest local-only design with no hosted proxy.

[`OpenWeb`](https://github.com/openweb-org/openweb) by [openweb-org](https://github.com/openweb-org)  
An agent-native skill that accesses 90+ websites by calling their underlying APIs directly (typed JSON in, JSON out) instead of screenshotting and parsing the DOM, with auth auto-resolved locally from your existing browser session. Security is first-class — every operation is tagged read/write/delete/transact behind permission tiers, SSRF protection runs on each request, and there is no vendor backend or proxy in the request path.

[`chrome-cdp-ex`](https://github.com/EndeavorYen/chrome-cdp-ex) by [Endeavor Yen](https://github.com/EndeavorYen)  
A zero-dependency Claude Code skill (68 commands) that connects to your *real* Chrome — logged-in tabs, cookies, live page state — to give the agent a perception layer: layout, visible styles, per-action "what changed" evidence, CSS-cascade-to-source tracing, and session replay/Playwright export. Notably rigorous about its own claims, with a dogfood benchmark gate that blocks performance/adoption assertions unless it passes.

[`SPARDA`](https://github.com/zyx77550/sparda) by [Zakaria Gharzouli (Residual Labs)](https://github.com/zyx77550)  
Converts a running Express or FastAPI app into an MCP server by AST-parsing its routes and injecting a marked, byte-for-byte-removable `/mcp` router, so the agent can operate your live application (real auth, real data) rather than just read files. Exceptionally safety-minded: writes are disabled by default behind two-phase confirmation, docstrings are sanitized against prompt injection, a circuit-breaker quarantines failing routes, nothing leaves the machine, and persistence stores structure never payloads.

[`Flue`](https://github.com/SFKislev/Flue) by [S.F. Kislev](https://github.com/SFKislev)  
A tiny bridge that lets Claude Code drive desktop software — Photoshop, Premiere, Blender, Unity, InDesign, Office, 13 apps total — by writing one-time scripts against each app's own automation runtime (COM / AppleScript / CEP), instead of MCP servers or fragile screenshot-based computer use. A genuinely novel approach that unlocks the apps' full scripting surfaces (InDesign alone exposes ~28k objects) with low maintenance.

[`claude-code-wsl2-setup`](https://github.com/congmnguyen/claude-code-wsl2-setup) by [congmnguyen](https://github.com/congmnguyen)  
A focused collection of documented scripts that fix the most painful Claude Code papercuts on WSL2 + Windows Terminal — clipboard screenshot paste via a Go daemon, Windows notifications on Stop/PermissionRequest hooks, LSP wiring, a usage-aware status line, and voice-mode audio routing. Each fix is written up with root cause and exact config (including non-obvious traps like SessionEnd firing per subagent), and the work was upstreamed into Awesome-WSL.

<br>

## Remote Control, Notifications & Voice I/O

[`Claude Threads`](https://github.com/anneschuth/claude-threads) by [Anne Schuth](https://github.com/anneschuth)  
Streams a locally-running Claude Code session live into a Slack or Mattermost thread so a whole team can watch, type, and approve actions together — "screen-sharing for AI pair programming, but everyone can type." Mature and well-maintained (npm-published with CI and coverage), with reaction-based tool approvals, git-worktree isolation, multi-account rotation, and per-thread sessions that survive restarts.

[`ai-agent-notifier`](https://github.com/DevinoSolutions/ai-agent-notifier) by [Amin Dhouib (Devino Solutions)](https://github.com/DevinoSolutions)  
A zero-dependency, cross-platform notifier that fires a desktop toast and a free phone push (via ntfy) the moment Claude Code (or Codex/Cursor/Gemini) finishes a task or needs input, wired up by a one-command setup. The standout among notifiers is its testing rigor — CI drives the *real* agent CLIs end to end and asserts real ntfy round-trips and real OS toast delivery, no mocks.

[`Telegram-Claude (tg-claude)`](https://github.com/Imolatte/tg-claude) by [Imolatte](https://github.com/Imolatte)  
A feature-rich Telegram bot that turns your machine into a remote Claude Code terminal driven from your phone: streaming tool progress, voice input, a git panel, Mac remote control, and 30+ commands. Its standout is the approval flow — dangerous-op Approve/Deny taps are injected straight into the real terminal prompt via `tmux send-keys`, so you authorize from your phone without killing the session or losing context.

[`dictate`](https://github.com/vimalk78/dictate) by [Vimal Kumar](https://github.com/vimalk78)  
Local, offline voice-to-text for Claude Code on Linux built on faster-whisper, with a warm daemon for instant transcription, system-wide push-to-talk, a voice-enabled editor, and per-project vocabulary hints that fix technical terms ("Claude" not "cloud"). Fully private — no cloud, no API keys, with thoughtful touches like mic-health monitoring and the ability to offload transcription to a LAN GPU; hardware-tested down to a Jetson Orin.

[`Lockpaw`](https://github.com/sorkila/lockpaw) by [Erik Nielsen](https://github.com/sorkila)  
A native-Swift macOS menu-bar app (10 MB, no Electron) that covers and input-locks your screen with one hotkey while your agents keep running, then makes the locked screen glow when Claude Code pauses for permission or finishes. Polished and well-engineered — CI with 50 tests, signed/notarized builds, an honest "visual privacy tool, not a security boundary" disclosure, no analytics, and an idempotent hook installer that backs up and never clobbers foreign hooks.

[`WhatsApp Channel Plugin`](https://github.com/Rich627/whatsapp-claude-plugin) by [Richie Liu](https://github.com/Rich627)  
Connects WhatsApp as a native Claude Code channel via Baileys linked-device (no bot token or API keys), with bidirectional messaging, full media, voice transcription, remote tool approval, access control, and per-group personalities. Runs entirely locally and was the first community plugin officially reviewed and published on Anthropic's plugin marketplace.

<br>

## Alternative Clients

[`CloudCLI (Claude Code UI)`](https://github.com/siteboon/claudecodeui) by [siteboon](https://github.com/siteboon)  
A web and mobile PWA for driving Claude Code (and Cursor/Codex/Gemini) from any device — file explorer, git, integrated shell, and full session management that reads and writes your real `~/.claude` config rather than duplicating it. By far the most-adopted Claude Code UI, with a self-hostable open-source core, an optional Docker microVM sandbox mode, a plugin ecosystem, and tools disabled by default for safety.

[`Cate`](https://github.com/0-AI-UG/cate) by [0-AI UG](https://github.com/0-AI-UG)  
A cross-platform desktop IDE built on an infinite zoomable canvas, where editors, terminals, browsers, and docs float in freeform space instead of tabs — and ships skills that let Claude Code spawn agent terminals on the canvas, coordinate through canvas notes, and drive browser panels. A genuinely novel UX, well-engineered (CI, e2e tests, context-isolated IPC, scoped filesystem access) and widely adopted.

[`Vibeyard`](https://github.com/elirantutia/vibeyard) by [Eliran Tutia](https://github.com/elirantutia)  
A cross-platform desktop IDE that wraps Claude Code sessions with a swarm mode (parallel agents in a grid), a real-time session inspector (cost, tokens, tool-usage, context), multiple isolated Claude profiles, a kanban board, and encrypted P2P session sharing over WebRTC. Signed/notarized, broadly adopted, and built squarely for the multi-agent, multi-session workflow.

[`Nimbalyst`](https://github.com/nimbalyst/nimbalyst) by [Greg Hinkle](https://github.com/nimbalyst)  
A visual workspace for building with Claude Code (and Codex) where you and the agent co-edit *visually* — markdown, mockups, mermaid, Excalidraw, CSV, and data models — approving the agent's changes as red/green WYSIWYG diffs, with session/task kanban, worktrees, an extension SDK, and a native iOS companion app. A distinctive higher-bandwidth take on agent collaboration, open source with transparent, opt-out telemetry.

[`FlyCrys`](https://github.com/SergKam/FlyCrys) by [Sergii Kamenskyi](https://github.com/SergKam)  
A native Linux GUI for Claude Code agents built in Rust + GTK4 — single binary, no Electron, starts in under a second — with a file tree, syntax-highlighted viewer, markdown preview, embedded VTE4 terminal, streaming agent chat, workspace tabs, and tool-restricted agent profiles. Fills a real gap as essentially the only native (non-webview) Linux desktop client, using your own Claude Code CLI with no proxy.

[`Sidekick for Max`](https://github.com/cesarandreslopez/sidekick-for-claude-max) by [César Andrés López](https://github.com/cesarandreslopez)  
A VS Code extension and standalone terminal dashboard that adds visibility and AI conveniences on top of your Claude Max subscription — inline completions, code transforms, AI commit messages, plus deep session observability (token-burn, a 13-week quota heatmap, multi-account management, cross-session search, and asset extraction). Mature and well-maintained (CI, published to the marketplace and npm, extensive docs).

[`Claude Overlay`](https://github.com/shengyanlin/claude-overlay) by [shengyanlin](https://github.com/shengyanlin)  
A frameless, always-on-top floating chat window for Claude Code on Windows. It captures every monitor and lets Claude read the screen to answer questions in context, and drives the user's existing claude CLI login through the Agent SDK, with image paste, model switching, live streaming, and a context-usage statusline.

<br>

## Status Lines

[`claude-statusbar`](https://github.com/leeguooooo/claude-code-usage-bar) by [leeguooooo](https://github.com/leeguooooo)  
The most complete Claude Code status line: 5-hour and 7-day rate-limit usage with reset countdowns and *learned* end-of-window projections, context window, prompt-cache-expiry countdown, per-session cost, plus live todo/tool/git activity — across 3 styles and 9 themes, configurable by CLI or natural-language skill. Genuinely well-engineered (PyPI, 320+ tests, a sub-1%-CPU daemon, deep docs) and the clear standout of a very crowded field.

[`claude-code-personalities`](https://github.com/kumamaki/Claude-Code-Personalities) by [kumamaki](https://github.com/kumamaki)  
A delightfully different status line: 30+ kaomoji text-faces that react in real time to what Claude is doing — context-aware personas by file type, and a frustration-escalation system where mounting errors progress from `( ദ്ദി ˙ᗜ˙ )` toward a table-flip `(╯°□°)╯︵ ┻━┻`. Pure Rust with sub-2ms rendering, a single binary, hook-based activity tracking, and an interactive config TUI — the standout creative pick in a sea of metrics bars.

[`claudinho`](https://github.com/arturogarrido/claudinho) by [Arturo Garrido](https://github.com/arturogarrido)  
2026 World Cup live scores in your terminal, Claude Code statusline & MCP. No API keys.

<br>

## Design & UI/UX

[`Dev Browser`](https://github.com/SawyerHood/dev-browser) by [Sawyer Hood](https://github.com/SawyerHood)  
A browser-automation plugin/skill that lets Claude Code drive a browser to test and verify its own work — full Playwright API plus pixel- and DOM-level computer-use toolsets, connecting to your running Chrome or a fresh Chromium. Notably secure and fast: scripts execute inside a QuickJS WASM sandbox with no host filesystem or network access, and a published benchmark shows it beating Playwright MCP on time, cost, and turns.

[`StyleSeed`](https://github.com/bitjaru/styleseed) by [kiwiman](https://github.com/bitjaru)  
A design engine that takes a different tack from "feed the model more tokens": it teaches design *judgment* — ~74 rules pros carry but never write down ("the refined black isn't #000, it's #2A2A2A"; "one accent color, everything else grayscale") — as plain markdown the agent reads automatically, plus a brand-agnostic skin system, a named motion vocabulary, and `/ss-*` review skills. Widely adopted and demonstrably effective (a live demo morphs one UI across Toss/Raycast/Arc via a single attribute).

[`UI Craft`](https://github.com/educlopez/ui-craft) by [Eduardo Calvo](https://github.com/educlopez)  
A deep design-engineering skill that makes agents "design like they have taste" by default, layered so you can just install it, drive it with 22 single-lens commands, or wire its deterministic MCP gates and CLI into CI. Its signature is a *scoreable, defensible* critique — Nielsen's heuristics × classic design laws × persona walkthroughs, every finding tagged by business impact — backed by anti-slop rules, outcome recipes, accessibility-first review, and 31 domain references.

[`Snip`](https://github.com/rixinhahaha/snip) by [rixinhahaha](https://github.com/rixinhahaha)  
A visual whiteboard between you and your agent: Claude renders diagrams, HTML, or UI components through Snip instead of describing them in text, you approve or annotate directly on the output (circle, arrow, note), and the agent gets structured feedback and iterates. Works via CLI or MCP, doubles as a full local screenshot/annotation app with on-device AI organization (Ollama), and adds a genuine human-in-the-loop visual review step to Claude Code.

[`visual-explainer`](https://github.com/nicobailon/visual-explainer) by [nicobailon](https://github.com/nicobailon)  
Agent skill and plugin that turns complex terminal output into styled HTML pages or slide decks for diagrams, diff reviews, plan audits, data tables, and project recaps. Generates self-contained browser-readable artifacts with Mermaid diagrams, responsive layouts, themes, and sharing commands.

<br>

## Writing & Prose Quality

[`Avoid AI Writing`](https://github.com/conorbronsdon/avoid-ai-writing) by [Conor Bronsdon](https://github.com/conorbronsdon)  
A portable writing skill that audits and rewrites prose to remove "AI-isms" — 49+ pattern categories and a tiered word-replacement vocabulary, with detect / rewrite / edit-in-place modes, content-type and voice profiles, and a two-pass re-check. Stands well above the crowded de-slop field: it ships a deterministic, zero-dependency detector engine (the single source of its 0–100 score) with CI tests, and frames itself honestly as a writing-quality tool, not a detector-evasion gimmick.

[`naming`](https://github.com/glacierphonk/naming) by [GlacierPhonk](https://github.com/glacierphonk)  
A Claude Code skill for naming products, SaaS tools, brands, and projects via a structured metaphor-driven process — naming brief, metaphor exploration, candidate generation, anti-slop filtering, a weighted evaluation rubric, and availability checks for domains/handles/package names. A genuinely different (and creative) take that produces names grounded in meaning instead of the random tech-syllable mush an unguided model reaches for.

<br>

## Creative Media

[`capcut-cli`](https://github.com/renezander030/capcut-cli) by [René Zander](https://github.com/renezander030)  
A zero-dependency Node CLI (and Claude Code plugin/skill) that lets the agent edit CapCut / JianYing video projects programmatically — inspect timelines, build drafts, add text/audio, word-level captions and Whisper transcription, templates, and cut long-form into shorts — JSON in, JSON out, no server. Deeply mature for a media tool: 205 tests across macOS/Windows/Linux CI, a huge documented command surface, and a deliberately stateless "the CLI is the protocol" design.

[`motion-skills`](https://github.com/iart-ai/motion-skills) by [iart.ai](https://github.com/iart-ai)  
An open-source collection of ~50 motion-graphics, animation, and video skills across 14 installable packs — kinetic typography, data-driven charts, explainers, TikTok/Reels, web/WebGL animation, and Manim math animation — that teach an agent how a professional would build each piece. Every visual skill ships a deliver-and-verify loop (render a frame → screenshot → check) plus a small verify toolkit, so the agent inspects its own output instead of guessing at timing and framing.

[`Vox director skill`](https://github.com/Alisa0808/vox-director) by [Alisa Qian](https://github.com/Alisa0808)  
Vox Director is an open-source skill that turns a one-line topic into a finished Vox-style paper-collage explainer or ad video. It automates the full pipeline — script, collage keyframes, motion, voice-over, music, and captions — on the Atlas Cloud API plus local ffmpeg, with two human approval gates for the beat map and visual style.

[`claude-replay`](https://github.com/es617/claude-replay) by [es617](https://github.com/es617)  
An outstanding, creative library that converts Claude Code session transcripts into self-contained, embeddable HTML replays - interactive playback with speed control, a local editor, collapsible tool-call and thinking blocks, redaction for private information - the output is fantastic. Also supports other providers.

<br>

## Infrastructure & DevOps

[`terraform-skill`](https://github.com/antonbabenko/terraform-skill) by [Anton Babenko](https://github.com/antonbabenko)  
A best-practices skill that teaches the agent to write safer Terraform and OpenTofu through a diagnose-first workflow, failure-mode routing, LLM-mistake checklists, and a feature-version guard table mapping features to their version floor and common errors — covering testing, modules, remote state, CI/CD, and security scanning across AWS/Azure/GCP. From an AWS Hero behind the terraform-aws-modules ecosystem, and the most authoritative, most-adopted IaC resource in the set.

[`otelcol-doctor`](https://github.com/s3onghyun/otelcol-doctor) by [s3onghyun](https://github.com/s3onghyun)  
A focused, vendor-neutral skill that writes, fixes, and *validates* OpenTelemetry Collector configs — encoding the Collector's real footguns (memory_limiter/batch ordering, core-vs-contrib components, pull-vs-push exporters, deprecated exporters, pipelines that validate but were never wired) as an authoring workflow and diagnosis checklist. Its standout is honesty plus a verification loop: it always finishes by running `otelcol validate` and ships CI-checked before/after example configs rather than handing back an unverified file.

<br>

## Security

[`SkillSpector`](https://github.com/NVIDIA/SkillSpector) by [NVIDIA](https://github.com/NVIDIA)  
Security scanner for AI agent skills. Detect vulnerabilities, malicious patterns, and security risks.

[`aicontainer`](https://github.com/stefanoginella/aicontainer) by [stefanoginella](https://github.com/stefanoginella)  
Sandboxed devcontainer for running Claude Code, Codex, and OpenCode in bypass / auto-approve mode.

[`Node9`](https://github.com/node9-ai/node9-proxy) by [node9-ai](https://github.com/node9-ai)  
The Execution Security Layer for the Agentic Era. Providing deterministic "Sudo" governance and audit logs for autonomous AI agents.

[`Claude Code Safety Net`](https://github.com/kenryu42/claude-code-safety-net) by [kenryu42](https://github.com/kenryu42)  
A coding agent CLI hook that acts as a safety net, catching destructive git and filesystem commands before they execute. Supports Codex, Claude Code, OpenCode, Gemini CLI, Copilot CLI, Kimi Code and Pi.

[`machine`](https://github.com/katspaugh/machine) by [katspaugh](https://github.com/katspaugh)  
One isolated Lima VM per GitHub project — sandboxed Claude Code/Codex, Docker, Node, signed git

[`SkilLock`](https://github.com/skills-lock/skil-lock) by [skills-lock](https://github.com/skills-lock)  
Pin AI Skill behavior. Block unapproved drift in CI. See exactly what changed in every PR.

[`Brood Box`](https://github.com/stacklok/brood-box) by [stacklok](https://github.com/stacklok)  
CLI tool for running coding agents inside hardware-isolated microVMs

[`Claude Code Safety Guard`](https://github.com/inoX-Network/claude-code-safety-guard) by [inoX-Network](https://github.com/inoX-Network)  
3-level override system for Claude Code - prevents destructive system operations. Born from a real incident.

[`Code on Incus`](https://github.com/mensfeld/code-on-incus) by [mensfeld](https://github.com/mensfeld)  
Give each AI agent its own isolated machine with root, Docker, and systemd. Active defense detects and stops threats automatically..

[`compass`](https://github.com/dshakes/compass) by [dshakes](https://github.com/dshakes)  
Developer-grade Claude Code + Codex configuration: cost-tiered subagents, workflow commands, guardrail hooks, MCP parity, and an installable plugin/marketplace.

[`Cleat`](https://github.com/cleatdev/cleat) by [cleatdev](https://github.com/cleatdev)  
Give the agent a cage, not your keys. One-command Docker sandbox for AI coding agents: full autonomous permissions, per-project isolation, your host stays untouched.

[`Agent Guard`](https://github.com/JeongJaeSoon/agent-guard) by [JeongJaeSoon](https://github.com/JeongJaeSoon)  
Real-time secret-leak guardrails for AI coding agents (Claude Code, Codex), Git hooks, and CI.

[`authsome`](https://github.com/agentrhq/authsome) by [agentrhq](https://github.com/agentrhq)  
Credential gateway for AI agents. Log in once via Oauth2 or API Key. Every agent stays authenticated — headless, no SaaS, agents never see your credentials.

[`Airut`](https://github.com/airutorg/airut) by [airutorg](https://github.com/airutorg)  
Airut is a system for running Claude Code tasks from email and Slack. It handles workspace provisioning, container isolation, network sandboxing, session persistence, and cleanup — a secure foundation for autonomous agentic development.

[`GouvernAI`](https://github.com/Myr-Aya/GouvernAI-claude-code-plugin) by [Myr-Aya](https://github.com/Myr-Aya)  
Runtime guardrails for Claude Code. Auto-approve what's safe, gate what's risky, block what's dangerous. Dual enforcement, full audit trail. MIT.

<br>

## Agent Orchestration

[`Agent Collab Skills`](https://github.com/WenyuChiou/agent-collab-skills) by [Wenyu Chiou](https://github.com/WenyuChiou)  
Claude Code marketplace for multi-agent collaboration — task splitter, output reconciler, adversarial debate, shared memory, acceptance gate. Composes with codex-delegate / gemini-delegate.

[`gstack`](https://github.com/garrytan/gstack) by [Garry Tan](https://github.com/garrytan)  
Garry Tan's (Y Combinator) Claude Code setup and "open source software factory" for managing the development lifecycle end-to-end. Includes a set of agents and in-depth skills/tools along with workflows for advancing a product from ideation to production.

[`Claude Code Harness`](https://github.com/Chachamaru127/claude-code-harness) by [Chachamaru](https://github.com/Chachamaru127)  
A Claude Code development harness that enables reliable high-quality development through an autonomous Plan -> Work -> Review cycle. Well documented and includes an Output Style.

[`AB Method`](https://github.com/ayoubben18/ab-method) by [Ayoub Bensalah](https://github.com/ayoubben18)  
A principled, spec-driven workflow that transforms large problems into focused, incremental missions using Claude Code's specialized sub agents. Includes slash-commands, sub agents, and specialized workflows designed for specific parts of the SDLC.

[`Harness`](https://github.com/revfactory/harness) by [revfactory](https://github.com/revfactory)  
A meta-skill that designs domain-specific agent teams, defines specialized agents, and generates the skills they use. Resources are in Korean but can produce high-quality English-language output.

[`Project Workflow System`](https://github.com/harperreed/dotfiles/tree/master/.claude/commands) by [harperreed](https://github.com/harperreed)  
A set of commands that provide a comprehensive workflow system for managing projects, including task management, code review, and deployment processes.

[`RIPER Workflow`](https://github.com/tony/claude-code-riper-5) by [Tony Narlock](https://tony.sh)  
Structured development workflow enforcing separation between Research, Innovate, Plan, Execute, and Review phases. Features consolidated subagents for context-efficiency, branch-aware memory bank, and strict mode enforcement for guided development.

### Ralph Wiggum

[`Ralph for Claude Code`](https://github.com/frankbria/ralph-claude-code) by [Frank Bria](https://github.com/frankbria)  
An autonomous AI development framework that enables Claude Code to work iteratively on projects until completion. Features intelligent exit detection, rate limiting, circuit breaker patterns, and comprehensive safety guardrails to prevent infinite loops and API overuse. Built with Bash, integrated with tmux for live monitoring, and includes 75+ comprehensive tests.

[`ralph-orchestrator`](https://github.com/mikeyobrien/ralph-orchestrator) by [mikeyobrien](https://github.com/mikeyobrien)  
Ralph Orchestrator implements the simple but effective "Ralph Wiggum" technique for autonomous task completion, continuously running an AI agent against a prompt file until the task is marked as complete or limits are reached. This implementation provides a robust, well-tested, and feature-complete orchestration system for AI-driven development. Also cited in the Anthropic Ralph plugin documentation.

[`Ralph Wiggum Plugin`](https://github.com/anthropics/claude-code/tree/main/plugins/ralph-wiggum) by [Anthropic PBC](https://github.com/anthropics)  
The official Anthropic implementation of the Ralph Wiggum technique for iterative, self-referential AI development loops in Claude Code.

<br>

## Memory & Context Persistence

[`Callimachus`](https://github.com/BetaBots-LLC/callimachus) by [BetaBots-LLC](https://github.com/BetaBots-LLC)  
One local, searchable index of your AI coding-agent history Claude Code, Codex, Cursor, Gemini & more. Keyword + semantic search, MCP server, CLI & VS Code extension.

[`MAMA`](https://github.com/jungjaehoon-lifegamez/MAMA) by [jungjaehoon-lifegamez](https://github.com/jungjaehoon-lifegamez)  
Always-on companion for Claude that remembers your decisions and their evolution. Local-first memory       using SQLite + transformers.js embeddings.

[`fable`](https://github.com/grooverLab/fable) by [grooverLab](https://github.com/grooverLab)  
High-fidelity transcript memory for Claude Code — index every session, recall byte-identical, search, prune, compose. Local-first, stdlib-only, MCP.

[`presence`](https://github.com/sara-star-quant/presence) by [sara-star-quant](https://github.com/sara-star-quant)  
Per-repo memory, outcome telemetry, and a calibrated-confidence gate for Claude Code, with MCP and AGENTS.md projections so other AI coding tools can read its context. Notes survive sessions; success claims need test evidence; your reverts are remembered. Local-only, stdlib runtime.

[`roampal-core`](https://github.com/roampal-ai/roampal-core) by [roampal-ai](https://github.com/roampal-ai)  
Outcome-based persistent memory MCP server for Claude Code and OpenCode. Good advice promoted, bad advice demoted. pip install roampal.

[`Hivemind`](https://github.com/activeloopai/hivemind) by [activeloopai](https://github.com/activeloopai)  
Hivemind turns your traces into reusable skills across agents

[`Claude Mnemonic`](https://github.com/lukaszraczylo/claude-mnemonic) by [lukaszraczylo](https://github.com/lukaszraczylo)  
Memory management and retrieval for Claude Code

[`capy`](https://github.com/serpro69/capy) by [serpro69](https://github.com/serpro69)  
🦫 Privacy-first virtualization layer for LLM context with MCP protocol for tool access.

[`Selvedge`](https://github.com/masondelan/selvedge) by [masondelan](https://github.com/masondelan)  
Long-term memory for AI-coded codebases. A git blame for AI agents — but for the why. MCP server that captures the agent's reasoning live, in context, as each change is made. Local SQLite, zero deps.

[`claude-context-optimizer`](https://github.com/egorfedorov/claude-context-optimizer) by [Egor Fedorov](https://github.com/egorfedorov)  
Claude Code plugin that tracks token usage, identifies wasted context, and saves money on unnecessary API costs, by tracking which information is actually being reused later. Visuals include heatmaps, ROI reports, budget alerts, efficiency scores, git-aware suggestions - all local, zero config. The design is still somewhat exploratory, but it shows promise.

<br>

## Observability & Monitoring

### Usage & Cost

[`Claumon`](https://github.com/fabioconcina/claumon) by [fabioconcina](https://github.com/fabioconcina)  
Claude Code dashboard for Pro/Max users: live rate-limit gauges, calibrated usage forecasts, session costs, memory browser. Single binary, zero config.

[`ccvitals`](https://github.com/educlopez/ccvitals) by [educlopez](https://github.com/educlopez)  
The prettiest statusline for Claude Code — pure bash, never blocks your prompt. Usage quota, context window, git status & more.

[`toktrack`](https://github.com/mag123c/toktrack) by [mag123c](https://github.com/mag123c)  
Ultra-fast token & cost tracker for LLM Token Usage (e.g. Claude Code)

[`cc-probeline`](https://github.com/labzink/cc-probeline) by [labzink](https://github.com/labzink)  
See where it leaks, stop paying for it — a live Claude Code status line that prices every turn, your subagents, cache rebuilds, plus limits, context and git.

[`claude-code-status-bar`](https://github.com/briansmith80/claude-code-status-bar) by [briansmith80](https://github.com/briansmith80)  
Configurable status bar for Claude Code: usage limits with pacing markers, context window, git state, live activity, session cost, and 8 colour themes. Pure bash, zero dependencies.

[`cc-costline`](https://github.com/Ventuss-OvO/cc-costline) by [Ventuss-OvO](https://github.com/Ventuss-OvO)  
Enhanced statusline for Claude Code — see your 7d/30d spend at a glance

[`CCDash`](https://github.com/zihenghe04/CCDash) by [zihenghe04](https://github.com/zihenghe04)  
Open-source unified usage dashboard for Claude — track tokens, quota, costs across Claude Code, claude.ai & API in one panel. 开源 Claude 全平台用量监控面板，聚合 Claude Code / claude.ai / API 数据，适用于 Pro/Max 订阅用户与开发者。https://dyp23yngrtumg.ok.kimi.link

[`Pacer`](https://github.com/EricAndrechek/Pacer) by [EricAndrechek](https://github.com/EricAndrechek)  
Native macOS app for tracking Claude Code usage — tokens, cost, rate-limit pacing, per-project breakdowns. SwiftUI + SwiftData.

[`AgentWatch`](https://github.com/mishanefedov/agentwatch) by [mishanefedov](https://github.com/mishanefedov)  
Local-only observability for AI agents on your machine. One timeline across coding and non-coding agents.

[`goccc`](https://github.com/backstabslash/goccc) by [backstabslash](https://github.com/backstabslash)  
Fast, zero-dependency cost calculator and customizable statusline for Claude Code. Breakdowns by model, day, project, and branch. Lightweight, single binary, no runtime needed.

[`ClaudeBar`](https://github.com/tddworks/ClaudeBar) by [tddworks](https://github.com/tddworks)  
A macOS menu-bar app that surfaces remaining usage quota for Claude, Codex, Gemini, Copilot, and other AI coding providers at a glance, with burn-rate, dollar-balance, and reset-countdown indicators plus a lightweight live-session indicator. Swift 6 with a layered Domain/Infrastructure architecture.

[`ccusage`](https://github.com/ccusage/ccusage) by [ryoppippi](https://github.com/ryoppippi)  
A zero-install CLI (npx ccusage) that analyzes Claude Code token usage and cost from local JSONL logs — daily, monthly, per-session, and 5-hour-block breakdowns, a live monitoring mode, and per-model cost estimates. Runs entirely locally, with JSON output for scripting.

### Observability

[`Multi-Agent Observability`](https://github.com/disler/claude-code-hooks-multi-agent-observability) by [disler](https://github.com/disler)  
A real-time dashboard that captures Claude Code hook events across concurrent agents — tracing every tool call, task handoff, and lifecycle event through a Bun/SQLite/WebSocket/Vue stack, with session tracking and live filtering.

[`Claude Code Observability Stack`](https://github.com/ColeMurray/claude-code-otel) by [Cole Murray](https://github.com/ColeMurray)  
A Dockerized OpenTelemetry-to-Grafana observability stack for Claude Code that implements Anthropic's observability guidance, surfacing session activity, performance, token usage, and cost in prebuilt dashboards.

[`agents-observe`](https://github.com/simple10/agents-observe) by [Joe Johnston](https://github.com/simple10)  
A real-time Claude Code observability dashboard installed as a plugin: it registers hooks across the full session lifecycle (tool calls, subagent start/stop, task and permission events) and streams them to a local React UI backed by a Dockerized SQLite server, with filtering, parent/subagent hierarchy, full session replay, and per-model token stats.

### Session Monitors

[`Claude Code Agent Monitor`](https://github.com/hoangsonww/Claude-Code-Agent-Monitor) by [hoangsonww](https://github.com/hoangsonww)  
A self-hosted real-time dashboard that monitors Claude Code agent activity via its native hooks — live sessions, subagent orchestration trees, tool-call timelines, and per-session status — keeping data local (loopback-only). Built on Node/Express + React + SQLite, with a companion MCP server, VS Code extension, and desktop app.

[`c9watch`](https://github.com/minchenlee/c9watch) by [minchenlee](https://github.com/minchenlee)  
A macOS menu-bar app (and companion JSON CLI, built from one Rust/Tauri binary) that auto-discovers running Claude Code sessions by scanning OS processes and shows live working / needs-attention / idle status, plus session-history search, cost tracking, and PM-style worker orchestration. Rust + Tauri 2 + Svelte 5, with a token-gated mobile web client.

[`claude-status-bar`](https://github.com/m1ckc3s/claude-status-bar) by [mick](https://github.com/m1ckc3s)  
A tiny, hook-driven macOS menu-bar indicator of Claude Code's live turn status — an animated icon while thinking or running a tool, a dot when awaiting permission, and an elapsed-turn timer — aggregated across concurrent CLI, Claude Desktop, and Cursor sessions. Stateless AppKit/Swift app that self-launches on session start and quits when idle.

[`Claude Status`](https://github.com/gmr/claude-status) by [Gavin M. Roy](https://github.com/gmr)  
A native macOS menu-bar app with desktop widgets showing the live state of every running Claude Code session — active, waiting-for-input, compacting, or idle — across many terminals and IDEs, with one-click focus to any session's exact window, tab, or pane. SwiftUI + AppKit + WidgetKit, driven by a bundled hook plugin with process-tree and JSONL-tail fallbacks.

[`claude-control`](https://github.com/sverrirsig/claude-control) by [Sverrir Sigurdsson](https://github.com/sverrirsig)  
A native macOS Electron dashboard that auto-discovers running Claude Code CLI sessions and shows live per-session status, git changes, PR checks, and conversation previews across repos and worktrees — and can focus, send input to, approve or reject, kill, or spawn sessions from one place. Electron + Next.js + TypeScript, local-only, via an auto-installed status hook with process-table and JSONL-mtime fallbacks.

[`cctop`](https://github.com/stefanprodan/cctop) by [Stefan Prodan](https://github.com/stefanprodan)  
A live top-style terminal TUI that lists every running Claude Code session with process stats, busy/idle state, context size, model, and git branch, plus a live sub-agent and sub-process tree with open and orphaned ports — reading only the local process table and ~/.claude session and transcript files. Zero-dependency Bun; can signal a runaway session or free orphaned dev-server ports in place.

[`so-agentbar`](https://github.com/sotthang/so-agentbar) by [sotthang](https://github.com/sotthang)  
A native macOS menu-bar app that watches Claude Code and OpenAI Codex CLI session logs in real time and shows each running session's live status, tokens, and cost, with subagent grouping and an optional animated pixel-art view. Swift/SwiftUI + SpriteKit, using FSEvents with incremental JSONL parsing plus multi-provider quota tracking.

[`CC Harness`](https://github.com/lookfree/cc-harness) by [lookfree](https://github.com/lookfree)  
Desktop workbench that reads Claude Code session files locally and renders the subagent and workflow topology as a live graph, with per-node latency, token cost, and nesting depth. Token spend is broken down by source (base session, skills, subagents, MCP) and can be traced from a cost bucket to the exact message that produced it.

<br>

## Linting

[`agnix`](https://github.com/agent-sh/agnix) by [agent-sh](https://github.com/agent-sh)  
The linter and LSP for AI coding assistants — validates CLAUDE.md, AGENTS.md, SKILL.md, hooks, and MCP config, with autofixes and IDE plugins.

[`BlockWatch`](https://github.com/mennanov/blockwatch) by [mennanov](https://github.com/mennanov)  
A language-agnostic linter (Rust) that keeps co-dependent code, docs, and config in sync, with a Claude Code plugin skill.

[`Ctxlint`](https://github.com/ctxlint/Ctxlint) by [ctxlint](https://github.com/ctxlint)  
A CLI linter for AI agent context files that catches stale references, dead commands, and hardcoded secrets, with a modular tested rule set.

[`Schliff`](https://github.com/Zandereins/schliff) by [Zandereins](https://github.com/Zandereins)  
Deterministic quality scorer for AI agent instruction files — 8-dimension scoring with security, multi-format (SKILL.md, CLAUDE.md, .cursorrules, AGENTS.md), anti-gaming detection, zero dependencies

[`agents-md-cookbook`](https://github.com/Taiizor/agents-md-cookbook) by [Taiizor](https://github.com/Taiizor)  
The tested, tool-agnostic AGENTS.md kit — verified templates, a CI linter, and migrators from .cursorrules/CLAUDE.md/Copilot/Windsurf/Cline/Aider.

[`Upkeep`](https://github.com/wei18/Upkeep) by [wei18](https://github.com/wei18)  
Upkeep — an AI audit crew for your repo. Catches docs/spec/asset drift with evidence; output-only. Claude Code plugin/skill + reusable CI workflow.

<br>

## From Anthropic

[`Agent Skills`](https://github.com/anthropics/skills) by [Anthropic](https://github.com/anthropics)  
Anthropic's official repository for Agent Skills — the SKILL.md format, a skill template, and example skills, the same format Claude Code loads natively.

[`Official Plugin Directory`](https://github.com/anthropics/claude-plugins-official) by [Anthropic](https://github.com/anthropics)  
Anthropic's official, curated directory of high-quality Claude Code plugins, installable from within Claude Code.

[`Claude Code GitHub Action`](https://github.com/anthropics/claude-code-action) by [Anthropic](https://github.com/anthropics)  
The official GitHub Action for running Claude Code in CI: mention @claude in issues and pull requests to delegate code changes, reviews, and fixes.

[`Claude Code Security Review`](https://github.com/anthropics/claude-code-security-review) by [Anthropic](https://github.com/anthropics)  
An official AI-powered security-review GitHub Action that uses Claude to analyze pull-request diffs for vulnerabilities.

[`Claude Code Best Practices`](https://code.claude.com/docs/en/best-practices) by [Anthropic](https://code.claude.com/docs)  
Anthropic's canonical guide to working effectively with Claude Code: the agentic-loop mental model, CLAUDE.md guidance, and workflow patterns.

[`How Claude Code Works`](https://code.claude.com/docs/en/how-claude-code-works) by [Anthropic](https://code.claude.com/docs)  
The official conceptual explainer of Claude Code's agentic loop, tools, and context window, and how skills, hooks, and subagents layer on top.

[`Steering Claude Code: Skills, Hooks, Rules, Subagents and More`](https://claude.com/blog/steering-claude-code-skills-hooks-rules-subagents-and-more) by [Anthropic](https://claude.com/blog)  
A framework for choosing which extension mechanism to reach for, organized around deterministic-versus-probabilistic control and context isolation.

[`Building Effective Agents`](https://www.anthropic.com/research/building-effective-agents) by [Anthropic](https://www.anthropic.com)  
Anthropic's foundational taxonomy of agent patterns — prompt chaining, routing, orchestrator-workers, and evaluator-optimizer — and when to use each.

[`How We Built Our Multi-Agent Research System`](https://www.anthropic.com/engineering/multi-agent-research-system) by [Anthropic](https://www.anthropic.com)  
A practical account of orchestrator and subagent coordination, prompt design, and evaluation that maps directly to Claude Code's subagents and agent teams.

[`Effective Context Engineering for AI Agents`](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents) by [Anthropic](https://www.anthropic.com)  
Anthropic's guide to curating the context window — compaction, just-in-time retrieval, and note-taking — the discipline underlying effective long-horizon agent use.

[`Claude Code Cheatsheet`](https://support.claude.com/en/articles/14553413-claude-code-cheatsheet) by [Anthropic](https://support.claude.com)  
Anthropic's official Claude Code cheatsheet — a quick reference for the core vocabulary (session, context window, CLAUDE.md), built-in slash commands, and keyboard shortcuts.

<br>

## Start Here

[`Claude Code Guide`](https://github.com/zebbern/claude-code-guide) by [zebbern](https://github.com/zebbern)  
A current single-page reference for Claude Code: install, environment variables, slash commands, MCP, hooks, and subagents, kept in sync with the official changelog.

[`Claude Code Hooks: Complete Guide`](https://hidekazu-konishi.com/entry/claude_code_hooks_complete_guide.html) by [Hidekazu Konishi](https://hidekazu-konishi.com)  
A thorough walkthrough of every hook event, when each fires, the two return channels, common anti-patterns, and copy-ready settings.json examples.

[`Writing a Good CLAUDE.md`](https://www.humanlayer.dev/blog/writing-a-good-claude-md) by [HumanLayer](https://www.humanlayer.dev)  
An essay on CLAUDE.md craft: instruction-budget reasoning, progressive disclosure, and the test of whether Claude would err without a given line.

[`claude-howto`](https://github.com/luongnv89/claude-howto) by [luongnv89](https://github.com/luongnv89)  
A structured, chapter-based getting-started guide for Claude Code with a self-assessment quiz and a ten-module progressive learning path — slash commands, memory, skills, subagents, MCP, hooks, plugins, and checkpoints — with visual diagrams and copy-paste templates.

[`Claude Code: Everything You Need to Know`](https://github.com/wesammustafa/Claude-Code-Everything-You-Need-to-Know) by [wesammustafa](https://github.com/wesammustafa)  
A conceptual, mental-models-first primer that explains what Claude Code is and how its agentic loop works, then layers setup, prompt-engineering workflows, skills, hooks, MCP, subagents, and agent teams, with an experience-tiered path for newcomers.

[`explore-claude-code`](https://github.com/LukeRenton/explore-claude-code) by [Luke Renton](https://github.com/LukeRenton)  
An interactive click-through of an annotated Claude Code project where every file and folder — CLAUDE.md, settings.json, rules, commands, skills, agents, hooks, plugins, and .mcp.json — is a real, explained concept, teaching the tool's surface area by orientation rather than prose.

[`andrej-karpathy-skills`](https://github.com/multica-ai/andrej-karpathy-skills) by [multica-ai](https://github.com/multica-ai)  
A drop-in CLAUDE.md distilling four behavioral guidelines for LLM-assisted coding into Claude Code — a low-friction quick win. Karpathy-inspired, derived from Andrej Karpathy's public notes on LLM coding pitfalls and authored by multica-ai.

[`Learn Claude Code`](https://github.com/shareAI-lab/learn-claude-code) by [shareAI-lab](https://github.com/shareAI-lab)  
A really interesting analysis of how coding agents like Claude Code are designed. It attempts to break an agent down into its fundamental parts and reconstruct it with minimal code. Great learning resource. Final product is a rudimentary agent with skills, sub-agents, and a todo-list in roughly a few hundred lines of Python.

[`A Field Guide to Claude Fable 5`](https://claude.com/blog/a-field-guide-to-claude-fable-finding-your-unknowns) by [Thariq Shihipar, Anthropic](https://github.com/ThariqS)  
Really solid, insightful guidance on working/thinking with Claude Fable, and with AI in general. Very well written. Hints of Rumsfeld epistemology, but otherwise it's a great piece.

[`Beyond the Prompt: Claude Code`](https://arps18.github.io/posts/claude-code-mastery) by [Arpan Patel](https://arps18.github.io/)  
This has what you need. Remarkably clear, information-dense, it's Claude Code: the good parts, for beginners, advanced users, pets, anybody.

<br>

## Skills

[`fable-mode`](https://github.com/mrtooher/fable-mode) by [mrtooher](https://github.com/mrtooher)  
A Claude skill that activates Fable-style agentic behavior: explicit multi-stage planning, sub-agent delegation, and self-verification.

[`Caveman`](https://github.com/JuliusBrussee/caveman) by [Julius Brussee](https://github.com/JuliusBrussee)  
A plugin that conserves message tokens by communicating in fragmented "caveman speak" - sort of a clever form of compression. Now accompanied by a whole caveman ecosystem including a memory system, caveman spec kit, and a caveman agent.

[`Claude Code Infrastructure Showcase`](https://github.com/diet103/claude-code-infrastructure-showcase) by [diet103](https://github.com/diet103)  
A remarkably innovative approach to working with Skills, the centerpiece of which being a technique that leverages hooks to ensure that Claude intelligently selects and activates the appropriate Skill given the current context. Well-documented and adaptable to different projects and workflows.

[`Superpowers`](https://github.com/obra/superpowers) by [Jesse Vincent](https://github.com/obra)  
A strong bundle of core competencies for software engineering, with good coverage of a large portion of the SDLC - from planning, reviewing, testing, debugging... Well written, well organized, and adaptable. The author refers to them as "superpowers", but many of them are just consolidating engineering best practices - which sometimes does feel like a superpower when working with Claude Code.

<br>


## Contributing 🌻

Please note that this project is released with a [Contributor Code of Conduct](code-of-conduct.md). By participating in this project you agree to abide by its terms.

Regarding content, we especially welcome:

- Proven, effective resources that follow best practices and may even be in use in production.
- Innovative, creative, or experimental workflows that perhaps are still being iterated upon, but have high potential value, and push the boundaries of Claude Code's documented capabilities and use cases.
- Additional libraries and tooling that are built on top of Claude Code and offer enhanced functionality.
- Applications of Claude Code outside of the traditional "coding assistant" context, e.g., CI/CD integration, testing, documentation, dev-ops, etc.

See [CONTRIBUTING.md](CONTRIBUTING.md) for more information on how to contribute to this project. Or, fire up Claude Code and invoke the `/project:add-new-resource` command and let Claude walk you through it!

If you have any suggestions or thoughts on how to improve the repo, or how to best organize the list, feel free to start a Discussion topic. This is meant to be for the Claude Code community, and in general I prefer not to act on sole authority.

### A note about licenses

Because simply listing a hyperlink does not qualify as redistribution, the license of the original source is not relevant to its inclusion. However, for posterity and convenience, we do host copies of all resources whose license permits it. Therefore, please include information about the resource's license. Additionally, take note: _if you do not include a LICENSE in your GitHub repo, then by default it is fully copyrighted and redistribution is not allowed_. So, if you are intending to make an open source project, it's critical to pick from one of the many available open source licenses. This is just a reminder that without a LICENSE, your project is not open source (it's merely source-code-available) - it may of course still be included on this list, but this notice is to inform readers about the default rules regarding GitHub and LICENSE files. See [here](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository) for more details.
