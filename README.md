<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <img src="assets/hero-light.svg" width="1280" alt="Physiotherapy &amp; Clinical Skills — clear questions, repeatable workflows, reviewable results">
</picture>

# Physiotherapy & Clinical Skills

[English](README.md) · [Türkçe](README.tr.md)

![Edition](https://img.shields.io/badge/edition-2026.10.14-0f6e8c) [![Validate](https://github.com/yigityildiz0/physiotherapy-clinical-skills/actions/workflows/validate.yml/badge.svg)](https://github.com/yigityildiz0/physiotherapy-clinical-skills/actions/workflows/validate.yml) [![Release](https://img.shields.io/github/v/release/yigityildiz0/physiotherapy-clinical-skills?display_name=tag&sort=date)](https://github.com/yigityildiz0/physiotherapy-clinical-skills/releases/latest) ![Skills](https://img.shields.io/badge/skills-5-b0303f) ![Languages](https://img.shields.io/badge/EN%20%2B%20TR-guides-e0a43a)

**Clinical reasoning, rehabilitation evidence, study support and crisis response workflows.**

5 maintained entry points. Choose one for the job; do not load the entire library into context.

[Start here](docs/INSTALL.md) · [Browse the catalog](https://yigityildiz0.github.io/universal-ai-skill-library/) · [Downloads](DOWNLOADS.md) · [Maintenance model](MAINTAINING.md)

## New in 2026.10.14

- **presentation-studio** (new): complete editable PowerPoint decks — course rules as defaults, slide plan, real licensed photos, JS and Python deck kits, timed speaker notes with pronunciations, PowerPoint render QA, `pptx_audit.py` and a pre-talk reading guide.
- `slides` is renamed **html-slides** and only handles browser decks; PowerPoint requests route to presentation-studio.
- academic-study-coach, office-docs-qa, design and design-system now hand deck building to presentation-studio (fixes a broken PPTX QA link).
- Gemini packages (CLI folders and filtered Gemini app uploads), an installation table for every app and a real GitHub Release with SHA-256 checksums.

## Works with

| App | Package |
|---|---|
| Claude Code | portable folder → ~/.claude/skills |
| Claude.ai | one upload ZIP per skill |
| Codex / ChatGPT desktop | Codex.zip → ~/.codex/skills |
| ChatGPT web | plugin ZIP where the account offers import |
| Gemini CLI / app | ~/.gemini/skills · Skills upload (filtered copy) |
| OpenCode · DeepSeek Harness | portable folder + skills path |

Step-by-step: [Installation](docs/INSTALL.md). A file on disk is not proof of activation; test with one example request.

## Start with the work you want to do

<details open>
<summary><strong>Learn & write</strong> · 1</summary>

| Skill | What it helps with |
|---|---|
| [academic-study-coach](docs/skills/academic-study-coach.en.md) | Turn course material into a study plan, active recall and literature-reading practice. |

</details>

<details open>
<summary><strong>Design & create</strong> · 1</summary>

| Skill | What it helps with |
|---|---|
| [presentation-studio](docs/skills/presentation-studio.en.md) | Make complete, editable PowerPoint decks: course rules as defaults, slide plan, real licensed photos, a design kit, timed speaker notes with pronunciations, rendered QA and an audit. |

</details>

<details open>
<summary><strong>Health & rehabilitation</strong> · 3</summary>

| Skill | What it helps with |
|---|---|
| [medical-evidence-research](docs/skills/medical-evidence-research.en.md) | Search, appraise and synthesize medical evidence, including rehabilitation and Türkiye applicability. |
| [mental-health-crisis-support](docs/skills/mental-health-crisis-support.en.md) | Support a calm, safety-oriented response to mental-health crisis signals. |
| [physio-clinical-copilot](docs/skills/physio-clinical-copilot.en.md) | Support clinician-reviewed rehabilitation reasoning, assessment and draft planning. |

</details>

## What happens when a skill runs?

~~~mermaid
flowchart LR
 A[Your goal] --> B[Match the skill]
 B --> C[Load relevant module]
 C --> D[Use available tools]
 D --> E[Verify and explain]
~~~

This is the workflow, not a claim that tools ran or every result is verified. Each skill page explains an example request, trigger, mechanics, inputs/outputs and source modules.

## One source. Durable collections.

The canonical source is [Universal AI Skill Library](https://github.com/yigityildiz0/universal-ai-skill-library). Domain repositories are selected views of the same release—not independently edited forks. Existing links and history stay intact.

[All collections / Tüm koleksiyonlar](COLLECTIONS.md) · [Legacy/community resources](LEGACY.md) · [Licenses & provenance](docs/LICENSE-SCOPE.md)

## Honest scope

- Installing a skill does not train a model or connect an account/tool.
- Local files and a web-account import are different; follow the supported host flow.
- No automatic extra billed API or model download.
- The historical community catalog is not counted as maintained or claimed as runtime-tested.
- Source licenses remain attached; no blanket third-party license is assumed.

---
Maintained by [Yigit Yildiz](https://github.com/yigityildiz0) · Source edition 2026.10.14
