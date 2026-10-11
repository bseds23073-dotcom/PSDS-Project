# Know Your Data: Under-5 mortality in South Asia (WDI, 2000-2023)

Part A of Assignment 1, Problem Solving with Data Science (ITU, Fall 2026).
Partners: Mustafa Shahid, Ayan Mahmood

## How to reproduce
1. `pip install -r requirements.txt`
2. Put the untouched World Bank extract in `data/raw/` (see `data/raw/README.md`).
3. `python src/load_and_reshape.py`  (raw -> long/panel format, no cleaning decisions)
4. Open `notebooks/01_cleaning_eda.ipynb` and run top to bottom.
   Optional: `python src/fetch_data.py` re-pulls the same series from the WDI API.

## Files
PROPOSAL_v2.md, CLEANING.md, DATA_DICTIONARY.md, JOURNAL.md,
LIMITATIONS.md, CONTRIBUTIONS.md, AI_USE_LOG.md
