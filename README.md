## Statistical Methods for Data Science Final Project
### Project Title: E-commerce Sales Analysis and Recommendation System

### Project Overview
This project explores e-commerce sales data to develop a robust recommendation system for a UK-based online gifting platform. By analyzing user behavior and transaction patterns, we aimed to create a system that optimizes product suggestions, predicts sales trends, and enhances the customer shopping experience.

### Business Proposition
The goal was to help users save time and reduce stress in finding gifts by developing a personalized, efficient recommendation system. By leveraging advanced machine learning techniques, we sought to:

- Predict customer preferences and suggest complementary or substitute products.
- Analyze optimal product-launch and promotion times.
- Increase profitability for both the platform and its retailer partners.

### Dataset Overview
Source: Kaggle (UK E-commerce dataset)
- Variables: InvoiceNo, Description, Quantity, UnitPrice, CustomerID, Country, InvoiceDate.
- Size: 541,909 observations across 4,224 products, with data spanning 38 countries.
- Key Metrics:
            - Unique Orders: 25,900
            - Unique Users: 4,373
  
### Methods and Techniques
We employed a combination of statistical analysis, machine learning, and deep learning to achieve project goals:

- Exploratory Data Analysis (EDA): Sales trends by time, product popularity, and customer segmentation.
- NLP (Word Clouds): Visualized product descriptions to analyze popular items.
- Regression and Classification:
            - Random Forest and XGBoost for sales prediction.
            - K-Nearest Neighbors (KNN) for personalized product recommendations.
            - Recommendation System: Built using a user-item matrix and KNN to suggest similar products based on purchase history.

### Results
1. Recommendation System: Successfully identified similar products using KNN with cosine similarity.
2. Sales Trends:
            - Higher sales observed during mid-month and weekends.
            - Increased activity toward the end of the year due to holiday shopping.
3. Predictions: XGBoost outperformed Random Forest for forecasting daily sales quantities.

### Tools and Libraries
**Python:** pandas, numpy, matplotlib, seaborn, scikit-learn, XGBoost
**Visualization:** t-SNE, Word Clouds, and bar charts for trend analysis.

### Challenges
- Initial deep learning models were computationally expensive, prompting a shift to ensemble learning methods for efficiency.
- Lack of demographic data limited user-specific insights.

### Conclusion
The project demonstrated the potential of data-driven approaches to improve user experiences and boost profitability in e-commerce. Our recommendation system and sales analysis highlighted actionable insights for better product targeting and promotional planning.

### Resources
Project Report:  [Project Document](documents/ProjectReport.docx)  
Presentation Slides: [Project Presentation](documents/ecommerce.pptx)

Data Source: [Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

### How to Run the Project
- Clone this repository.
- Install dependencies using pip install -r requirements.txt.
- Run the Jupyter notebook or Python script to explore the recommendation system and models.
