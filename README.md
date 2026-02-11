# NSTC-Proposal-LaTeX-Template

A structured LaTeX template for the NSTC Undergraduate Research Project Proposal 國科會大專學生研究計畫 LaTeX 排版模板

------------------------------------------------------------------------

## 📌 Project Overview

This repository provides a modular and production-ready LaTeX template for preparing the NSTC (National Science and Technology Council, Taiwan) Undergraduate Research Proposal.

The template is designed to:

-   Ensure structural completeness of proposal documents
-   Separate logical components for maintainability
-   Support bibliography management via BibTeX
-   Produce submission-ready PDF output
-   Compatible with Overleaf online editing

本模板已完成完整模組化設計，可直接用於國科會大專學生研究計畫申請文件撰寫與編譯，並支援 Overleaf 線上編輯環境。

------------------------------------------------------------------------

## 📂 Repository Structure

```
NSTC-Proposal-LaTeX-Template/ 
│
├── main.tex
├── combined.tex
├──budget.tex
├── advisor.tex
├── wrapper.sty
├── reference.bib
│
├──additional.pdf
├── transcript.pdf
│ 
└── README.md
│
└── figures
      ├── img1.png
      └── img2.png
```

------------------------------------------------------------------------

## 🧱 Architecture Design

-   main.tex controls document flow.
-   wrapper.sty defines layout and formatting rules.
-   Section files improve readability and modularity.
-   reference.bib manages citation sources.
-   combined.tex provides a unified export for submission.

------------------------------------------------------------------------

## 🛠 Compilation Guide

### ✅ Overleaf (Recommended)

1.  Upload the entire repository to Overleaf.
2.  Click **Menu → Settings**.
3.  Set **Compiler** to **XeLaTeX**.
4.  Ensure `main.tex` is selected as the main document.
5.  Click **Recompile**.

使用 Overleaf 時請務必將編譯器設定為**XeLaTeX**，以確保中文字型與版面正常顯示。

------------------------------------------------------------------------

### 💻 Local Environment

#### Requirements

-   TeX Live 2022+
-   XeLaTeX (Recommended)
-   BibTeX

#### Compile (XeLaTeX Recommended)

xelatex main.tex\
bibtex main\
xelatex main.tex\
xelatex main.tex

------------------------------------------------------------------------

## 📎 Submission Notes

-   Ensure compliance with the latest NSTC formatting regulations.
-   Verify page limits and margin constraints before submission.
-   Replace placeholder content with official information.
-   Remove optional attachments if not required.

------------------------------------------------------------------------

## 🎯 Intended Users

-   Undergraduate students applying for NSTC research grants
-   Academic advisors supervising proposal preparation
-   Research groups requiring standardized LaTeX proposal templates

------------------------------------------------------------------------

## 📜 License

This project is licensed under the MIT [License](LICENSE).

You are free to use, modify, and distribute this template, provided that the original license notice is retained.

------------------------------------------------------------------------

## ⚖ Disclaimer

This repository is an unofficial LaTeX template. Users are responsible for ensuring compliance with official NSTC guidelines.
