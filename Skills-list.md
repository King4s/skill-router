# AI Agent Skills – curated list

A curated overview of AI-agent skill projects: SKILL.md-based Agent Skills (Claude Code / Anthropic), Cursor rules and plugins, Codex/OpenAI skills, awesome lists, marketplaces, registries and tooling.

- **Last updated:** 2026-11-16
- **Updated:** weekly (automated research, verified against the GitHub API)
- ★ = GitHub stars at time of update. "Updated" = last push (UTC).
- Abandoned (~9+ months without a push), empty and suspicious repos are left out. Star counts in this space are very high; they are reported as shown, not verified as organic.

## Changes this week

- **Added (official):** janestreet/agent_skills, MiniMax-AI/mcode-stack.
- **Added (collections):** alchaincyf/nuwa-skill, Vincentwei1021/video-shotcraft, wanshuiyin/Auto-claude-code-research-in-sleep, deanpeters/Product-Manager-Skills, tw93/Waza.
- **Added (awesome lists):** composio-community/awesome-claude-plugins, LeoYeAI/agent-master-skills; **restored** libukai/awesome-agent-skills (reachable again, last push 2026-10-25).
- **Added (tooling):** alchaincyf/darwin-skill, activeloopai/hivemind.
- **Stars/dates refreshed** for all listed GitHub repos; none archived or newly abandoned. kepano/obsidian-skills moved to obsidianmd/obsidian-skills (renamed). Biggest ★ movers: cloudflare/security-audit-skill (+16.7k), mattpocock/skills (+15.9k), pbakaus/impeccable (+11.2k), google/elephant-goldfish-model (+10.6k), anthropics/skills (+9.0k).
- **Removed:** none this week.
- **Flagged:** new wave of `*/GitHub-Copilot-app` impersonation clones; wanghuan9/skilldock still 404; numman-ali/openskills still no push since 2026-01-18.

## 1. Official repos (vendors and orgs)

