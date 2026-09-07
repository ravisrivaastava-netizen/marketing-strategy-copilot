# Marketing Strategy Copilot

**Marketing × Innovation × AI**

An AI-powered strategic challenger for Category Managers and Marketing Leaders.

The Copilot is designed to help marketing teams **diagnose the real business problem, identify growth opportunities, challenge weak thinking, prioritise strategic choices, and connect recommendations to commercial outcomes.**

> This repository is a portfolio prototype. All company, brand and dataset examples are fictional and created for demonstration/testing.

## The problem

Most marketing strategy work starts too quickly with solutions:

- Run a campaign
- Increase awareness
- Launch an innovation
- Improve distribution
- Cut price
- Increase media

The Copilot takes the opposite approach:

**Diagnose before prescribing.**

It explicitly separates:

**Symptom → Problem → Root Cause → Opportunity → Solution**

## Strategic philosophy

The framework is built around seven principles:

1. Nail the problem statement before touching a solution.
2. Diagnose before you prescribe.
3. Generate multiple hypotheses — MECE, not the first idea.
4. Prioritise causes by size and controllability.
5. Generate multiple solutions, not one favourite.
6. Decide against explicit criteria, then pilot before scaling.
7. Execute with named owners, leading indicators and a fixed review date.

A recommendation is not considered complete unless it can answer:

> **How does this make money?**

## Copilot modes

### BUILD
Generate a strategy from a business challenge.

### CHALLENGE
Stress-test an existing strategy, diagnosis, positioning or innovation idea.

### CO-CREATE
Work interactively with the marketer as a strategic thinking partner.

## Diagnostic hierarchy

The Copilot investigates:

**Consumer → Category → Brand → Consumer Occasion → Competition → Portfolio → Company Capabilities → Market Trends → Business/P&L → Channel → Pricing → Distribution**

The order is intentional: it prevents the model from jumping immediately to tactics.

## Growth opportunity engine

Potential growth levers include:

- Penetration
- Frequency
- Recruitment
- Retention
- Distribution
- Availability
- Pricing
- Pack-price architecture
- Premiumisation
- Portfolio expansion
- Occasion expansion
- New channels
- Geographic expansion
- Communication
- Innovation
- Consumer experience
- Partnerships
- E-commerce / Q-commerce

The engine should diagnose the constraint first rather than treating every lever as equally attractive.

## Strategic choice framework

Every strategy should answer:

### Where will we play?
Consumer, occasion, category, channel, geography and portfolio.

### How will we win?
Consumer insight, proposition, product, experience and execution.

### What will we NOT do?
Explicit trade-offs are mandatory.

### Why should the brand win?
Brand permission, distinctive assets and right-to-win.

### What evidence supports the choice?
Every major conclusion is tagged as evidence, inference or hypothesis.

## Positioning framework

> **For [target], who [tension/need], [Brand] is the [frame of reference] that [benefit] because [RTB] — unlike [competitive frame], which [gap].**

Two non-negotiables:

- **Single-mindedness:** a positioning cannot become a laundry list of benefits.
- **Evidence traceability:** insight and reason-to-believe must be distinguishable from AI inference.

AI-generated positioning remains a **hypothesis until validated**.

## Challenge Engine

The Copilot stress-tests strategy using:

1. Logo-swap test
2. Choice test
3. Trade-off test
4. Why test
5. Falsifiability test
6. Growth test
7. Insight test
8. Reverse-math test
9. Adaptability test
10. Ownership test

## Commercial engine

Every meaningful recommendation should attempt to connect:

**Consumer opportunity → Growth lever → Volume impact → Revenue impact → Margin impact → Investment required → Incremental contribution → ROI**

Where evidence is insufficient, the Copilot must say:

**DATA REQUIRED**

It must never fabricate commercial precision.

## Evidence system

- 🟢 **Evidence** — directly supported by available data.
- 🟡 **Inference** — reasoned interpretation of evidence.
- 🔴 **Hypothesis** — proposition requiring validation.

## MVP Case: Nectar Syrup

**Fictional company:** Nectar Foods India

**Hero brand:** Nectar Syrup

**Market:** India

**Challenge:**

> **Nectar Syrup has high brand awareness but low household penetration. Diagnose the underlying growth constraint and identify commercially viable growth opportunities for the next 12–18 months.**

The case deliberately contains conflicting signals:

- Awareness increases.
- Consideration increases.
- Distribution increases.
- Penetration remains relatively low.
- Revenue grows.
- Volume growth is less impressive.
- Gross-margin pressure emerges.
- Q-commerce grows rapidly.
- GT becomes less productive.
- Premium packs gain mix.
- Entry-pack momentum weakens.
- Media spend rises while recruitment efficiency does not improve proportionately.

The Copilot must determine **what is actually causing the growth constraint**, rather than accepting the obvious explanation.

## Dataset architecture

The synthetic dataset contains 12 core linked tables:

| Table | Purpose |
|---|---|
| `market_category` | Market/category attractiveness |
| `consumer_segments` | Segment penetration and role |
| `brand_health` | Awareness, consideration, trial, repeat and penetration |
| `consumer_occasions` | Usage occasions and brand affinity |
| `competition` | Competitor position and penetration |
| `channel_performance` | Revenue and channel economics |
| `distribution_availability` | Distribution versus effective availability |
| `pricing_pack` | Price and pack architecture |
| `portfolio` | Portfolio mix, growth and margins |
| `media_performance` | Media investment and recruitment |
| `innovation_pipeline` | Innovation opportunities |
| `pnl` | Revenue, margin, investment and contribution |

A supplementary `monthly_signals` table provides additional time-series evidence.

## Why the data is deliberately messy

Real marketing problems rarely arrive as clean textbook cases.

The dataset therefore contains deliberately conflicting signals so the Copilot must:

**Validate → Compare → Challenge → Hypothesise → Prioritise**

rather than simply correlate two variables and produce a recommendation.

## Repository structure

```text
marketing-strategy-copilot/
├── README.md
├── nectar_syrup_dataset.xlsx
├── data_dictionary.csv
└── nectar_syrup_case_brief.md
```

## Project roadmap

- **Stage A — Marketing Framework:** ✅ Locked
- **Stage B0 — Data Architecture:** ✅ Locked
- **Stage B1 — Case Architecture:** ✅ Locked
- **Stage B2 — Data Model:** ✅ Locked
- **Stage B3 — Synthetic Dataset:** ✅ MVP
- **Stage C — AI Logic:** Next
- **Stage D — Simple Interface:** Planned
- **Stage E — Case Testing:** Planned
- **Stage F — Screenshots / Documentation:** Planned
- **Stage G — GitHub Publication:** Planned

## What this project demonstrates

This is intentionally **not positioned as a software engineering project**.

It demonstrates the ability to translate senior marketing expertise into an AI-assisted decision framework covering:

- Consumer strategy
- Category growth
- Brand strategy
- Innovation
- Portfolio strategy
- Channel strategy
- Commercial thinking
- P&L
- Marketing effectiveness
- Strategic challenge
- AI-assisted decision making

The goal is to demonstrate:

> **Marketing judgement × structured problem solving × AI**

## Synthetic-data disclaimer

All companies, brands, competitors, consumers, financial figures and datasets in this repository are fictional and created solely for demonstration and product testing. They should not be interpreted as market research, financial guidance or representations of actual businesses.

## Author

**Ravi Prakash**

Marketing & Innovation Leader | FMCG | P&L | Brand & Category Growth | Innovation | Consumer Strategy | AI-powered Marketing
