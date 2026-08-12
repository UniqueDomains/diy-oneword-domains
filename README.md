# Available .DIY One-Word Domains (13,627)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-13%2C627%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .diy one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **13,627 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 13,627 domains · **Median ask:** $121.27 · **High-demand under $2,500:** 46

**Last updated:** 2026-08-12
**Canonical page:** `https://unique.domains/domains/tld/diy`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/diy?utm_source=github&utm_medium=referral&utm_campaign=repo_diy_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./diy.csv">CSV</a> / <a href="./diy.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_diy_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_diy_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .DIY search](https://unique.domains/domains/tld/diy?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_diy_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .DIY search](https://unique.domains/domains/tld/diy?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_diy_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_diy_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .DIY one-word domain catalog.

### Files

- `diy.csv`, public CSV extract (1,000 rows)
- `diy.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/diy-oneword-domains/main/diy.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain    | status    | ask_price | renewal_price | attractiveness | demand | length | registrar    |
| --------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------ |
| boob.diy  | available | $5.49     | $39.99        | high           | low    | 4      | namesilo     |
| bold.diy  | resell    | —         | —             | high           | high   | 4      | Dynadot, LLC |
| ada.diy   | premium   | $875      | —             | medium         | medium | 3      | name.com     |
| html.diy  | available | $5.49     | $39.99        | high           | low    | 4      | namesilo     |
| ADS.diy   | premium   | $875      | —             | high           | medium | 3      | name.com     |
| lxii.diy  | available | $4.98     | $51.98        | low            | low    | 4      | namecheap    |
| ale.diy   | premium   | $875      | —             | medium         | low    | 3      | name.com     |
| Elias.diy | available | $5.49     | $39.99        | high           | low    | 5      | namesilo     |
| all.diy   | premium   | $910      | $1,300        | high           | medium | 3      | namecheap    |
| heard.diy | available | $5.49     | $39.99        | medium         | low    | 5      | namesilo     |
| arm.diy   | premium   | $437.50   | —             | high           | medium | 3      | name.com     |
| lviii.diy | available | $4.98     | $51.98        | low            | low    | 5      | namecheap    |
| ash.diy   | premium   | $875      | —             | medium         | low    | 3      | name.com     |
| lxiii.diy | available | $4.98     | $51.98        | low            | low    | 5      | namecheap    |
| ass.diy   | premium   | $875      | $1,250        | low            | low    | 3      | name.com     |
| ohoh.diy  | available | $5.49     | $39.99        | high           | low    | 5      | namesilo     |
| bee.diy   | premium   | $875      | —             | high           | medium | 3      | name.com     |
| orso.diy  | available | $5.49     | $39.99        | medium         | low    | 5      | namesilo     |
| big.diy   | premium   | $455      | $650          | high           | medium | 3      | namecheap    |
| owens.diy | available | $5.49     | $39.99        | medium         | low    | 5      | namesilo     |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 13,627 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 46 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/diy?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_diy_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/diy?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_diy_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_diy_oneword_domains&utm_content=related_pricing)

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

This is a focused list of one-word .diy domain names built from common, everyday English words rather than invented terms. Names like out.diy, half.diy, christmas.diy, and sorry.diy show the range: short, pronounceable, and easy to remember, which fits the hands-on, maker-culture identity of the .diy extension. With a median ask near $152 across 12,167 names, entry pricing stays low relative to legacy TLDs, giving both early-stage buyers and long-term holders room to act before demand concentrates on the cleanest words.

- 12,167 one-word .diy domains built from common English words
- Median ask near $152 keeps entry cost low for buyers
- Short names like out.diy and half.diy fit DIY-style brands
- Pricing updates daily to reflect current ask levels

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DIY One-Word Domains*. Version 2026-08-12. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DIY page](https://unique.domains/domains/tld/diy?utm_source=github&utm_medium=referral&utm_campaign=repo_diy_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_diy_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_diy_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_diy_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
