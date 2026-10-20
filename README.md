# IndexHot GEO Data

Public datasets for AI search visibility research. Maintained by [IndexHot](https://indexhot.com).

## Overview

This repository contains structured data on how Large Language Models (LLMs) mention, cite, and rank brands in their generated answers. Our goal is to provide a transparent, reproducible foundation for Generative Engine Optimization (GEO) research.

## Datasets

### 1. AI Citation Behavior Dataset (2026 Q3)
- **File:** `data/ai-citation-behavior-2026q3.csv`
- **Scope:** 20 B2B SaaS brands × 50 prompts × 3 platforms (ChatGPT, Perplexity, Gemini) = 3,000 sampled answers.
- **Fields:** `prompt_id`, `platform`, `brand_mentioned`, `citation_source`, `rank_position`
- **Description:** Tracks whether a brand is mentioned, what source the AI cites, and the position of the brand in the generated list.

### 2. Brand Mention Rates by Industry
- **File:** `data/brand-mention-rates.csv`
- **Scope:** Aggregated mention rates across 5 industries.
- **Fields:** `industry`, `platform`, `total_prompts`, `mention_rate`

### 3. Schema Markup Impact Data
- **File:** `data/schema-markup-impact.csv`
- **Scope:** 50 web pages tested for the correlation between JSON-LD schema markup and AI citation frequency.
- **Fields:** `page_id`, `has_schema`, `platform`, `citation_count`

## How to Cite

If you use this data in your research, reports, or tools, please cite it as:

> IndexHot. (2026). IndexHot GEO Data 2026. Retrieved from https://github.com/indexhot-code/geo-data

BibTeX format:

    @misc{indexhot2026data,
      title={IndexHot GEO Data 2026},
      author={IndexHot},
      year={2026},
      url={https://github.com/indexhot-code/geo-data}
    }

## License

This data is licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE) license. You are free to share and adapt the data, provided you give appropriate credit.
