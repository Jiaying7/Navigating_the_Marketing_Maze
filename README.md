# Customer Segmentation and Predictive Modeling in Marketing

This project applies machine learning models to analyze customer purchasing behavior, segment customers, and predict customer lifetime value (CLV). Using demographic and transactional data, the project aims to provide insights that enhance targeted marketing strategies and improve business decision-making.

## Project Overview

The project focuses on understanding customer behavior by predicting key attributes such as total spending, recency of purchases, customer lifetime, and purchase frequency. It also segments customers using K-means clustering to tailor marketing campaigns to different customer groups. Machine learning models such as Decision Trees, Random Forests, Gradient Boosting, and Neural Networks are employed to provide accurate predictions.

### Key Objectives:
1. Identify key predictive indicators of customer purchasing behavior.
2. Use machine learning algorithms to predict customer lifetime value (CLV).
3. Segment customers using K-means clustering based on demographic and transactional data.

## Dataset

The project uses customer transaction data, demographic information, and online behavior metrics to perform the analysis. Key features include:
- **Customer Lifetime**: Total duration (in days) a customer has been active.
- **Recency**: Number of days since the last purchase.
- **Total Amount**: The total monetary value of all purchases made by the customer.
- **Purchase Frequency**: The total number of purchases made by the customer.

## Machine Learning Models

The following models were implemented to predict CLV and segment customers:
1. **Decision Tree**: A tree-based model used for regression tasks.
2. **Random Forest**: An ensemble learning method for improving the prediction accuracy of decision trees.
3. **Gradient Boosting**: A model that builds strong learners by combining weak ones.
4. **Neural Networks**: A deep learning model for capturing complex relationships in data.
5. **K-means Clustering**: A segmentation algorithm used to group customers into distinct clusters based on their purchasing behavior and demographics.

## Methodology

1. **Data Preprocessing**: The dataset was cleaned by handling missing values, standardizing numerical features, and encoding categorical variables. Outliers were removed to improve model accuracy.
2. **Exploratory Data Analysis (EDA)**: Visualizations were used to understand data distributions and relationships, including histograms and box plots of transaction amounts.
3. **Feature Engineering**: New features such as customer lifetime, recency, total amount, and purchase frequency were derived.
4. **Model Training and Evaluation**:
    - Models were evaluated using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² Score.
    - Clustering was evaluated using the Silhouette Score.

### Model Performance
- **Decision Tree**: Achieved an R² score of 1.0 but showed signs of overfitting.
- **Random Forest**: Achieved an R² score of 0.99, with an MAE of 0.058.
- **Gradient Boosting**: R² score of 0.998 with an MAE of 2.23.
- **Neural Network**: Demonstrated strong performance with an R² score of 0.9995.
- **K-means Clustering**: Achieved a moderate Silhouette Score of 0.428, indicating reasonably well-defined clusters.

## Visualizations

The project includes visualizations such as:
- **Feature Importance**: Displaying the most significant features for predicting CLV.
- **Customer Segmentation**: Using K-means clustering to group customers based on behavior and demographics.
- **Actual vs Predicted Values**: Scatter plots comparing model predictions to actual CLV values.

## How to Run

1. **Clone the repository**:
    ```bash
    git clone https://github.com/YOUR_USERNAME/customer-segmentation-predictive-modeling.git
    ```
2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3. **Run the Jupyter Notebooks**:
    - To run the models and visualizations, open and execute the provided Jupyter notebooks:
    ```bash
    jupyter notebook
    ```

## Technologies Used

- **Python**: Main programming language.
- **Pandas, Scikit-learn**: For data preprocessing, model building, and evaluation.
- **TensorFlow**: Used for building and training Neural Networks.
- **Matplotlib, Seaborn**: For creating data visualizations.

## Results and Insights

- **Key Predictors**: Total amount spent by a customer was the strongest predictor of CLV, followed by recency and customer lifetime.
- **Customer Segmentation**: Customers were effectively grouped into clusters for targeted marketing campaigns, improving personalized marketing efforts.
- **Business Implications**: These insights can guide businesses in allocating resources more effectively, increasing marketing ROI, and improving customer retention.

## Future Enhancements

1. **Include Social Media Data**: Integrating customer feedback and online interactions for deeper insights.
2. **Real-time Prediction**: Implement real-time data processing to dynamically adjust marketing strategies.
3. **Advanced Models**: Explore hybrid models or deep learning techniques for improved accuracy.

## License

This project is licensed under the MIT License.
