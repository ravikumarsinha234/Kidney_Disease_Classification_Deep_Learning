# Kidney_Disease_Classification_Deep_Learning
🫀 🎗️This repository is about end to end  Deep Learning Project for the classification of Kidney Disease

```
## Workflows

1. Update config.yaml
2. Update secrets.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml
app.py
```

```
# How to run?
```

### STEPS:

Clone the repository

```bash
https://github.com/ravikumarsinha234/Kidney_Disease_Classification_Deep_Learning
```

### STEP 01 - Create a virtual environment

```bash
python -m venv "Kidney_Disease_Classification_Deep_Learning"
```

```bash
\kidney_class_venv\Scripts\Activate.ps1 
```

### STEP 02 - install the requirements
```bash
pip install -r requirements.txt
```



## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

- [MLflow tutorial](https://youtu.be/qdcHHrsXA48?si=bD5vDS60akNphkem)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)


MLFLOW_TRACKING_URI=https://dagshub.com/ravikumarsinha234/Kidney_Disease_Classification_Deep_Learning.mlflow \
MLFLOW_TRACKING_USERNAME=ravikumarsinha234 \
MLFLOW_TRACKING_PASSWORD=77b378539ea9ef13a073d044d0f9b61f60ac7eb7 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/ravikumarsinha234/Kidney_Disease_Classification_Deep_Learning.mlflow

export MLFLOW_TRACKING_USERNAME=ravikumarsinha234 

export MLFLOW_TRACKING_PASSWORD=77b378539ea9ef13a073d044d0f9b61f60ac7eb7

```