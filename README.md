# NLP_hate_memes

# repo structure 

the below structure should be referenced and maintained for all file additions to the repository.

```nohighlight
├── README.md          <- The top-level README for developers using this project. * this file
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- all project docuemnetation goes here
│   └──references      <- Data dictionaries, manuals, and all other explanatory materials.
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.   
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment
│                          to be updated to envirment.yml 
│
└── src                <- Source code for use in this project.
    ├── data           <- Scripts to download or generate data
    │   └── make_dataset.py <- example filename
    │
    ├── features       <- Scripts to turn raw data into features for modeling
    │   └── build_features.py 
    │
    ├── models         <- Scripts to train models and then use trained models to make
    │   │                 predictions
    │   ├── predict_model.py
    │   └── train_model.py
    │
    └── visualization  <- Scripts to create exploratory and results oriented visualizations
        └── visualize.py
```
