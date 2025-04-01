# 3D Convolutional Neural Networks (Ensemble) For Action Recognition 



## Overview
This repository presents an ensemble approach to action recognition in videos using 3D Convolutional Neural Networks (3D-CNNs). Each model is trained independently, and their predictions are averaged to produce the final classification. This technique has been shown to improve accuracy by leveraging the strengths of multiple models. The models are trained and evaluated on the UCF101 dataset, which comprises 101 action categories.


## Project Structure

VideoActionRecognition/
│
├── ActionRecognition              # Model Implementation NoteBook
│
├── Saved models/                  # Model Weights
│   ├── Individual Models/         # Saved Individual Model Files
│   └── Ensemble_Model.h5          # Saved Ensemble Model File
│
├── Results/                       # Output results (plots, evaluation logs)
│   ├── accuracy_loss_plots/       # Plots for training/validation accuracy and loss
│   ├── result.txt                 # Final model performance results (e.g., test accuracy)
│   └── README.md                  # Instructions for viewing results
│
├── requirements.txt               # Python dependencies
├── README.md                      # Project overview and setup instructions
├── .gitignore                     # Git ignore file (e.g., ignore .h5 files, output)
└── LICENSE                        # License file (optional)


Results



UCF101 Dataset: https://www.crcv.ucf.edu/data/UCF101.php
