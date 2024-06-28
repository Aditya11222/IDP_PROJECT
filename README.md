Intelligent Document Processing
Intelligent Document Processing (IDP) automates the extraction and analysis of data from various documents using advanced machine learning models. This project leverages fine-tuned transformer models for Named Entity Recognition (NER), state-of-the-art text summarization techniques, and cutting-edge Table Structure Recognition (TSR) methods to streamline document handling processes.

Features

Named Entity Recognition (NER):

Models: LUKE, DistilBERT
Automates identification of key entities
Enhances accuracy and reduces manual effort

Text Summarization:

Models: Pegasus, BART-CNN
Condenses extensive texts into concise summaries
Saves time and mitigates information overload
Table Structure Recognition (TSR):

Models: YOLOv8, PaddleOCR

Accurately extracts and preserves relationships in tabular data
Improves efficiency and scalability



Project Instructions
==============================

This repo contains the instructions for a machine learning project.

Project Organization
------------

    ├── README.md          <- The top-level README for describing highlights for using this ML project.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention should snake case.
    │
    ├── reports            
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │   └── README.md      <- Youtube Video Link
    │   └── final_project_report <- final report .pdf format and supporting files
    │   └── presentation   <-  final power point presentation 
    |
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── src                <- Source code for use in this project.
       ├── __init__.py    <- Makes src a Python module
       ├── data
       │   ├── processed      <- The final, canonical data sets for modeling.
       │   └── raw            <- The original, immutable data dump.
       │
       ├── preprocessing_data           <- Scripts to download or generate data and pre-process the data
       │   └── pre-processing.py
       │
       ├── feature_engineering       <- Scripts to turn raw data into features for modeling
       │   └── build_features.py
       │
       ├── models         <- Scripts to train models and then use trained models to make
       │   │                 predictions
       │   ├── predict_model.py
       │   └── train_model.py
       │
       └── visualization  <- Scripts to create exploratory and results oriented visualizations
       │   └── visualize.py  
       │
       └── main.py  <- main script to run all the models and call appropriate functions
       |
       ├── LICENSE  <- LICENSE terms to be included for the use of the source code distribution



