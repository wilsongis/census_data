# Census Data Processor based on [Python Dev Environment](https://github.com/wilsongis/census_data)

==============================

## A project to parse the American Community Survey 5-Year Data

Project processed the Census ACS for use in the [Quality of Life Dashboard](https://github.com/tobinbradley/quality-of-life-dashboard)

## Features:

- zsh shell (with oh my zsh)
- python3
- Jupyter and JupyterLab


Based on [How to Setup Your JupyterLab Project Environment](https://towardsdatascience.com/how-to-setup-your-jupyterlab-project-environment-74909dade29b)

To Run Environment:

On Mac:

```bash
sh run.sh
```

On Windows:

```cmd
run.bat
```

The image will launch the zsh shell prompt.

To run JupyterLab:

```bash
sh config/run_jupyter.sh
```


Folder layout is based on:
[cookiecutter data science project template](https://drivendata.github.io/cookiecutter-data-science/).

## Project Organization

---

    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py

---

B06004IPR_005E