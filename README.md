# Available .XYZ One-Word Domains (57,771)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-57%2C771%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .xyz one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **57,771 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 57,771 domains · **Median ask:** $15,452.39 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-04  
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

- `xyz.csv` — public CSV extract (1,000 rows)
- `xyz.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/xyz-oneword-domains/main/xyz.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price   | renewal_price | attractiveness | demand | length | registrar                                   |
| ---------------- | --------- | ----------- | ------------- | -------------- | ------ | ------ | ------------------------------------------- |
| refereeing.xyz   | available | $1.99       | $20.99        | 52             | 72     | 10     | name.com                                    |
| distant.xyz      | resell    | $3,448.85   | $20.99        | 64             | 14     | 7      | Go Daddy, LLC                               |
| insight.xyz      | premium   | $47,615.72  | —             | 76             | 69     | 8      | Go Daddy, LLC                               |
| RedSox.xyz       | available | $19.48      | —             | 72             | 60     | 7      | namecheap                                   |
| plier.xyz        | resell    | $1,263.85   | $20.99        | 70             | 4      | 5      | Go Daddy, LLC                               |
| travel.xyz       | premium   | $13,000     | $13,000       | 115            | 50     | 6      | namecheap                                   |
| Obamacare.xyz    | available | $19.48      | —             | 66             | 8      | 10     | namecheap                                   |
| cloak.xyz        | resell    | —           | —             | 86             | 96     | 5      | Go Daddy, LLC                               |
| designs.xyz      | premium   | $108,972.82 | —             | 72             | 21     | 7      | Go Daddy, LLC                               |
| StGeorges.xyz    | available | $19.48      | —             | 54             | 6      | 10     | namecheap                                   |
| adv.xyz          | resell    | —           | —             | 62             | 96     | 3      | GoDaddy Online Services Cayman Islands Ltd. |
| whiteboard.xyz   | premium   | $118,317.34 | —             | 74             | 20     | 10     | West263 International Limited               |
| havenots.xyz     | available | $1.99       | —             | 60             | 5      | 9      | name.com                                    |
| coyote.xyz       | resell    | —           | —             | 56             | 96     | 6      | Name.com, Inc                               |
| blacktea.xyz     | premium   | $236.90     | —             | 74             | 15     | 9      | name.com                                    |
| rollwithit.xyz   | available | $1.99       | —             | 56             | 5      | 12     | name.com                                    |
| compassion.xyz   | resell    | —           | —             | 90             | 92     | 10     | Sav.com, LLC                                |
| intersection.xyz | premium   | $76,859.84  | —             | 72             | 14     | 12     | Dynadot LLC                                 |
| intheory.xyz     | available | $1.99       | —             | 52             | 5      | 9      | name.com                                    |
| mayor.xyz        | resell    | —           | —             | 62             | 88     | 5      | 1API GmbH                                   |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 57,771 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/xyz?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/xyz?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=related_pricing)

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

These domains are all single-word names on the .xyz extension. The set ranges from short, clean words such as unit.xyz and stick.xyz to more specific or longer terms like semicircle.xyz and barbecuesauce.xyz. That mix matters. Shorter, broader words usually have wider appeal and better resale optionality, while longer or more technical words depend more on a precise end user. With a median ask of $15,452, this selection sits well above impulse-buy territory, so each name should be judged on clarity, recall, spelling, and whether the word feels commercially usable in .xyz rather than just available.

- Short, common words usually have broader buyer appeal
- Long or niche words need a clearer end-market
- Check if the word is easy to say, spell, and remember
- At a $15,452 median ask, price discipline matters

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .XYZ One-Word Domains*. Version 2026-05-04. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .XYZ page](https://unique.domains/domains/tld/xyz?utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_xyz_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
