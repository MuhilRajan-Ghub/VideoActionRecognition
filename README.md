# 3D Convolutional Neural Networks (Ensemble) For Action Recognition 

## Overview
This repository presents an ensemble approach to action recognition in videos using 3D Convolutional Neural Networks (3D-CNNs). Each model is trained independently, and their predictions are averaged to produce the final classification. This technique has been shown to improve accuracy by leveraging the strengths of multiple models. The models are trained and evaluated on the UCF101 dataset, which comprises 101 action categories.


## Features
- **Action Recognition:** Detects and classifies human actions from video clips.
- **3D CNN Ensemble:** Uses multiple 3D CNN models to enhance classification accuracy.
- **Data Preprocessing:** Prepares raw video frames for model training. Skips video frames for more efficiency.
- **Evaluation & Visualization:** Displays training metrics (loss, accuracy) through plots.
- **Batch Prediction:** Processes multiple video files and exports results.
- **Model Checkpointing:** Saves model weights for future use. Allows us to train models one at a time (to overcome google colab limitations).


## Dataset
UCF101 Dataset: https://www.crcv.ucf.edu/data/UCF101.php
**Dataset Directory Structure**
```
📂 Data
├── UCF101             
├── Examples.png                     
│   ├── Action_Class_1  
│   ├── Action_Class_2
│   └── ...
```


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


## Results
- Accuracy and loss plots have been saved in the Results/Individual Results/ directory.
- Final evaluation results (e.g., test accuracy) have been saved in rResults/Ensemble_Result.txt.


## Future Improvements
- Experiment with different CNN architectures.
- Implement data augmentation techniques to improve generalization.
- Fine-tune hyperparameters for better accuracy.
- Explore transformer-based models for action recognition.
