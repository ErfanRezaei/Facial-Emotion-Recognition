# Facial Emotion Recognition

This project implements a deep learning model to recognize and classify 7 basic human emotions using the well-known **FER2013** dataset. The model is a **Convolutional Neural Network (CNN)** built with the TensorFlow/Keras framework.

---

## 📊 Dataset

This project utilizes the [FER2013] dataset, originally published for a Kaggle competition. The dataset consists of over 35,000 grayscale images of faces, each 48x48 pixels in size. The images are labeled with one of the following 7 emotion categories:

- **0**: Angry
- **1**: Disgust
- **2**: Fear
- **3**: Happy
- **4**: Sad
- **5**: Surprise
- **6**: Neutral

---

## 🚀 Setup and Installation

To run this project, follow the steps below.

**1. Clone the Repository:**
First, clone the project from GitHub:

git clone [https://github.com/YOUR_USERNAME/Facial-Emotion-Recognition.git](https://github.com/YOUR_USERNAME/Facial-Emotion-Recognition.git)
cd Facial-Emotion-Recognition

**2. Create and Activate a Virtual Environment (Recommended):**

# Create the environment

python -m venv venv

# Activate on Windows

venv\Scripts\activate

# Activate on Linux/macOS

source venv/bin/activate

**3. Install Dependencies:**
pip install -r requirements.txt

**4. Download the Dataset:**
Download the fer2013.csv file from [FER2013](https://www.kaggle.com/datasets/nicolejyt/facialexpressionrecognition) and place it inside the data/ folder.

Note: To run the project, open the Facial Emotion Reconition.ipynb in notebooks directory using Jupyter Notebook or Visual Studio Code and execute the cells in order.

## Technologies Used

- Python
- TensorFlow / Keras
- Pandas & NumPy
- Matplotlib
