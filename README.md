# Zomato Delivery Data Analysis and Performance Optimization

An Exploratory Data Analysis (EDA) project to optimize Zomato's delivery performance using Python, Pandas, and Seaborn. Analyzed 45k+ delivery records to uncover factors affecting delivery times and customer satisfaction, with actionable recommendations for operational efficiency.[](https://github.com/Yashwant-pro/Zomato-Delivery-EDA-Optimization)

## Project Overview
This project analyzes Zomato delivery data to identify key factors impacting delivery performance, such as traffic, weather, distance, and time of day. The dataset includes delivery person details, order details, location, traffic, weather, and delivery times. The analysis involves data cleaning, feature engineering, visualization, and insights generation to optimize operations.

## Key Findings
- **Traffic Impact**: High traffic density increases delivery time by ~20% (26 to 31 minutes).
- **Weather Effect**: Adverse weather (e.g., Fog, Stormy) adds ~15% to delivery time (30 vs. 26 minutes).
- **Distance vs Rating**: Short deliveries (<5 km) have higher ratings (4.7 vs. 4.5 for >10 km).
- **Time of Day**: Evening orders (post-6 PM) face 10% higher delays (28 vs. 25 minutes).
- **City and Festival Impact**: Metropolitan cities during festivals see 12% longer deliveries (32 vs. 28 minutes).
- **Data Quality**: Corrected 38 invalid ages, 53 invalid ratings, and 431 invalid distances for robust analysis.

## Recommendations
1. **Dynamic Delivery Assignment**: Use real-time traffic and weather data to assign personnel.
2. **Incentive Programs**: Reward high-rated delivery personnel (ratings > 4.5).
3. **Route Optimization**: Prioritize shorter routes using mapping algorithms.

## Visualizations
- **Boxplot**: Delivery time by weekday and city.
- **Histogram**: Distribution of delivery distances and times.
- **Pairplot**: Relationships among age, ratings, time, and distance.

## Tools and Technologies
- **Python**: Pandas, NumPy for data manipulation.
- **Visualization**: Matplotlib, Seaborn for plots.
- **Data Cleaning**: Haversine formula for distance calculation, median imputation for anomalies.
- **Optional**: Scikit-learn, SciPy, Plotly for advanced analysis (commented in notebook).

## How to Run
1. Clone the repository: `git clone https://github.com/<your-username>/Zomato-Delivery-EDA-Optimization.git`
2. Install dependencies: `pip install pandas numpy matplotlib seaborn scipy scikit-learn plotly`
3. Place `zomato_dataset.csv` in the root folder or update the dataset path to the Kaggle URL.
4. Open and run the notebook in Jupyter: `jupyter notebook Zomato Delivery Data Analysis and Performance Optimization.ipynb`

## Dataset
- Source: [Kaggle Food Delivery Dataset](https://www.kaggle.com/datasets/saurabhbadole/zomato-delivery-operations-analytics-dataset)
- Size: ~45k records
- Columns: Delivery person details, order details, location, traffic, weather, delivery time.

## About the Author
**Yashwant Singh**  
Data Analyst (Fresher) passionate about uncovering insights from data to drive business decisions.  
- GitHub: [github.com/<your-username>](https://github.com/Yashwant-pro)  
- LinkedIn: [linkedin.com/in/<your-linkedin>](www.linkedin.com/in/yashwantsingh01)  

## Future Improvements
- Add predictive modeling for delivery time forecasting.
- Incorporate real-time traffic data APIs.
- Expand analysis to customer segmentation.

