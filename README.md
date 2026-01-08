# NLP - Game Sentiment Analysis Project

This repository contains code and data for analyzing game reviews text from the [steam-reviews](https://www.kaggle.com/datasets/andrewmvd/steam-reviews/data) dataset, and applying ML and DL models for sentiment classification. 

## Folder Structure

```
.
├── game-sentiment-analysis.ipynb
├── README.md
├── requirements.txt
├── data/
│   ├── cleaned_dataset.csv
│   ├── dataset.csv
│   ├── dataset_balanced_500k.csv
├── figures/
│   └── *.png
├── models/
│   └── *.keras, *.pkl, *.kv, *.model
```

---

## Setup & Requirements

- Python 3.8+
- Install dependencies:
  ```
  pip install -r requirements.txt
  ```

---

## Data Acquisition

- **KaggleHub: Steam Reviews Dataset**  
  - [steam-reviews](https://www.kaggle.com/datasets/andrewmvd/steam-reviews/data)

---

## Notebooks

- **game-sentiment-analysis.ipynb**  
    Main notebook, contains code to fetch the dataset, clean it, perform text representation and model training.

## Outputs

- **figures/** — All plots that were generated in the notebook.
- **models/** — All the models that were trained. 