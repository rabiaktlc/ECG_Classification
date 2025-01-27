# **Heart Rhythm Analysis and Anomaly Detection from ECG Signals**  

![ECG Signal](https://upload.wikimedia.org/wikipedia/commons/e/e7/ECG_Principle_fast.gif)  
*Source: Wikipedia*  

---

## **📖 Project Overview**  
This project aims to classify **ECG (Electrocardiogram) signals** into five distinct categories:  

✔️ **Normal Beat (N)**  
✔️ **Supraventricular Premature or Ectopic Beat (S)**  
✔️ **Premature Ventricular Contraction (V)**  
✔️ **Fusion of Ventricular and Normal Beat (F)**  
✔️ **Unclassified Beat (Q)**  

🔍 *Machine learning models are used to detect cardiac rhythm abnormalities.*  

---

## **📊 Dataset**  
The dataset used in this study is:  
- **MIT-BIH Arrhythmia Dataset**  
- **PTB Diagnostic ECG Database**  

✅ It consists of **preprocessed and segmented heartbeat signals**, labeled according to different heartbeat types.  

📌 Below is an example of the class distribution in the dataset:  

![Class Distribution](https://upload.wikimedia.org/wikipedia/commons/3/3d/Confusion_matrix.png)  
*Example Confusion Matrix (Illustrative Image)*  

---

## **🧠 Machine Learning Models**  
The following machine learning models were trained and evaluated:  
🔹 **Support Vector Machine (SVM)**  
🔹 **K-Nearest Neighbors (KNN)**  
🔹 **Logistic Regression**  
🔹 **Random Forest**  

💡 *The table below summarizes the model comparison results:*  

| Model  | Accuracy |
|--------|----------|
| 🌲 **Random Forest** | ✅ 97% |
| 📉 **SVM**          | 96% |
| 🔍 **KNN**          | 95% |
| 🧮 **Logistic Regression** | 91% |

📌 **The highest accuracy (97%) was achieved by the Random Forest model.**  

---

## **⚙️ Implementation & How to Run the Project**  
This project was developed using **Python**, and the following libraries were utilized:  
- `numpy`  
- `pandas`  
- `scikit-learn`  
- `matplotlib`  
- `seaborn`  

### **🚀 Run the Project**  
To set up and run the project, follow these steps:

1️⃣ **Clone the repository**  
```bash
git clone https://github.com/yourusername/yourproject.git
cd yourproject
```
2️⃣ **Install dependencies**  
```bash
pip install -r requirements.txt
```
3️⃣ **Run the main script**  
```bash
python main.py
```

---

## **📊 Results & Performance**  
The **Random Forest model** performed the best in classifying ECG signals. Below is a summary of precision, recall, and F1-score for each class:  

📌 **Classification Report Example:**  
```
              Precision    Recall   F1-Score
Normal (N)       0.97       1.00       0.98
Supraventricular 0.96       0.56       0.71
Premature Vent.  0.97       0.86       0.91
Fusion Beat      0.75       0.48       0.59
Unclassified     1.00       0.91       0.95
Overall Acc.     0.96
```

---

## **🛠️ Future Improvements**  
🔹 Fine-tuning hyperparameters to further optimize accuracy  
🔹 Implementing deep learning models (CNNs) for better feature extraction  
🔹 Deploying the model as a **web or mobile application** for real-time ECG analysis  

---

## **👥 Contributors**  
- **Rabia Kutluca** – rabiakutluca@ogr.eskisehir.edu.tr  
- **Melek Gül Kaya** – melekgulkaya@ogr.eskisehir.edu.tr  

---

## **📜 License**  
This project is licensed under the **MIT License**. See the `LICENSE` file for more details.  
