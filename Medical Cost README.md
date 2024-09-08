📊 Medical Cost Prediction with Linear Regression

This project explores medical cost data to understand the impact of various factors such as age, gender, BMI, smoking habits, and region on medical costs. We use Python for data analysis and build a linear regression model to predict medical costs.

📝 Project Overview

The goal of this project is to analyze medical costs and predict them using linear regression. The dataset contains various features like age, gender, BMI, children, smoking status, and region. The analysis includes exploratory data visualization, data preprocessing, and model training and evaluation.

🔑 Key Features

- Data Visualization: Insights into the distribution of medical costs, and analysis of how different factors affect costs.

- Data Preprocessing: Converting categorical variables into numerical features using one-hot encoding.

- Model Training: Building and training a linear regression model to predict medical costs.

- Evaluation: Evaluating the model's performance using Mean Squared Error (MSE) and R-squared (R²) metrics.

📊 Data Visualization

- Medical Costs Distribution: A histogram with a kernel density estimate to show the distribution of medical costs.

- Medical Costs by Smoking Status: A boxplot to analyze the impact of smoking on medical costs.

- Medical Costs by Region: A boxplot to compare medical costs across different regions.

🚀 Getting Started

To run the project on your local machine, follow these steps:

Prerequisites

- Python 3.x
- Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/medical-cost-prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd medical-cost-prediction
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

Running the Project

1. Ensure that the dataset (`medical_costs.csv`) is available in the project directory.

2. Run the script to perform data analysis, model training, and evaluation:
   ```bash
   python medical_cost_prediction.py
   ```

📈 Model Performance

The linear regression model was evaluated using Mean Squared Error (MSE) and R-squared (R²) metrics:

- Train MSE: 83,769.12
- Test MSE: 84,926.74
- Train R²: 0.9977
- Test R²: 0.9977

📊 Visualizations

- Actual vs Predicted Medical Costs: A scatter plot comparing the actual medical costs to the predicted costs from the model.

![Actual vs Predicted Medical Costs](visualizations/actual_vs_predicted.png)

🤝 Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request. Contributions are welcome!

📜 License

This project is licensed under the MIT License.

📧 Contact

For any inquiries, feel free to reach out via email at [surbhijaiswal8223@gmail.com](mailto:surbhijaiswal8223@gmail.com).
```

Customization Tips

- Replace `yourusername` with your GitHub username and `your-email@example.com` with your actual email address.

- Add details on where to obtain the dataset if it's publicly available.

- Add paths to any screenshots or visualizations, such as `visualizations/actual_vs_predicted.png`.

- Generate a `requirements.txt` file for required libraries using:

  ```bash
  pip freeze > requirements.txt
  ``` 