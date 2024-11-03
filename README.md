<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bank Churn Prediction</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #121212; /* Dark background for VS Code theme */
            color: #ffffff;
            margin: 0;
            padding: 20px;
        }

        h1 {
            color: #2a9d8f;
            text-align: center;
            margin-bottom: 20px;
        }

        .section {
            background-color: #1e1e1e;
            border-radius: 10px;
            padding: 20px;
            margin: 20px 0;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .section:hover {
            transform: scale(1.02);
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
        }

        h2 {
            color: #e76f51;
        }

        p {
            color: #dddddd;
        }

        a {
            color: #2a9d8f;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        a:hover {
            color: #e76f51;
            text-decoration: underline;
        }

        code {
            background-color: #333;
            padding: 2px 4px;
            border-radius: 4px;
        }

        /* Responsive design */
        @media (max-width: 600px) {
            .section {
                padding: 15px;
            }
        }
    </style>
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
        <h2>Installation</h2>
        <p>To set up the project, follow these steps:</p>
        <ol>
            <li>Clone the repository: <code>git clone https://github.com/yourusername/bank-churn-prediction.git</code></li>
            <li>Navigate to the project directory: <code>cd bank-churn-prediction</code></li>
            <li>Install required packages: <code>pip install -r requirements.txt</code></li>
        </ol>
    </div>

    <div class="section">
        <h2>Usage</h2>
        <p>To run the project, use the command: <code>python main.py</code>. Follow the instructions in the command line interface.</p>
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
            <li>Support Vector Machines</li>
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
                <td style="padding: 10px;">XX%</td>
            </tr>
            <tr>
                <td style="padding: 10px;">Decision Tree</td>
                <td style="padding: 10px;">XX%</td>
            </tr>
            <tr>
                <td style="padding: 10px;">Random Forest</td>
                <td style="padding: 10px;">XX%</td>
            </tr>
            <tr>
                <td style="padding: 10px;">SVM</td>
                <td style="padding: 10px;">XX%</td>
            </tr>
        </table>
    </div>

    <div class="section">
        <h2>Contributors</h2>
        <p>Developed by <a href="https://github.com/yourusername">Hasaan Khan</a> and <a href="https://www.openai.com">ChatGPT</a>.</p>
    </div>

    <div class="section">
        <h2>License</h2>
        <p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.</p>
    </div>

</body>
</html>
