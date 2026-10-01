# R for Core Facilities: SC3 ABRF Workshop

Unlock the power of R to optimize your core facility workflows. This hands-on workshop provides immediate value for administrative staff managing revenue trends (like iLab exports) and operational staff tracking instrument performance and turnaround times. 

Tailored specifically for beginners within the Association of Biomolecular Resource Facilities (ABRF) community, this session covers essential data importing, wrangling, and visualization using real-world core metrics. Participants will leave with practical, reproducible scripts ready to analyze operational efficiency and financial trends at their home institutions.

🌐 **Workshop Website & Materials:** [devonjboland.github.io](https://devonjboland.github.io)

## 📋 Pre-Workshop To-Do List

To get the most out of our time together, registered attendees should complete the following before the workshop:
1. **Install R and Positron:** We will be using [Positron](https://github.com/posit-dev/positron), the new user-friendly IDE from Posit.
2. **Clone/Download this Repository:** Download the repository to your local machine to access the scripts and datasets.

## 🕒 Workshop Timeline & Modules

**00:00 - 00:35 | Module 1: The Modern R Ecosystem & Project Sandbox**
*   *Goal:* Overcome the initial setup hurdle and introduce modern tools.
*   Welcome to Positron & basic navigation.
*   The reproducibility crisis: Using `renv` (virtual environments) to lock down package versions so your scripts work for the whole team.
*   Installing and loading CRAN packages, and setting up the Tidyverse.

**00:35 - 01:10 | Module 2: R Syntax & Core Data Structures**
*   *Goal:* Demystify code mechanics without getting bogged down in computer science theory.
*   Variable assignment (`<-`), calling functions, and deciphering basic error messages.
*   Data Frames and Tibbles: The R equivalent of an Excel spreadsheet.
*   Importing dirty data: Reading `.csv` and `.xlsx` files exported from core management software using `readr` and `readxl`.

**01:10 - 01:20 | Break**
*   Catch-up, troubleshooting buffer, environment debugging, and networking.

**01:20 - 02:10 | Module 3: Core Admin – Wrangling & Visualizing iLab Revenue**
*   *Goal:* Give admin-facing staff immediate value by aggregating and plotting financial metrics.
*   Data wrangling with `dplyr`: Filtering out internal test accounts, chaining commands with the pipe (`|>`), and extracting Month/Quarter from timestamps.
*   Visualizing trends with `ggplot2`: Building bar charts for seasonal dips, stacked charts for institution types, and exporting publication-quality plots.
*   *Dataset:* iLab revenue tracking (exported from the TAMU TIGSS Genomics Core iLab page).

**02:10 - 02:55 | Module 4: Core Operations – Instrument QA/QC & Analytics**
*   *Goal:* A deeply technical, operations-focused module designed for the staff running the instruments.
*   QC Data Wrangling: Handling missing values (NAs) from failed runs in instrument run logs.
*   Comparing Groups: Using t-tests and ANOVA to compare performance across machine operators or prep protocols.
*   Tracking Drift: Using linear regression to plot control sample values over time and detect baseline instrument drift before failure.
*   *Datasets:* Simulated Mass-Spec QC logs and NGS sample turnaround times.

**02:55 - 03:00 | Wrap-up**
*   Reviewing ABRF community channels.
*   Next steps and resources for continuing your R skill development.

## 📂 Repository Contents

*   `data/`: Datasets used during the workshop, including:
    *   iLab Revenue Tracking export examples.
    *   `mass_spec_qc_logs.csv` (Time-series data for tracking instrument drift).
    *   `genomics_core_ops.xlsx` (Turnaround time tracking for NovaSeq/MiSeq platforms).

## 👤 Instructor

**Devon J. Boland, Ph.D.**  
Program Chair, South Central Core Collective (SC3)
President-elect, Texas Genetics Society
Assistant Research Scientist, Texas A&M Institute for Genome Sciences & Society  
Texas A&M University
