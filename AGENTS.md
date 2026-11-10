# AGENTS.md

Rules for maintaining this repo. `README.md` holds one table of papers.

## README format

- The intro line under the title stays exactly: `Papers on building machines that scale, and also most fundamental.`
- Table columns, in order: `#`, `Date`, `Paper`, `Links`.
- Sort rows newest first, by `Date`. Renumber `#` from 1 after any change.
- `Date` is `YYYY-MM`, from the paper's first public version (for arXiv, the v1 date).
- `Paper` is the full title in bold. If the paper has a well-known short name, add it in parentheses after the title, e.g. `**Attention Is All You Need** (Transformer)`. Skip the short name when the title already contains it.
- Do not list authors.

## Links column

- Each row has exactly one link, and its label is always `arXiv`, wherever it points.
- Use the arXiv abstract page (`https://arxiv.org/abs/<id>`). If a paper is not on arXiv, point to its official page, but still label the link `arXiv`.
- Do not add PDF links or any other links.

## Adding a paper

1. Look up the title and v1 date from arXiv (or the official page).
2. Add the row, re-sort newest first, renumber.
3. Commit and push to `main`.