| Repo | ★ | Updated | Description |
|---|---:|---|---|
| [anthropics/skills](https://github.com/anthropics/skills) | 195,519 | 2026-11-14 | Reference Agent Skills repo (docx/pdf/pptx/xlsx, frontend-design, skill-creator, claude-api) |
| [anthropics/claude-code](https://github.com/anthropics/claude-code) | 155,821 | 2026-11-15 | Claude Code; `plugins/` holds the official example plugins |
| [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | 47,412 | 2026-11-14 | Anthropic's directory of high-quality Claude Code plugins |
| [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins) | 36,230 | 2026-11-13 | Plugins and skills for knowledge workers (Claude Cowork) |
| [anthropics/claude-plugins-community](https://github.com/anthropics/claude-plugins-community) | 4,901 | 2026-11-12 | Community plugin marketplace (read-only mirror) |
| [github/awesome-copilot](https://github.com/github/awesome-copilot) | 41,204 | 2026-11-16 | GitHub's community instructions, agents and skills for Copilot |
| [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) | 34,148 | 2026-11-12 | Vercel's official skills (React best practices, web design guidelines) |
| [openai/skills](https://github.com/openai/skills) | 28,764 | 2026-10-28 | Skills catalog for Codex |
| [openai/plugins](https://github.com/openai/plugins) | 7,966 | 2026-11-14 | OpenAI/Codex plugins |
| [huggingface/skills](https://github.com/huggingface/skills) | 11,355 | 2026-11-13 | Hugging Face skills (hf-cli, training, datasets, evals) |
| [cursor/plugins](https://github.com/cursor/plugins) | 16,497 | 2026-11-15 | Cursor plugin specification and official plugins |
| [google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills) | 9,467 | 2026-08-17 | Google's Agent Skills for the Stitch MCP server |
| [google/agents-cli](https://github.com/google/agents-cli) | 6,359 | 2026-11-12 | Google CLI plus skills for building and evaluating agents (ADK) |
| [google-gemini/gemini-skills](https://github.com/google-gemini/gemini-skills) | 4,501 | 2026-11-12 | Skills for the Gemini API and SDK |
| [gemini-cli-extensions/conductor](https://github.com/gemini-cli-extensions/conductor) | 3,793 | 2026-09-01 | Gemini CLI extension for spec-driven development |
| [trailofbits/skills](https://github.com/trailofbits/skills) | 8,219 | 2026-11-12 | Security research and audit skills |
| [remotion-dev/skills](https://github.com/remotion-dev/skills) | 7,302 | 2026-11-11 | Remotion's official skills |
| [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | 84,871 | 2026-11-16 | HeyGen's HTML-to-video skills |
| [alibaba/open-code-review](https://github.com/alibaba/open-code-review) | 52,417 | 2026-11-16 | Alibaba open-source code-review tool with bundled agent skills (deterministic + LLM) |
| [larksuite/cli](https://github.com/larksuite/cli) | 18,125 | 2026-11-13 | Official Lark/Feishu CLI with many skills |
| [googleworkspace/cli](https://github.com/googleworkspace/cli) | 32,332 | 2026-11-03 | Google Workspace CLI with bundled AI agent skills (Drive, Gmail, Calendar, Docs, Sheets, Chat, Admin) |
| [microsoft/skills](https://github.com/microsoft/skills) | 3,208 | 2026-11-13 | Microsoft skills, MCP servers and AGENTS.md for its SDKs |
| [microsoft/azure-skills](https://github.com/microsoft/azure-skills) | 1,644 | 2026-11-13 | Official Azure skills plus MCP configuration |
| [microsoft/power-platform-skills](https://github.com/microsoft/power-platform-skills) | 1,152 | 2026-11-16 | Power Platform plugin marketplace |
| [cloudflare/skills](https://github.com/cloudflare/skills) | 3,374 | 2026-11-10 | Cloudflare skills |
| [supabase/agent-skills](https://github.com/supabase/agent-skills) | 3,091 | 2026-11-12 | Supabase skills |
| [expo/skills](https://github.com/expo/skills) | 4,163 | 2026-11-15 | Expo/EAS skills |
| [stripe/ai](https://github.com/stripe/ai) | 2,065 | 2026-11-16 | Stripe's AI toolkit (includes skills) |
| [callstackincubator/agent-skills](https://github.com/callstackincubator/agent-skills) | 1,709 | 2026-10-08 | React Native skills from Callstack |
| [browserbase/skills](https://github.com/browserbase/skills) | 3,756 | 2026-10-27 | Browserbase's official agent skills for web access and browser automation |
| [matlab/matlab-agentic-toolkit](https://github.com/matlab/matlab-agentic-toolkit) | 1,303 | 2026-11-09 | MATLAB skills for agents |
| [matlab/simulink-agentic-toolkit](https://github.com/matlab/simulink-agentic-toolkit) | 1,349 | 2026-11-11 | MathWorks' Simulink skills plus MCP tools for Model-Based Design (Claude Code, Copilot, Codex, Gemini CLI) |
| [getsentry/skills](https://github.com/getsentry/skills) | 1,173 | 2026-11-14 | Sentry's skills |
| [awslabs/agent-plugins](https://github.com/awslabs/agent-plugins) | 943 | 2026-11-14 | AWS agent plugins and skills |
| [hashicorp/agent-skills](https://github.com/hashicorp/agent-skills) | 929 | 2026-11-04 | HashiCorp skills and Claude Code plugins |
| [firebase/agent-skills](https://github.com/firebase/agent-skills) | 518 | 2026-11-09 | Firebase skills |
| [mongodb/agent-skills](https://github.com/mongodb/agent-skills) | 198 | 2026-11-13 | Official MongoDB agent skills (Atlas, schema, query, search) |
| [redis/agent-skills](https://github.com/redis/agent-skills) | 176 | 2026-11-05 | Redis' official collection of agent skills |
| [neondatabase/agent-skills](https://github.com/neondatabase/agent-skills) | 114 | 2026-11-14 | Neon Postgres skills |
| [google/skills](https://github.com/google/skills) | 24,348 | 2026-11-16 | Agent Skills for Google products and technologies |
| [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) | 73,385 | 2026-09-14 | Cloudflare's multi-phase security-audit skill with verified findings |
| [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | 263,710 | 2026-11-16 | Hermes Agent with built-in SKILL.md support |
| [NousResearch/hermes-official-plugins](https://github.com/NousResearch/hermes-official-plugins) | 740 | 2026-11-15 | Nous Research's official first-party plugins for Hermes Agent (plugin catalog) |
| [android/skills](https://github.com/android/skills) | 10,554 | 2026-11-15 | Android's official Agent Skills (SKILL.md) based on developer.android.com guidance |
| [Tencent/BrowserSkill](https://github.com/Tencent/BrowserSkill) | 10,443 | 2026-11-15 | Tencent's CLI + extension that lets agents use your real, logged-in browser |
| [dotnet/skills](https://github.com/dotnet/skills) | 6,223 | 2026-11-15 | Microsoft .NET team's skills for .NET and C# (100+ SKILL.md) |
| [BuilderIO/skills](https://github.com/BuilderIO/skills) | 4,672 | 2026-11-15 | Builder.io's small, composable agent skills (`npx @agent-native/skills`) |
| [apify/agent-skills](https://github.com/apify/agent-skills) | 2,500 | 2026-11-11 | Apify's agent skills for web scraping and Actors |
| [WordPress/agent-skills](https://github.com/WordPress/agent-skills) | 2,372 | 2026-11-16 | WordPress' official skills (blocks, themes, plugins, best practices) |
| [Kotlin/kotlin-agent-skills](https://github.com/Kotlin/kotlin-agent-skills) | 1,124 | 2026-10-30 | JetBrains/Kotlin agent skills for Kotlin projects |
| [laravel/agent-skills](https://github.com/laravel/agent-skills) | 737 | 2026-11-14 | Laravel's official agent skills |
| [elastic/agent-skills](https://github.com/elastic/agent-skills) | 605 | 2026-11-13 | Elastic's official skills (50+ SKILL.md) |
| [ClickHouse/agent-skills](https://github.com/ClickHouse/agent-skills) | 567 | 2026-11-02 | Official skills for ClickHouse and ClickHouse Cloud |
| [google/elephant-goldfish-model](https://github.com/google/elephant-goldfish-model) | 19,961 | 2026-11-15 | Google's Elephant-Goldfish Model plugin/skills: deep-context agent drafts specs, zero-context subagents review them |
| [google-deepmind/science-skills](https://github.com/google-deepmind/science-skills) | 3,482 | 2026-11-10 | Google DeepMind's science skills for grounded, token-efficient agentic scientific workflows |
| [typesafe-ai/skills](https://github.com/typesafe-ai/skills) | 2,902 | 2026-10-23 | TypeSafe's official skill/Claude Code plugin for its System One API (typed decisions, e.g. Jev) |
| [EpicGames/unreal-engine-skills-for-claude-code-plugin](https://github.com/EpicGames/unreal-engine-skills-for-claude-code-plugin) | 1,976 | 2026-10-27 | Epic Games' Claude Code plugin: `unreal-mcp` skill plus hooks to drive Unreal Editor via MCP |
| [MicrosoftDocs/Agent-Skills](https://github.com/MicrosoftDocs/Agent-Skills) | 814 | 2026-11-09 | Microsoft Learn's curated skills for Microsoft and Azure services |
| [dbt-labs/dbt-agent-skills](https://github.com/dbt-labs/dbt-agent-skills) | 763 | 2026-11-06 | dbt Labs' official skills for working with dbt projects |
| [TheQtCompanyRnD/agent-skills](https://github.com/TheQtCompanyRnD/agent-skills) | 545 | 2026-11-09 | The Qt Company's official Qt/QML skills (Claude Code, Codex, Copilot, Gemini) |
| [databricks/databricks-agent-skills](https://github.com/databricks/databricks-agent-skills) | 402 | 2026-11-16 | Databricks' skills and plugins for Claude Code, Cursor and Codex |
| [janestreet/agent_skills](https://github.com/janestreet/agent_skills) | 9,178 | 2026-11-03 | Jane Street's agent skills repo (released 2026-11-03; first skill: `socratic-tutor`) |
| [MiniMax-AI/mcode-stack](https://github.com/MiniMax-AI/mcode-stack) | 725 | 2026-11-11 | Workflows and skills the MiniMax Code team uses to build MiniMax Code |

## 2. Large community collections

| Repo | ★ | Updated | Description |
|---|---:|---|---|
| [obra/superpowers](https://github.com/obra/superpowers) | 318,184 | 2026-11-03 | Skills framework and development methodology (brainstorming, TDD, debugging) |
| [mattpocock/skills](https://github.com/mattpocock/skills) | 325,399 | 2026-11-13 | Engineering skills; most-installed source on skills.sh |
| [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | 150,077 | 2026-11-16 | UI/UX design skill for many agents |
| [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) | 120,540 | 2026-11-16 | Token-saving skill plus proxy |
| [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | 118,051 | 2026-11-14 | Production-grade engineering skills |
| [nexu-io/open-design](https://github.com/nexu-io/open-design) | 107,811 | 2026-11-16 | Open-source design plugin/harness with a large SKILL.md library (prototypes, landing pages, slides) |
| [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | 116,394 | 2026-11-08 | Design-taste skills against generic "AI slop" |
| [tt-a1i/archify](https://github.com/tt-a1i/archify) | 96,927 | 2026-11-16 | Agent skill that turns ideas or codebases into interactive architecture diagrams |
| [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | 110,918 | 2026-11-16 | Design-language skill |
| [career-ops-hq/career-ops](https://github.com/career-ops-hq/career-ops) | 82,847 | 2026-11-16 | AI job-search agent skills: board scan, CV scoring, resume/cover letters, interview prep |
| [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | 67,461 | 2026-11-12 | Editorial diagram-design skill (44 types, HTML/SVG) for Claude Code, Codex, Cursor, Copilot |
| [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) | 60,648 | 2026-11-11 | Marketing, CRO and SEO skills |
| [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | 57,360 | 2026-11-09 | Large library of science skills |
| [Yuan1z0825/nature-skills](https://github.com/Yuan1z0825/nature-skills) | 53,700 | 2026-11-16 | Academic/research skills for Nature-style writing, figures and literature search |
| [emilkowalski/skills](https://github.com/emilkowalski/skills) | 57,283 | 2026-11-15 | Skills for designers and engineers |
| [wshobson/agents](https://github.com/wshobson/agents) | 42,561 | 2026-11-16 | Plugin marketplace for Claude Code, Codex, Cursor, OpenCode and Copilot |
| [virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill) | 38,017 | 2026-11-08 | Turns technical book PDFs into ready-to-use Claude Code skills |
| [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) | 29,870 | 2026-11-16 | 380+ skills, agents and commands |
| [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) | 28,083 | 2026-11-11 | Persistent file-based planning for coding agents (crash-proof plans, session recovery) |
| [phuryn/pm-skills](https://github.com/phuryn/pm-skills) | 28,028 | 2026-11-08 | 100+ product-management skills |
| [JimLiu/baoyu-skills](https://github.com/JimLiu/baoyu-skills) | 27,582 | 2026-11-06 | Popular Chinese skills collection |
| [EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin) | 26,114 | 2026-11-13 | Compound Engineering plugin (Claude Code, Codex, Cursor) |
| [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) | 27,550 | 2026-10-18 | Skill that builds interactive isometric illustrations of machines and systems (SVG, WebGL, 3D) |
| [Orchestra-Research/AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs) | 14,578 | 2026-10-11 | AI research and ML-engineering skills |
| [Jeffallan/claude-skills](https://github.com/Jeffallan/claude-skills) | 12,382 | 2026-11-15 | 67 full-stack skills |
| [alchaincyf/huashu-design](https://github.com/alchaincyf/huashu-design) | 29,614 | 2026-11-10 | HTML-native design skill: web/app prototypes, editable PPTX, animation, infographics (Chinese/English) |
| [titanwings/distilly](https://github.com/titanwings/distilly) | 26,597 | 2026-10-13 | Distills how people think into reusable skills (formerly Colleague Skill) |
| [rehan-remade/universal-modder](https://github.com/rehan-remade/universal-modder) | 9,722 | 2026-11-16 | Skills, tools and knowledge base that let coding agents mod almost any PC game (with fal MCP) |
| [alchaincyf/huashu-art-motion](https://github.com/alchaincyf/huashu-art-motion) | 6,999 | 2026-11-15 | Art-animation skill: 35+ art styles and 9 narration grammars rendered in code (Chinese/English) |
| [Mindrally/skills](https://github.com/Mindrally/skills) | 306 | 2026-10-08 | 255+ skills converted from Cursor rules |
| [Jahrome907/minecraft-agent-skills](https://github.com/Jahrome907/minecraft-agent-skills) | 205 | 2026-10-30 | Minecraft modding/server skills for Codex and Claude Code |
| [affaan-m/ECC](https://github.com/affaan-m/ECC) | 303,991 | 2026-11-16 | Agent harness system (formerly everything-claude-code): skills, memory, security |
| [garrytan/gstack](https://github.com/garrytan/gstack) | 141,737 | 2026-11-16 | Garry Tan's Claude Code setup: opinionated role skills (CEO, designer, eng manager, QA) |
| [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) | 67,806 | 2026-11-16 | Research skill across Reddit, X, YouTube, HN and the web |
| [blader/humanizer](https://github.com/blader/humanizer) | 69,594 | 2026-11-10 | Skill that removes signs of AI-generated writing |
| [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd) | 61,333 | 2026-10-19 | Skill that keeps agent answers short and ADHD-friendly (stops burying the answer) |
| [obsidianmd/obsidian-skills](https://github.com/obsidianmd/obsidian-skills) | 52,860 | 2026-11-11 | Obsidian skills (CLI, Markdown, Bases, Canvas) from Obsidian's CEO |
| [gamedev-skills/awesome-gamedev-agent-skills](https://github.com/gamedev-skills/awesome-gamedev-agent-skills) | 9,042 | 2026-11-12 | 74 game-dev skills (Godot, Unity, Unreal, Phaser, three.js, Bevy) |
| [op7418/guizang-ppt-skill](https://github.com/op7418/guizang-ppt-skill) | 29,853 | 2026-10-30 | Skill for polished HTML slide decks (editorial magazine and Swiss layouts) |
| [KKKKhazix/khazix-skills](https://github.com/KKKKhazix/khazix-skills) | 22,284 | 2026-11-15 | Popular Chinese skills collection (goal-setting, writing, analysis) |
| [ConardLi/garden-skills](https://github.com/ConardLi/garden-skills) | 15,254 | 2026-11-14 | Skills for web design, knowledge retrieval and image generation |
| [Agents365-ai/drawio-skill](https://github.com/Agents365-ai/drawio-skill) | 10,785 | 2026-11-10 | Turns text, code, Terraform/K8s, SQL and API specs into draw.io diagrams |
| [ibelick/ui-skills](https://github.com/ibelick/ui-skills) | 11,103 | 2026-11-14 | UI skills for design engineers |
| [antfu/skills](https://github.com/antfu/skills) | 6,074 | 2026-11-11 | Anthony Fu's curated agent skills (Vue/Vite ecosystem) |
| [alchaincyf/nuwa-skill](https://github.com/alchaincyf/nuwa-skill) | 38,378 | 2026-11-15 | Skill that distills how anyone thinks (mental models, decision heuristics, style) into a reusable skill (Chinese/English) |
| [Vincentwei1021/video-shotcraft](https://github.com/Vincentwei1021/video-shotcraft) | 20,240 | 2026-11-15 | AI video skill for Claude Code and Codex: cinematic, editable product promos with Remotion |
| [wanshuiyin/Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) | 19,271 | 2026-11-14 | ARIS: Markdown-only skills for autonomous ML research with cross-model review |
| [deanpeters/Product-Manager-Skills](https://github.com/deanpeters/Product-Manager-Skills) | 8,039 | 2026-11-13 | Product-management skills framework for Claude Code, Cowork, Codex and other agents |
| [tw93/Waza](https://github.com/tw93/Waza) | 7,599 | 2026-11-11 | Familiar engineering habits packaged as skills for Claude Code, Codex and Cursor |

## 3. Awesome lists

| Repo | ★ | Updated | Description |
|---|---:|---|---|
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | 79,602 | 2026-09-18 | The biggest Claude Skills list |
| [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) | 58,105 | 2026-11-16 | Claude Code skills, hooks, commands and plugins |
| [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) | 53,804 | 2026-10-30 | 5,400+ OpenClaw skills, categorized |
| [sickn33/agentic-awesome-skills](https://github.com/sickn33/agentic-awesome-skills) | 49,776 | 2026-11-15 | Large skills catalog plus a local catalog tool |
| [PatrickJS/awesome-cursorrules](https://github.com/PatrickJS/awesome-cursorrules) | 41,163 | 2026-05-30 | The canonical Cursor rules list |
| [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) | 37,225 | 2026-11-15 | 1,000+ skills from official teams and the community |
| [composio-community/awesome-codex-skills](https://github.com/composio-community/awesome-codex-skills) | 17,333 | 2026-07-26 | Codex skills |
| [travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills) | 15,834 | 2026-04-28 | Claude Skills list (updates have slowed) |
| [BehiSecc/awesome-claude-skills](https://github.com/BehiSecc/awesome-claude-skills) | 10,434 | 2026-11-02 | Claude Skills list |
| [VoltAgent/awesome-codex-subagents](https://github.com/VoltAgent/awesome-codex-subagents) | 6,480 | 2026-11-02 | Curated list of 130+ specialized Codex subagents |
| [heilcheng/awesome-agent-skills](https://github.com/heilcheng/awesome-agent-skills) | 6,394 | 2026-11-09 | Tutorials and skill directories |
| [Prat011/awesome-llm-skills](https://github.com/Prat011/awesome-llm-skills) | 1,865 | 2026-07-14 | LLM and agent skills |
| [hashgraph-online/awesome-codex-plugins](https://github.com/hashgraph-online/awesome-codex-plugins) | 1,579 | 2026-11-16 | Codex plugins and skills |
| [ccplugins/awesome-claude-code-plugins](https://github.com/ccplugins/awesome-claude-code-plugins) | 1,011 | 2026-08-12 | Claude Code plugins |
| [spencerpauly/awesome-cursor-skills](https://github.com/spencerpauly/awesome-cursor-skills) | 891 | 2026-08-02 | Cursor skills |
| [ZeroPointRepo/awesome-hermes-skills](https://github.com/ZeroPointRepo/awesome-hermes-skills) | 683 | 2026-11-02 | Hermes Agent skills |
| [quemsah/awesome-claude-plugins](https://github.com/quemsah/awesome-claude-plugins) | 1,617 | 2026-11-16 | Automated index of Claude Code plugins with adoption metrics |
| [lawve-ai/awesome-legal-skills](https://github.com/lawve-ai/awesome-legal-skills) | 956 | 2026-10-19 | Agent Skills for legal work |
| [0xNyk/awesome-hermes-agent](https://github.com/0xNyk/awesome-hermes-agent) | 6,026 | 2026-10-27 | Independent directory of Hermes Agent skills, plugins, memory providers and tools |
| [libukai/awesome-agent-skills](https://github.com/libukai/awesome-agent-skills) | 5,220 | 2026-10-25 | The Ultimate Guide to Agent Skills: quick start, resources, curated skills and tools (Chinese/English) |
| [composio-community/awesome-claude-plugins](https://github.com/composio-community/awesome-claude-plugins) | 1,995 | 2026-11-05 | Curated list of Claude Code plugins (commands, agents, hooks, MCP servers) |
| [LeoYeAI/agent-master-skills](https://github.com/LeoYeAI/agent-master-skills) | 2,194 | 2026-11-13 | Curated collection of 2,700+ harness-agnostic agent skills |

## 4. Marketplaces and registries

| Site / repo | ★ | Updated | Description |
|---|---:|---|---|
| [skills.sh](https://skills.sh) | – | – | Vercel's skills directory with install leaderboard (`npx skills`) |
| [SkillsMP](https://skillsmp.com) | – | – | Aggregator claiming 3M+ skills from GitHub; REST API and MCP server |
| [Smithery skills](https://smithery.ai/skills) | – | – | Skill registry with install counts |
| [claude-plugins.dev](https://claude-plugins.dev) ([source](https://github.com/Kamalnrf/claude-plugins)) | 566 | 2026-11-09 | Registry plus `npx claude-plugins` CLI |
| [cursor.directory](https://cursor.directory) | – | – | Cursor plugins, rules and MCP servers |
| [ClawHub](https://clawhub.ai) ([openclaw/clawhub](https://github.com/openclaw/clawhub)) | 9,554 | 2026-11-16 | OpenClaw skill and plugin registry |
| [davepoon/buildwithclaude](https://github.com/davepoon/buildwithclaude) | 3,752 | 2026-11-16 | Hub for skills, plugins and marketplaces |
| [obra/superpowers-marketplace](https://github.com/obra/superpowers-marketplace) | 1,328 | 2026-11-03 | Curated Claude Code marketplace |
| [numman-ali/n-skills](https://github.com/numman-ali/n-skills) | 1,051 | 2026-09-12 | Curated marketplace (Claude Code, Codex, openskills) |
| [LinklyAI/best-skills](https://github.com/LinklyAI/best-skills) | 773 | 2026-11-16 | Daily Top 100 skills ranking |
| [trailofbits/skills-curated](https://github.com/trailofbits/skills-curated) | 537 | 2026-07-14 | Community-vetted marketplace |
| [skilld-dev/skilld](https://github.com/skilld-dev/skilld) | 333 | 2026-10-10 | Open-source alternative to skills.sh |
| [jeremylongshore/tons-of-skills-marketplace](https://github.com/jeremylongshore/tons-of-skills-marketplace) | 2,924 | 2026-11-16 | Model-agnostic skills marketplace with adapters for several agents |
| [tech-leads-club/agent-skills](https://github.com/tech-leads-club/agent-skills) | 7,167 | 2026-11-12 | Validated skill registry for coding agents (Claude Code, Cursor, Copilot, Antigravity) |
| [iflytek/skillhub](https://github.com/iflytek/skillhub) | 5,430 | 2026-11-16 | iFlytek's self-hosted enterprise skill registry: versioning, RBAC, audit logs, Docker/Kubernetes |

## 5. Tooling (spec, CLI, convert, validate, security)

| Repo | ★ | Updated | Description |
|---|---:|---|---|
| [vercel-labs/skills](https://github.com/vercel-labs/skills) | 39,558 | 2026-11-16 | `npx skills`, the open install CLI |
| [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) | 33,792 | 2026-11-16 | CLI to configure Claude Code (skills, agents, hooks) |
| [agentskills/agentskills](https://github.com/agentskills/agentskills) ([agentskills.io](https://agentskills.io)) | 27,332 | 2026-11-04 | Open Agent Skills spec plus `skills-ref validate`; ~50 supporting clients |
| [agentsmd/agents.md](https://github.com/agentsmd/agents.md) | 25,515 | 2026-09-10 | The AGENTS.md standard |
| [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) | 26,281 | 2026-11-14 | Security scanner for skills |
| [microsoft/SkillOpt](https://github.com/microsoft/SkillOpt) | 19,094 | 2026-11-10 | Optimizer/trainer for natural-language skills |
| [yusufkaraaslan/Skill_Seekers](https://github.com/yusufkaraaslan/Skill_Seekers) | 15,324 | 2026-11-16 | Turns docs sites, repos and PDFs into skills |
| [rebelytics/one-skill-to-rule-them-all](https://github.com/rebelytics/one-skill-to-rule-them-all) | 3,925 | 2026-11-15 | A skill that builds and improves your other skills |
| [intellectronica/ruler](https://github.com/intellectronica/ruler) | 2,974 | 2026-11-14 | Same rules for all coding agents |
| [cisco-ai-defense/skill-scanner](https://github.com/cisco-ai-defense/skill-scanner) | 2,732 | 2026-11-15 | Security scanner for skills |
| [rohitg00/skillkit](https://github.com/rohitg00/skillkit) | 1,579 | 2026-06-02 | Install, translate and share skills across agents |
| [dyoshikawa/rulesync](https://github.com/dyoshikawa/rulesync) | 1,612 | 2026-11-16 | Syncs rules and skills between agents |
| [jiweiyeah/Skills-Manager](https://github.com/jiweiyeah/Skills-Manager) | 1,063 | 2026-09-10 | Desktop app: write once, sync to 32 tools |
| [huggingface/upskill](https://github.com/huggingface/upskill) | 768 | 2026-10-27 | Generates and evaluates skills |
| [EverMind-AI/SkillCorpus](https://github.com/EverMind-AI/SkillCorpus) | 704 | 2026-11-12 | Turns SKILL.md files into a searchable corpus |
| [VikashLoomba/copilot-mcp](https://github.com/VikashLoomba/copilot-mcp) | 508 | 2026-06-15 | VS Code extension to find and install skills for Copilot |
| [K-Dense-AI/claude-skills-mcp](https://github.com/K-Dense-AI/claude-skills-mcp) | 411 | 2026-07-20 | MCP server for skill search |
| [VintLin/skill-flow](https://github.com/VintLin/skill-flow) | 266 | 2026-11-06 | Install and share skills across agents |
| [block/ai-rules](https://github.com/block/ai-rules) | 146 | 2026-05-11 | Manages rules and skills across agents |
| [microsoft/skill-recorder](https://github.com/microsoft/skill-recorder) | 5,828 | 2026-11-12 | Desktop app that records a work session and turns it into a reusable skill (Copilot SDK) |
| [cloudflare/agent-skills-discovery-rfc](https://github.com/cloudflare/agent-skills-discovery-rfc) | 379 | 2026-04-23 | Proposal for discovering Agent Skills via `.well-known` URIs (RFC 8615) |
| [refly-ai/refly](https://github.com/refly-ai/refly) | 7,556 | 2026-11-02 | Open-source visual builder for agent skills that run in Claude Code, Cursor and Codex |
| [benchflow-ai/skillsbench](https://github.com/benchflow-ai/skillsbench) | 1,919 | 2026-11-14 | Benchmark of how much skills help agents (dataset on Hugging Face below) |
| [Adyen/agent-marketplace](https://github.com/Adyen/agent-marketplace) | 92 | 2026-11-15 | Adyen's open-source CLI that installs shared skills, commands, subagents, hooks and MCP servers into each agent's format (released 2026-10-22) |
| [alchaincyf/darwin-skill](https://github.com/alchaincyf/darwin-skill) | 6,935 | 2026-11-14 | Autonomous skill optimizer: evaluate → improve → test → keep or roll back |
| [activeloopai/hivemind](https://github.com/activeloopai/hivemind) | 1,655 | 2026-11-11 | Turns agent traces into reusable skills shared across agents |

## 6. GitLab and Hugging Face

| Project | ★ / likes | Updated | Description |
|---|---:|---|---|
| [gitlab-org/ai/skills](https://gitlab.com/gitlab-org/ai/skills) | 48 | 2026-11-16 | GitLab's official skills; also a Claude Code marketplace. GitLab Duo supports SKILL.md natively ([docs](https://docs.gitlab.com/user/duo_agent_platform/customize/agent_skills/)) |
| [hf-skills](https://huggingface.co/hf-skills) | – | – | Hugging Face org with skill Spaces (skill-finder, llm-trainer); `hf skills add` installs from the Hub |
| [benchflow/skillsbench](https://huggingface.co/datasets/benchflow/skillsbench) | 19 | 2026-06-16 | Skills benchmark dataset |
| [open-index/open-skills](https://huggingface.co/datasets/open-index/open-skills) | 15 | 2026-04-10 | Archive of skills.sh |

## Flagged / excluded

- [wanghuan9/skilldock](https://github.com/wanghuan9/skilldock) (Desktop skill manager; last recorded 607★, pushed 2026-10-03): GitHub API and public repository URL returned HTTP 404 on 2026-10-12 and again on 2026-10-19, 2026-10-26, 2026-11-02 and 2026-11-16 (the owner account `wanghuan9` also returns 404). Moved here with owner approval; retained for source accounting, excluded from indexing until available again.
- [numman-ali/openskills](https://github.com/numman-ali/openskills) (Cross-agent skills loader; 10,817★, last push 2026-01-18): no push for 9+ months as of 2026-11-16; removed from Tooling. Will be restored if development resumes.
- skills.sh leaderboard entries with install counts far out of line with GitHub activity (e.g. `prime-skills/runcomfy-agent-skills`, `flowkit-labs/skills`, `lllllllama/RigorPilot-Skills`).
- Repos copying the `obra/superpowers` name (`101-skills/superpowers`, `qu-skills/superpowers`).
- `mukul975/Anthropic-Cybersecurity-Skills` (35.4k★): uses "Anthropic" in its name but is not from Anthropic.
- `DietrichGebert/ponytail` (182k★, single skill, unclear star origin) and `anbeime/skill` (points to an external store).
- `Jakeschincariol/*-skill` series (`replica-skill` 7.0k★, `day-trader-skill` 4.4k★, `instagram-agent-skill` 4.4k★, `youtube-agent-skill` 4.2k★, `linkedin-agent-skill` 3.0k★, `founder-skill` 2.3k★, `arena-skill` 1.2k★, `trader-skill` 1.1k★, plus 8 smaller ones): near-identical "Eleven free Claude skills" repos with few commits (checked 2026-11-02); stars out of line with substance.
- `morluto/rea` (419.9k★, created 2026-04-14): reverse-engineering tool tagged agent-skills; out of scope and star count out of line with age. `unclebob/ub-mode` (6.4k★, 4 commits, no description).
- `*/GitHub-Copilot-app` clones (e.g. `trackersnailgrip/GitHub-Copilot-app`, `TrapBladesmith/GitHub-Copilot-app`; 8+ throwaway accounts, all created 2026-11-14 with ~375–385★ each): impersonate GitHub's Copilot app; do not install.
- Older than ~9 months: `flyeric0212/cursor-rules`, `ananddtyagi/cc-marketplace`.

> Before installing third-party skills, prefer official repos or run them through a scanner such as SkillSpector or cisco-ai-defense/skill-scanner.
