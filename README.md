# 3D Convolutional Neural Networks (Ensemble) For Action Recognition 

## Overview
This repository presents an ensemble approach to action recognition in videos using 3D Convolutional Neural Networks (3D-CNNs). Each model is trained independently, and their predictions are averaged to produce the final classification. This technique has been shown to improve accuracy by leveraging the strengths of multiple models. The models are trained and evaluated on the UCF101 dataset, which comprises 101 action categories.

## Project Structure
```
📂 Project
├── ActionRecognition.ipynb  # Model Implementation NoteBook           
├── Examples.png             # Video Frames With Labels
├── 📁 Results              
│   ├── Individual Results   # Plots For Training/Validation Accuracy And Loss
│   └── Ensemble_Result      # Test Set Accuracy And Loss For Ensemble Model 
├── 📁 Saved models                  
│   ├── Individual Models    # Saved Individual Model Files
│   └── Ensemble_Model.h5    # Saved Ensemble Model File
└── README.md                 
```

Results





UCF101 Dataset: https://www.crcv.ucf.edu/data/UCF101.php
