# Cat vs Dog Classification

A machine learning project for classifying images of cats and dogs using a Convolutional Neural Network (CNN) model. This project uses a labeled dataset from Kaggle to train and evaluate the model’s performance in identifying images as either a cat or a dog.

## Dataset

The dataset for this project is the **Dogs vs Cats** dataset available on Kaggle ([link to dataset](https://www.kaggle.com/datasets/salader/dogs-vs-cats)). The dataset contains labeled images of cats and dogs, ideal for binary classification tasks. It is licensed under the MIT License.

## Features

- **Data Preprocessing**: Resize, normalize, and augment images for efficient training.
- **Model Architecture**: Utilizes a CNN architecture to extract image features for classification.
- **Performance Metrics**: Includes accuracy, precision, recall, F1-score, and confusion matrix for evaluation.
- **Deployment Ready**: Model is exportable for deployment in applications.

## Project Workflow

1. **Data Preprocessing**: Images are resized and normalized, and data augmentation is applied to enhance model robustness.
2. **Model Training**: The CNN model is trained using the processed dataset with binary cross-entropy loss.
3. **Evaluation**: The model’s accuracy is tested on a separate dataset with detailed performance metrics.

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/CoderDebajyoti/Cat_vs_Dog_Classification.git
   cd Cat_vs_Dog_Classification
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/salader/dogs-vs-cats) and place it in the dataset directory.

4. Run the training script:
   ```bash
   python train.py
   ```

5. Evaluate the model:
   ```bash
   python evaluate.py
   ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## MIT License
```
Copyright (c) 2024 Debajyoti Das

Permission is hereby granted, free of charge, to any person obtaining a copy...
```

## Acknowledgments

- Thanks to Kaggle for the [Dogs vs Cats dataset](https://www.kaggle.com/datasets/salader/dogs-vs-cats).
  
---
