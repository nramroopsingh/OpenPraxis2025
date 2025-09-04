

# Open vs Print: Learning, Access, and Perception  
**Same Course, Open vs Print: Learning, Access, and Perception: A comparative study of online open vs. traditional print textbooks in BIOL 1110**

[![R](https://img.shields.io/badge/R-4.x-blue)]() [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)]() [![Made with ggplot2](https://img.shields.io/badge/ggplot2-%F0%9F%8E%A8-black)]()

## Overview
This project analyzes survey and course-marks data to compare **online open textbooks** and **traditional print textbooks** used by first-year biology students. We examine:
- Overall satisfaction  
- Accessibility  
- Perceived learning effectiveness  
- Academic performance (percentage marks & letter grades)

> **Key findings (high level):**  
> - **Accessibility:** Online textbooks rated significantly more accessible (*p* = 0.013).  
> - **Satisfaction & Effectiveness:** No significant difference between formats.  
> - **Performance:** No significant difference in marks; Cohen’s *d* ≈ −0.25 (small/negligible).  
> - **Preference:** Visual trends favor digital/hybrid formats for future courses.

## Repository Structure


```text
.
├─ data/
│  ├─ BIOL 1110 Survey on Open Online Textbooks.csv
│  ├─ BIOL 1110 Survey on Traditional Textbooks.csv
│  └─ online_traditional_marks.xlsx
├─ R/
│  └─ 01_open_vs_print.Rmd
├─ figures/
│  ├─ satisfaction_plot.png
│  ├─ accessibility_plot.png
│  ├─ effectiveness_plot.png
│  ├─ future_preference_plot.png
│  ├─ box_plot.png
│  ├─ histogram_online_plot.png
│  └─ histogram_traditional_plot.png
├─ README.md
└─ LICENSE
## Data

- **Survey files:**  
  - `BIOL 1110 Survey on Open Online Textbooks.csv`  
  - `BIOL 1110 Survey on Traditional Textbooks.csv`  

- **Marks:**  
  - `online_traditional_marks.xlsx` (contains percentage grades and letter grades for Online/Traditional cohorts)  

⚠️ *Privacy note: Ensure student identifiers are removed or anonymized before sharing.*
