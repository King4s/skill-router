# AI Agent Skills – curated list

A curated overview of AI-agent skill projects: SKILL.md-based Agent Skills (Claude Code / Anthropic), Cursor rules and plugins, Codex/OpenAI skills, awesome lists, marketplaces, registries and tooling.

- **Last updated:** 2026-11-02
- **Updated:** weekly (automated research, verified against the GitHub API)
- ★ = GitHub stars at time of update. "Updated" = last push (UTC).
- Abandoned (~9+ months without a push), empty and suspicious repos are left out. Star counts in this space are very high; they are reported as shown, not verified as organic.

## Changes this week

- **Added (official):** google/elephant-goldfish-model, google-deepmind/science-skills, typesafe-ai/skills, EpicGames/unreal-engine-skills-for-claude-code-plugin, MicrosoftDocs/Agent-Skills, dbt-labs/dbt-agent-skills, TheQtCompanyRnD/agent-skills, databricks/databricks-agent-skills.
- **Added (collections):** op7418/guizang-ppt-skill, KKKKhazix/khazix-skills, ConardLi/garden-skills, Agents365-ai/drawio-skill, ibelick/ui-skills, antfu/skills.
- **Added (awesome lists):** 0xNyk/awesome-hermes-agent.
- **Added (tooling):** refly-ai/refly, benchflow-ai/skillsbench, Adyen/agent-marketplace.
- **Stars/dates refreshed** for all listed GitHub repos; no listed repo was archived, renamed or newly abandoned. Biggest ★ movers: pbakaus/impeccable (+11.6k), cloudflare/security-audit-skill (+9.2k, still no push since 2026-09-14), mattpocock/skills (+6.0k), affaan-m/ECC (+5.9k), obra/superpowers (+5.6k).
- **Removed:** none this week.
- **Flagged:** wanghuan9/skilldock and libukai/awesome-agent-skills still 404 (rechecked 2026-11-02); numman-ali/openskills still no push since 2026-01-18; `Jakeschincariol/*-skill` series keeps growing (now 16 repos, incl. new `console-skill`, `closer-skill`, `seed-skill`) and is still excluded. Not added: `morluto/rea` (419.9k★, reverse-engineering tool rather than a skills project; stars out of line with age) and `unclebob/ub-mode` (6.4k★, 4 commits, no description).

## 1. Official repos (vendors and orgs)

