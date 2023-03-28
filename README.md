# yolov8-bear-detection
![GitHub repo size](https://img.shields.io/github/repo-size/Odilbek99/yolov8-bear-detection)
![GitHub contributors](https://img.shields.io/github/contributors/Odilbek99/yolov8-bear-detection)
![GitHub stars](https://img.shields.io/github/stars/Odilbek99/yolov8-bear-detection)
![GitHub forks](https://img.shields.io/github/forks/Odilbek99/yolov8-bear-detection)


The repository contains the code for object detection using YOLOv8 architecture. The repository contains the following folders and files:

# Folders
- ***csv_file***: This folder contains the following files which are required for the project:
  - **train.csv**
  - **test.csv**
  - **sample_submission.csv**
- ***notebooks***: This folder contains the following Jupyter Notebooks:

  - **train.ipynb**: This notebook contains the code for training the data.
  - **output_prep.ipynb**: This notebook contains the code for making the predictions as sample_submission.csv.
  - **yolo_data_preparation.ipynb**: This notebook contains the code for preparing yolo_data from the given images.
- ***outputs***: This folder contains the out.csv file which is the final submission file.
- ***yolo_data***: This folder contains two subfolders - train and val. Each subfolder contains images and labels for training and validation.
# Files
- config.yaml: This file contains the configuration settings for the YOLOv8 model.

#To use this repository, follow the below steps:

- Clone the repository to your local machine.
- Install the required libraries.
- Run yolo_data_preparation.ipynb to prepare the yolo data.
- Run train.ipynb to train the model.
- Run output_prep.ipynb to create the submission file.
- Please refer to the README files in each folder for detailed instructions on how to use the code in that folder.

Note: The code in this repository is based on the YOLOv8 architecture and has been specifically trained for object detection.
