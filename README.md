# Available .TOWN One-Word Domains (8,904)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-8%2C903%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-8%2C904%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .town one-word domains from Unique Domains.

> **Important:** this repository is a **public 8,903-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **8,904 domains** on the canonical page below.

**Public extract:** 8,903 rows · **Live catalog:** 8,904 domains

**Last updated:** 2026-04-12  
**Canonical page:** `https://unique.domains/domains/tld/town`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/town?utm_source=github&utm_medium=referral&utm_campaign=repo_town_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./town.csv">CSV</a> / <a href="./town.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_town_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_town_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .TOWN search](https://unique.domains/domains/tld/town?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_town_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .TOWN search](https://unique.domains/domains/tld/town?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_town_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_town_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .TOWN one-word domain catalog.

### Files

- `town.csv` — public CSV extract (8,903 rows)
- `town.json` — public JSON extract (8,903 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/town-oneword-domains/main/town.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| agile.town    | available | $9.99     | $48.99        | 92             | 41     | 5      | name.com          |
| clean.town    | resell    | —         | —             | 130            | 99     | 5      | Sav.com, LLC      |
| one.town      | premium   | $123.75   | $123.75       | 132            | 50     | 3      | name.com          |
| quick.town    | available | $9.99     | $48.99        | 72             | 41     | 5      | name.com          |
| white.town    | resell    | —         | —             | 102            | 98     | 5      | Spaceship, Inc.   |
| real.town     | premium   | $85.80    | $85.80        | 78             | 49     | 4      | namecheap         |
| unity.town    | available | $9.99     | $48.99        | 70             | 40     | 5      | name.com          |
| american.town | resell    | —         | —             | 98             | 98     | 8      | GoDaddy.com, LLC  |
| security.town | premium   | $260      | $260          | 70             | 49     | 8      | namecheap         |
| eternal.town  | available | $9.99     | $48.99        | 92             | 39     | 7      | name.com          |
| box.town      | resell    | —         | —             | 68             | 78     | 3      | GoDaddy.com, LLC  |
| travel.town   | premium   | $520      | $520          | 115            | 48     | 6      | namecheap         |
| forward.town  | available | $9.99     | $48.99        | 68             | 39     | 7      | name.com          |
| hello.town    | resell    | —         | —             | 130            | 70     | 5      | Sav.com, LLC - 25 |
| gold.town     | premium   | $260      | $260          | 72             | 48     | 4      | namecheap         |
| unify.town    | available | $9.99     | $48.99        | 72             | 38     | 5      | name.com          |
| easy.town     | resell    | —         | —             | 128            | 68     | 4      | Sav.com, LLC - 49 |
| car.town      | premium   | $260      | $260          | 94             | 46     | 3      | namecheap         |
| instant.town  | available | $9.99     | $48.99        | 108            | 37     | 7      | name.com          |
| the.town      | resell    | —         | —             | 98             | 58     | 3      | GoDaddy.com, LLC  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 8,903-row public sample | 8,904 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/town?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_town_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/town?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_town_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_town_oneword_domains&utm_content=related_pricing)

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

> Unique Domains. *Available .TOWN One-Word Domains*. Version 2026-04-12. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .TOWN page](https://unique.domains/domains/tld/town?utm_source=github&utm_medium=referral&utm_campaign=repo_town_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_town_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_town_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_town_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
