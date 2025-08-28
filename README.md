## 🫁 Lung Cancer Detection using Deep Learning

This project implements a Hybrid Deep Learning model (CCDC-HNN + UNet) for early detection and classification of lung cancer using CT scan images. The system provides an easy-to-use Tkinter-based GUI where users can upload datasets, preprocess images, train/test models, visualize metrics, and detect cancer from new images.

---

## 🚀 Features

* 📂 **Upload & preprocess dataset** (LIDC-IDRI dataset).
* 🔄 **Data normalization & splitting** (train/test split with shuffling).
* 🧠 **Hybrid deep learning architecture**:

  * **UNet** for image segmentation (tumor boundary detection).
  * **3D CNN + LSTM (CCDC-HNN)** for classification (Benign/Malignant).
* 📊 **Performance metrics & visualization**:

  * Accuracy, Precision, Recall, F1-score.
  * Confusion Matrix & ROC Curve.
  * Training Accuracy/Loss graph.
* 🩻 **Cancer Detection & Classification**: Upload new CT scan image → Detects & highlights tumor → Classifies as **Benign** or **Malignant**.
* 🖥️ **User-friendly GUI** built with Tkinter.

---

## 🛠️ Tech Stack

* **Programming Language**: Python
* **Libraries/Frameworks**:

  * Deep Learning: `TensorFlow/Keras`
  * Machine Learning: `Scikit-learn`
  * Image Processing: `OpenCV`
  * Visualization: `Matplotlib`, `Seaborn`
  * GUI: `Tkinter`
* **Dataset**: [LIDC-IDRI Dataset](https://wiki.cancerimagingarchive.net/display/Public/LIDC-IDRI)

---


### GUI Workflow:

1. **Upload LIDC-IDRI Dataset**
2. **Process Dataset** (normalization & resizing)
3. **Train/Test Split**
4. **Run Hybrid CCDC-HNN Algorithm** (model training/testing)
5. **View Training Graphs & Metrics**
6. **Detect & Classify Cancer** from new images

---

## 📈 Performance Metrics

The system evaluates performance using:

* ✅ Accuracy
* 🎯 Precision
* 🔄 Recall
* 📉 F1-Score

---

## 📜 License

This project is licensed under the **MIT License**.

