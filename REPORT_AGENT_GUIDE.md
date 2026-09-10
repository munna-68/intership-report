# Next-Agent Guide — RDRS MIS Internship Report

This file tells the next agent how to add new field material to the report. Read this fully before editing.

## 1. Files

- Main report: `RDRS_MIS_Internship_Report.tex` (compiles with `latexmk -pdf RDRS_MIS_Internship_Report.tex` → 30 pages)
- Field notes: `Interview_Field_Notes_Humanized.md`
- This guide: `REPORT_AGENT_GUIDE.md` (you are here)

Never create a new `.tex`. Always edit the main file in place.

## 2. What the user will give you

User pastes raw gathered info, usually like:

```markdown
## For Chapter 2 — ...
... product names, figures, thresholds, policy details ...

## For Chapter 4 — ...
... monitoring checklist, workflows, claim paths ...
Note on sourcing: ...
```

Headings indicate target chapter but adjust to actual numbering. Figures/thresholds may need cross-check — always preserve that caveat.

## 3. What you must do (workflow)

1. Read `RDRS_MIS_Internship_Report.tex` (relevant chapters) + `Interview_Field_Notes_Humanized.md`.
2. Decide placement:
   - Org/product/savings/governance background → Chapter 2 Organizational Overview (new `\section{}` if needed)
   - Tools, data flow, checklists, insurance, compliance, approval hierarchy → Chapter 4 Analysis and Findings (new `\section{}` if needed)
   - Do not touch Chapters 1/3/5/6 unless the new material directly changes them.
3. Humanize then insert (see §4). Keep first-person observational tone: "I saw / I copied / What struck me".
4. Update support elements if new terms appear:
   - Abbreviations box (front matter) — add `ABBR -- Full form;`
   - Findings table `tab:findings` — add 1 row max per new concept
   - References — add `\bibitem{...} RDRS Bangladesh, ... (internal, reviewed during placement).`
5. Compile: `latexmk -pdf -interaction=nonstopmode RDRS_MIS_Internship_Report.tex` must end with `Output written ... .pdf` and zero `! LaTeX Error`.
6. Reply with: where you added it (chapter/section), 3-6 bullet summary of changes, quality score table (§4.3).

## 4. Writing rules — humanizer-zh (mandatory)

Core 5 principles:
1. Delete filler openers and emphasis crutches (moreover, crucially, vibrant, tapestry, landscape, seamless, robust).
2. Break formula structure: no "not only...but also", no "this is not X, it is Y", no forced 3-item lists (use 2 or 4).
3. Vary rhythm. Mix short and long sentences. Never end 3 paragraphs the same way.
4. Trust reader. State facts directly. No softening, no hand-holding, no explaining metaphors.
5. Delete quotable punchlines. If it sounds like a slogan, rewrite flat.

Also banned:
- Em-dash reveals (— ensuring / — reflecting). Use period + new sentence.
- Bold `**Term:** definition` vertical lists. Fold into prose or a table.
- Emojis, `**` overuse, Title Case Headings, curved-quote churn.
- Vague attribution ("experts say", "industry reports"). Name the source or cut it.
- "As proof of / marks a pivotal moment / broader trend / plays a key role". Just give date + what it does.

Voice target: plain BBA field intern. Concrete numbers over adjectives. "Water Credit is BDT 10,000–100,000 in 93 branches across six districts: ..." beats "innovative portfolio addressing dual livelihood/protection goals".

### Quality score (include in every reply)

| 维度 | 标准 | 得分 |
|---|---|---|
| 直接性 | straight vs padded | /10 |
| 节奏 | varied vs mechanical | /10 |
| 信任度 | concise vs over-explained | /10 |
| 真实性 | human vs robotic | /10 |
| 精炼度 | no redundancy | /10 |
| 总分 | | **/50** |

45-50 excellent, 35-44 good, <35 revise.

## 5. LaTeX style rules (this repo is styled — follow it)

Local TeX Live is MINIMAL. Available: `color, colortbl, array, longtable, multicol, fancyhdr, geometry, graphicx, amsmath, url, lmodern`. Missing: `xcolor, booktabs, microtype, enumitem, caption, titlesec, tikz, etoolbox` (so `hyperref` is conditionally loaded only).

Do:
- Colors: `RDRSBlue, RDRSTeal, RDRSOrange, RDRSLight, RDRSGrey, RDRSMidGrey` (defined via `color.sty`).
- Boxes: `\highlightbox{...}`, `\keybox{...}`, `\warnbox{...}` (fcolorbox-based, safe everywhere).
- Tables: `\begin{table}[htbp]`, header row `\rowcolor{RDRSBlue}\headercell{A} & \headercell{B}...`, `\hline` after header. Never use `\hline\hline`.
- Figures: wrap in `\fcolorbox{RDRSBlue|RDRSTeal}{RDRSLight}{\begin{minipage}{0.92\textwidth}...\end{minipage}}`. Use `$\rightarrow$` / `$\longrightarrow$` / `$\blacktriangleright$` for flows. No `picture` environment.
- Captions auto-styled (blue bold label). Just use `\caption{...}\label{...}`.
- Chapters/sections auto-styled (blue). Just use `\section{}`, `\subsection{}`.
- Escape `% & _` in text. Use `--` for ranges, `\%` for percent, `BDT~15,000` style non-breaking space before numbers where natural.

Do NOT:
- Add `\usepackage{xcolor, booktabs, microtype, enumitem, caption, titlesec, tikz, tcolorbox, setspace, hyperref}` unconditionally — local compile will break. The preamble already does `\IfFileExists{...}` conditional loading for Overleaf enhancement. Leave preamble alone unless asked.
- Use `\framebox`, raw `\colorbox`, raw `\fbox`, or `[h]`-only floats.
- Reformat title page unless asked — it is final.

## 6. Example

Input:
> Water Credit — BDT 10,000–100,000, 93 branches, 6 districts, with hygiene training.

Good output (Ch.2):
> Water Credit is a WASH-linked loan of BDT 10,000–100,000 for safe water and sanitary latrine installation. It runs in 93 branches across six districts: Dinajpur, Nilphamari, ... The loan comes with technical help and hygiene training, not cash alone.

Bad output (do not write):
> Moreover, Water Credit serves as a testament to RDRS's crucial role in the evolving WASH landscape — ensuring vibrant, seamless, and robust outcomes. This is not just credit, but empowerment.

## 7. Reply template

```markdown
Done — added to [Ch.X §Y] in RDRS_MIS_Internship_Report.tex, compiles to [N] pages.
- ...
- ...
Quality: 直接性 x/10, 节奏 x/10, 信任度 x/10, 真实性 x/10, 精炼度 x/10 = total/50.
Caveat: [figures to re-check, if any].
```
