# 🖼️ Image Classification Predictor  

This repository contains a **Streamlit web application** for **image classification** using a **pre-trained Keras model**. The app allows users to upload an image and get predicted labels based on attributes like **color, type, season, and gender**.

---

## 📁 Repository Structure  

```
├── app.py                 # Streamlit app for image classification
├── Final_CODEMONK.ipynb   # Jupyter notebook with model training experiments
├── final_model.keras      # Pre-trained Keras model for predictions
├── temp.jpg               # Temporary file for uploaded images
├── data/                  # Directory containing sample images for testing
├── requirements.txt       # Dependencies for running the application
└── README.md              # Project documentation
```

---

## 🔧 Installation  

To set up the project, follow these steps:

1. **Clone the repository**  
   ```sh
   git clone https://github.com/your-username/image-classification-predictor.git
   cd image-classification-predictor
   ```

2. **Install dependencies**  
   ```sh
   pip install -r requirements.txt
   ```

---

## 🚀 Running the Application  

Start the **Streamlit web app** with the following command:  
```sh
streamlit run app.py
```
This will launch the **web interface** where you can upload images and get predictions.

---

## 🎯 Usage  

1. **Upload an image** using the file uploader.  
2. **Click the "Predict" button** to analyze the image.  
3. **View predicted attributes** (e.g., color, clothing type, season, gender).  

---

## 🛠️ Dependencies  

The project requires the following libraries:  

- **Streamlit** – For building the web application  
- **TensorFlow** – For loading and running the deep learning model  
- **NumPy** – For image preprocessing  
- **PIL (Pillow)** – For handling image files  

Install them using:  
```sh
pip install streamlit tensorflow numpy pillow
```

---


