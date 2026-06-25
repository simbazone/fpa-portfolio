# FP&A Automation Portfolio

**Live dashboard:** [simbazone.github.io/fpa-portfolio](https://simbazone.github.io/fpa-portfolio)

---

## What This Is

An end-to-end FP&A automation system built on eBay's public financial data,
replicating the FP&A workflow. Built as a portfolio project using Claude Cowork.

---

## What's Built
1. Excel Models (Claude Cowork automation)
2. Interactive Dashboard (this repo)
- **Overview** — Revenue trend, take rate story, Budget vs Actuals RAG, HC summary
- **Scenario Analysis** — Live BASE/BULL/BEAR toggle across KPIs, forecast, sensitivities
- **Variance Engine** — Paste variance table → generate CFO-ready Claude prompt in 1 click

---

## Key Findings

- Revenue is a take rate story: GMV down 9% peak-to-trough, revenue up 25% same period (10.2% → 13.9% take rate)
- FY2025 dual inflection: first year since FY2020 where both GMV and take rate grew simultaneously
- G&A overage explains everything: $354M revenue beat flipped to $323M op income miss by a single $467M G&A line
- FCF compression is balance-sheet funded: $2.5B buybacks funded via net debt expansion $3.2B → $3.8B

---

## Stack
Claude Desktop (Cowork) · Claude API · Excel/openpyxl · Vanilla HTML/JS · GitHub Pages

## Data Sources
eBay SEC filings (10-K FY2022–FY2025), Q1 2026 Earnings Deck, 2026 Proxy Statement,
eBay Investor Relations historical tables. All public disclosures.

---

## Disclaimer: 

Independent portfolio project built from public information.
GMX financials are modeled estimates, eBay does not disclose GMX as a separate segment. Not affiliated with or endorsed by eBay Inc. All data sourced exclusively from publicly available SEC filings and eBay investor relations disclosures. No proprietary or non-public information was used.

---
