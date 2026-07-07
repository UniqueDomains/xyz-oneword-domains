# Available .XYZ One-Word Domains (57,974)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-57%2C974%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .xyz one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **57,974 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 57,974 domains · **Median ask:** $3,870.36 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
**Canonical page:** `https://unique.domains/domains/tld/xyz`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/xyz?utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./xyz.csv">CSV</a> / <a href="./xyz.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .XYZ search](https://unique.domains/domains/tld/xyz?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .XYZ search](https://unique.domains/domains/tld/xyz?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .XYZ one-word domain catalog.

### Files

- `xyz.csv`, public CSV extract (1,000 rows)
- `xyz.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/xyz-oneword-domains/main/xyz.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price   | renewal_price | attractiveness | demand | length | registrar                                   |
| --------------- | --------- | ----------- | ------------- | -------------- | ------ | ------ | ------------------------------------------- |
| pointat.xyz     | available | $1.99       | —             | low            | low    | 8      | name.com                                    |
| dairy.xyz       | resell    | $114,871.20 | $20.99        | high           | high   | 5      | Dynadot LLC                                 |
| detox.xyz       | premium   | $640        | $640          | high           | low    | 5      | namesilo                                    |
| comewith.xyz    | available | $1.99       | —             | medium         | low    | 9      | name.com                                    |
| plier.xyz       | resell    | $1,263.85   | $20.99        | high           | low    | 5      | Go Daddy, LLC                               |
| travel.xyz      | premium   | $13,000     | $13,000       | high           | medium | 6      | namecheap                                   |
| eachtime.xyz    | available | $1.99       | —             | medium         | low    | 9      | name.com                                    |
| distant.xyz     | resell    | $3,448.85   | $20.99        | medium         | low    | 7      | Go Daddy, LLC                               |
| grocery.xyz     | premium   | $1,107      | $1,107        | high           | low    | 7      | namesilo                                    |
| extendto.xyz    | available | $1.99       | —             | high           | low    | 9      | name.com                                    |
| hacking.xyz     | resell    | $4,943.85   | $20.99        | medium         | low    | 7      | Go Daddy, LLC                               |
| learning.xyz    | premium   | $1,300      | $1,300        | high           | low    | 8      | namecheap                                   |
| saddening.xyz   | available | $1.99       | —             | high           | low    | 9      | name.com                                    |
| perforation.xyz | resell    | $1,033.85   | $20.99        | medium         | low    | 11     | Go Daddy, LLC                               |
| musiccenter.xyz | premium   | $1,717.52   | —             | high           | low    | 12     | name.com                                    |
| comeupto.xyz    | available | $1.99       | —             | medium         | low    | 10     | name.com                                    |
| adv.xyz         | resell    | —           | —             | medium         | high   | 3      | GoDaddy Online Services Cayman Islands Ltd. |
| WestCountry.xyz | premium   | $1,717.52   | —             | medium         | low    | 12     | name.com                                    |
| discdrive.xyz   | available | $1.99       | —             | high           | low    | 10     | name.com                                    |
| hug.xyz         | resell    | —           | —             | high           | low    | 3      | Dynadot LLC                                 |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 57,974 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/xyz?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/xyz?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list contains 57,974 one-word domain names registered under the .xyz extension, ranging from everyday words like half.xyz and using.xyz to distinctive picks such as fascinate.xyz and bonappetit.xyz. The median asking price across this selection is near $3,870, giving a practical benchmark for comparing individual listings. Because .xyz allows short, single-word registrations across nearly every industry, this set spans a wide mix of styles — from playful (bad.xyz, allstar.xyz) to descriptive (propose.xyz, humanbeing.xyz). Evaluating options here means weighing price against brandability, spelling simplicity, and renewal cost before committing to a name.

- 57,974 one-word .xyz domains in this set — updated daily
- Median asking price near $3,870 across the selection
- Mix of short, brandable, and descriptive one-word names
- Compare price, spelling, and renewal before choosing a name

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .XYZ One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .XYZ page](https://unique.domains/domains/tld/xyz?utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
