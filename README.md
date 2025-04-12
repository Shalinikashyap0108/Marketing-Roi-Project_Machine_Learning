# Optimizing Retail Marketing ROI Through Data-Driven Decision Making

In a world where retail brands invest heavily across multiple marketing channels, one question often goes unanswered—Which channel truly drives sales? This project began as a thought experiment while exploring the disconnect between marketing spend and actual returns. Could we quantify the ROI of different campaigns using data science? The result: a Market Mix Modeling approach designed to bring clarity and control to retail marketing strategies.

**The Motivation**

Marketing teams often face pressure to "do more" with limited budgets. TV ads, online campaigns, and email promotions all compete for attention—but not every rupee spent yields the same return. This project simulates a retail brand's marketing landscape and uses regression models and optimization techniques to identify the most impactful marketing mix. The aim is to empower decision-makers with insights that replace guesswork with strategy.

**Project Overview**

We built a Market Mix Model using simulated yet realistic data for TV ads, online advertising, and email campaigns. Each record represents a marketing spend scenario and its corresponding sales outcome. From this foundation, we constructed regression models, performed feature importance analysis, and used optimization techniques to propose an ideal budget allocation.

**Workflow Breakdown**

1. Data Generation & EDA

- Generated synthetic data to simulate marketing spends and sales figures.

- Incorporated randomness to reflect real-world marketing unpredictability.

- Conducted exploratory data analysis to examine relationships between spends and sales using correlation matrices and pair plots.

  ![image](https://github.com/user-attachments/assets/8ca946d2-6f78-49d5-afb0-b93c1c88f1ae)

2. Model Building

- Developed Linear, Ridge, and Lasso regression models.

- Evaluated models based on R² and RMSE to understand performance.

- Compared feature coefficients to assess the influence of each channel.
  
  ![image](https://github.com/user-attachments/assets/21b91ff5-e186-4250-b2f5-754631fea8d1)

3. Optimization Strategy

- Formulated a constrained optimization problem using scipy.optimize to maximize sales within a fixed budget.

- Recommended an optimized budget split across TV, online, and email channels to yield the best returns.

**Key Insights**

- Email Marketing emerged as the most impactful channel with a coefficient of 0.34, followed by online ads (0.23) and TV (0.14).

- Interestingly, TV spend showed the highest correlation with sales (0.25), but that didn’t translate into the highest ROI when controlling for all variables.

- All three regression models yielded consistent results, though overall R² values were negative due to the small sample size and synthetic nature of the data—highlighting the importance of real-world data for future iterations.

Optimized Budget Allocation
- TV Ads: ₹50,000

- Online Ads: ₹25,000

- Email Marketing: ₹10,000

This allocation maximizes returns while respecting a defined marketing budget.

**Tools & Technologies**

- Python (Jupyter Notebook)

- pandas, numpy – Data preparation & manipulation

- matplotlib, seaborn – Visualization

- scikit-learn – Modeling (Linear, Ridge, Lasso)

- scipy.optimize – Budget optimization logic

**Looking Ahead**

This project provides a powerful proof of concept. With access to real-world retail data, the model can:

- Support more marketing channels (e.g., social media, influencer campaigns).

- Integrate seasonality and lag effects.

- Use time series or Bayesian models for deeper forecasting.

**Contact**

Have questions or want to collaborate on retail analytics?

Reach me at shalini.kashyap0108@gmail.com
