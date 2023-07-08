# iMRSAPred.

 iMRSAPred: Improved Prediction of Anti-MRSA peptides using Pysicochemical Properties and Interaction Energy of Amino Acids

##Pipeline

###iMRSAPred uses the following dependencies:

MATLAB2018a 
python 3.8
numpy
scipy 
pandas
scikit-learn
imblearn
matplotlib
catboost
gc_forset *xgboost-1.5.0
pickle
###Guiding principles:

**The data contains training dataset and testing dataset. Training dataset includes TR_SCMRSA.fasta and Testing dataset includes TS_SCMRSA

**Feature extraction: DDE is the implementation of Dipeptide Deviation from Expected Mean .ExPseAAC is the implementation of Extended Pseudo Amino Acid Composition. RCEM_T contains the Pairwise Contact Energy Matrix features

** Classifier: This director contain the Deep Forest, Catboost, KTBoost, HisgGradientBoost etc ML classifiers implementation to predict AntiMRSA peptides.

##Pipeline

###iMRSAPred uses the following dependencies:

MATLAB2018a *blast-2.6.0+
python 3.7
numpy
scipy *pandas
scikit-learn
gc_forset *xgboost-1.5.0
KTBoost.KTBoost as KTBoost
sklearn.experimental for enable_hist_gradient_boosting
sklearn.ensemble for HistGradientBoostingClassifier
###Guiding principles:

**The data contains training dataset and testing dataset. Training dataset includes TR_SCMRSA.fasta, testing dataset TS_SCMRSA.fasta

**Feature extraction: DDE is the implementation of Dipeptide Deviation from Expected Mean  . ExPseAAC is the implementation of Extended Pseudo Amino Acid Composition. RCEM_T cantain Pairwise Contact Energy Matrix features.

** Classifier: Cascade Deep Forest, CatBoost , KTBoost HistGradientBoostingClassifier is the implementation of ML algorithms to predict Anti_MRSA peptides.
