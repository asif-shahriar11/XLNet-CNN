## Introduction

This repository contains the code and data of the paper titled **"XLNet-CNN: Combining Global Context Understanding of XLNet with Local Context Capture through Convolution for Improved Multi-Label Text Classification"**, which has been accepted at **NSysS 2024**.

Our proposed model, **XLNet-CNN**, builds upon XLNet's strength in global context understanding by incorporating a 1D CNN layer to capture local dependencies and patterns within the text. This combination allows the model to recognize important phrases and word combinations, which are crucial for multi-label text classification. Our experiments on three distinct datasets — Ohsumed (medical abstracts), CAVES (anti-COVID vaccine tweets), and HateXplain (cyberbullying detection)—demonstrate that XLNet-CNN consistently outperforms XLNet and domain-specific BERT models in terms of F1-score.

## Datasets

The datasets used in this study—**OHSUMED**, **CAVES**, and **HateXplain**—are available in the `data` directory.  These datasets have been carefully preprocessed to adapt them for use in a **multi-label classification** setting. 


## Model Codes

The model codes for each dataset are organized into separate directories:  
- **CAVES**: `caves-models`
- **OHSUMED**: `ohsumed-models`
- **HateXplain**: `hatespeech-models`

Each directory contains four Jupyter Notebook (`.ipynb`) files, one for each model used in the study. Below is the directory structure for clarity:

```
├── caves-models │
  ├── caves-bert.ipynb │
  ├── caves-ctbert.ipynb │
  ├── caves-xlnet.ipynb │
  ├── caves-xlnet-cnn.ipynb │ 
├── ohsumed-models │
  ├── ohsumed-bert.ipynb │
  ├── ohsumed-biobert.ipynb │
  ├── ohsumed-xlnet.ipynb │
  ├── ohsumed-xlnet-cnn.ipynb │ 
├── hatespeech-models │
  ├── hatespeech-bert.ipynb │
  ├── hatespeech-hatebert.ipynb │
  ├── hatespeech-xlnet.ipynb │
  ├── hatespeech-xlnet-cnn.ipynb
```




### Description

- Each notebook in the corresponding directory is dedicated to a specific model. For example:
  - `caves-BERT.ipynb` contains the implementation of the BERT model for the **CAVES** dataset.
  - `ohsumed-CTBERT.ipynb` implements the CT-BERT model for the **OHSUMED** dataset.
  - `hatespeech-XLNet-CNN.ipynb` contains the XLNet-CNN model for the **HateXplain** dataset.

- These notebooks include the preprocessing, training, evaluation, and performance analysis of each model.

Feel free to explore the directories and open the corresponding `.ipynb` files for detailed implementations and results.
