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

The dataset contains hourly averaged responses from a gas multisensor device deployed in an Italian city.
**Target variable:** `CO(GT)` (Carbon Monoxide concentration).

📥 **Source:** [Air Quality Dataset (UCI)](https://archive.ics.uci.edu/ml/datasets/Air+Quality)

---

### 📖 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/<your-username>/Air_Quality.git
   cd Air_Quality
   ```

2. Open the notebook in **Google Colab** or Jupyter.

3. Run the notebook cells sequentially to:

   * Load and clean the dataset.
   * Visualize and analyze the data.
   * Train and evaluate the ML model.

4. The trained model is saved as `air_quality_model.pkl`.

---

### 📊 Project Workflow

1. **Data Ingestion** – Load raw dataset.
2. **Preprocessing** – Handle missing values and scale features.
3. **EDA** – Generate visual insights and explore relationships.
4. **Model Training** – Train a Random Forest Regressor with hyperparameter tuning.
5. **Evaluation** – Validate model performance using Mean Squared Error (MSE).
6. **Model Saving** – Store pipeline for future use.

---

### 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
