# Quarto templates for [Accounting Research: An Introductory Course](https://iangow.github.io/far_book/)

This page provides Quarto templates for use with the course book [Accounting Research: An Introductory Course](https://iangow.github.io/far_book/).

To use a template, you will need [Quarto](https://quarto.org).
A recent installation of [RStudio](https://posit.co/downloads/) will include Quarto.
See instructions [here](https://iangow.github.io/far_book/intro.html#install) for setting up your computer to use this course book.

To download a template, simply "right click" a link below and save the template on your computer, then open it on your computer.

For each template provided below, we have prepared suggested solutions (as both executable Quarto files and the PDFs these produce).
Instructors can contact [Ian Gow](mailto:ian.gow@unimelb.edu.au) for these solutions.

## Templates

Each template below shares its name with the corresponding chapter in the [book](https://iangow.github.io/far_book/).

For chapters of the book that use the WRDS PostgreSQL database, we have also included a template that uses a local parquet repository as described in [an appendix](https://iangow.github.io/far_book/parquet-wrds.html) of the book.
To use these templates, you simply need to have downloaded the needed parquet files and edit the line in the template to set `DATA_DIR` to the location of these files on your hard drive.

### Part I: Foundations

| Chapter | PostgreSQL template | Parquet template |
|---------|---------------------|------------------|
| Describing data | [r-intro.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/r-intro.qmd) | Use PostgreSQL template |
| Regression fundamentals | [reg-basics.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/reg-basics.qmd) | Use PostgreSQL template |
| Causal inference | [causal-inf.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/causal-inf.qmd) | Use PostgreSQL template |
| Statistical inference  | Template to come | Template to come |
| Financial statements: A first look | [fin-state.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/fin-state.qmd) | [fin-state-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/fin-state-pq.qmd) |
| Financial statements: A second look | [fin-state-reprise.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/fin-state-reprise.qmd) | [fin-state-reprise-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/fin-state-reprise-pq.qmd) | 
| Linking databases | Template to come later | Template to come later
| Importing data | [web-data.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/web-data.qmd) | Use PostgreSQL template |

### Part II: Capital markets research

| Chapter | PostgreSQL template | Parquet template |
|---------|---------------------|------------------|
| Capital markets research in accounting | [cap-mkts.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/cap-mkts.qmd) | [cap-mkts-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/cap-mkts-pq.qmd) |
| FFJR | [ffjr.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/ffjr.qmd) | [ffjr-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/ffjr-pq.qmd) |
| Ball and Brown (1968) | [bb68.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/bb68.qmd) | [bb68-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/bb68-pq.qmd) |
| Beaver (1968) | [beaver68.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/beaver68.qmd) |  [beaver68-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/beaver68-pq.qmd) |
| Event studies | [event-studies.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/event-studies-pq.qmd) | [event-studies.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/event-studies-pq.qmd) |
| Post-earnings announcement drift | [pead.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/pead.qmd) | Template to come |
| Accruals | [accruals.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/accruals.qmd) | Template to come |
| Earnings management | [earnings-mgt.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/earnings-mgt.qmd) | Template to come |

### Part III: Causal inference

| Chapter | PostgreSQL template | Parquet template |
|---------|---------------------|------------------|
| Natural experiments | [natural.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/natural.qmd) | Template to come |
| Causal mechanisms | [mechanisms.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/mechanisms.qmd) | Template to come |
| Natural experiments revisited | [natural-revisited.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/natural-revisited.qmd) | Template to come |
| Instrumental variables | [iv.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/iv.qmd) | Template to come |
| Panel data | [panel-data.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/panel-data.qmd) | Template to come |
| Regression discontinuity designs | [rdd.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/rdd.qmd) | Template to come |
 
### Part IV: Additional topics

| Chapter | PostgreSQL template | Parquet template |
|---------|---------------------|------------------|
| Beyond OLS | Template to come | Template to come |
| Extreme values and sensitivity analysis | Template to come | Template to come |
| Matching | Template to come | Template to come |
| Prediction | Template to come | Template to come |

### Other files

 - Bibliography file: [`book.bib`](https://raw.githubusercontent.com/iangow/far_templates/main/book.bib)
