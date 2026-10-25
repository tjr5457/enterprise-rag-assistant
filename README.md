# Enterprise RAG Assistant

An enterprise-focused retrieval-augmented generation (RAG) application for
answering questions grounded in life insurance policy documents. The policy
PDFs in `data/` are the reference corpus for developing and evaluating the
assistant. Responses should be based on retrieved document content rather than
unsupported assumptions.

## Policy document corpus

The current reference documents are:

- [HDFC Life Click 2 Wealth](data/HDFC-Life-Click-2-Wealth-101L133V03-Policy-Document.pdf)
- [HDFC Life Guaranteed Savings Plan](data/HDFC-Life-Guaranteed-Savings-Plan-101N131V04-Policy-bond-Single-Pay.pdf)
- [HDFC Life Sampoorn Nivesh Plus](data/HDFC-Life-Sampoorn-Nivesh-Plus-V01-Policy-Document.pdf)
- [HDFC Life Sanchay Plus — Long-Term Income Option](data/HDFC-Life-Sanchay-Plus-101N134V30-Long-Term-Income-Option-Policy-Document.pdf)
- [HDFC Life Smart Protect Plus](data/HDFC-Life-Smart-Protect-Plus-101L187V04-Policy-Document.pdf)

Use these documents as source material for ingestion, indexing, retrieval, and
grounded answer generation. When adding or replacing policy documents, keep
this list in sync with the contents of `data/`.

## Repository layout

| Path | Purpose |
| --- | --- |
| `data/` | Policy PDFs used as the RAG reference corpus |
| `src/` | Application and RAG pipeline implementation |
| `evals/` | Evaluation data and workflows |
| `tests/` | Automated tests |

## Project status

This repository is being set up for RAG development. The directories above
identify the intended project areas; add implementation, evaluation workflows,
and tests as they are developed.
