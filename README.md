# Data Analysis Portfolio

This repository contains three data analysis portfolio projects completed for LSE MY472 Data for Data Scientists. The projects demonstrate text mining, public data visualisation, mapping, social media data management, and SQL-based analysis using R.

## Projects

| Project | Focus | Main methods |
|---|---|---|
| Project 1: Text Mining and Social Media Analysis with R | Extracting, cleaning, and analysing text from PDFs, OCR documents, and social media data | `quanteda`, `pdftools`, OCR, tokenisation, document-feature matrices, n-grams, word clouds, word embeddings |
| Project 2: Data Visualization | Public data visualisation and mapping | `tidyverse`, `ggplot2`, `sf`, election mapping, demographic visualisation, social media engagement charts |
| Project 3: Managing Social Media Data with Databases | Managing and querying social media data with a relational database | SQLite, SQL joins, account/post tables, party-level and account-level social media analysis |

## Repository Structure

```text
.
├── Project1 Text Mining and Social Media Analysis with R/
├── Project2 Data Visualization/
└── Project3 Managing Social Media Data with Databases/
```

Each project folder includes source code, supporting documents, data used for the analysis where practical, and selected outputs for portfolio review.

## Notes on Large Files

Two large files are intentionally excluded from GitHub:

- `glove.6B.50d.txt`, the Stanford GloVe embedding file used in Project 1.
- `facebook-db.sqlite`, a generated SQLite database output from Project 3.

These files can be regenerated or downloaded using the project code. They are excluded because GitHub blocks normal uploads of files larger than 100MB.

## Author

Zhao Zhanyu