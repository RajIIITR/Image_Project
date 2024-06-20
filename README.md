# Image_Project
Project_Heading
Brain Tumor Segmentation Project
This repository contains code and resources for the brain tumor segmentation project using the UNet architecture. The primary goal of this project is to accurately delineate the tumor region within brain images through image segmentation.

#Project Overview
In the Jupyter notebook brain_tumer_project.ipynb, we have implemented the UNet architecture to perform brain tumor segmentation. The dataset consists of brain images, where the goal is to segment out the tumor region.

#Key Components
Model Architecture: We utilized the UNet architecture, which is highly effective for image segmentation tasks. The model was trained for approximately 37 epochs using Kaggle's T4*2 GPU.
Output Results: The folder containing PNG images showcases the results of our model, including the initial images used for training, the expected output, and the segmented results produced by the model.
Model Checkpoint: The saved version of our model, named model.keras, can be accessed via this link.
Evaluation Metrics: The performance metrics of our final model are stored in score.csv, which includes the evaluation results.
Training Logs: The training and validation loss, along with accuracy metrics, are recorded in log.csv.


#Metrics Used
->Dice Coefficient: We used the dice coefficient as one of the primary metrics to evaluate the performance of our segmentation model. It is a commonly used metric in image segmentation tasks that measures the overlap between the predicted segmentation and the ground truth.
->Dice Loss: To optimize the model, we employed dice loss, which is derived from the dice coefficient and helps in improving the segmentation performance by focusing on the overlap between the predicted and actual tumor regions.


#Files and Directories
->brain_tumer_project.ipynb: Jupyter notebook containing the code for training and evaluating the UNet model.
->model.keras: The saved model file which can be loaded for inference.
->score.csv: Contains the evaluation metrics of the final model.
->log.csv: Stores the training and validation loss and accuracy metrics.