| Repo | ★ | Updated | Description |
|---|---:|---|---|
| [anthropics/skills](https://github.com/anthropics/skills) | 186,471 | 2026-10-28 | Reference Agent Skills repo (docx/pdf/pptx/xlsx, frontend-design, skill-creator, claude-api) |
| [anthropics/claude-code](https://github.com/anthropics/claude-code) | 154,205 | 2026-11-01 | Claude Code; `plugins/` holds the official example plugins |
| [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | 45,757 | 2026-11-01 | Anthropic's directory of high-quality Claude Code plugins |
| [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins) | 34,405 | 2026-11-01 | Plugins and skills for knowledge workers (Claude Cowork) |
| [anthropics/claude-plugins-community](https://github.com/anthropics/claude-plugins-community) | 4,812 | 2026-11-01 | Community plugin marketplace (read-only mirror) |
| [github/awesome-copilot](https://github.com/github/awesome-copilot) | 40,690 | 2026-11-02 | GitHub's community instructions, agents and skills for Copilot |
| [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) | 33,373 | 2026-10-28 | Vercel's official skills (React best practices, web design guidelines) |
| [openai/skills](https://github.com/openai/skills) | 28,454 | 2026-10-28 | Skills catalog for Codex |
| [openai/plugins](https://github.com/openai/plugins) | 7,708 | 2026-10-30 | OpenAI/Codex plugins |
| [huggingface/skills](https://github.com/huggingface/skills) | 11,252 | 2026-10-30 | Hugging Face skills (hf-cli, training, datasets, evals) |
| [cursor/plugins](https://github.com/cursor/plugins) | 15,062 | 2026-11-01 | Cursor plugin specification and official plugins |
| [google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills) | 8,657 | 2026-08-17 | Google's Agent Skills for the Stitch MCP server |
| [google/agents-cli](https://github.com/google/agents-cli) | 6,279 | 2026-10-27 | Google CLI plus skills for building and evaluating agents (ADK) |
| [google-gemini/gemini-skills](https://github.com/google-gemini/gemini-skills) | 4,370 | 2026-10-30 | Skills for the Gemini API and SDK |
| [gemini-cli-extensions/conductor](https://github.com/gemini-cli-extensions/conductor) | 3,778 | 2026-09-01 | Gemini CLI extension for spec-driven development |
| [trailofbits/skills](https://github.com/trailofbits/skills) | 7,943 | 2026-10-28 | Security research and audit skills |
| [remotion-dev/skills](https://github.com/remotion-dev/skills) | 6,056 | 2026-10-26 | Remotion's official skills |
| [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | 77,285 | 2026-11-02 | HeyGen's HTML-to-video skills |
| [alibaba/open-code-review](https://github.com/alibaba/open-code-review) | 49,259 | 2026-11-01 | Alibaba open-source code-review tool with bundled agent skills (deterministic + LLM) |
| [larksuite/cli](https://github.com/larksuite/cli) | 17,923 | 2026-11-02 | Official Lark/Feishu CLI with many skills |
| [googleworkspace/cli](https://github.com/googleworkspace/cli) | 32,053 | 2026-10-30 | Google Workspace CLI with bundled AI agent skills (Drive, Gmail, Calendar, Docs, Sheets, Chat, Admin) |
| [microsoft/skills](https://github.com/microsoft/skills) | 3,166 | 2026-11-02 | Microsoft skills, MCP servers and AGENTS.md for its SDKs |
| [microsoft/azure-skills](https://github.com/microsoft/azure-skills) | 1,609 | 2026-10-30 | Official Azure skills plus MCP configuration |
| [microsoft/power-platform-skills](https://github.com/microsoft/power-platform-skills) | 1,102 | 2026-11-01 | Power Platform plugin marketplace |
| [cloudflare/skills](https://github.com/cloudflare/skills) | 3,248 | 2026-10-31 | Cloudflare skills |
| [supabase/agent-skills](https://github.com/supabase/agent-skills) | 2,980 | 2026-10-02 | Supabase skills |
| [expo/skills](https://github.com/expo/skills) | 4,014 | 2026-11-01 | Expo/EAS skills |
| [stripe/ai](https://github.com/stripe/ai) | 2,028 | 2026-11-02 | Stripe's AI toolkit (includes skills) |
| [callstackincubator/agent-skills](https://github.com/callstackincubator/agent-skills) | 1,694 | 2026-10-08 | React Native skills from Callstack |
| [browserbase/skills](https://github.com/browserbase/skills) | 3,748 | 2026-10-27 | Browserbase's official agent skills for web access and browser automation |
| [matlab/matlab-agentic-toolkit](https://github.com/matlab/matlab-agentic-toolkit) | 1,237 | 2026-10-27 | MATLAB skills for agents |
| [matlab/simulink-agentic-toolkit](https://github.com/matlab/simulink-agentic-toolkit) | 1,308 | 2026-10-29 | MathWorks' Simulink skills plus MCP tools for Model-Based Design (Claude Code, Copilot, Codex, Gemini CLI) |
| [getsentry/skills](https://github.com/getsentry/skills) | 1,109 | 2026-10-26 | Sentry's skills |
| [awslabs/agent-plugins](https://github.com/awslabs/agent-plugins) | 933 | 2026-11-02 | AWS agent plugins and skills |
| [hashicorp/agent-skills](https://github.com/hashicorp/agent-skills) | 911 | 2026-10-28 | HashiCorp skills and Claude Code plugins |
| [firebase/agent-skills](https://github.com/firebase/agent-skills) | 498 | 2026-10-30 | Firebase skills |
| [mongodb/agent-skills](https://github.com/mongodb/agent-skills) | 194 | 2026-10-31 | Official MongoDB agent skills (Atlas, schema, query, search) |
| [redis/agent-skills](https://github.com/redis/agent-skills) | 171 | 2026-10-27 | Redis' official collection of agent skills |
| [neondatabase/agent-skills](https://github.com/neondatabase/agent-skills) | 109 | 2026-10-30 | Neon Postgres skills |
| [google/skills](https://github.com/google/skills) | 21,779 | 2026-11-01 | Agent Skills for Google products and technologies |
| [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) | 56,637 | 2026-09-14 | Cloudflare's multi-phase security-audit skill with verified findings |
| [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | 259,593 | 2026-11-02 | Hermes Agent with built-in SKILL.md support |
| [NousResearch/hermes-official-plugins](https://github.com/NousResearch/hermes-official-plugins) | 569 | 2026-11-02 | Nous Research's official first-party plugins for Hermes Agent (plugin catalog) |
| [android/skills](https://github.com/android/skills) | 10,259 | 2026-10-29 | Android's official Agent Skills (SKILL.md) based on developer.android.com guidance |
| [Tencent/BrowserSkill](https://github.com/Tencent/BrowserSkill) | 9,903 | 2026-11-02 | Tencent's CLI + extension that lets agents use your real, logged-in browser |
| [dotnet/skills](https://github.com/dotnet/skills) | 5,792 | 2026-11-02 | Microsoft .NET team's skills for .NET and C# (100+ SKILL.md) |
| [BuilderIO/skills](https://github.com/BuilderIO/skills) | 4,627 | 2026-10-28 | Builder.io's small, composable agent skills (`npx @agent-native/skills`) |
| [apify/agent-skills](https://github.com/apify/agent-skills) | 2,481 | 2026-10-30 | Apify's agent skills for web scraping and Actors |
| [WordPress/agent-skills](https://github.com/WordPress/agent-skills) | 2,320 | 2026-10-26 | WordPress' official skills (blocks, themes, plugins, best practices) |
| [Kotlin/kotlin-agent-skills](https://github.com/Kotlin/kotlin-agent-skills) | 1,104 | 2026-10-30 | JetBrains/Kotlin agent skills for Kotlin projects |
| [laravel/agent-skills](https://github.com/laravel/agent-skills) | 733 | 2026-10-29 | Laravel's official agent skills |
| [elastic/agent-skills](https://github.com/elastic/agent-skills) | 603 | 2026-10-29 | Elastic's official skills (50+ SKILL.md) |
| [ClickHouse/agent-skills](https://github.com/ClickHouse/agent-skills) | 565 | 2026-10-30 | Official skills for ClickHouse and ClickHouse Cloud |
| [google/elephant-goldfish-model](https://github.com/google/elephant-goldfish-model) | 9,375 | 2026-11-01 | Google's Elephant-Goldfish Model plugin/skills: deep-context agent drafts specs, zero-context subagents review them |
| [google-deepmind/science-skills](https://github.com/google-deepmind/science-skills) | 3,378 | 2026-10-23 | Google DeepMind's science skills for grounded, token-efficient agentic scientific workflows |
| [typesafe-ai/skills](https://github.com/typesafe-ai/skills) | 2,863 | 2026-10-23 | TypeSafe's official skill/Claude Code plugin for its System One API (typed decisions, e.g. Jev) |
| [EpicGames/unreal-engine-skills-for-claude-code-plugin](https://github.com/EpicGames/unreal-engine-skills-for-claude-code-plugin) | 1,858 | 2026-10-27 | Epic Games' Claude Code plugin: `unreal-mcp` skill plus hooks to drive Unreal Editor via MCP |
| [MicrosoftDocs/Agent-Skills](https://github.com/MicrosoftDocs/Agent-Skills) | 804 | 2026-11-02 | Microsoft Learn's curated skills for Microsoft and Azure services |
| [dbt-labs/dbt-agent-skills](https://github.com/dbt-labs/dbt-agent-skills) | 750 | 2026-10-29 | dbt Labs' official skills for working with dbt projects |
| [TheQtCompanyRnD/agent-skills](https://github.com/TheQtCompanyRnD/agent-skills) | 521 | 2026-10-20 | The Qt Company's official Qt/QML skills (Claude Code, Codex, Copilot, Gemini) |
| [databricks/databricks-agent-skills](https://github.com/databricks/databricks-agent-skills) | 380 | 2026-11-01 | Databricks' skills and plugins for Claude Code, Cursor and Codex |

## 2. Large community collections

| Repo | ★ | Updated | Description |
|---|---:|---|---|
| [obra/superpowers](https://github.com/obra/superpowers) | 310,794 | 2026-10-29 | Skills framework and development methodology (brainstorming, TDD, debugging) |
| [mattpocock/skills](https://github.com/mattpocock/skills) | 309,454 | 2026-11-01 | Engineering skills; most-installed source on skills.sh |
| [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | 143,939 | 2026-11-01 | UI/UX design skill for many agents |
| [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) | 116,772 | 2026-11-02 | Token-saving skill plus proxy |
| [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | 112,616 | 2026-11-01 | Production-grade engineering skills |
| [nexu-io/open-design](https://github.com/nexu-io/open-design) | 105,404 | 2026-11-02 | Open-source design plugin/harness with a large SKILL.md library (prototypes, landing pages, slides) |
| [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | 108,057 | 2026-10-31 | Design-taste skills against generic "AI slop" |
| [tt-a1i/archify](https://github.com/tt-a1i/archify) | 92,509 | 2026-11-02 | Agent skill that turns ideas or codebases into interactive architecture diagrams |
| [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | 99,684 | 2026-11-01 | Design-language skill |
| [career-ops-hq/career-ops](https://github.com/career-ops-hq/career-ops) | 79,353 | 2026-11-02 | AI job-search agent skills: board scan, CV scoring, resume/cover letters, interview prep |
| [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | 64,100 | 2026-11-01 | Editorial diagram-design skill (44 types, HTML/SVG) for Claude Code, Codex, Cursor, Copilot |
| [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) | 57,916 | 2026-10-31 | Marketing, CRO and SEO skills |
| [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | 55,722 | 2026-10-26 | Large library of science skills |
| [Yuan1z0825/nature-skills](https://github.com/Yuan1z0825/nature-skills) | 51,768 | 2026-11-02 | Academic/research skills for Nature-style writing, figures and literature search |
| [emilkowalski/skills](https://github.com/emilkowalski/skills) | 52,812 | 2026-10-28 | Skills for designers and engineers |
| [wshobson/agents](https://github.com/wshobson/agents) | 42,092 | 2026-11-02 | Plugin marketplace for Claude Code, Codex, Cursor, OpenCode and Copilot |
| [virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill) | 36,729 | 2026-10-28 | Turns technical book PDFs into ready-to-use Claude Code skills |
| [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) | 29,143 | 2026-10-31 | 380+ skills, agents and commands |
| [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) | 27,817 | 2026-10-30 | Persistent file-based planning for coding agents (crash-proof plans, session recovery) |
| [phuryn/pm-skills](https://github.com/phuryn/pm-skills) | 27,611 | 2026-10-29 | 100+ product-management skills |
| [JimLiu/baoyu-skills](https://github.com/JimLiu/baoyu-skills) | 27,173 | 2026-11-01 | Popular Chinese skills collection |
| [EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin) | 25,841 | 2026-11-02 | Compound Engineering plugin (Claude Code, Codex, Cursor) |
| [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) | 23,868 | 2026-10-18 | Skill that builds interactive isometric illustrations of machines and systems (SVG, WebGL, 3D) |
| [Orchestra-Research/AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs) | 14,188 | 2026-10-11 | AI research and ML-engineering skills |
| [Jeffallan/claude-skills](https://github.com/Jeffallan/claude-skills) | 12,172 | 2026-10-30 | 67 full-stack skills |
| [alchaincyf/huashu-design](https://github.com/alchaincyf/huashu-design) | 28,434 | 2026-10-30 | HTML-native design skill: web/app prototypes, editable PPTX, animation, infographics (Chinese/English) |
| [titanwings/distilly](https://github.com/titanwings/distilly) | 26,293 | 2026-10-13 | Distills how people think into reusable skills (formerly Colleague Skill) |
| [rehan-remade/universal-modder](https://github.com/rehan-remade/universal-modder) | 9,324 | 2026-11-02 | Skills, tools and knowledge base that let coding agents mod almost any PC game (with fal MCP) |
| [alchaincyf/huashu-art-motion](https://github.com/alchaincyf/huashu-art-motion) | 5,946 | 2026-10-16 | Art-animation skill: 35+ art styles and 9 narration grammars rendered in code (Chinese/English) |
| [Mindrally/skills](https://github.com/Mindrally/skills) | 289 | 2026-10-08 | 255+ skills converted from Cursor rules |
| [Jahrome907/minecraft-agent-skills](https://github.com/Jahrome907/minecraft-agent-skills) | 197 | 2026-10-30 | Minecraft modding/server skills for Codex and Claude Code |
| [affaan-m/ECC](https://github.com/affaan-m/ECC) | 294,971 | 2026-11-02 | Agent harness system (formerly everything-claude-code): skills, memory, security |
| [garrytan/gstack](https://github.com/garrytan/gstack) | 138,618 | 2026-11-02 | Garry Tan's Claude Code setup: opinionated role skills (CEO, designer, eng manager, QA) |
| [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) | 66,291 | 2026-11-01 | Research skill across Reddit, X, YouTube, HN and the web |
| [blader/humanizer](https://github.com/blader/humanizer) | 63,633 | 2026-10-28 | Skill that removes signs of AI-generated writing |
| [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd) | 59,724 | 2026-10-19 | Skill that keeps agent answers short and ADHD-friendly (stops burying the answer) |
| [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) | 50,590 | 2026-09-15 | Obsidian skills (CLI, Markdown, Bases, Canvas) from Obsidian's CEO |
| [gamedev-skills/awesome-gamedev-agent-skills](https://github.com/gamedev-skills/awesome-gamedev-agent-skills) | 6,495 | 2026-10-28 | 74 game-dev skills (Godot, Unity, Unreal, Phaser, three.js, Bevy) |
| [op7418/guizang-ppt-skill](https://github.com/op7418/guizang-ppt-skill) | 29,108 | 2026-10-30 | Skill for polished HTML slide decks (editorial magazine and Swiss layouts) |
| [KKKKhazix/khazix-skills](https://github.com/KKKKhazix/khazix-skills) | 21,808 | 2026-10-01 | Popular Chinese skills collection (goal-setting, writing, analysis) |
| [ConardLi/garden-skills](https://github.com/ConardLi/garden-skills) | 13,475 | 2026-10-25 | Skills for web design, knowledge retrieval and image generation |
| [Agents365-ai/drawio-skill](https://github.com/Agents365-ai/drawio-skill) | 10,511 | 2026-11-01 | Turns text, code, Terraform/K8s, SQL and API specs into draw.io diagrams |
| [ibelick/ui-skills](https://github.com/ibelick/ui-skills) | 10,469 | 2026-11-01 | UI skills for design engineers |
| [antfu/skills](https://github.com/antfu/skills) | 6,032 | 2026-10-30 | Anthony Fu's curated agent skills (Vue/Vite ecosystem) |

## 3. Awesome lists

| Repo | ★ | Updated | Description |
|---|---:|---|---|
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | 78,539 | 2026-09-18 | The biggest Claude Skills list |
| [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) | 57,073 | 2026-11-02 | Claude Code skills, hooks, commands and plugins |
| [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) | 53,500 | 2026-10-30 | 5,400+ OpenClaw skills, categorized |
| [sickn33/agentic-awesome-skills](https://github.com/sickn33/agentic-awesome-skills) | 49,008 | 2026-11-02 | Large skills catalog plus a local catalog tool |
| [PatrickJS/awesome-cursorrules](https://github.com/PatrickJS/awesome-cursorrules) | 41,084 | 2026-05-30 | The canonical Cursor rules list |
| [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) | 36,740 | 2026-11-02 | 1,000+ skills from official teams and the community |
| [composio-community/awesome-codex-skills](https://github.com/composio-community/awesome-codex-skills) | 17,170 | 2026-07-26 | Codex skills |
| [travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills) | 15,671 | 2026-04-28 | Claude Skills list (updates have slowed) |
| [BehiSecc/awesome-claude-skills](https://github.com/BehiSecc/awesome-claude-skills) | 10,333 | 2026-11-01 | Claude Skills list |
| [VoltAgent/awesome-codex-subagents](https://github.com/VoltAgent/awesome-codex-subagents) | 6,431 | 2026-11-02 | Curated list of 130+ specialized Codex subagents |
| [heilcheng/awesome-agent-skills](https://github.com/heilcheng/awesome-agent-skills) | 6,334 | 2026-11-02 | Tutorials and skill directories |
| [Prat011/awesome-llm-skills](https://github.com/Prat011/awesome-llm-skills) | 1,842 | 2026-07-14 | LLM and agent skills |
| [hashgraph-online/awesome-codex-plugins](https://github.com/hashgraph-online/awesome-codex-plugins) | 1,484 | 2026-11-02 | Codex plugins and skills |
| [ccplugins/awesome-claude-code-plugins](https://github.com/ccplugins/awesome-claude-code-plugins) | 992 | 2026-08-12 | Claude Code plugins |
| [spencerpauly/awesome-cursor-skills](https://github.com/spencerpauly/awesome-cursor-skills) | 873 | 2026-08-02 | Cursor skills |
| [ZeroPointRepo/awesome-hermes-skills](https://github.com/ZeroPointRepo/awesome-hermes-skills) | 656 | 2026-10-19 | Hermes Agent skills |
| [quemsah/awesome-claude-plugins](https://github.com/quemsah/awesome-claude-plugins) | 1,515 | 2026-11-01 | Automated index of Claude Code plugins with adoption metrics |
| [lawve-ai/awesome-legal-skills](https://github.com/lawve-ai/awesome-legal-skills) | 920 | 2026-10-19 | Agent Skills for legal work |
| [0xNyk/awesome-hermes-agent](https://github.com/0xNyk/awesome-hermes-agent) | 5,941 | 2026-10-27 | Independent directory of Hermes Agent skills, plugins, memory providers and tools |

## 4. Marketplaces and registries

| Site / repo | ★ | Updated | Description |
|---|---:|---|---|
| [skills.sh](https://skills.sh) | – | – | Vercel's skills directory with install leaderboard (`npx skills`) |
| [SkillsMP](https://skillsmp.com) | – | – | Aggregator claiming 3M+ skills from GitHub; REST API and MCP server |
| [Smithery skills](https://smithery.ai/skills) | – | – | Skill registry with install counts |
| [claude-plugins.dev](https://claude-plugins.dev) ([source](https://github.com/Kamalnrf/claude-plugins)) | 564 | 2026-10-26 | Registry plus `npx claude-plugins` CLI |
| [cursor.directory](https://cursor.directory) | – | – | Cursor plugins, rules and MCP servers |
| [ClawHub](https://clawhub.ai) ([openclaw/clawhub](https://github.com/openclaw/clawhub)) | 9,544 | 2026-11-02 | OpenClaw skill and plugin registry |
| [davepoon/buildwithclaude](https://github.com/davepoon/buildwithclaude) | 3,706 | 2026-11-01 | Hub for skills, plugins and marketplaces |
| [obra/superpowers-marketplace](https://github.com/obra/superpowers-marketplace) | 1,316 | 2026-10-21 | Curated Claude Code marketplace |
| [numman-ali/n-skills](https://github.com/numman-ali/n-skills) | 1,052 | 2026-09-12 | Curated marketplace (Claude Code, Codex, openskills) |
| [LinklyAI/best-skills](https://github.com/LinklyAI/best-skills) | 692 | 2026-11-02 | Daily Top 100 skills ranking |
| [trailofbits/skills-curated](https://github.com/trailofbits/skills-curated) | 523 | 2026-07-14 | Community-vetted marketplace |
| [skilld-dev/skilld](https://github.com/skilld-dev/skilld) | 329 | 2026-10-10 | Open-source alternative to skills.sh |
| [jeremylongshore/tons-of-skills-marketplace](https://github.com/jeremylongshore/tons-of-skills-marketplace) | 2,890 | 2026-11-02 | Model-agnostic skills marketplace with adapters for several agents |
| [tech-leads-club/agent-skills](https://github.com/tech-leads-club/agent-skills) | 7,122 | 2026-11-01 | Validated skill registry for coding agents (Claude Code, Cursor, Copilot, Antigravity) |
| [iflytek/skillhub](https://github.com/iflytek/skillhub) | 5,354 | 2026-11-02 | iFlytek's self-hosted enterprise skill registry: versioning, RBAC, audit logs, Docker/Kubernetes |

## 5. Tooling (spec, CLI, convert, validate, security)

| Repo | ★ | Updated | Description |
|---|---:|---|---|
| [vercel-labs/skills](https://github.com/vercel-labs/skills) | 37,682 | 2026-10-30 | `npx skills`, the open install CLI |
| [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) | 33,054 | 2026-11-02 | CLI to configure Claude Code (skills, agents, hooks) |
| [agentskills/agentskills](https://github.com/agentskills/agentskills) ([agentskills.io](https://agentskills.io)) | 26,634 | 2026-08-09 | Open Agent Skills spec plus `skills-ref validate`; ~50 supporting clients |
| [agentsmd/agents.md](https://github.com/agentsmd/agents.md) | 25,269 | 2026-09-10 | The AGENTS.md standard |
| [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) | 23,897 | 2026-11-02 | Security scanner for skills |
| [microsoft/SkillOpt](https://github.com/microsoft/SkillOpt) | 18,811 | 2026-11-01 | Optimizer/trainer for natural-language skills |
| [yusufkaraaslan/Skill_Seekers](https://github.com/yusufkaraaslan/Skill_Seekers) | 15,264 | 2026-09-30 | Turns docs sites, repos and PDFs into skills |
| [rebelytics/one-skill-to-rule-them-all](https://github.com/rebelytics/one-skill-to-rule-them-all) | 3,684 | 2026-10-28 | A skill that builds and improves your other skills |
| [intellectronica/ruler](https://github.com/intellectronica/ruler) | 2,956 | 2026-10-28 | Same rules for all coding agents |
| [cisco-ai-defense/skill-scanner](https://github.com/cisco-ai-defense/skill-scanner) | 2,680 | 2026-10-26 | Security scanner for skills |
| [rohitg00/skillkit](https://github.com/rohitg00/skillkit) | 1,568 | 2026-06-02 | Install, translate and share skills across agents |
| [dyoshikawa/rulesync](https://github.com/dyoshikawa/rulesync) | 1,577 | 2026-11-02 | Syncs rules and skills between agents |
| [jiweiyeah/Skills-Manager](https://github.com/jiweiyeah/Skills-Manager) | 1,052 | 2026-09-10 | Desktop app: write once, sync to 32 tools |
| [huggingface/upskill](https://github.com/huggingface/upskill) | 761 | 2026-10-27 | Generates and evaluates skills |
| [EverMind-AI/SkillCorpus](https://github.com/EverMind-AI/SkillCorpus) | 694 | 2026-10-29 | Turns SKILL.md files into a searchable corpus |
| [VikashLoomba/copilot-mcp](https://github.com/VikashLoomba/copilot-mcp) | 507 | 2026-06-15 | VS Code extension to find and install skills for Copilot |
| [K-Dense-AI/claude-skills-mcp](https://github.com/K-Dense-AI/claude-skills-mcp) | 411 | 2026-07-20 | MCP server for skill search |
| [VintLin/skill-flow](https://github.com/VintLin/skill-flow) | 264 | 2026-11-01 | Install and share skills across agents |
| [block/ai-rules](https://github.com/block/ai-rules) | 143 | 2026-05-11 | Manages rules and skills across agents |
| [microsoft/skill-recorder](https://github.com/microsoft/skill-recorder) | 5,641 | 2026-10-31 | Desktop app that records a work session and turns it into a reusable skill (Copilot SDK) |
| [cloudflare/agent-skills-discovery-rfc](https://github.com/cloudflare/agent-skills-discovery-rfc) | 366 | 2026-04-23 | Proposal for discovering Agent Skills via `.well-known` URIs (RFC 8615) |
| [refly-ai/refly](https://github.com/refly-ai/refly) | 7,546 | 2026-11-02 | Open-source visual builder for agent skills that run in Claude Code, Cursor and Codex |
| [benchflow-ai/skillsbench](https://github.com/benchflow-ai/skillsbench) | 1,889 | 2026-10-24 | Benchmark of how much skills help agents (dataset on Hugging Face below) |
| [Adyen/agent-marketplace](https://github.com/Adyen/agent-marketplace) | 87 | 2026-10-30 | Adyen's open-source CLI that installs shared skills, commands, subagents, hooks and MCP servers into each agent's format (released 2026-10-22) |

## 6. GitLab and Hugging Face

| Project | ★ / likes | Updated | Description |
|---|---:|---|---|
| [gitlab-org/ai/skills](https://gitlab.com/gitlab-org/ai/skills) | 47 | 2026-10-31 | GitLab's official skills; also a Claude Code marketplace. GitLab Duo supports SKILL.md natively ([docs](https://docs.gitlab.com/user/duo_agent_platform/customize/agent_skills/)) |
| [hf-skills](https://huggingface.co/hf-skills) | – | – | Hugging Face org with skill Spaces (skill-finder, llm-trainer); `hf skills add` installs from the Hub |
| [benchflow/skillsbench](https://huggingface.co/datasets/benchflow/skillsbench) | 18 | 2026-06-16 | Skills benchmark dataset |
| [open-index/open-skills](https://huggingface.co/datasets/open-index/open-skills) | 14 | 2026-04-10 | Archive of skills.sh |

## Flagged / excluded

- [wanghuan9/skilldock](https://github.com/wanghuan9/skilldock) (Desktop skill manager; last recorded 607★, pushed 2026-10-03): GitHub API and public repository URL returned HTTP 404 on 2026-10-12 and again on 2026-10-19, 2026-10-26 and 2026-11-02 (the owner account `wanghuan9` also returns 404). Moved here with owner approval; retained for source accounting, excluded from indexing until available again.
- [libukai/awesome-agent-skills](https://github.com/libukai/awesome-agent-skills) (Agent Skills guide, Chinese/English; last recorded 5,183★, pushed 2026-09-04): on 2026-10-26 the GitHub API returned 404 and the public URL redirects to `shikaijiaoyu/awesome-agent-skills`, which also returns 404 (still 404 on 2026-11-02). Removed from Awesome lists; will be restored if it becomes available again.
- [numman-ali/openskills](https://github.com/numman-ali/openskills) (Cross-agent skills loader; 10,817★, last push 2026-01-18): no push for 9+ months as of 2026-11-02; removed from Tooling. Will be restored if development resumes.
- skills.sh leaderboard entries with install counts far out of line with GitHub activity (e.g. `prime-skills/runcomfy-agent-skills`, `flowkit-labs/skills`, `lllllllama/RigorPilot-Skills`).
- Repos copying the `obra/superpowers` name (`101-skills/superpowers`, `qu-skills/superpowers`).
- `mukul975/Anthropic-Cybersecurity-Skills` (35.4k★): uses "Anthropic" in its name but is not from Anthropic.
- `DietrichGebert/ponytail` (182k★, single skill, unclear star origin) and `anbeime/skill` (points to an external store).
- `Jakeschincariol/*-skill` series (`replica-skill` 7.0k★, `day-trader-skill` 4.4k★, `instagram-agent-skill` 4.4k★, `youtube-agent-skill` 4.2k★, `linkedin-agent-skill` 3.0k★, `founder-skill` 2.3k★, `arena-skill` 1.2k★, `trader-skill` 1.1k★, plus 8 smaller ones): near-identical "Eleven free Claude skills" repos with few commits (checked 2026-11-02); stars out of line with substance.
- `morluto/rea` (419.9k★, created 2026-04-14): reverse-engineering tool tagged agent-skills; out of scope and star count out of line with age. `unclebob/ub-mode` (6.4k★, 4 commits, no description).
- Older than ~9 months: `flyeric0212/cursor-rules`, `ananddtyagi/cc-marketplace`.

> Before installing third-party skills, prefer official repos or run them through a scanner such as SkillSpector or cisco-ai-defense/skill-scanner.
