# OldScript Repository

This repository appears to contain code for generating PDFs based on genetic data.
However, several required source files are missing, most notably `helper.py` and
`main.py`. Only compiled versions of these files exist in `__pycache__` and
cannot be reliably decompiled in this environment. Without them the program's
logic is incomplete and cannot be executed or tested.

## Current contents
- `compute.py` – main logic for building PDF reports using ReportLab.
- `constants/` – constants and utility functions used within `compute.py`.
- Various data files (`Database.xlsx`, `current_Database.xlsx`, etc.).
- Log files and compiled `.pyc` files (not needed for source control).

## Issues
- Missing modules (`helper.py`, `main.py`), so the code cannot run.
- Many large binary files and logs were committed which should normally be
  excluded from version control.

## Recommendation
To restore functionality you will need the original `helper.py` and `main.py`
source files. Once those are available, remove unnecessary binaries and logs
from version control and add appropriate tests.
