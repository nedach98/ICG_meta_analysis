# ICG meta-analysis

Analysis notebook, Excel data files, and generated figures.

Open `ICG_meta_analysis.ipynb` in Jupyter with pandas, numpy, matplotlib,
scipy, statsmodels, and openpyxl installed.

## Large figure

`figs/figure3.tiff.zip` contains the original, unmodified `figure3.tiff`.
The TIFF exceeds GitHub's 100 MiB per-file limit and is stored as a lossless
ZIP archive. Extract it into `figs/` to restore the original file.

The local Python virtual environment and system/cache files are excluded.

## Repository contents and exclusions

The repository keeps the analysis source, study-level Excel tables, and figures.
`ICG(1).xlsx` is retained because the notebook still references that legacy input;
`ICG2.xlsx` is used for the primary analysis.

The published notebook has stored outputs, error tracebacks, execution counts,
and editor metadata removed. Its analysis source is preserved. Private review
notes, manuscript drafts, Office lock files, credentials, and local environments
are excluded through `.gitignore`.

## Analysis status

This is the existing research analysis, not a fully validated reproducible pipeline.
Some cells depend on earlier interactive state, use legacy row-index alignment,
or contain manually entered figure summaries. The current models treat cohort
rows as independent, including multiple arms from the same publication.
