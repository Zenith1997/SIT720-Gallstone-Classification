# Dataset and reproducibility notes

This project uses the **UCI Gallstone Disease dataset**, retrieved in the notebook via `ucimlrepo.fetch_ucirepo(id=1150)` when a local copy is absent.

The notebook first looks for `dataset-uci.csv` or `gallstone.csv` and then tries the UCI API. Use the original UCI source and check the data's reuse licence before republishing. The source experiment contains 319 observations and 38 predictors.

Reported classification metrics are historical saved notebook outputs. The GitHub Action checks JSON structure only; it does not retrain the model or independently verify clinical performance.

## Running the original notebook

```bash
python -m pip install -r requirements.txt
jupyter notebook SIT720_6_2C_Gallstone_Classification_FINAL.ipynb
```

These are version *ranges*, not an exact captured original environment. A fresh run has not been validated by this documentation update.
