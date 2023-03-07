Employee_Attrition
==============================

The purpose of this project is to analyze the data obtained from the Human Resources Department of IBM, determine the factors that influence employees to leave IBM, and build a prediction model to predict which employees will become attrition. 

This project will help IBM’s HR Department and employers by providing an in-depth analysis as to identify what types of employees are choosing to leave, and determining which employees are at risk to leave next. Predicting employee attrition before it happens will allow organization employers and managers to develop strategies to minimize employee attrition rates and motivate employees to stay in their jobs. This project can also help determine the underlying factors and insights important for employee retention. 


Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── interim        <- Intermediate data that has been transformed.
    │   │    └── IBM_HR-Employee-Attrition_cleaned.csv
    │   └── raw            <- The original, immutable data dump.
    │        └── IBM_HR-Employee-Attrition.csv
    │  
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Model metrics file
    │    └── IBM_HR-Employee-Attrition.csv
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering
    │    ├── 1.0-cml-ibm-data_wrangling.ipynb
    │    ├── 2.0-cml-ibm-eda.ipynb
    │    └── 3.0-cml-ibm-preprocessing_and_modeling.ipynb.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as PDF, PPTX, etc.
    │    ├── TableauViz-IBM_Employee_Attrition.pdf
    │    ├── Tableau-IBM_Employee_Attrition.twbx
    │    ├── Employee_Attrition_Report.pdf
    │    ├── Employee_Attrition_SlideDeck.pdf
    │    └── Employee_Attrition_Presentation.pptx
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
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
