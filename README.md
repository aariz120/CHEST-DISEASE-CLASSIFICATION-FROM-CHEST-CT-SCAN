# CHEST-DISEASE-CLASSIFICATION-FROM-CHEST-CT-SCAN

[Data link] (https://drive.google.com/drive/folders/1Qqpwswv2t-emQzTL99RoJHKVtEslUdEB?usp=drive_link)

##Workflows

''''
    Update config.yaml
    Update params.yaml
    Update the entity
    Update the configuration manager in src config
    Update the components
    Update the pipeline
    Update the main.py
    Update the dvc.yaml
''''

# Git commands

''''
git add .
'''
git commit -m "Updated"
'''
git push origin main
''''


# How to run?

''''
conda create -n chest python=3.8 -y
'''

conda activate chest
'''

pip install -r requirements.txt
''''
python app.py
'''

## Mlflow dagshub connection uri
'''''

MLFLOW_TRACKING_URI=https://dagshub.com/aariz120/CHEST-DISEASE-CLASSIFICATION-FROM-CHEST-CT-SCAN.mlflow \
MLFLOW_TRACKING_USERNAME=aariz120 \
MLFLOW_TRACKING_PASSWORD=35f449339f48eb1892339db57ff59a05c4094376  \
python script.py
'''''


## RUN from bash terminal

'''''
export MLFLOW_TRACKING_URI= https://dagshub.com/aariz120/CHEST-DISEASE-CLASSIFICATION-FROM-CHEST-CT-SCAN.mlflow 

export MLFLOW_TRACKING_USERNAME= aariz120

export MLFLOW_TRACKING_PASSWORD=35f449339f48eb1892339db57ff59a05c4094376
