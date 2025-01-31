# Cl-Code
Repository for code used to analyze chloride ion concentration data.

# Datasets
traindata_originalmodel and testdata_originalmodel contain the datasets used to train and test the original RF model. 

traindata_retrainedmodel and testdata_retrainedmodel contain the datasets of non-random repeat data used to train and test the retrained RF model. 

nonrandom_order_dataset is the complete dataset of the non-random repeat data. Same data as the train and test files above, just in one dataset.

random_order_dataset is the complte dataset of the random order repeat data.

# Models

original_model.rds is the original RF model with two features.
retrained_model.rds is the rtrained RF model with three features.
