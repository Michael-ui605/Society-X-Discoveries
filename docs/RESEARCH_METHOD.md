# Initial research method

## Why this first experiment?
A first autonomous system needs a transparent, reproducible task that can run without a paid model API or private credentials. The prototype scans a finite set of open indicators for persistent relationships that may merit deeper investigation. It is intentionally modest: a first instrument for discovery, not a claim to general intelligence or scientific validation.

## Dataset
World Bank World Development Indicators, accessed through the documented public API. The selected indicators, codes, years, and retrieval URLs are captured in each run record. Review the World Bank's terms and attribution guidance before reusing data outside this prototype: https://datahelpdesk.worldbank.org/knowledgebase/articles/898581-api-basic-call-structures and https://www.worldbank.org/en/about/legal/terms-of-use-for-datasets

## Analysis
For each pair of indicators, calculate Pearson's r separately for each year using only countries with both values. Require at least 40 countries in a year and at least 8 usable years. Rank pairs by mean absolute yearly correlation and direction consistency. No causal inference, p-value fishing, or novelty assertion is made.

## Next research loop
A candidate association should generate competing explanations, possible confounders, falsification tests, and a more focused follow-up question. The next stage should add independent datasets and time-aware robustness checks before any claim is promoted.
