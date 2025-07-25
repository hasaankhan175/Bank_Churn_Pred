<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Bank Churn Prediction Project</h1>
    <div class="section">
        <h2>Overview</h2>
        <p>This project aims to predict customer churn in the banking sector using machine learning algorithms. By analyzing customer behavior and characteristics, banks can implement strategies to retain customers.</p>
    </div>
    <div class="section">
        <h2>Features</h2>
        <ul>
            <li>Data Analysis: In-depth analysis of customer data.</li>
            <li>Predictive Modeling: Various machine learning models to predict churn.</li>
            <li>Visualization: Interactive plots to display results.</li>
        </ul>
    </div>
    <div class="section">
        <h2>Data Description</h2>
        <p>The dataset includes columns such as:</p>
        <ul>
            <li><code>CustomerId</code>: Unique identifier for each customer.</li>
            <li><code>Gender</code>: Gender of the customer.</li>
            <li><code>Age</code>: Age of the customer.</li>
            <li><code>Tenure</code>: Number of years with the bank.</li>
            <li><code>Balance</code>: Account balance.</li>
            <li><code>Exited</code>: Target variable indicating churn status (1 for churn, 0 for non-churn).</li>
        </ul>
    </div>
    <div class="section">
        <h2>Modeling</h2>
        <p>The project implements various machine learning algorithms, including:</p>
        <ul>
            <li>Logistic Regression</li>
            <li>Decision Trees</li>
            <li>Random Forest</li>
            <li>KNN</li>
        </ul>
    </div>
    <div class="section">
        <h2>Results</h2>
        <p>The final model achieved an accuracy of <strong>XX%</strong>. Here’s a summary of the model performance:</p>
        <table style="width: 100%; border-collapse: collapse;">
            <tr style="border-bottom: 1px solid #444;">
                <th style="text-align: left; padding: 10px;">Model</th>
                <th style="text-align: left; padding: 10px;">Accuracy</th>
            </tr>
            <tr>
                <td style="padding: 10px;">Logistic Regression</td>
                <td style="padding: 10px;">83%</td>
            </tr>
            <tr>
                <td style="padding: 10px;">K Nearest Neighbours</td>
                <td style="padding: 10px;">76%</td>
            </tr>
            <tr>
                <td style="padding: 10px;">Random Forest</td>
                <td style="padding: 10px;">99.95%</td>
            </tr>
            <tr>
                <td style="padding: 10px;">Decision Tree Classifier</td>
                <td style="padding: 10px;">99.10%</td>
            </tr>
        </table>
    </div>
    <div class="section">
        <h2>Contributors</h2>
        <p>Developed by <a href="https://github.com/hasaankhan175">Hasaan Khan</a>
    </div>
</body>
</html>
