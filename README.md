# Machine Learning Projects

## Project 1: Plant Species Classification

### Overview
This project involves building a classifier to identify the species of plants from images. It uses supervised learning, neural networks, and CNNs to achieve high accuracy in classifying images into one of 12 plant species.

### Features
- **Domain**: Botanical Research
- **Objective**: Automate plant species identification using image classification techniques.
- **Data Source**: [Kaggle Plant Seedlings Classification Dataset](https://www.kaggle.com/c/plant-seedlings-classification/data)
- **Key Steps**:
  1. Import and visualize the dataset.
  2. Train and compare supervised learning models, neural networks, and CNNs.
  3. Pickle the best-performing model for future use.
  4. Use the model to predict plant species for new images.

---

## Project 2: Cast and Crew Detection from Movie Scenes

### Overview
This project automates the detection of human faces in movie scenes to provide cast information for streaming applications. A face mask detection model is designed using U-Net and pre-trained transfer learning models.

### Features
- **Domain**: Entertainment
- **Objective**: Detect human faces in movie screenshots for cast and crew information.
- **Data**: Images and masks indicating face regions.
- **Key Steps**:
  1. Import and preprocess the dataset.
  2. Train a face mask detection model using U-Net.
  3. Evaluate the model and generate predictions for new images.

---

## Project 3: Face Recognition with Pre-trained Models

### Overview
This project builds a face recognition model to identify whether two faces belong to the same person using embedding vectors and an SVM classifier.

### Features
- **Domain**: Face Recognition
- **Objective**: Recognize human faces using a pre-trained model and SVM classifier.
- **Data**: Face-aligned dataset from Pinterest (10,770 images for 100 individuals).
- **Key Steps**:
  1. Load the dataset and metadata.
  2. Generate embedding vectors for each face.
  3. Apply PCA for dimensionality reduction.
  4. Train an SVM classifier to predict identities from facial images.

---

## Notes
- **Tools and Technologies**: Python, TensorFlow/Keras, OpenCV, U-Net, SVM, PCA
- **Data Availability**:
  - Project 1: Dataset available on Kaggle.
  - Project 2 & 3: Datasets are not uploaded due to licensing restrictions.

Feel free to explore the repository and share your feedback!
