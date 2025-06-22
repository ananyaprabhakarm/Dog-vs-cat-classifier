# 🐶🐱 Dog vs Cat Image Classifier

This project is a **Convolutional Neural Network (CNN)** model built to classify images of **dogs** and **cats**. Using **deep learning** techniques, the model is trained on labeled image data to accurately distinguish between the two categories.

---

## 🧠 Features

- Builds a CNN from scratch using Keras with TensorFlow backend
- Trained on a labeled dataset of dog and cat images
- Preprocesses image data (resizing, normalization, augmentation)
- Achieves high classification accuracy on test images
- Can predict new/unseen images as either dog or cat
- Visualizes training accuracy, loss, and sample predictions

---

## 🛠 Tech Stack

- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Matplotlib**
- **OpenCV / PIL** (for image handling)

---

## 🖼 Dataset

You can use the popular **Dogs vs. Cats dataset** provided by Kaggle:  
🔗 [Kaggle - Dogs vs. Cats](https://www.kaggle.com/c/dogs-vs-cats/data)

Make sure to unzip and organize the dataset as shown in the project structure above.

---

## 🚀 Getting Started

### 1. Clone the repository

```
git clone https://github.com/your-username/dog-vs-cat-classifier.git
cd dog-vs-cat-classifier
```
### 2. Install dependencies
```
pip install -r requirements.txt
```
### 3. Train the model
```
python dog_cat_classifier.py
```
### 4. Predict on a new image
```
Modify the script or use a function like:
```
predict_image("path/to/image.jpg")

### 📊 Output

    Plots for training & validation accuracy and loss

    Classification predictions on test images

    Saved model for future use
