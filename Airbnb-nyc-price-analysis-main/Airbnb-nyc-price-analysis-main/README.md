 NYC Airbnb Price Analysis
 
This project explores how room type, location, and availability affect Airbnb pricing in New York City. Using Python in Google Colab, we performed data cleaning, visual analysis, and trend discovery to uncover valuable insights for pricing strategy.

Dataset
- Source: [Kaggle - NYC Airbnb Open Data (2019)](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)
- Size: 48,895 rows × 16 columns
- Format: CSV

Objectives
- Clean and preprocess real-world Airbnb listing data
- Explore price distribution and identify outliers
- Compare average prices across boroughs and room types
- Visualize insights for decision-making

Tools & Libraries
- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn

## 📊 Key Insights
- Manhattan has the highest concentration of listings and the highest average prices.
- Entire home/apartment listings command significantly higher prices than private/shared rooms.
- Most listings fall under $200; outliers above $1,000 were excluded.
- Brooklyn and Queens offer more affordable options with decent availability.

Project Steps
1. Load and inspect the dataset
2. Drop irrelevant columns (e.g., ID, host name)
3. Handle missing values and fill or drop appropriately
4. Remove listings with price = 0 and price > $1000 (outliers)
5. Create visualizations to interpret pricing trends

 Files in This Repository
- Airbnb_Price_Analysis_NYC.ipynb – The full notebook (Google Colab)
- README.md – Project overview and insights
  -Raw data
  
Future Enhancements
- Add geospatial maps (using Folium or Plotly)
- Apply machine learning to predict Airbnb prices
- Explore seasonal or temporal price patterns
Author
Imeobong Tom Monday 
GitHub Portfolio | Google Colab Notebooks
