<h1>Lung Cancer Survival Prediction</h1>

<p><img src="banner_lung_cancer_model.png" alt="Lung Cancer Model Banner" width="600"></p>

<p>
This project uses machine learning to predict the survival of lung cancer patients based on medical and demographic data. It was trained on over <strong>890,000 data points</strong> and achieved a training accuracy of <strong>0.77</strong> using the XGBoost classifier.
</p>

<h2>📌 Project Description</h2>
<p>
Lung cancer is one of the leading causes of cancer-related deaths. Predicting survival outcomes can help guide treatment decisions and resource allocation. This model uses features such as:
</p>
<ul>
  <li>Age, Gender</li>
  <li>Cancer Stage</li>
  <li>Cholesterol and BMI</li>
  <li>Smoking Status</li>
  <li>Type of Treatment</li>
  <li>Treatment Duration (calculated from Diagnosis and End Treatment Dates)</li>
</ul>

<h2>📊 Dataset Overview</h2>
<p><img src="dataset_overview_infographic.png" alt="Dataset Overview Infographic" width="500"></p>
<p>
The dataset underwent preprocessing steps including:
</p>
<ul>
  <li>Dropping irrelevant columns (like <code>ID</code>, <code>Country</code>)</li>
  <li>Encoding categorical features using one-hot encoding</li>
  <li>Calculating treatment duration in days</li>
</ul>

<h2>🧠 ML Workflow</h2>
<p><img src="model_pipeline_diagram.png" alt="Model Pipeline Diagram" width="500"></p>
<ul>
  <li>Data cleaning and preprocessing</li>
  <li>Train-test split</li>
  <li>XGBoost model training</li>
  <li>Model evaluation and feature importance analysis</li>
</ul>

<h2>📈 Feature Importance</h2>
<p><img src="feature_importance.png" alt="Feature Importance" width="500"></p>
<p>
Most important features included:
</p>
<ul>
  <li>Cancer Stage</li>
  <li>Type of Treatment</li>
  <li>Treatment Duration</li>
  <li>Age</li>
</ul>

<h2>📉 Model Results</h2>
<p><img src="ml_result_summary_card.png" alt="Model Results Summary" width="500"></p>
<p>
The XGBoost classifier achieved:
</p>
<ul>
  <li>Training Accuracy: <strong>77%</strong></li>
  <li>Robust handling of missing values</li>
  <li>Good generalization with default parameters</li>
</ul>

<h2>🚀 Future Improvements</h2>
<ul>
  <li>Apply cross-validation and hyperparameter tuning</li>
  <li>Integrate model into a web-based application using Streamlit or Flask</li>
  <li>Build an interactive dashboard for healthcare use</li>
</ul>

<h2>👨‍💻 Author</h2>
<p>
<strong>Sanskar Gupta</strong><br>
Aspiring Data Scientist<br>
Passionate about solving real-world problems with machine learning and AI
</p>
