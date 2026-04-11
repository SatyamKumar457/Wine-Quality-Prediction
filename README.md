# Wine-Quality-Prediction



## Workflows

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update app.py




# How to run?

### STEPS:

Clone the repository

```bash
https://github.com/SatyamKumar457/Wine-Quality-Prediction
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda active -n mlproj python=3.8 -y
```

```bash
conda activate mlproj
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
python app.py
```

Now,
```bash
open up you local host and port
```



## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)


##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

Run this to export as env variables:

```bash

import dagshub
dagshub.init(repo_owner='SatyamKumar457', repo_name='Wine-Quality-Prediction', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)

```

