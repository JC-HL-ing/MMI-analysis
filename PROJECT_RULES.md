# Project Rules

1. Keep the full analysis workflow in the notebook. Do not move the logic into separate `.py` files.
2. Read the original `.loglaserscan_ymlz` measurement file directly from this folder.
3. Keep the notebook order simple: load data, find local peaks/deeps, fit IL, calculate ER, then plot.
4. Use beginner-friendly variable names, short comments, and short Markdown explanations.
5. If you change detection settings, update only the parameter cell so the rest of the notebook stays easy to follow.
6. The main output should stay as four subplots:
   - raw data
   - `gc1->gc2` raw data with peak/deep markers and fitted envelopes
   - `gc1->gc3` raw data with peak/deep markers and fitted envelopes
   - ER curves
