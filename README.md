# Available .NGO One-Word Domains (33,324)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-33%2C324%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .ngo one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **33,324 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 33,324 domains · **Median ask:** $27.46 · **High-demand under $2,500:** 86

**Last updated:** 2026-10-02
**Canonical page:** `https://unique.domains/domains/tld/ngo`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/ngo?utm_source=github&utm_medium=referral&utm_campaign=repo_ngo_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./ngo.csv">CSV</a> / <a href="./ngo.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_ngo_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ngo_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .NGO search](https://unique.domains/domains/tld/ngo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_ngo_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .NGO search](https://unique.domains/domains/tld/ngo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_ngo_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ngo_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .NGO one-word domain catalog.

### Files

- `ngo.csv`, public CSV extract (1,000 rows)
- `ngo.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/ngo-oneword-domains/main/ngo.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar  |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------- |
| scale.ngo      | available | $15.20    | $15.20        | high           | medium | 5      | cloudflare |
| clarity.ngo    | available | $15.20    | $15.20        | high           | medium | 7      | cloudflare |
| pink.ngo       | available | $18.98    | $24.98        | high           | low    | 4      | namecheap  |
| don.ngo        | available | $18.98    | $24.98        | high           | low    | 3      | namecheap  |
| date.ngo       | available | $15.20    | $15.20        | high           | low    | 4      | cloudflare |
| fortune.ngo    | available | $16.72    | $16.72        | high           | low    | 7      | dynadot    |
| genial.ngo     | available | $18.98    | $24.98        | high           | low    | 6      | namecheap  |
| case.ngo       | available | $15.20    | $15.20        | high           | low    | 4      | cloudflare |
| developing.ngo | premium   | $62.50    | $31.25        | high           | low    | 10     | name.com   |
| artwork.ngo    | available | $18.98    | $24.98        | high           | low    | 7      | namecheap  |
| revenue.ngo    | available | $16.72    | $16.72        | high           | low    | 7      | dynadot    |
| answer.ngo     | premium   | $65       | $32.50        | high           | low    | 6      | namecheap  |
| pan.ngo        | available | $18.98    | $24.98        | high           | low    | 3      | namecheap  |
| region.ngo     | available | $15.20    | $15.20        | high           | low    | 6      | cloudflare |
| tbd.ngo        | available | $29.99    | $29.99        | high           | low    | 3      | godaddy    |
| spike.ngo      | available | $18.98    | $24.98        | high           | low    | 5      | namecheap  |
| tradition.ngo  | available | $16.72    | $16.72        | high           | low    | 9      | dynadot    |
| destiny.ngo    | available | $16.72    | $16.72        | high           | low    | 7      | dynadot    |
| term.ngo       | available | $18.98    | $24.98        | high           | low    | 4      | namecheap  |
| right.ngo      | premium   | $1,625    | $812.50       | high           | low    | 5      | namecheap  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 33,324 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 86 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/ngo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_ngo_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/ngo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_ngo_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_ngo_oneword_domains&utm_content=related_pricing)

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
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set covers 12,367 one-word domain names on the .NGO extension, with a median ask around $39. The names are short and single-word — from travel and lifestyle terms like bonvoyage.ngo and getready.ngo to tech and service names like hightech.ngo and dogwalking.ngo. Because .NGO is a smaller, mission-aligned extension, clear one-word names remain widely available across sectors, giving buyers more room to find a fitting match before committing.

- 12,367 one-word .NGO domains available across sectors
- Median asking price near $39 per domain
- Includes travel, tech, lifestyle, and mission-driven names
- Updated daily to reflect current .NGO listings

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .NGO One-Word Domains*. Version 2026-10-02. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .NGO page](https://unique.domains/domains/tld/ngo?utm_source=github&utm_medium=referral&utm_campaign=repo_ngo_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_ngo_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_ngo_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ngo_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
