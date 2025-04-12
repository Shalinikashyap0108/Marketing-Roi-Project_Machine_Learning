# Optimizing Marketing ROI for a Retail Brand

**Objective**

This project builds a Market Mix Model to determine the effectiveness of various marketing channels (TV, online ads, email marketing, etc.) in driving sales. It provides actionable insights to optimize marketing spend and maximize ROI.

**Key Features**

- Data Generation: Hypothetical data simulating marketing spends and corresponding sales.

- Regression Modeling: Implementation of Linear, Ridge, and Lasso regression models to estimate the contributions of each channel to sales.

- Feature Importance Analysis: Evaluating the significance of each marketing channel.

- Budget Optimization: Using optimization techniques to recommend the best allocation of marketing budgets.

- Visualizations: Clear and informative visualizations to aid understanding and decision-making.

**Tools and Libraries**

- Python

- pandas, numpy: Data manipulation and preprocessing.

- matplotlib, seaborn: Data visualization.

- scikit-learn: Building regression models.

- scipy.optimize: Budget optimization.

**Workflow**

- Data Generation:

  - Simulated data for TV, online, and email marketing spends with corresponding sales figures.

  - Added randomness to mimic real-world data.

- Exploratory Data Analysis (EDA):

  - Visualized pairwise relationships between marketing channels and sales.

![image](https://github.com/user-attachments/assets/8ca946d2-6f78-49d5-afb0-b93c1c88f1ae)


- Model Building:

  - Trained Linear, Ridge, and Lasso regression models on the data.

  - Evaluated model performance using metrics like MSE and R².

- Feature Importance:

  - Extracted and compared feature coefficients across models.

![image](https://github.com/user-attachments/assets/21b91ff5-e186-4250-b2f5-754631fea8d1)


- Optimization:

  - Formulated and solved a budget optimization problem to maximize ROI.

  - Output the optimized budget allocation for TV, online ads, and email marketing.

**Insights**

- Effectiveness of Marketing Channels: Detailed insights into the effectiveness of different marketing channels indicate that:

- Email marketing (0.34) has the highest impact on sales, followed by online ads (0.23) and TV ads (0.14).

- Correlation Analysis:

  - Correlation matrix indicates that TV ad spend (0.25) has the highest linear relationship with sales, followed by online ad spend (0.17) and email marketing spend (0.11).
      
  - ![image](https://github.com/user-attachments/assets/aeabf4d9-10f9-403a-ab1e-7f4e232621ce)

- Model Performance:
    
  - For all three models:
      
    - R²: -0.8826733986045829
        
    - RMSE: 7248.41286282087

- Recommended optimized budget allocation for maximizing sales: TV = 50000.00, Online = 25000.00, Email = 10000.00

**Future Enhancements**

- Incorporate real-world data to improve model accuracy.

- Add support for additional marketing channels like social media and print media.

- Explore advanced modeling techniques for better predictions.

**Contact**

For queries or contributions, feel free to reach out at shalini.kashyap0108@gmail.com.
