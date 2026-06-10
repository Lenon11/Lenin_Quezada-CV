# Lenin Quezada – CV

Curriculum vitae built using LaTeX and the AltaCV template.

## Areas of interest

- Data Science
- Quantitative Finance
- Machine Learning
- Computer Vision

## Projects

- Corporate Credit Risk Valuation
- Mean-Reverting Portfolio (Cointegration research)
- Credit Risk Machine Learning models
- Computer Vision industrial classification system

## CV

Download the latest version:

- 🇪🇸 [Lenin_Quezada_CV.pdf](Lenin_Quezada_CV.pdf) (Spanish)
- 🇬🇧 [Lenin_Quezada_CV_EN.pdf](Lenin_Quezada_CV_EN.pdf) (English)

Both PDFs are generated automatically from a single source file (`cv.tex`).
Each piece of text uses the `\tr{Spanish}{English}` macro, so both languages
stay in sync. The GitHub Action compiles the Spanish version directly and the
English version through a flag (`\def\CVEN{}`), then commits both PDFs.
