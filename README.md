## 📄 Research Publication

This project is based on a published research paper:

**"Automated Pneumonia Detection using VGG19: A Deep Learning Approach for Chest X-Ray Analysis"**

📅 Published in: International Conference on Advance IT, Engineering and Management (2024)

📌 Key Contributions:
- Built and evaluated 3 deep learning models
- Achieved ~96% training accuracy
- Used transfer learning with VGG19
- Applied data augmentation & preprocessing techniques

## 🏅 Publication Certificate

This project is backed by a published research paper and certified contribution.

<img width="800" height="559" alt="image" src="https://github.com/user-attachments/assets/6a1704e0-3ee2-4905-994f-d065d62ef2dc" />


## 🏗️ Architecture

User → Flask Web App → Image Processing → VGG19 Model → Prediction Output

---

## 📂 Project Structure

```
PNEUMONIA_DETECTION/
│
├── app/                 # Flask application
│   ├── static/          # CSS, JS files
│   ├── templates/       # HTML pages
│   ├── uploads/         # Uploaded images
│   └── app.py           # Main Flask app
│
├── notebook/            # Jupyter notebook (model training)
├── research/            # Research paper
├── training.py          # Model training script
├── README.md
```

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* Flask
* NumPy, Pandas

---

## 🔄 How it Works

1. User uploads X-ray image
2. Image is preprocessed (resize, normalize)
3. Model predicts class (Normal / Pneumonia)
4. Result displayed on UI

---

## 🚀 Future Improvements

* Improve model accuracy with larger dataset
* Add multi-class disease detection
