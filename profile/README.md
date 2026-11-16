# CUHK Business School AI Initiatives

**Research · Teaching · Entrepreneurship**

CUHK Business School AI Initiatives brings together two parallel areas at [CUHK Business School](https://www.bschool.cuhk.edu.hk/): the established **CUHK Business School Tony Song AI Hub for Business**, responsible for research support and high-performance computing (HPC), and the proposed **AI-powered Business Education & Entrepreneurship** area, covering enterprise training and applications, entrepreneurship, and teaching support.

The two areas exchange reusable tools, code templates, methods, cases, and workflows. This page provides a common entry point to their resources and projects.

## Scope of CUHK Business School AI Initiatives

| Area | Scope |
| --- | --- |
| **CUHK Business School Tony Song AI Hub for Business** — established | Research infrastructure and HPC/GPU operations, research model/API access, research engineering, and academic exchange for faculty members and research postgraduate students. |
| **AI-powered Business Education & Entrepreneurship** — proposed | Non-degree enterprise training, applied AI projects and solutions, support for entrepreneurs including one-person companies (OPCs), and selected course upgrades using shared tools and cases. |

## Start here

| If you want to… | Go to |
| --- | --- |
| Use the faculty HPC cluster | [`ai_hub_HPC_user_guide`](https://github.com/CUHK-Business-School-AI-Hub/ai_hub_HPC_user_guide) |
| Run a first GPU example | [`AI_Hub_showcases`](https://github.com/CUHK-Business-School-AI-Hub/AI_Hub_showcases) |
| Join faculty/staff knowledge sharing | [`AI-Frontiers-Learn-Share-and-Apply`](https://github.com/CUHK-Business-School-AI-Hub/AI-Frontiers-Learn-Share-and-Apply) |
| Audit and rebuild a lecture you already teach | [`Blickwechsel`](https://github.com/CUHK-Business-School-AI-Hub/Blickwechsel) |
| Turn materials or a learning goal into a Socratic course | [`Quaestio-Socratica`](https://github.com/CUHK-Business-School-AI-Hub/Quaestio-Socratica) |
| Capture how work is actually done, as an SOP or agent playbook | [`waymark`](https://github.com/CUHK-Business-School-AI-Hub/waymark) |
| Turn a product idea into a plan an agent can implement | [`coding_agent_constitution`](https://github.com/CUHK-Business-School-AI-Hub/coding_agent_constitution) |
| Check whether a small product is ready for a limited launch | [`coding_agent_autoQA`](https://github.com/CUHK-Business-School-AI-Hub/coding_agent_autoQA) |

## Repository map

### CUHK Business School Tony Song AI Hub for Business

Research support combines computing resources, model access, and research engineering. Dedicated research repositories will be listed here as they are released.

#### Research infrastructure and onboarding

- [`ai_hub_HPC_user_guide`](https://github.com/CUHK-Business-School-AI-Hub/ai_hub_HPC_user_guide) — Account application, SSH/VS Code login, modules and Conda, Slurm jobs, and resource policy for the CUHK Business School Tony Song AI Hub for Business HPC cluster.
- [`AI_Hub_showcases`](https://github.com/CUHK-Business-School-AI-Hub/AI_Hub_showcases) — Runnable GPU cases on the cluster: review sentiment classification, bank marketing, Qwen inference, and a short guide video.

### AI-powered Business Education & Entrepreneurship

The following teaching resources, enterprise projects, and entrepreneurship tools form an existing foundation for this proposed area. Reusable outputs can also support research onboarding and other activities across CUHK Business School AI Initiatives.

#### Teaching, faculty development & knowledge sharing

**Open**

- [`AI-Frontiers-Learn-Share-and-Apply`](https://github.com/CUHK-Business-School-AI-Hub/AI-Frontiers-Learn-Share-and-Apply) — Monthly internal series for faculty and staff: try tools, share practice, and apply AI in research, teaching, and everyday work. Session pages: [GitHub Pages](https://cuhk-business-school-ai-hub.github.io/AI-Frontiers-Learn-Share-and-Apply/). Next session: 27 October 2026, *Using AI in Teaching: Reviewing Materials and Guiding Students*.
- [`Blickwechsel`](https://github.com/CUHK-Business-School-AI-Hub/Blickwechsel) — A Claude skill (`teaching-with-ai`) that audits an existing lecture from the student’s seat, then rebuilds activities, rotatable datasets, and the slide file itself. It measures first, labels guesses, and leaves the teaching decisions with you.
- [`Quaestio-Socratica`](https://github.com/CUHK-Business-School-AI-Hub/Quaestio-Socratica) — Builds a checkpoint-based Socratic course from source materials or a learning goal. The mentor asks rather than lectures; progress is saved, and the learner leaves with personal notes and a mindmap.

#### Enterprise training & applied AI projects

**Restricted**

- [`SME_training`](https://github.com/CUHK-Business-School-AI-Hub/SME_training) — Two-day corporate programme on agent-native work: from chat tools to agents, BRICK practice, and how a team hands work over. Pitch, slides, and instructor notes. *(Restricted access.)*
- [`Ronghua`](https://github.com/CUHK-Business-School-AI-Hub/Ronghua) — Industry collaboration: an agent workspace for reviewing procurement contracts against templates and producing revision packs. *(Restricted access.)*
- [`TaoYuanWeiYe`](https://github.com/CUHK-Business-School-AI-Hub/TaoYuanWeiYe) — Industry collaboration: an enterprise AI-transformation case with a cross-border e-commerce operator, including training/coaching methods and replenishment implementations. *(Restricted access.)*

#### Entrepreneurship & one-person companies

Public skills are designed to be used in sequence. Clarify the work with Waymark, turn the idea into a bounded plan with Constitution, then check launch readiness with AutoQA.

- [`waymark`](https://github.com/CUHK-Business-School-AI-Hub/waymark) — Interview-style skill that turns tacit operational knowledge into a human SOP, an agent playbook, or both. Adapted from `grill-me` for non-technical staff and operators.
- [`coding_agent_constitution`](https://github.com/CUHK-Business-School-AI-Hub/coding_agent_constitution) — Skill for Codex, Cursor, and Claude Code. Writes durable specs, architecture, rules, contracts, and small implementation tasks before the agent starts building.
- [`coding_agent_autoQA`](https://github.com/CUHK-Business-School-AI-Hub/coding_agent_autoQA) — Companion skill that checks an implemented product against those constitution documents, repairs defects it can fix, and tells a non-technical owner whether a limited first launch is justified.

**Restricted**

- [`BRICK`](https://github.com/CUHK-Business-School-AI-Hub/BRICK) — Bounded, Reviewable, Iterative Construction Kit: turn a way of working into a tool an agent can run and a person can review. Used in teaching and in industry cases. *(Restricted access.)*
- [`AgentDesk`](https://github.com/CUHK-Business-School-AI-Hub/AgentDesk) — Local app skeleton: take a finished product design, swap in one business module and UI, and reuse local run, check, history, and export. *(Restricted access.)*

---

Collaboration repositories marked *restricted* require access authorization for the relevant repository. Public tools and session pages are available through the links above.
