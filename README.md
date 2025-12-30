# Bookshelf Project (2025-12-27)

Short project to clean, document, and analyze a personal bookshelf export. Contains raw CSV data, a Jupyter notebook for cleaning/analysis, and the cleaned output.

## Repository structure
- Bookshelf-2025-12-27.csv — raw export (source of truth)
- cleaned_bookshelf.csv — cleaned output produced by the notebook
- Bookshelfproject.ipynb — data cleaning, exploration, and visualizations
- README.md — this file

## Goals
- Clean and normalize bookshelf metadata (titles, authors, years, identifiers, categories).
- Produce a reproducible cleaned CSV.
- Provide basic exploratory analysis and visualizations.

## Quick setup (Windows)
1. Create & activate a venv:
```powershell
python -m venv .venv
.venv\Scripts\activate
```
2. Install dependencies:
```powershell
pip install -r requirements.txt
# or
pip install jupyter pandas numpy matplotlib seaborn
```
3. Launch the notebook:
```powershell
jupyter notebook Bookshelfproject.ipynb
```

## Usage
- Open and run all cells in Bookshelfproject.ipynb to reproduce cleaning steps and analyses.
- The notebook saves the cleaned dataset to cleaned_bookshelf.csv in the repo root (see notebook cell that writes the CSV).

## Data notes
- See the CSV header in Bookshelf-2025-12-27.csv for the dataset schema.
- Cleaning steps in the notebook include: trimming/normalizing text, parsing dates/years, deduplicating records, standardizing categories, and handling missing values.

## Reproduce from command line (optional)
- If a script exists (e.g., scripts/clean_books.py), run:
```powershell
python scripts/clean_books.py --input Bookshelf-2025-12-27.csv --output cleaned_bookshelf.csv
```
- Otherwise, run the notebook and export the cleaned CSV.

## Tests & CI
- No automated tests included by default. Add unit tests for cleaning functions if you extract them to .py modules.

## Contributing
- Fork, make changes, and open a pull request. Document data-source changes and cleaning logic additions in the notebook or a CHANGELOG.

## Contact
- Author: Thenmozhi Boopathy and contact : thenmozhi.boopathy@gmail.com.

```// filepath: c:\Users\thenboo\OneDrive\Documents\MSBA\ISA 514 BigData\BookshelfProject\README.md

# Bookshelf Project (2025-12-27)

Short project to clean, document, and analyze a personal bookshelf export. Contains raw CSV data, a Jupyter notebook for cleaning/analysis, and the cleaned output.

## Repository structure
- Bookshelf-2025-12-27.csv — raw export (source of truth)
- cleaned_bookshelf.csv — cleaned output produced by the notebook
- Bookshelfproject.ipynb — data cleaning, exploration, and visualizations
- requirements.txt — (optional) pinned dependencies
- README.md — this file

## Goals
- Clean and normalize bookshelf metadata (titles, authors, years, identifiers, categories).
- Produce a reproducible cleaned CSV.
- Provide basic exploratory analysis and visualizations.

## Quick setup (Windows)
Launch the notebook:
```powershell
jupyter notebook Bookshelfproject.ipynb
```

## Usage
- Open and run all cells in Bookshelfproject.ipynb to reproduce cleaning steps and analyses.
- The notebook saves the cleaned dataset to cleaned_bookshelf.csv in the repo root (see notebook cell that writes the CSV).

## Data notes
- See the CSV header in Bookshelf-2025-12-27.csv for the dataset schema.
- Cleaning steps in the notebook include: trimming/normalizing text, parsing dates/years, deduplicating records, standardizing categories, and handling missing values.

## Contributing
- Fork, make changes, and open a pull request. Document data-source changes and cleaning logic additions in the notebook or a CHANGELOG.

## Contact
- Author:   Thenmozhi Boopathy
- Contact : thenmozhi.boopathy@gmail.com
