# Fluckiger Taxes

Personal tax document repository for Joseph & Sarah Fluckiger.

## Structure

```
taxes/
├── 2024/
│   ├── tax_docs/        # Source documents (W2s, 1099s, K-1s, etc.)
│   ├── Taxes 2024.xlsx  # Working spreadsheet
│   └── my tax notes overview - ron ruiz + joseph fluckiger.txt
├── 2025/
│   ├── scanned_docs/    # Scanned source documents — each PDF has a matching .md with extracted data
│   │   └── pdfs/
│   ├── TAX_SUMMARY_2025.md          # Summary of income, deductions, and filing status
│   ├── Taxdocs_2025_Checklist.csv   # Document checklist
│   ├── charitable_donations_2025.csv
│   ├── tithing_2025.csv
│   ├── true_charity_2025.csv
│   ├── mission_2025.csv
│   └── eager_llc_expenses_2025.csv
└── phil_notes/          # Session notes from AI-assisted tax prep sessions
```

## Workflow

PDFs are scanned and OCR-processed (pytesseract + pdf2image) by a sub-agent. Each PDF gets a matching `.md` file in `scanned_docs/` with the extracted tax-relevant data. Session notes in `phil_notes/` track what was processed and any open action items.

## Tax Preparer

Ron Ruiz (CPA)

## Filing Status

Married Filing Jointly
