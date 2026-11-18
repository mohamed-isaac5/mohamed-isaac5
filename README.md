# Mohamed Isaac

**I build the systems that turn buying signals into pipeline.**

GTM Engineer based in Cairo, Egypt. I design and ship outbound infrastructure: signal detection, enrichment waterfalls, AI lead scoring, and CRM sync - the unglamorous plumbing that decides whether a sales team talks to the right company at the right moment, or burns its domain on the wrong one.

## What I build

- **Signal-driven outbound systems** - watch target accounts for hiring, funding and leadership signals, score them on timing and fit, and trigger outreach only when the moment is right. No spray and pray.
- **Enrichment waterfalls** - multi-provider contact enrichment with dedup-before-enrich, conditional gating and verification, engineered for cost per verified lead, not vanity coverage.
- **AI scoring and personalization** - LLM scoring against a documented ICP rubric, with structured outputs and evidence gates: the model never writes on empty data.
- **Revenue operations automation** - inbound-to-CRM pipelines with idempotent upserts, dedupe, and routing that gets a hot lead to a human in minutes.

## Stack

`Clay` `Apollo` `Smartlead` `Instantly` `n8n` `Make` `Claude Code` `Codex` `Grok`

## Selected work

- **[signal-outbound-engine](https://github.com/mohamed-isaac5/signal-outbound-engine)** - live: end-to-end signal-driven outbound engine in Python. Hiring + funding signal capture, an explainable scoring model with a published ICP formula, a cost-ordered enrichment waterfall, offline-first drafting with a named human approval gate, a full audit trail, and Smartlead/Instantly-ready export. 206 tests, mutation-tested, CI on every commit.
- **[campaign-reply-agent](https://github.com/mohamed-isaac5/campaign-reply-agent)** - local-first review queue for high-volume campaign replies: full conversation context in view, deterministic drafting with an optional LLM, a human approval gate on the exact words, cross-campaign stop handling, and durable receipts with a full audit trail. 153 tests plus a Playwright acceptance suite. Runs in offline simulation with fictional data; not yet live-tested against real Gmail or a model API.
- **[inbound-lead-agent](https://github.com/mohamed-isaac5/inbound-lead-agent)** - inbound lead qualification agent: form + GoHighLevel webhook intake (signature-verified), consent-first gating, rules-first scoring where every fact keeps its source quote, a human review queue, a follow-up scheduler, and hot-lead handoff cards with SLA. 210 tests. Local demo in offline simulation; not yet live-tested against real GoHighLevel, Gmail or an AI model.
- **[Prospect Brief Copilot](https://pz8jti7kyb8s.run.agentplace.io/)** - published AI agent (built on Agentplace): give it your company URL, then target companies one by one. Returns a fit verdict, real people from public sources, and three outreach messages with the best channel for each. Never invents emails or phone numbers.

Building next:

1. **gtm-agent-skills** - my GTM methodology as installable agent skills (Claude Code / Codex): ICP gating, signal building, enrichment waterfall, signal-tied outreach writing, deliverability pre-flight.
2. **deliverability-preflight** - a CLI + MCP tool that checks a sending domain before a campaign: SPF, DKIM, DMARC and warmup status in one command.

## Background

- Previously **Project Operations Coordinator at CellServe** (remote, US).
- **Google Project Management certified.**
- Open to GTM Engineering and Revenue Operations roles - remote, EMEA or US hours.

## Contact

- LinkedIn: [linkedin.com/in/mohamed-isaac](https://www.linkedin.com/in/mohamed-isaac)
