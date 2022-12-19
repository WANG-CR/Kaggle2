# Kaggle Competition 2 IFT 6390

## Author
Chuanrui Wang, matricule no. 20242243
Jianan Zhao, matricule no. 20242788

## Package dependencies

```
numpy 
pandas
torch
matplotlib
sklearn
nltk
huggingface/transformers
```

for full packages, see environment.yml

## How to run the code:

- Remark: before running the above scripts, please create a sub-repository called 'data' to put all csv files.
- `python preprocess_data.py` to preprocess and filter the data with nltk toolkit. Run it before the other 3 basic methods.
  
- `python naive_bayes.py` to train NB model and give prediction under the model's best hyperparameters.

- `python svm_linear_kernel.py` to train kernelized SVM model and give prediction under the model's best hyperparameters.

- `python neural_network.py` to train neural network model and give prediction under the model's best hyperparameters.

- `python src/models/Bert/train.py` to train Bert model and give prediction under the model's best hyperparameters.

  

