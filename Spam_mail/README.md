# 📧 Spam Mail Detection using Machine Learning  

> 🚀 Detect spam emails with Python & Machine Learning — fast, accurate, and efficient!  

![Spam Detection Banner](images/banner.png)  

![ML](https://img.shields.io/badge/Machine%20Learning-Spam%20Detection-blue?style=for-the-badge)  
![Python](https://img.shields.io/badge/Python-3.8+-green?style=for-the-badge)  
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.0-orange?style=for-the-badge)  
![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)  

---

## 📝 Project Overview  

Spam emails clutter inboxes, waste time, and pose security threats.  
This project builds a **Spam Mail Classifier** using **Machine Learning** to automatically detect spam based on email content.  

It uses **TF-IDF Vectorization** and **Logistic Regression** for high accuracy in classification.  

---

## ⚙️ Tech Stack  

- **Programming Language:** Python 🐍  
- **Libraries:**  
  - `pandas` — Data manipulation  
  - `scikit-learn` — ML model, preprocessing, evaluation  
  - `TfidfVectorizer` — Text feature extraction  
- **Model Used:** Logistic Regression  
- **Dataset:** `mail_data.csv`  

---

## 📂 Project Structure  

```
Spam_mail/
│── mail_data.csv                 # Dataset
│── spam_mail_detection.ipynb     # Jupyter Notebook with code
│── README.md                     # Project Documentation
│── requirements.txt              # Python dependencies
│── images/                       # Screenshots and banner
```

---

## 🔍 Workflow  

1. **Import Dependencies**  
   Load Python libraries and helper modules.  

2. **Load Dataset**  
   Read `mail_data.csv` containing email text & labels (spam/ham).  

3. **Preprocessing**  
   - Remove null values  
   - Convert labels to binary (spam = 0, ham = 1)  
   - Split into train/test sets  

4. **Feature Extraction**  
   - Use **TfidfVectorizer** to convert text into numerical form  

5. **Model Training**  
   - Train a **Logistic Regression** classifier  

6. **Model Evaluation**  
   - Check accuracy on both training & test datasets  

---

## 📊 Results  

| Dataset   | Accuracy |
|-----------|----------|
| Training  | ~98%     |
| Testing   | ~96%     |

![Accuracy Graph](images/accuracy.png)  

---

## 🚀 Installation & Usage  

1️⃣ **Clone this repository**  
```bash
git clone https://github.com/Abhishek-09-Tomar/Data-Science-with-AI-and-ML.git
cd Data-Science-with-AI-and-ML/Spam_mail
```

2️⃣ **Install dependencies**  
```bash
pip install -r requirements.txt
```

3️⃣ **Run the notebook**  
```bash
jupyter notebook spam_mail_detection.ipynb
```

---

## 📌 Future Improvements  

- Integrate with **Flask/Django API** for real-time spam detection  
- Use **Naive Bayes**, **Random Forest**, and compare results  
- Deploy as a **Web App**  

---

## 📸 Screenshots  

### Email Dataset Example  
![Dataset Preview](images/dataset_preview.png)  

### Model Training Output  
![Training Output](images/training_output.png)  

### Spam Detection in Action  
![Spam Detection](images/detection_example.png)  

---

## 🤝 Contributing  

Pull requests are welcome! Please follow the project's code style and add proper documentation.  

---

## 📜 License  

This project is licensed under the **MIT License** — free to use and modify.  
