# Rice Leaf Disease Detection Using CNN

## Project Overview

This project explores deep learning techniques for classifying rice leaf images into three disease categories: Bacterial Leaf Blight, Brown Spot, and Leaf Smut.

The notebook investigates a Convolutional Neural Network (CNN) and pretrained deep learning architectures to compare their performance on rice leaf disease classification.

## Objectives

- Explore and preprocess rice leaf image data.
- Build a CNN-based image classification model.
- Experiment with transfer learning using pretrained architectures.
- Compare model performance using evaluation metrics and visualizations.

## Technologies Used

- Python
- Jupyter Notebook
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

## Models Explored

- Basic CNN
- MobileNetV2
- ResNet50
- EfficientNetB0
- Fine-tuned MobileNetV2

## Dataset

The dataset contains images belonging to three classes:

- Bacterial Leaf Blight
- Brown Spot
- Leaf Smut

The dataset is included in the `Data/` directory.

## Project Structure

```text
Rice-Leaf-Disease-Detection-Project/
├── Data/
│   ├── Bacterial leaf blight/
│   ├── Brown spot/
│   └── Leaf smut/
├── Rice-Leaf-Disease-Detection-using CNN.ipynb
└── README.md
```

*The folder names above are illustrative; the actual dataset folder names may differ.*

## How to Run

1. Clone or download this repository.
2. Install Python and Jupyter Notebook.
3. Install the libraries required by the notebook.
4. Open `Rice-Leaf-Disease-Detection-using CNN.ipynb` in Jupyter Notebook.
5. Update the dataset path in the notebook if necessary for your computer.
6. Run the notebook cells in order.

## Results and Limitations

The notebook compares multiple deep learning architectures. The reported evaluation results should be interpreted cautiously because the test dataset is small. Further testing on a larger, independent dataset is necessary to assess performance on real-world rice leaf images.

## Disclaimer

This project is intended for educational purposes and experimentation with deep learning. Its predictions should not be used as the sole basis for agricultural treatment decisions.

## Author

Nikhil Goud Panjala
