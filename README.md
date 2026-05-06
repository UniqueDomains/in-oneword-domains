# Available .IN One-Word Domains (6,548)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-6%2C548%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .in one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **6,548 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 6,548 domains · **Median ask:** $11.20 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/in`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/in?utm_source=github&utm_medium=referral&utm_campaign=repo_in_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./in.csv">CSV</a> / <a href="./in.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_in_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_in_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .IN search](https://unique.domains/domains/tld/in?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_in_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .IN search](https://unique.domains/domains/tld/in?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_in_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_in_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .IN one-word domain catalog.

### Files

- `in.csv` — public CSV extract (1,000 rows)
- `in.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/in-oneword-domains/main/in.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar              |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------------- |
| RedSox.in        | available | $11.98    | —             | 72             | 60     | 7      | namecheap              |
| makers.in        | resell    | —         | —             | 62             | 67     | 6      | Realtime Register B.V. |
| irons.in         | premium   | —         | —             | 62             | 8      | 5      | —                      |
| tomorrows.in     | available | $7.95     | $7.95         | 60             | 11     | 9      | namesilo               |
| united.in        | resell    | —         | —             | 74             | 41     | 6      | Dynadot, LLC           |
| legalheir.in     | premium   | —         | —             | 71             | 1      | 10     | —                      |
| yoursever.in     | available | $11.98    | —             | 56             | 10     | 10     | namecheap              |
| shortcuts.in     | resell    | —         | —             | 48             | 41     | 10     | Dynadot, LLC           |
| plateout.in      | premium   | —         | —             | 65             | 1      | 9      | —                      |
| mutualaid.in     | available | $11.98    | —             | 78             | 9      | 10     | namecheap              |
| block.in         | resell    | —         | —             | 68             | 36     | 5      | NAMECHEAP              |
| platearmour.in   | premium   | —         | —             | 65             | 1      | 12     | —                      |
| divein.in        | available | $11.98    | —             | 76             | 9      | 7      | namecheap              |
| list.in          | resell    | —         | —             | 70             | 35     | 4      | Dynadot, LLC           |
| chiefofstaff.in  | available | $11.98    | —             | 60             | 9      | 14     | namecheap              |
| dawn.in          | resell    | —         | —             | 70             | 33     | 4      | Dynadot, LLC           |
| VirginiaBeach.in | available | $11.98    | —             | 58             | 9      | 14     | namecheap              |
| assistant.in     | resell    | —         | —             | 64             | 32     | 9      | Dynadot, LLC           |
| keeptrack.in     | available | $11.98    | —             | 76             | 8      | 10     | namecheap              |
| partners.in      | resell    | —         | —             | 61             | 32     | 8      | 1API GmbH              |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 6,548 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/in?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_in_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/in?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_in_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_in_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

These domains are single-word .in names, which makes the set relevant for both buyers seeking clear brand assets and investors scanning for buyable keyword inventory. The selection includes dictionary-style words, verbs, and broad commercial terms such as moving.in, hashtag.in, mirror.in, obtain.in, pacific.in, study.in, and paper.in. When comparing these domains, focus on how naturally the word fits the .in extension, how memorable it is on first read, and whether the ask matches the word’s commercial breadth. Short, familiar words usually hold attention better, but ambiguity, weak category fit, or possible trademark overlap can reduce confidence.

- Single-word .in names with broad commercial and brand use
- Median ask is 11.20 across 6,548 listed domains
- Examples include moving.in, mirror.in, study.in, paper.in
- Check clarity, category fit, and trademark risk before buying

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .IN One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .IN page](https://unique.domains/domains/tld/in?utm_source=github&utm_medium=referral&utm_campaign=repo_in_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_in_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_in_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_in_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
