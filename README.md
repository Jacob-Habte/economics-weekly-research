# Economics Weekly Research

Companion code, data workflows, charts, and reproducibility notes for long-form Economics Weekly market research.

Each article is kept in its own project folder so its datasets, figures, and Python environment remain separate from unrelated analysis.

## Article project

### [Private Credit Article](private-credit-article/)

Research, code, charts, and data notes supporting the publication's private-credit coverage. The article-specific methodology and reproduction steps will be completed after its source files are imported and reviewed.

## Intended project structure

```text
private-credit-article/
├── README.md          # Thesis, methodology, and instructions
├── notebooks/         # Jupyter analysis
├── src/               # Reusable Python scripts
├── data/              # Small shareable inputs or source instructions
├── outputs/           # Selected charts and result tables
└── requirements.txt   # Article-specific dependencies
```

A project does not need every directory. Files are retained only when they help explain, reproduce, or audit the published analysis.

## Reproducibility principles

- Source data should be linked and dated.
- Downloadable raw data should normally be retrieved by code rather than committed.
- Important transformations and chart calculations should remain visible.
- Selected final figures may be committed for easy review.
- Credentials, virtual environments, caches, and private exports must remain outside Git.
- Important assumptions and limitations should be documented.

## Disclaimer

This repository is provided for research and educational purposes. Its contents are not investment advice.
