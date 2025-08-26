# 📓 Conditional Recoding Notebook for Epidemiologic Analysis

This repository contains an RMarkdown notebook that demonstrates conditional 
recoding of raw survey variables for epidemiologic research. It showcases 
steps to confirm final logic of your variables with reproducible techniques 
using a subset of data from BRFSS 2008 focusing on two smoking variables.

## What's Included

- **Notebook**: `ConditionalRecodingVariables.Rmd`  
  Walks through conditional logic, recoding, and manual table formatting in 
  RMarkdown.
  
- **PDF Output**: `ConditionalRecodingVariables.pdf`  
  Final rendered version with manually numbered tables and float-resistant 
  LaTeX layout.
  
- **Custom LaTeX Styling**: `preamble.tex`  
  Used to control table appearance, spacing, and typography during 
  PDF generation.

## Additional Modifications

- Manual control over table titles and numbering (no auto-numbering)
- Float-resistant LaTeX tables using `longtable` and raw LaTeX blocks
- Conditional logic for BRFSS smoking variables
- Clean, reproducible RMarkdown-to-PDF pipeline using `pdflatex`

## How to Reproduce

To regenerate the notebook and PDF:

1. Clone this repository
2. Open `ConditionalRecodingVariables.Rmd` in RStudio
3. Knit to PDF using `pdflatex`
4. Ensure `preamble.tex` is in the same directory

> Note: This notebook is designed for manual control over table layout and numbering. Auto-numbering and float environments are intentionally disabled.

## 👤 Author

**Lindsay Trujillo, PhD, MPH**  
Principal Data Scientist & Epidemiologist  
Specializing in reproducible analytics, regulatory documentation, 
and stakeholder-ready reporting.

## 📜 License

This project is released under the MIT License. See `LICENSE` for details.
