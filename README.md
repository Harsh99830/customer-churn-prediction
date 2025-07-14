<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6; padding: 2rem; max-width: 800px; margin: auto;">

  <h1>📉 Customer Churn Prediction</h1>
  <p>Predicting telecom customer churn using <strong>XGBoost</strong>, <strong>SMOTE</strong>, and <strong>PCA</strong>. This project tackles class imbalance and provides insight into which features most impact customer retention.</p>

  <hr>

  <h2>📂 Dataset</h2>
  <ul>
    <li><strong>Source:</strong> <a href="https://www.kaggle.com/datasets/blastchar/telco-customer-churn" target="_blank">Kaggle - Telco Customer Churn</a></li>
    <li><strong>Rows:</strong> 7043 customers</li>
    <li><strong>Target:</strong> Churn (Yes/No)</li>
  </ul>

  <h2>🧠 Project Goals</h2>
  <ul>
    <li>Classify whether a customer is likely to <strong>churn</strong> or not.</li>
    <li>Handle <strong>imbalanced classes</strong> using SMOTE.</li>
    <li>Use PCA for <strong>dimensionality reduction</strong> and visualization.</li>
    <li>Evaluate performance using classification metrics.</li>
  </ul>

  <h2>🛠️ Techniques Used</h2>
  <table border="1" cellspacing="0" cellpadding="8">
    <thead>
      <tr>
        <th>Task</th>
        <th>Method</th>
      </tr>
    </thead>
    <tbody>
      <tr><td>📊 Preprocessing</td><td>Label Encoding, Scaling</td></tr>
      <tr><td>📈 Classification</td><td>XGBoost</td></tr>
      <tr><td>⚖️ Imbalance Handling</td><td>SMOTE</td></tr>
      <tr><td>🔍 Dimensionality Reduction</td><td>PCA</td></tr>
      <tr><td>📉 Evaluation</td><td>Confusion Matrix, ROC AUC, Classification Report</td></tr>
      <tr><td>🔎 Anomaly Detection</td><td>Isolation Forest (optional)</td></tr>
    </tbody>
  </table>

  <h2>📌 Key Results</h2>
  <ul>
    <li><strong>Accuracy:</strong> 74%</li>
    <li><strong>Recall (Churn class):</strong> 72%</li>
    <li><strong>ROC AUC:</strong> 0.81</li>
    <li><strong>Model:</strong> XGBoost + SMOTE</li>
  </ul>



</body>
</html>
