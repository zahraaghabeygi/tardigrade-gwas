TARDIGRADE · MULTI-GWAS EXPLORER
Windows Portable Edition — Version 1.0.1

============================================================
ABOUT
=====

Tardigrade · Multi-GWAS Explorer is a desktop application for
comparing and analyzing gene-level signals across multiple GWAS
datasets.

The application provides tools for data preprocessing,
significant-gene extraction, gene-overlap analysis, similarity
calculation, consensus analysis, report generation, and analytical
data visualization.

This portable Windows edition includes the required runtime
components. A separate Python installation is not required.

============================================================
SYSTEM REQUIREMENTS
===================

* 64-bit Microsoft Windows
* x86-64 processor architecture
* A graphical desktop environment
* Sufficient memory for loading and processing GWAS datasets

============================================================
ARCHIVE CONTENTS
================

The extracted Tardigrade directory contains:

```
Tardigrade.exe
_internal/
outputs/
LICENSE
README.txt
```

Tardigrade.exe and the _internal directory must remain together
inside the same folder.

============================================================
HOW TO RUN
==========

1. Extract the entire ZIP archive.

2. Open the extracted Tardigrade folder.

3. Double-click:

   Tardigrade.exe

Do not move Tardigrade.exe outside the extracted folder. The
application requires the accompanying _internal directory to start
and operate correctly.

Windows may display a security warning because the application is
not digitally signed. Confirm that the application was downloaded
from one of the official project repositories before running it.

============================================================
BASIC WORKFLOW
==============

1. Open the application.

2. Add one or more supported GWAS dataset files.

3. Review the detected dataset information and file status.

4. Confirm or modify the analysis settings, including:

   P-value column
   Gene column
   Significance threshold

5. Run the analysis.

6. Review the generated report, gene-overlap results, similarity
   information, consensus results, and available visualizations.

7. Select and open any generated visualization from the results
   section.

8. Save reports, tables, or plots manually when required.

Plots are displayed for review and are not automatically saved
unless the user explicitly chooses a save or export action.

============================================================
DEFAULT ANALYSIS COLUMNS
========================

The default column names are:

```
P-VALUE
MAPPED_GENE
```

For genomic visualizations, valid chromosome and genomic-position
columns are also required.

============================================================
SUPPORTED INPUT FORMATS
=======================

The application supports common tabular GWAS data formats,
including:

```
CSV
TSV
TXT
CSV.GZ
TSV.GZ
```

Input files must contain valid tabular data and the required
analysis columns.

============================================================
OUTPUTS
=======

The included outputs directory can be used for exported reports,
tables, plots, and other generated analysis files.

Files are created only when the user selects a save or export
action.

Before sharing the application folder, remove all private,
sensitive, temporary, or test data from the outputs directory.

============================================================
IMPORTANT DATA NOTES
====================

* Gene symbols are compared as text values.
* Gene aliases are not automatically harmonized.
* Gene-symbol capitalization may affect comparisons.
* Genome-build conversion is not performed.
* Input datasets are loaded into memory.
* Very large datasets may require substantial RAM.
* Results depend on the quality, structure, and original study
  design of the input datasets.

============================================================
PROJECT REPOSITORIES
====================

Amir Izadi repository:

https://github.com/amirizadi-1/tardigrade-gwas

Zahra Aghabeygi repository:

https://github.com/zahraaghabeygi/tardigrade-gwas

============================================================
PYTHON PACKAGE
==============

The Python-library edition is available on PyPI:

https://pypi.org/project/tardigrade-gwas/

Installation command:

```
pip install tardigrade-gwas
```

============================================================
DEVELOPER PROFILES
==================

Amir Izadi:

https://github.com/amirizadi-1

Zahra Aghabeygi:

https://github.com/zahraaghabeygi

============================================================
DEVELOPMENT AND DESIGN
======================

Amir Izadi — Technical Development, Software Engineering,
and Deployment

Responsibilities included technical architecture, software
development, analytical implementation, data-processing workflow,
visualization integration, software optimization, testing,
debugging, Python-library development, packaging, and Windows/Linux
deployment.

Zahra Aghabeygi — Visual Identity, Branding, UI, and UX Design

Responsibilities included visual identity, logo design,
TARDIGRADE wordmark design, color-system development, dashboard
structure, interface components, visual hierarchy, interaction
flow, usability review, and supervision of the final visual design.

============================================================
SHARED IDEATION
===============

We contributed equally to the project’s ideation and concept
development.

The functional, analytical, visual, and product directions of
Tardigrade were shaped through continued discussion, evaluation,
and collaboration between both contributors.

============================================================
USE OF AI-ASSISTED TOOLS
========================

We used AI-assisted tools as supporting resources in selected
parts of both the technical engineering and UI/UX design
workflows.

All assisted outputs were reviewed, tested, modified, and adapted
to the specific requirements of Tardigrade.

No AI-assisted output was included in the final project without
our direct evaluation, modification, and approval.

============================================================
LICENSE
=======

Tardigrade is distributed under the MIT License.

Copyright (c) 2026 Amir Izadi and Zahra Aghabeygi

The complete license text is included in the LICENSE file
distributed with this application.

============================================================
RESEARCH-USE NOTICE
===================

Tardigrade is intended for research and educational use.

It is not a clinical diagnostic tool and must not be used as the
sole basis for medical, diagnostic, or treatment decisions.

============================================================
TROUBLESHOOTING
===============

If the application does not start:

1. Confirm that the entire ZIP archive was extracted.

2. Confirm that Tardigrade.exe and the _internal directory remain
   together.

3. Do not run Tardigrade.exe directly from inside the ZIP archive.

4. Extract the archive to a normal writable folder.

5. Check whether Windows Security or antivirus software has blocked
   or quarantined any required files.

If a dataset cannot be analyzed:

* Verify that the file format is supported.
* Verify that the required columns exist.
* Verify that P-value entries are valid numeric values.
* Confirm that the selected column names match the input file.
