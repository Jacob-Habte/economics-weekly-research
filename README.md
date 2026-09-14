# Economics Weekly Research

Companion code, data workflows, charts, and reproducibility notes for long-form Economics Weekly market research.

The repository separates each article into its own project folder. This keeps the analysis behind an article traceable without mixing unrelated datasets, figures, or Python environments.

## Article projects

| Project | Research focus |
| --- | --- |
| [Oil Price Article](oil-price-article/) | How oil-price movements travel through inflation, consumers, corporate margins, monetary policy, and public equities. |
| [Private Credit Article](private-credit-article/) | Research and analysis supporting the publication's private-credit coverage. |
| [Treasury Debt Article](treasury-debt-article/) | U.S. federal debt, Treasury issuance, interest rates, and their wider market implications. |

## Intended project structure

Each article folder will use the following structure where applicable:

```text
article-name/
├── README.md          # Article-specific thesis, methodology, and instructions
├── notebooks/         # Jupyter analysis
├── src/               # Reusable Python scripts
├── data/              # Small shareable inputs or source instructions
├── outputs/           # Selected charts and result tables
└── requirements.txt   # Article-specific dependencies
```

A smaller project does not need every directory. Files are kept only when they help explain, reproduce, or audit the published analysis.

## Reproducibility principles

- Source data should be linked and dated.
- Downloadable raw data should normally be retrieved by code rather than committed.
- Important transformations and chart calculations should be visible.
- Selected final figures may be committed for easy review.
- Credentials, virtual environments, caches, and private exports must remain outside Git.
- Each project should state important assumptions and limitations.

## Disclaimer

This repository is provided for research and educational purposes. Its contents are not investment advice.
