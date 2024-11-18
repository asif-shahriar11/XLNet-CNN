## Datasets

The datasets used in this study—**OHSUMED**, **CAVES**, and **HateXplain**—are available in the `data` directory.  These datasets have been carefully preprocessed to adapt them for use in a **multi-label classification** setting. 


## Model Codes

The model codes for each dataset are organized into separate directories:  
- **CAVES**: `caves-models`
- **OHSUMED**: `ohsumed-models`
- **HateXplain**: `hatespeech-models`

Each directory contains four Jupyter Notebook (`.ipynb`) files, one for each model used in the study. Below is the directory structure for clarity:

```
├── caves-models │ ├── caves-BERT.ipynb │ ├── caves-CTBERT.ipynb │ ├── caves-XLNet.ipynb │ ├── caves-XLNet-CNN.ipynb │ ├── ohsumed-models │ ├── ohsumed-BERT.ipynb │ ├── ohsumed-CTBERT.ipynb │ ├── ohsumed-XLNet.ipynb │ ├── ohsumed-XLNet-CNN.ipynb │ ├── hatespeech-models │ ├── hatespeech-BERT.ipynb │ ├── hatespeech-CTBERT.ipynb │ ├── hatespeech-XLNet.ipynb │ ├── hatespeech-XLNet-CNN.ipynb
```




### Description

- Each notebook in the corresponding directory is dedicated to a specific model. For example:
  - `caves-BERT.ipynb` contains the implementation of the BERT model for the **CAVES** dataset.
  - `ohsumed-CTBERT.ipynb` implements the CT-BERT model for the **OHSUMED** dataset.
  - `hatespeech-XLNet-CNN.ipynb` contains the XLNet-CNN model for the **HateXplain** dataset.

- These notebooks include the preprocessing, training, evaluation, and performance analysis of each model.

Feel free to explore the directories and open the corresponding `.ipynb` files for detailed implementations and results.
