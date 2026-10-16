# Gallstone Disease Classification

Compare an interpretable linear classifier with a tree ensemble and inspect the types of errors they make.

**Python · scikit-learn · Logistic Regression · Random Forest**

## Project at a glance

For the recorded 70:30 split, Logistic Regression has test ROC-AUC 0.8142 and accuracy 0.7292; Random Forest has ROC-AUC 0.7361. A separate 80:20 experiment is included. These are exploratory comparisons, not clinical validation.

## Technical work

- Missing-value handling and mixed-feature preprocessing
- Stratified splitting and cross-validation
- Hyperparameter search and train–validation gap analysis
- Confusion matrices, sensitivity to split ratio and feature analysis

## Explore the evidence

- [SIT720_6_2C_Gallstone_Classification_FINAL.ipynb](SIT720_6_2C_Gallstone_Classification_FINAL.ipynb)
- [SIT720_6_2C_Gallstone_Classification_FINAL_Report.pdf](SIT720_6_2C_Gallstone_Classification_FINAL_Report.pdf)

## Run locally

```bash
python -m venv .venv
# Activate the environment, then:
python -m pip install jupyter numpy pandas matplotlib scikit-learn ucimlrepo
jupyter notebook
```

Follow the notebook's local_file and configured download settings for the Gallstone dataset.

Open the linked notebook and run the cells in order. Package names reflect the source imports; a fresh environment was not tested during this documentation update. Dataset downloads require internet access.

## Limitations and status

Small public dataset; model recommendation in the source also refers to test results. Further independent evaluation is needed before treating the recommendation as validated.

The repository preserves saved notebook outputs. Results are from those outputs, not a new execution.

**Author:** Zenith Anthony Dabarera · SIT720 Machine Learning  
[AI/ML portfolio](https://github.com/Zenith1997)
