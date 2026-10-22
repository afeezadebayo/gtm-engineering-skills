# GTM Engineering — SKILL.md files for AI agents

[![13 skills](https://img.shields.io/badge/skills-13-0b7285)](#whats-inside)
[![Format: Agent Skills](https://img.shields.io/badge/format-SKILL.md-5f3dc4)](https://agentskills.io/specification)
[![Works with Claude Code & Codex](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Codex%20%7C%20Claude.ai-1c7ed6)](#install)
[![Licence: CC BY 4.0](https://img.shields.io/badge/licence-CC%20BY%204.0-2b8a3e)](https://creativecommons.org/licenses/by/4.0/)

Free, ready-to-run **GTM engineering** skills for **Claude, Claude Code, OpenAI Codex** and any agent that reads
the [Agent Skills](https://agentskills.io/specification) format. Clay table design, enrichment waterfalls, ICP
and account scoring, signal-based outbound, AI copy columns, data cleaning, CRM sync and routing, outbound
infrastructure, workflow QA, documentation, cost control and reporting. Each skill is a single `SKILL.md`: a senior
practitioner's workflow — when to use it, the inputs to ask for, a numbered process, decision rules, an output
template and sources — loaded only when a task needs it.

Part of the [Marketing Skills library](https://github.com/afeezadebayo/marketing-skills) by
[Afeez Adebayo](https://afeezadebayo.com) · [Browse online](https://afeezadebayo.com/skills-md/marketing/gtm-engineering/)

## Install

Each skill is its own folder with a `SKILL.md`, so you can drop any folder straight into an agent.

**Claude Code**
```bash
git clone https://github.com/afeezadebayo/gtm-engineering-skills.git
cp -r gtm-engineering-skills/gtm-engineering-audit ~/.claude/skills/        # all projects
# or  .claude/skills/   inside one project
```

**OpenAI Codex**
```bash
cp -r gtm-engineering-skills/gtm-engineering-audit ~/.agents/skills/         # all repos
```

**Claude.ai / Desktop** — zip a skill folder, then **Settings → Capabilities → Skills → Upload skill**
(code execution must be enabled). To bulk-load the whole category into a Claude Project, custom GPT or
knowledge base, grab the single-folder `.zip` from the
[library page](https://afeezadebayo.com/skills-md/marketing/gtm-engineering/).

Then start a new session and ask your agent which skills it can use.

## What's inside

| Skill | What it does |
|---|---|
| [`gtm-engineering-audit`](gtm-engineering-audit/SKILL.md) | Audit a GTM engineering stack end to end, with a funnel, scorecard and 90-day plan. The entry point. |
| [`clay-table-design`](clay-table-design/SKILL.md) | Design Clay and similar GTM tables that are cheap, fast and debuggable, with staged columns. |
| [`enrichment-waterfalls`](enrichment-waterfalls/SKILL.md) | Design enrichment waterfalls for emails, phones and company data ordered by cost per valid result. |
| [`icp-account-scoring`](icp-account-scoring/SKILL.md) | Score accounts and contacts: fit, timing and tiers validated against won and lost deals. |
| [`signal-based-outbound`](signal-based-outbound/SKILL.md) | Run outbound on buying signals with a play library, freshness decay and non-creepy openers. |
| [`ai-copy-columns`](ai-copy-columns/SKILL.md) | Design AI copy columns for outbound with rules, fallbacks, scoring and QA against invented facts. |
| [`data-deduplication-normalisation`](data-deduplication-normalisation/SKILL.md) | Clean GTM data: normalisation rules, company and contact matching, merge rules, CRM lookups. |
| [`crm-sync-routing`](crm-sync-routing/SKILL.md) | Sync GTM tables to CRMs and sequencers safely: field mapping, ownership, routing, suppression. |
| [`outbound-infrastructure`](outbound-infrastructure/SKILL.md) | Set up cold outbound infrastructure: domains, mailboxes, authentication, warm-up, deliverability. |
| [`gtm-workflow-qa`](gtm-workflow-qa/SKILL.md) | QA every row of a GTM table against a written spec before sending or syncing, with Claude Code scripts. |
| [`gtm-workflow-documentation`](gtm-workflow-documentation/SKILL.md) | Document GTM workflows so others can run and debug them: specs, dictionaries, runbooks, handovers. |
| [`gtm-cost-control`](gtm-cost-control/SKILL.md) | Control GTM engineering costs with a ledger, unit costs per meeting and a waste checklist. |
| [`gtm-reporting`](gtm-reporting/SKILL.md) | Report GTM results from source to revenue, with attribution by segment, signal and copy version. |

## How these skills work

Agents use *progressive disclosure*: they read each skill's `name` and `description` (~100 tokens) at the start
of a session and load the full `SKILL.md` only when your request matches — so you can install many without
filling the context window.

## Author & licence

By [**Afeez Adebayo**](https://afeezadebayo.com) — Marketing, SEO & Growth (SEO & Organic Growth at Grey, YC W22).
[LinkedIn](https://www.linkedin.com/in/afeez-adebayo/) · [X](https://x.com/za_icon) · [Newsletter](https://afeezadebayo.com/newsletter/)

Released under [**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/) — use, share and adapt, including
commercially, with credit to Afeez Adebayo and a link to the source page in each file.

<sub>Keywords: GTM engineering skills, SKILL.md, Agent Skills, Claude skills, Claude Code skills, Codex skills, AI
agent skills, Clay, outbound automation, enrichment waterfalls, ICP scoring, account scoring, signal-based
outbound, AI personalisation, CRM sync, cold email infrastructure, deliverability, workflow QA, GTM reporting.</sub>
