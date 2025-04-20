# 🔐 NLP Password Strength Classifier

This project demonstrates how to build a **Password Strength Classifier** using **Natural Language Processing (NLP)** techniques and traditional machine learning. The goal is to classify passwords into different strength levels: **Weak**, **Medium**, or **Strong**, based on the features extracted from the passwords.

---

## 📊 Project Overview

The notebook performs the following:

- Loads and processes a dataset of passwords and their corresponding strength labels.
- Preprocesses passwords using `CountVectorizer` to convert text data into numerical features.
- Trains a **Multinomial Naive Bayes classifier** to predict password strength.
- Evaluates the model using metrics like accuracy and confusion matrix.
- Allows user input to test custom password strength predictions.

---

## 🧪 Tech Stack

- Python 🐍  
- Pandas 📊  
- NumPy 🔢  
- Scikit-learn 🤖  
- Matplotlib 📈  
- Seaborn 🎨  
- Jupyter Notebook 📓

---

## 🚀 How to Run

1. **Clone this repo** or download the notebook:
```bash
git clone https://github.com/yourusername/NLP_password_strength.git
```

2. **Navigate into the project folder**:
```bash
cd NLP_password_strength
```

3. **Install dependencies** (recommended inside a virtual environment):
```bash
pip install -r requirements.txt
```

> _Alternatively, install manually:_
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. **Open the notebook**:
```bash
jupyter notebook NLP_password_strength.ipynb
```

5. **Run all cells** to train the model and try it with your own password inputs.

---

## 📌 Features

- ✅ Password vectorization using NLP bag-of-words approach  
- ✅ Predicts strength as Weak (0), Medium (1), or Strong (2)  
- ✅ Confusion matrix and visualizations for performance analysis  
- ✅ Interactive test cell to evaluate password strength  

---

## 📷 Sample Output

Confusion matrix for classification:  
*(Add screenshot here if desired)*

---

## 💡 Future Improvements

- Use advanced NLP techniques like character-level embeddings or LSTMs  
- Add password policy feedback based on predictions  
- Deploy as a web app using Flask or Streamlit  

---

## 🤝 Contributing

Feel free to fork the project, suggest improvements, or submit PRs!

---

## 📜 License

This project is open-source under the MIT License.

---

> Created with 💡 and 💻 by SPD.
