# Hi, I'm Malebo Moleleki

**Analytics engineer working at the intersection of enterprise IT operations, data engineering and AI automation.**

I build pipelines that turn messy operational data into governed metrics, then put AI to work on top of them in ways that are safe to trust: read-only tools, guardrails that fail closed, evaluations against known answers and a human who approves before anything goes out.

My day-to-day is device-health analytics for a large enterprise Windows fleet. My portfolio uses fully synthetic data, with no employer data, code or business rules.

## How I work with AI

I treat AI as a capable collaborator that still needs a brief, boundaries and a test suite.

- **I own the decisions.** I write the brief, the metric definitions and the guardrails. AI implements to them and reports what it finds.
- **Governed access, not raw data.** Assistants answer through allowlisted, read-only tools that return aggregates with their definitions and data-quality caveats attached.
- **Evaluated, not assumed.** Answers are graded against an answer key, and the guardrails are tested, not just described.
- **Humans stay in the loop.** AI drafts; a named person reviews and approves. Nothing is acted on automatically.
- **Transparent.** I record what I decided and what AI built in every project.

## Featured project

### [Kestrel Device Intelligence](https://github.com/molelekimc/kestrel-device-intelligence) · [live demo](https://kestrel-control-room.onrender.com/)
*Enterprise device analytics with a governed AI assistant, for a fictional 18,000-device manufacturer.*

- **Medallion pipeline (DuckDB):** reconciles Intune, endpoint telemetry and a rollout tracker into Bronze, Silver and Gold layers. Every data-quality rule is logged and nothing is dropped silently.
- **MCP server for Claude:** 16 read-only fleet tools with small-group suppression, an identifier check that blocks the whole response, allowlisted inputs and a full audit log.
- **Weekly briefing automation:** Claude drafts the analyst briefing through the same governed tools, and a named reviewer approves it.
- **Evaluation harness:** 22 of 22 storyline questions pass the evidence tier; Silver layers match the answer key.
- **Business impact:** ties device health to production-line downtime, service-desk tickets and changes, with illustrative costs shown as ranges.
- **Live reporting app:** FastAPI and React/TypeScript with an "Ask the fleet" chat, a control room for plant managers, a TV mode for wall screens and freshness SLAs on every page. [Live demo](https://kestrel-control-room.onrender.com/).
- **Automation:** GitHub Actions rebuild the warehouse and run 290+ tests on every push, and every Monday they build the executive report and open the briefing for review.

## Toolkit

| Area | Tools |
|---|---|
| AI and automation | Claude, Model Context Protocol (MCP), LLM evaluation, GitHub Actions, prompt and tool design |
| Data engineering | Python, SQL, DuckDB, Azure Data Factory, Databricks, Microsoft Graph API |
| Analytics and BI | Power BI, DAX, metric design, data-quality monitoring |
| Apps | FastAPI, React, TypeScript |
| Domain | Windows endpoint management, Intune, device reliability telemetry |

## What I'm looking for

Analytics engineering, BI and AI-automation roles where reliable data and responsible AI matter.

[Connect with me on LinkedIn](https://www.linkedin.com/in/malebo-moleleki/)
