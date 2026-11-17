# The Legacy of Colonial Medicine in Central Africa – seminar slides

45-minute seminar presentation in which we present the paper as its authors.
Built on the SMILE beamer template (Nasy, https://github.com/uta-smile/beamer-theme).

## Files
- `main.tex`: the slides (edit here)
- `smile_styles.tex`: the theme (footer, colours, blocks)
- `references.bib`: bibliography (natbib + BibTeX)
- `figures/`: maps and plots taken from the paper

## Overleaf
New Project → Upload Project → choose the .zip. Compiler: pdfLaTeX (the default).
For a version without animation steps (printing, sharing), add `handout` to the class
options: `\documentclass[aspectratio=1610,handout]{beamer}`.

## Title slide
Only the three first names and the line "Master of Economics – École Normale Supérieure
Paris-Saclay". Add surnames in `\author{...}` and replace `\today` by the date of the talk
in `\date{...}` (the same date appears in the footer).

## Timing plan (30 numbered slides, about 43 min + 2 min buffer)
| Section | Slides | Time |
|---|---|---|
| 1 Introduction (puzzle, research question, preview, literature, gaps) | 1–5 | 7 min |
| 2 Historical background | 6–9 | 5 min |
| 3 Data | 10–11 | 3 min |
| 4 Empirical strategy | 12–15 | 6.5 min |
| 5 Results | 16–21 | 9 min |
| 6 Mechanisms and policy relevance | 22–24 | 4.5 min |
| 7 Discussion and conclusion | 25–30 | 8 min |

Suggested split: speaker 1 = sections 1–2 (about 12 min); speaker 2 = slides 10–20
(about 16.5 min); speaker 3 = slide 21 to the end (about 14.5 min).
If you run late, slides 20 (other robustness checks) and 29 (beyond the paper) can be
shortened to one sentence each.

## Where each grading criterion is covered
| Criterion (points) | Slides |
|---|---|
| Research question (1) | 2 |
| Literature review and gaps (2) | 4–5, references at the end |
| Methodology (2) | 10–15 |
| Main results and interpretation (4) | 16–24 |
| Critical analysis (4) | 25–28: strengths, identification, data quality, replicability, ethics, external validity |
| Bonus: comparisons and advanced critique, discussion (2) | 29 and the final slide with three questions for the audience |
| Slide design, flow, time (3) | outline slide at each section, figures and diagrams, a few animation steps, timing plan above |
| Response to questions (2) | backup slides |

## Backup slides
Everything after `\appendix` is a backup slide. Backup slides are not counted: the footer
shows "x/30" during the talk and "Backup" on the backup slides. Buttons in the main slides
jump to the backups; "Back" buttons return to the main slide.
To add one: give it `[label=bk-something]` (hyphens, not colons, in labels) and link to it
with `\backupbutton{bk-something}{Text}`.
