# SOCIETY-X — Discovery Portal

Public results portal for SOCIETY-X. This repository contains the static website, public research outputs, and public methodology. The autonomous research engine is maintained separately.

## Website
After enabling GitHub Pages, visit:
https://michael-ui605.github.io/Society-X-Discoveries/

## Published material
- Latest exploratory research record: `results/latest.json`
- Research run history: `results/history.jsonl`
- Method and source notes: `docs/RESEARCH_METHOD.md`

## Interpretation
Current records are exploratory and unverified. Correlation is not causation. These results do not establish novelty, causality, or predictive usefulness. Stronger claims require robustness checks and independent replication.

## Deployment
The GitHub Actions workflow in `.github/workflows/pages.yml` deploys this static site. In Settings → Pages, set **Build and deployment → Source** to **GitHub Actions**. Future pushes to `main` will deploy automatically.

## Separation and privacy
This repository is intended to remain public. Do not place private agent code, internal prompts, credentials, tokens, private data, or internal operational logs here. The core repository must be made private separately; moving files does not erase public Git history.
