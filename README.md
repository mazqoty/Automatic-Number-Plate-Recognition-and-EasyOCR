# Automatic Number Plate Recognition and EasyOCR


## Step 1: Download Kaggle Dataset

 - Download Dataset via kaggle API or manually from [KAGGLE](https://www.kaggle.com/datasets/andrewmvd/car-plate-detection)
 - Follow the instructions for Downloading via [Kaggle API](https://www.kaggle.com/docs/api)
 - Run `kaggle datasets download -d andrewmvd/car-plate-detection` in the terminal where the project folder is

## Step 2: Move Dataset into a Training and Testing Partition

- Run `python ./1.PrepareDataset.py` locally

## Step 3: Training and Detection

- Upload file `ANPR_and_EasyOCR_ColabRun_v1.ipynb` in Google Colaboratory
- Remember to Upload `archive.tar` file of prepared dataset in the step 2 when running `ANPR_and_EasyOCR_ColabRun_v1.ipynb` in the directory `Tensorflow/workspace/images`
 
 
