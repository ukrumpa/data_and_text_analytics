# Data and Text Analytics

Coursework and practical work for Data and Text Analytics.

## Repository structure

```text
.
├── data/
│   ├── amazon-reviews/
│   │   └── Amazon.csv
│   └── sentiment-labelled-sentences/
│       ├── amazon_cells_labelled.txt
│       ├── imdb_labelled.txt
│       ├── yelp_labelled.txt
│       └── readme.txt
└── notebooks/
    ├── coursework/
    │   ├── 2541184_IDTA_Code_CW2.ipynb
    │   └── IDTA_CW_2.ipynb
    └── exploratory/
        └── rumpaa-test.ipynb
```

## Notebooks

| Notebook | Description |
|---|---|
| [2541184_IDTA_Code_CW2](notebooks/coursework/2541184_IDTA_Code_CW2.ipynb) | Coursework notebook (original filename retained). |
| [IDTA_CW_2](notebooks/coursework/IDTA_CW_2.ipynb) | Coursework notebook containing descriptive analytics and machine-learning experiments. Its visible cells reference a healthcare stroke dataset that is not currently included in this repository. |
| [rumpaa-test](notebooks/exploratory/rumpaa-test.ipynb) | Exploratory notebook (original filename retained). |

## Datasets

- [Amazon review sentiment data](data/amazon-reviews/Amazon.csv) — CSV with `Sentence` and `Label` columns; labels are 0/1.
- [Sentiment Labelled Sentences](data/sentiment-labelled-sentences/) — sentence-level sentiment data from Amazon, IMDb, and Yelp. See the dataset's [readme](data/sentiment-labelled-sentences/readme.txt) for its provenance and format.

## Getting started

1. Clone the repository.
2. Open a notebook in Jupyter Notebook, JupyterLab, or Google Colab.
3. Install the libraries imported by the notebook (for example, pandas, NumPy, Matplotlib, Seaborn, and scikit-learn).
4. Update dataset paths in notebook cells to match the repository layout.

## Notes

- Original notebook files and dataset contents are retained; this reorganization changes their paths, not their contents.
- Some notebooks may depend on datasets that are not yet present. Check the file paths in each notebook before running it.
