# Deep Learning Model Deployment As a Web App (with MLFLOW, DVC, Flask, Docker, Github Actions, AWS & Azure)

In this project, a deep learning image classification model (model to classify the CT scan of kidney as normal or tumor) has been deployed as a flask web application to cloud (AWS and Azure). The intial code was written as jupyter notebooks (available in the research directory). These notebooks were used to develop the entire pipeline including - data ingestion, preparation of the model (VGG16 model with custom dense layers at the end), model training and model evaluation.
The experiments were tracked with MLFLow. A basic web interface was developed to serve the predictions.
Thereafter, a CI CD workdflow was created using Docker and Github actions. to deploy the application to AWS and Azure.

## Authors

- [@AnshumanTiware](https://github.com/AnshumanTiware)

# How to run?

### STEPS:

Clone the repository

```bash
https://github.com/AnshumanTiware/dl_project_w_mlops_cloud_deployment.git
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n venv python -y
```

```bash
conda activate venv
```

### STEP 02- install the requirements

```bash
pip install -r requirements.txt
```

```bashonce the
# Finally run the following command
python app.py
```

Now,

```bash
open up you local host and port
```

## Screenshots

![App Screenshot](https://i.postimg.cc/L4xpzRFZ/web-app-flask.png)
