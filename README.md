# Naive-bayes-Model
# Heart Attack Prediction Using Naïve Bayes  

## 📌 Overview  
This project uses **Machine Learning (Naïve Bayes Classifier)** to predict whether a person is at risk of a **heart attack** based on medical and lifestyle data. The dataset contains information such as **age, cholesterol, blood pressure, smoking habits, physical activity, and more**.  

## 🚀 Technologies Used  
- **Python** 🐍  
- **Pandas** (Data manipulation)  
- **Scikit-Learn** (Machine Learning)  
- **Jupyter Notebook / VS Code** (Development Environment)  

## 📂 Dataset  
The dataset (`heart_attack_prediction_dataset.csv`) contains the following key columns:  
- `Heart Attack Risk` (Target variable: 0 = Low Risk, 1 = High Risk)  
- `Age`, `Cholesterol`, `Blood Pressure` (Predictive medical factors)  
- `Smoking`, `Obesity`, `Exercise`, `Diet` (Lifestyle factors)  
- `Country`, `Continent`, `Hemisphere` (Geographic influence)  

## ⚙️ Project Workflow  
1. **Load and Preprocess the Dataset**  
2. **Encode Categorical Variables (e.g., Sex, Country, Diet, etc.)**  
3. **Split Data into Training and Testing Sets (80% - 20%)**  
4. **Train a Naïve Bayes Classifier**  
5. **Make Predictions and Evaluate Model Performance**  

## 📜 Installation & Setup  
### 🔹 Step 1: Clone the Repository  
```bash
git clone https://github.com/your-username/heart-attack-prediction.git
cd heart-attack-prediction
🔹 Step 2: Install Dependencies
Ensure you have Python 3.8+ and install the required libraries:

bash
Copy
Edit
pip install pandas scikit-learn
or if using Anaconda:

bash
Copy
Edit
conda install pandas scikit-learn
🔹 Step 3: Run the Model
bash
Copy
Edit
python heart_attack_prediction.py
🎯 Results
The model's accuracy is printed after execution:

bash
Copy
Edit
Model Accuracy: 85.43%
(Your accuracy may vary depending on the dataset and training process.)

📌 Future Improvements
Experiment with Decision Trees and Random Forest for better accuracy.
Improve feature selection to enhance predictions.
Create a web interface for real-time predictions.


📩 Author: Lee Tadiwarr

---

### **Next Steps:**
1. **Create a GitHub repo** ➝ Go to [GitHub](https://github.com/) and create a new repository.
2. **Add your files** ➝ Upload `heart_attack_prediction.py` and `heart_attack_prediction_dataset.csv`.
3. **Commit `README.md`** ➝ Copy-paste this file into the repository.
4. **Push it to GitHub**! 🚀  

Let me know if you need help with any of the steps! 😊
