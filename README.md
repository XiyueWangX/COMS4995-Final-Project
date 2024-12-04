# COMS4995-Final-Project
## Instacart Market Basket Analysis

### Dataset
The dataset used for this project is from a Kaggle competition released by Instacart. Its Kaggle page is [here](https://www.kaggle.com/competitions/instacart-market-basket-analysis/overview).

### Structute
* `Data`: a directory containing all the datasets, including the raw datasets in `.csv` format and feature engineered/preprocessed datasets in `.pkl` format. The final dataset used for prediction is `Finaldata.pkl`.
* `preprocess.ipynb`: python notebook for preprocessing the raw datasets into the final dataset.
* `logistic_regression.ipynb`: python notebook implementation for logistic regression model.
* `DT.ipynb`: python notebook implementation for decision tree model.
* `XGB.ipynb`: python notebook implementation for XGBoost model.
* `DNN.ipynb`: python notebook implementation for neural network model.

### Setup
To replicate the result of any above model, directly running the corresponding notebook in Google Colab suffices. Make sure to change the Colab runtime type to GPU to enable CUDA/GPU support. To run a localized version, make sure you have a correct GPU driver installed and its supporting CUDA version configured.

### Results
* Logistic regression:
  * Accuracy Score: 0.7619
  * ROC AUC Score: 0.8232
* Decision Tree:
  * Accuracy Score: 0.9081
  * ROC AUC Score: 0.8170
* XGBoost:
  * Accuracy Score: 0.7411
  * ROC AUC Score: 0.8341
* Neural Network:
  * Accuracy Score: 0.91015
  * ROC AUC Score: 0.83476
  
### Resources
* For GPU driver and CUDA version, please refer to this [link](https://docs.nvidia.com/cuda/cuda-toolkit-release-notes/index.html).
* [Tutorial notebook](https://colab.research.google.com/notebooks/gpu.ipynb) to enable GPUs in Colab.
* EDA slides are available [here](https://docs.google.com/presentation/d/16I7d0XtlW1DUeF7p1g67DKxpVwQDj8k9/edit?usp=sharing&ouid=111127467148301857990&rtpof=true&sd=true).

### Citations
```
@misc{instacart-market-basket-analysis,
    author = {jeremy stanley and Meg Risdal and sharathrao and Will Cukierski},
    title = {Instacart Market Basket Analysis},
    year = {2017},
    howpublished = {\url{https://kaggle.com/competitions/instacart-market-basket-analysis}},
    note = {Kaggle}
}
```
