# Available .IN One-Word Domains (4,812)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-4%2C812%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-4%2C812%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .in one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 4,812 rows · **Live catalog:** 4,812 domains

**Last updated:** 2026-04-12  
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

- `in.csv` — public CSV extract (4,812 rows)
- `in.json` — public JSON extract (4,812 rows)
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

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                           |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------- |
| hostile.in    | available | $11.98    | —             | 60             | 10     | 7      | namecheap                                           |
| fullscale.in  | resell    | $11.98    | —             | 72             | 7      | 10     | Costrar EOOD                                        |
| ma.in         | premium   | —         | —             | 94             | 99     | 4      | —                                                   |
| corrupted.in  | available | $11.98    | —             | 52             | 10     | 9      | namecheap                                           |
| weather.in    | resell    | —         | —             | 118            | 99     | 7      | Endurance Digital Domain Technology Private Limited |
| va.in         | premium   | —         | —             | 68             | 98     | 4      | —                                                   |
| compelling.in | available | $11.98    | —             | 92             | 9      | 10     | namecheap                                           |
| funny.in      | resell    | —         | —             | 111            | 99     | 5      | GoDaddy                                             |
| observed.in   | premium   | —         | —             | 68             | 97     | 8      | —                                                   |
| crying.in     | available | $11.98    | —             | 82             | 9      | 6      | namecheap                                           |
| quality.in    | resell    | —         | —             | 92             | 99     | 7      | Endurance Digital Domain Technology Private Limited |
| jo.in         | premium   | —         | —             | 96             | 41     | 4      | —                                                   |
| enduring.in   | available | $9.98     | —             | 82             | 9      | 8      | namecheap                                           |
| gas.in        | resell    | —         | —             | 72             | 99     | 3      | Endurance Digital Domain Technology Private Limited |
| ra.in         | premium   | —         | —             | 98             | 37     | 4      | —                                                   |
| contingent.in | available | $11.98    | —             | 80             | 9      | 10     | namecheap                                           |
| dock.in       | resell    | —         | —             | 70             | 99     | 4      | Dynadot, LLC                                        |
| sk.in         | premium   | —         | —             | 98             | 35     | 4      | —                                                   |
| abject.in     | available | $9.98     | —             | 94             | 8      | 6      | namecheap                                           |
| away.in       | resell    | —         | —             | 126            | 98     | 4      | Endurance Digital Domain Technology Private Limited |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 4,812-row public sample | 4,812 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .IN One-Word Domains*. Version 2026-04-12. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .IN page](https://unique.domains/domains/tld/in?utm_source=github&utm_medium=referral&utm_campaign=repo_in_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_in_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_in_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_in_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
