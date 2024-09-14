# Quarto templates for [Empirical Research in Accounting: Tools and Methods](https://iangow.github.io/far_book/)

This page provides Quarto templates for use with the course book [Empirical Research in Accounting: Tools and Methods](https://iangow.github.io/far_book/).

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
| Statistical inference  | [stat-inf.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/stat-inf.qmd) | Use PostgreSQL template |
| Financial statements: A first look | [fin-state.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/fin-state.qmd) | [fin-state-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/fin-state-pq.qmd) |
| Financial statements: A second look | [fin-state-reprise.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/fin-state-reprise.qmd) | [fin-state-reprise-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/fin-state-reprise-pq.qmd) | 
| Linking databases |  [identifiers.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/identifiers.qmd) | [identifiers-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/identifiers-pq.qmd) | 
| Importing data | [web-data.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/web-data.qmd) | Use PostgreSQL template |

### Part II: Capital markets research

| Chapter | PostgreSQL template | Parquet template |
|---------|---------------------|------------------|
| FFJR | [ffjr.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/ffjr.qmd) | [ffjr-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/ffjr-pq.qmd) |
| Ball and Brown (1968) | [bb68.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/bb68.qmd) | [bb68-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/bb68-pq.qmd) |
| Beaver (1968) | [beaver68.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/beaver68.qmd) |  [beaver68-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/beaver68-pq.qmd) |
| Event studies | [event-studies.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/event-studies-pq.qmd) | [event-studies-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/event-studies-pq.qmd) |
| Post-earnings announcement drift | [pead.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/pead.qmd) | [pead-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/pead-pq.qmd)  |
| Accruals | [accruals.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/accruals.qmd) | [accruals-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/accruals-pq.qmd)  |
| Earnings management | [earnings-mgt.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/earnings-mgt.qmd) | [earnings-mgt-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/earnings-mgt-pq.qmd) |

### Part III: Causal inference

| Chapter | PostgreSQL template | Parquet template |
|---------|---------------------|------------------|
| Natural experiments | [natural.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/natural.qmd) | Use PostgreSQL template |
| Causal mechanisms | [mechanisms.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/mechanisms.qmd) | Use PostgreSQL template |
| Natural experiments revisited | [natural-revisited.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/natural-revisited.qmd) |  [natural-revisited-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/natural-revisited-pq.qmd) |
| Instrumental variables | [iv.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/iv.qmd)  | Use PostgreSQL template |
| Panel data | [panel-data.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/panel-data.qmd) |[panel-data-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/panel-data-pq.qmd) |
| Regression discontinuity designs | [rdd.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/rdd.qmd) | Use PostgreSQL template |
 
### Part IV: Additional topics

| Chapter | PostgreSQL template | Parquet template |
|---------|---------------------|------------------|
| Beyond OLS | [glms.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/glms.qmd) | [glms-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/glms-pq.qmd) |
| Extreme values and sensitivity analysis | [extreme-vals.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/extreme-vals.qmd) | Use PostgreSQL template |
| Matching | Template to come | Template to come |
| Prediction | [prediction.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/prediction.qmd) | [prediction-pq.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/prediction-pq.qmd) |

### Other files

 - Bibliography file: [`book.bib`](https://raw.githubusercontent.com/iangow/far_templates/main/book.bib)
