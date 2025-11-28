# 🏭 Industrial Machine Maintenance Prediction

## 📘 Overview
This project focuses on predicting whether an industrial machine requires maintenance based on real-world numeric sensor data.  
It is a **Binary Classification** problem where:

- `1` = Machine needs maintenance  
- `0` = Machine is operating normally  

The dataset contains **654 rows** and **5 fully numeric features**, including temperature, pressure, vibration, humidity, and power metrics.  
Missing values, noise, and realistic variability were included to simulate real industrial environments.

## 🧠 Project Highlights
- **Type:** Binary Classification  
- **Language:** Python 🐍  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Dataset:** `factory_machine_health.csv` — numeric industrial sensor readings  
- **Data Type:** Entire dataset is numeric → preprocessing becomes simpler and faster

## ⚙️ Workflow
### ✔ Data Preprocessing
- Handling missing values  
- Scaling features using StandardScaler  
- Cleaning noisy numeric fields  

## 🚧 Challenges
- Dataset contained noisy numeric sensor data → required additional cleaning  
- Initial models sometimes favored the majority class  
- After tuning and proper preprocessing, Decision Tree achieved strong results for this task

## 📊 Results
- **Final Test Accuracy (Decision Tree): ~91%**  
- Precision & Recall indicate robust detection of maintenance cases  
- Confusion matrix and additional metrics are included in the notebook for detailed analysis  
- Model generalizes well on held-out data — suitable for initial predictive maintenance deployment

## 💡 Skills Used
- 🐍 Python  
- 🤖 Machine Learning  
- 📊 Data Analysis  
- 📈 Data Visualization  

## 📁 Files Included
- `industrial_observation.ipynb` → Main notebook (contains data processing, model training, and evaluation)  
- `factory_machine_health.csv` → Dataset

## 📬 Contact
📧 Email: **amirhossin6825@gmail.com**  
💬 Telegram: **@AmirHossin6825** 
