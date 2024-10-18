# Project Title

This project involves predicting stable heights using a machine learning model. The submission includes the model code, test predictions (in Kaggle format), and instructions to reproduce the results.

## Table of Contents
- Requirements
- Image Files
- Running the File
- CSV Predictions

## Requirements


Install the required Python packages using `pip`:

    pip install -r requirements.txt


   Ensure the following libraries are installed:
   - pandas
   - timm
   - matplotlib
   - torch
   - fastai
   - OpenCV (cv2)
   - numpy

   If the required packages are missing in the `requirements.txt`, you can manually install them:
   ```bash
    pip install pandas timm matplotlib torch fastai opencv-python numpy
```

## Image Files

- Training Data: Found in the relative file path \COMP90086_2024_Project_train
- Test Data: Found in the relative file path \COMP90086_2024_Project_test

## Running the File
The jupyter notebook can be run after the requirements have been installed. To test different configurations of models, item transformation, and batch transformations, uncomment the desired parts of the code found under the Training Loop section. Specific implementation details are can be found within the comments of the Jupyter notebook. 

## CSV Predictions
CSV predictions are found in results_vit_final.csv. It is in the Kaggle format of 

```bash
id,stable_height
17809,6
45934,1
22537,3
```