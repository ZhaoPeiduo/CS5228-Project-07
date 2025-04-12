#### Customer Segmentation and Churn Prediction in Telecommunications Companies
 
This repository contains the code for CS5228 Course Mini Project, which aims to leverage machine learning algorithms to predict whether a customer churns based on a set of features.

This repository contains the following notebooks:
- `data_preprocessing.ipynb` (@Zhao Peiduo): Performs feature engineering and preprocessing steps such as encoding and normalization.
- `eda.ipynb`(@Zhao Peiduo): Visualizes the correlation between features and uses PCA to remove less useful features.
- `kmeans.ipynb`(@Harry-Gao-H): Performs K-means clustering and analyzes the characteristics of the clusters formed through elbow method.
- `DBSCAN.ipynb`(@jingh-Y): Performs DBSCAN clustering with search on the optimal eps and analyzes the characteristics of the clusters formed.
- `supervised_learning.ipynb`(@tsiyuk, @Zhao Peiduo): Trains supervised learning models (logistic regression, random forest and XGBoost) to predict whether a customer will churn, and evaluates the model performance using different metrics. 

#### Quick Start

To set up the environment for the project, it is recommended to create a virtual environment and install the requirements:

```bash
pip install -r requirements.txt
```

To make a virtual environment, either use the following command or consider [virtualenvwrapper for linux](https://virtualenvwrapper.readthedocs.io/en/latest/) and [for windows](https://pypi.org/project/virtualenvwrapper-win/).

```bash
python -m venv .venv
```

Group project poster link: https://docs.google.com/presentation/d/1lZTOGErbuEHQERzOb0APedkiZ3pXGXxZ7SzoU0vRqJU/edit#slide=id.g22bd54775a0_0_0 