# 🏡 Real Estate Price Prediction using Machine Learning

This project predicts house prices using machine learning based on features like area, number of bedrooms, bathrooms, and more.

🔗 **GitHub Repository:**  
[https://github.com/Abhishek-09-Tomar/Data-Science-with-AI-and-ML](https://github.com/Abhishek-09-Tomar/Data-Science-with-AI-and-ML)

---

## 🚀 Features

- Real-time price prediction using trained ML models
- Clean preprocessing pipeline
- Model comparison and evaluation
- Lightweight web app for interaction

---

## 📁 Project Structure

```
Data-Science-with-AI-and-ML/
│
├── Evergreen_Estates/               # App folder
│   ├── app.py                       # Flask server
│   ├── Evergreen.joblib             # Trained model
│   ├── templates/
│   │   └── index.html               # Web UI
│   └── static/                      # Optional static assets
│
├── data.csv                         # Real estate dataset
├── Outputs_from_diff_model.txt      # Model comparison outputs
├── housing.data                     # Raw data
├── housing.names                    # Description of features
```

---

## 🛠️ Tech Stack

- **Languages:** Python
- **Libraries:** pandas, scikit-learn, NumPy, joblib
- **Web:** Flask, HTML, CSS

---

## 📊 ML Process

1. Data Cleaning & Feature Engineering  
2. Model Training with Linear Regression, Random Forest, etc.  
3. Model Evaluation (saved outputs)  
4. Deployment-ready model using `joblib`

---

## ⚙️ Getting Started

```bash
# Clone the repo
git clone https://github.com/Abhishek-09-Tomar/Data-Science-with-AI-and-ML.git

# Navigate to project
cd Data-Science-with-AI-and-ML/Evergreen_Estates

# Install dependencies
pip install -r requirements.txt

# Run the web app
python app.py
```

Visit `http://localhost:5000` in your browser to start predicting prices.

---

## 📸 Sample Output

- Enter home details ➝ Instantly get predicted price  
- Clean and responsive interface

---

## 🧠 Future Improvements

- Integrate map-based location data  
- Add model interpretability with SHAP/LIME  
- Deploy online (Heroku, Vercel)

---

## 📄 License

Open-source under the [MIT License](LICENSE).

---

Made with ❤️ by [Abhishek Tomar](https://github.com/Abhishek-09-Tomar)
