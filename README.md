# Kaggle Seizures Competition

# Changelog

## 10.09.16 00:07

* Refactoring of the notebook (deleted extra cells, added md-titles, cleared output)

## 09.09.16 23:32

* mat_to_pd()
* FFT histogram bins as features (PCA shows that it's a bad set of features + RF shows results ~0.5 roc_auc)
* save_to_npz()
* t-test showed that number of peaks in data does not matter 
