# An AI deal-sourcing platform, built by a non-engineer

**RTP Global · Investment Strategy &amp; Research Intern · Spring 2026**

I built and shipped an internal tool that turns a venture fund's fragmented deal data into a live, queryable engine for finding high-growth startups early — working solo, with AI-assisted development (Claude Code).

| | |
|---|---|
| **1** | solo non-engineer build |
| **4 → 1** | data sources unified |
| **40+** | emerging managers covered |

## Context

RTP Global is a global early-stage technology venture fund (about $1B in assets) that invests from Seed to Series A. Alongside its direct investing, its fund-of-funds arm backs 40+ emerging managers, which generates an enormous, constantly changing universe of portfolio companies to keep track of.

## The problem

Deal data lived in several disconnected systems. Surfacing interesting companies meant manual, cross-system lookups and a lot of tribal knowledge, so promising signals were easy to miss and hard to act on quickly. There was no consistent, queryable way for the investment team to ask "what should we be looking at right now?"

## What I built

An internal deal-sourcing intelligence platform that became the team's single source of truth for scouting startups. It pulls fragmented data into one place, keeps itself current automatically, and ranks companies so the most interesting ones rise to the top. I built it end to end as a solo non-engineer using AI-assisted development (Claude Code).

- **Unified data:** consolidated four previously siloed sources into a single, consistent database.
- **Always current:** scheduled pipelines refresh the data and flag week-over-week changes, so the team is alerted when a company shows a fundraising or growth signal.
- **Signal scoring:** a 0–100 model reads public signals (hiring patterns, technology footprint, and investor backing) to surface companies hitting an inflection before they are widely known.
- **Plain-English search:** non-technical associates can query the portfolio in natural language — a hybrid SQL + vector (RAG) backend with AI query planning — instead of waiting on a data pull.
- **Trustworthy by design:** entity resolution and automated data checks so the numbers leadership sees can be relied on.

## Impact

The platform replaced manual lookups with one queryable system and turned static, scattered records into an always-on sourcing engine, giving the team an earlier, more systematic read on which companies and which managers are generating the strongest deal flow.

## What I learned

The biggest takeaway is that a non-engineer who can think in systems can now ship real, production-grade software with AI in the loop. The hard parts were rarely the code: they were framing the right problem, designing signals that actually predict something useful, and treating data quality as a first-class feature rather than an afterthought. It is a preview of how operators, not just engineers, will build the next wave of internal tools.

---

> This is a sanitized overview shared with the firm's permission. Proprietary data, the specific scoring logic, and source code are intentionally omitted out of respect for confidentiality.

More of my work: [github.com/amankrai28](https://github.com/amankrai28) · [LinkedIn](https://linkedin.com/in/amakrai)
