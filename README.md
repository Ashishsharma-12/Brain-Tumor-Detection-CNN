# Brain Tumor Classification using MRI Images

## Overview
This project focuses on the classification of brain tumors using MRI images. The dataset used for this project is obtained from Kaggle: [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset). The model is built using deep learning techniques to accurately distinguish between different categories of brain tumors.

## Dataset
The dataset consists of MRI scans of brain tumors categorized into multiple classes. The images are preprocessed and used for training, validation, and testing in a deep learning model.


## Installation
To set up the project environment, install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage
### 1. Preprocess Data
Run the data preprocessing script to clean and prepare the images:
```bash
python src/data_preprocessing.py
```

### 2. Train Model
Train the deep learning model using the preprocessed dataset:
```bash
python src/train.py
```

### 3. Evaluate Model
Evaluate the model's performance using the test dataset:
```bash
python src/evaluate.py
```

### 4. Predict on New Images
Use the trained model to classify new MRI images:

## Dependencies
All dependencies are listed in `requirements.txt`. Install them using:
```bash
pip install -r requirements.txt
```

## Results
  Given the labels and the corresponding classification results, here's an interpretation of the model's performance for each tumour type:
  
  -Label 0: Glioma
  
  Precision: 96% — The model is 96% accurate in predicting gliomas.
  Recall: 99% — It correctly identifies 99% of actual gliomas.
  F1-score: 97% — A strong balance between precision and recall.
  
 - Label 1: Meningioma
  
  Precision: 98% — The model is highly precise in predicting meningiomas.
  Recall: 93% — It identifies 93% of actual meningiomas.
  F1-score: 95% — Very good performance with a slight trade-off between precision and recall.
  
  -Label 2: Pituitary
  
  Precision: 98% — The model is very precise when predicting pituitary tumours.
  Recall: 99% — It correctly identifies almost all pituitary tumours.
  F1-score: 99% — Excellent balance of precision and recall for this class.
  
  -Label 3: No Tumor
  
  Precision: 96% — The model is precise when predicting no tumour.
  Recall: 97% — It correctly identifies 97% of cases with no tumour.
  F1-score: 96% — A solid performance in identifying no tumour cases.
  
  -Summary:
  
  Glioma and Pituitary tumours have the highest performance (**F1-scores of 97% and 99%, respectively)**, with excellent precision and recall.
  Meningioma shows slightly lower recall (93%) but still has a very **high F1-score (95%)**.
  No Tumor is also well predicted with a balanced precision and recall of **96%** and** 97%, **respectively.
  The model shows consistent and strong performance across all tumour types.

  ![image](https://github.com/user-attachments/assets/0ab045e1-97ca-49f6-b9e0-df64ae07dd94)


## Future Improvements
- Improve model architecture for better accuracy.
- Increase dataset size for better generalization.
- Implement an interactive web application for easy image classification.

## License
This project is for educational and research purposes. Refer to the dataset's original source for licensing information.

## Acknowledgements
- The dataset is taken from [Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).
- Deep learning models used are inspired by research in medical imaging and classification.

---
For any questions or contributions, feel free to reach out!


