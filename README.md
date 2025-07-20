## 🌿 Air Quality Prediction – ML Pipeline

This project builds a **clean, modular, production-ready machine learning pipeline** to predict air pollutant levels using historical air quality data. The pipeline includes data cleaning, feature engineering, model training, and evaluation, along with visual insights into pollutant patterns.

---

### 🚀 Features

* End-to-end ML pipeline for regression tasks.
* Handles missing values and scales data effectively.
* Visualizes pollutant levels and relationships.
* Hyperparameter tuning using GridSearchCV.
* Saves the trained model for future predictions.

---

### 🛠️ Technologies Used

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
* Joblib

---

### 📂 Dataset

This project uses the **Air Quality Dataset** from Kaggle.
The dataset contains hourly measurements of air pollutants collected from multiple monitoring stations.
**Target variable:** `CO(GT)` (Carbon Monoxide concentration).

📥 **Source:** [Air Quality Dataset on Kaggle](https://www.kaggle.com/datasets/fedesoriano/air-quality-data-set)

---

### 📖 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/<your-username>/Air_Quality.git
   cd Air_Quality
   ```

2. Download the dataset from Kaggle and place it in the project folder.

3. Open the notebook in **Google Colab** or Jupyter.

4. Run the notebook cells sequentially to:

   * Load and clean the dataset.
   * Visualize and analyze the data.
   * Train and evaluate the ML model.

5. The trained model is saved as `air_quality_model.pkl`.

---

### 📊 Project Workflow

1. **Data Ingestion** – Load raw dataset from Kaggle.
2. **Preprocessing** – Handle missing values and scale features.
3. **EDA** – Generate visual insights and explore relationships.
4. **Model Training** – Train a Random Forest Regressor with hyperparameter tuning.
5. **Evaluation** – Validate model performance using Mean Squared Error (MSE).
6. **Model Saving** – Store pipeline for future use.

---

### 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
