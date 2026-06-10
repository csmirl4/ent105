# ENT 105 — Creo Advisors Marketing Plan

A tactical marketing plan developed for **Creo Advisors**, a Boston-area private-equity
value-creation advisory firm, as the team project for **Tufts ENT 105 — "Marketing is
Everything"** (Derby Entrepreneurship Center, Prof. Jack Derby).

## The idea

Private equity's hottest play is the **"AI roll-up"** — buy fragmented, labor-heavy services
businesses and use AI to expand margin. The market is full of AI claims and short on AI proof,
which is the opening. The plan positions Creo as the **independent, buyer-side authority on what
AI can actually do in a deal**, under one thesis:

> **AI value is a map, not a multiplier.**

AI helps different business functions by wildly different amounts; the durable play is to
**amplify the people who run the business, not gut it**. Creo's lead product is a free, rigorous
**AI-Automatability Diagnostic** that draws PE buyers in and generates qualified leads.

## What's in this repo

Each document is provided as both LaTeX source (`.tex`) and a compiled `.pdf`.

| Document | What it is |
| --- | --- |
| **[`creo-ai-marketing-plan`](creo-ai-marketing-plan.pdf)** ([source](creo-ai-marketing-plan.tex)) | The core deliverable — the AI value-creation marketing plan ("a map, not a multiplier"; the AI-Automatability Diagnostic; positioning, personas, campaign, budget, KPIs). |
| **[`creo-marketing-collateral`](creo-marketing-collateral.pdf)** ([source](creo-marketing-collateral.tex)) | Ready-to-use sample assets: positioning statement, messaging house, taglines, product/sell-sheet description, lead-magnet copy, website hero, sample LinkedIn posts, and a nurture email. |
| **[`discovery-meeting-questions`](discovery-meeting-questions.pdf)** ([source](discovery-meeting-questions.tex)) | A structured question list for the client discovery meeting — locking the objective and testing appetite for the AI direction. |
| **[`creo-advisors-market-analysis`](creo-advisors-market-analysis.pdf)** ([source](creo-advisors-market-analysis.tex)) | A market, competitive, and strategic analysis (deep, cited, adversarially-verified research): the competitive landscape, credence-good economics, 2026 demand data, and competitor go-to-market playbooks. |
| **[`ideal-boutique-benchmark`](ideal-boutique-benchmark.pdf)** ([source](ideal-boutique-benchmark.tex)) | A normative "ideal PE value-creation boutique" archetype, and a benchmark of Creo against it — turning the gaps into a roadmap of opportunities. |
| **[`value-creation-bridge`](value-creation-bridge.pdf)** (+ [`-guide`](value-creation-bridge-guide.pdf)) ([source](value-creation-bridge.tex), [guide source](value-creation-bridge-guide.tex)) | A value-creation measurement methodology that separates real operational value *created* from value merely *transferred* — one-pager plus a practitioner's guide. |
| **[`synergy-reality-test`](synergy-reality-test.pdf)** (+ [`-guide`](synergy-reality-test-guide.pdf)) ([source](synergy-reality-test.tex), [guide source](synergy-reality-test-guide.tex)) | A roll-up methodology that splits projected synergy into *durable* vs. *fragile* — one-pager plus guide. |
| **[`presentation-prep`](presentation-prep.pdf)** ([source](presentation-prep.tex)) | The team's run-of-show, speaker split, reveal discipline, and Q&A playbook for the final presentation. |
| **[`ENT 105 … Syllabus … .pdf`](<ENT 105 Marketing Fall Syllabus 1.0  05242026.pdf>)** | The course syllabus, for reference. |

## Where to start

1. **[`creo-ai-marketing-plan`](creo-ai-marketing-plan.pdf)** — the plan itself.
2. **[`creo-marketing-collateral`](creo-marketing-collateral.pdf)** — what the plan looks like as real marketing copy.
3. **[`creo-advisors-market-analysis`](creo-advisors-market-analysis.pdf)** and
   **[`ideal-boutique-benchmark`](ideal-boutique-benchmark.pdf)** — the research and
   strategy behind the plan.
4. The methodology one-pagers and the presentation prep round out the package.

## Building the PDFs

The compiled PDFs are committed, so you can read everything without building. To rebuild a
document from source:

```bash
pdflatex <document>.tex      # run twice for documents with a table of contents
```

A standard TeX distribution (e.g. TeX Live / MacTeX) is all that's required; build artifacts
(`.aux`, `.log`, `.out`, `.toc`, …) are git-ignored.

## Team

ENT 105 — Creo Advisors group: **Connor Smirl, Fiona Smirl, Luke Hotra, Laura Iorini, and
Heaven Oliva**.

## About the client

[Creo Advisors](https://creoadvisorsllc.com/) is a boutique strategy and value-creation
advisory firm serving private-equity sponsors, boards, and PE-backed portfolio companies.

---

*Prepared by the ENT 105 student team for Creo Advisors. Figures and timelines are illustrative
and to be finalized with the client.*
