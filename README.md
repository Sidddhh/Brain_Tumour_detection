## 🧠 **Brain Tumor Detection Using Deep Learning**

An intelligent **AI-based Brain Tumor Detection System** that uses deep learning to classify MRI brain images into **Glioma**, **Meningioma**, **Pituitary Tumor**, or **No Tumor**.
The system is deployed as a **Flask web application**, allowing users to upload MRI scans and instantly receive predictions with confidence scores.

---

## 🚀 **Features**

### 🩺 **Core Functionality**

* **AI-Based Detection:** Classifies brain MRI images into:
  - Glioma
  - Meningioma
  - Pituitary Tumor
  - No Tumor
* **Confidence Score:** Displays prediction confidence percentage.
* **Image Upload:** Upload MRI images directly through the web interface.
* **Real-Time Prediction:** Instant inference using a trained deep learning model.

---

## 🧠 **Model Details**

* Framework: **TensorFlow / Keras**
* Model File: `model.h5` (managed using Git LFS)
* Input Image Size: **224 × 224**
* Preprocessing:
  - Image resizing
  - Pixel normalization (0–1 range)
* Output:
  - Predicted tumor class
  - Confidence score

---

## 🏗️ **Tech Stack**

| Category             | Technology                     |
| -------------------- | ------------------------------ |
| **Frontend**         | HTML, CSS                      |
| **Backend**          | Flask (Python)                 |
| **Machine Learning** | TensorFlow, Keras              |
| **Image Processing** | NumPy, Keras Image Utilities   |
| **Model Storage**    | Git LFS (Large File Storage)   |
| **Version Control**  | Git & GitHub                   |

---

## ⚙️ **Installation & Setup**

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Sidddhh/Brain_Tumour_detection.git
cd Brain_Tumour_detection

pip install -r requirements.txt

To run use :
python app.py 
or 
flask run app.py