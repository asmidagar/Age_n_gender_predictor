# Age_n_gender_predictor

This project predicts a person’s age and gender from a facial image using a convolutional neural network (CNN) model trained in TensorFlow. The application features a user-friendly Gradio interface, processes grayscale images, and provides real-time predictions, making it useful for demographic analysis, personalization, and computer vision research.


# 🔍 Age & Gender Prediction with Deep Learning
A web-based application that predicts a person's **gender** and **age** from a facial image using a custom-trained deep learning model in TensorFlow and a clean UI powered by Gradio.

📸 Demo

![Screenshot 2025-05-01 165505](https://github.com/user-attachments/assets/c891fda3-84a6-495d-93e8-3108b24fd62f)

![Screenshot 2025-05-01 172815](https://github.com/user-attachments/assets/eb79659c-c030-4092-83dc-0cd4766e8094)



* 🧑 **Gender** (Male/Female)
* 🎂 **Estimated Age**


## 🚀 Features

* ✅ Deep learning model with CNN architecture
* ✅ Dual output: gender classification & age regression
* ✅ Grayscale image processing
* ✅ Clean, interactive Gradio interface
* ✅ Fully local, no internet/API calls required


## 🧠 Model Details

* Input Shape: `(128, 128, 1)` (grayscale)
* Outputs:

  * `gender_out`: Binary classification using sigmoid (0 = Male, 1 = Female)
  * `age_out`: Regression output (real age)
* Built using TensorFlow/Keras
* Trained on a labeled face dataset (e.g., UTKFace or custom dataset)
  


## ✏️ Example Prediction

| Input Image                | Predicted Gender | Predicted Age |
| -------------------------- | ---------------- | ------------- |
| ![Screenshot 2025-05-01 172837](https://github.com/user-attachments/assets/0d0efbee-5767-4efc-94aa-e50b6e5d5ce3)
 | 👨 Female         | 🕒 84 years   |

---

## 📦 Dependencies

* Python 3.7+
* TensorFlow
* Gradio
* Pillow
* NumPy



## 🙌 Acknowledgements

* UTKFace Dataset
* Gradio Team
* TensorFlow Community

