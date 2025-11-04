🏭 Factory Machine Health Monitoring  
📘 Overview  
This project applies **Machine Learning** techniques to predict the operational condition of factory machines.  
The dataset is **fully numeric**, containing only quantitative sensor measurements — ideal for model-based analysis.  
It’s a **Binary Classification** problem where the goal is to identify whether a machine is healthy or at risk of failure.  

🧠 Project Highlights  
- **Type:** Binary Classification  
- **Language:** Python 🐍  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Dataset:** `factory_machine_health.csv` — contains machine sensor data and operational indicators.  

⚙️ Workflow  
1. **Data Cleaning & Preprocessing** – handling missing values and outliers.  
2. **EDA (Exploratory Data Analysis)** – visualizing distributions, correlations, and feature importance.  
3. **Feature Scaling** – applied using `Pipeline` for consistent standardization.  
4. **Model Training** – several models tested (LR, LDA, KNN, NB, CART, SVM).  
5. **Model Tuning** – hyperparameter optimization to improve accuracy.  
6. **Model Evaluation** – accuracy, precision, recall, and F1-score metrics.  

🚧 Challenges  
Some sensor readings were noisy or contained outliers.  
Through preprocessing and model tuning, overall accuracy improved from ~78% to ~89%.  

📊 Results  
✅ Best Model: **Decision Tree (CART)**  
🎯 Test Accuracy: **91.67%**  
📉 The model performed exceptionally well for healthy machines (class 0) but had minor difficulty detecting faulty ones (class 1).  

💡 Skills Used  
🐍 Python  
🤖 Machine Learning  
📊 Data Science  
📈 Model Optimization  
📉 Data Visualization  

📁 Files Included  
- `industrial_observation.ipynb` → Main analysis notebook  
- `factory_machine_health.csv` → Dataset  

📬 Contact  
📧 amirhossin6825@gmail.com  
💬 Telegram: [@AmirHossin6825](https://t.me/AmirHossin6825)
