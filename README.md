# Differential Privacy Strategies for Data Analytics in the Banking Sector

## Project Overview

This project focuses on implementing differential privacy strategies to enhance data analytics within the banking sector. By applying differential privacy techniques, the goal is to safeguard sensitive customer information while enabling valuable insights from data analytics. The project will demonstrate how these privacy-preserving methods can be utilized in compliance with financial regulations, ensuring both privacy and effective decision-making.

## Project Structure

```
DIFFERENTIAL_PRIVACY_BANK/
├── data/
│   ├── processed/                # Processed datasets
│   │   └── bank_processed.csv    # Processed banking dataset
│   ├── raw/                      # Raw datasets
│   │   ├── bank-full.csv         # Raw banking dataset (full version)
│   │   └── bank-names.txt        # Dataset description
│   └── images/                   # Visualization outputs
│       ├── Metricas_LDP.png      # Metrics related to Local Differential Privacy
│       ├── ROC_threshold=0.4.png # ROC curve visualization with threshold 0.4
│       ├── stacked_bar_plots.png # Stacked bar chart visualizations
│       └── violin_plots.png      # Violin plot visualizations
├── notebooks/                    # Jupyter notebooks for analysis and modeling
│   ├── data_preprocessing.ipynb  # Data cleaning and preprocessing steps
│   ├── direct_encoding.ipynb     # Implementation of direct encoding techniques
│   ├── eda.ipynb                 # Exploratory Data Analysis (EDA)
│   ├── model_training.ipynb      # Training of machine learning models
├── .gitignore                    # Git ignore file to exclude unnecessary files
├── README.md                     # Project documentation (this file)
└── requirements.txt              # Python dependencies required for the project
```

### Notebooks Description

- **`data_preprocessing.ipynb`**: This notebook handles the initial data cleaning and preprocessing of the banking dataset.

- **`direct_encoding.ipynb`**: Focuses on implementing direct encoding strategies for categorical variables in the dataset. 

- **`eda.ipynb`**: Performs Exploratory Data Analysis (EDA) on the banking dataset. This notebook generates visualizations and computes basic statistics to understand data distributions.

- **`model_training.ipynb`**: Contains the code for training machine learning models on the preprocessed banking data, evaluates model performance, and optimizes hyperparameters.
