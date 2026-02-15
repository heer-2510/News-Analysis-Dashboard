📊 News Sentiment & Location Analysis Dashboard

📌 Project Overview

The News Sentiment & Location Analysis Dashboard is an interactive Power BI project designed to analyze news article headlines based on sentiment and geographic location. The dashboard categorizes news content into Positive, Neutral, and Negative sentiments and visualizes how these sentiments are distributed across different locations.

The complete data cleaning, transformation, modeling, and visualization process was performed entirely within Power BI using Power Query and DAX.

🎯 Objectives

- Perform sentiment-based analysis of news headlines
- Identify distribution of Positive, Neutral, and Negative sentiments
- Analyze location-wise news coverage
- Compare sentiment patterns across different cities
- Provide interactive filtering for deeper data exploration

🛠 Tools & Technologies Used

- Power BI Desktop
- Power Query (Data Cleaning & Transformation)
- DAX (Data Analysis Expressions)
- Data Modeling and Visualization inside Power BI

No external tools were used. The entire workflow was completed within Power BI.

🔄 Data Cleaning & Preparation

The following data preparation steps were performed using Power Query:

- Removed null and blank values
- Cleaned and standardized sentiment labels
- Formatted and corrected location names
- Removed duplicate records
- Structured data for proper modeling
- Created calculated columns and measures using DAX

📈 Dashboard Components

1️⃣ Sentiment Distribution
- Bar chart showing count of headlines by sentiment label
- Pie chart showing percentage distribution of sentiments

2️⃣ Location Analysis
- Bar chart showing count of news articles by named entity (location)
- Stacked column chart comparing sentiment distribution by location

3️⃣ Interactive Filters
- Sentiment slicer (Positive, Neutral, Negative)
- News type filter for dynamic analysis

📊 Key Insights

- Neutral sentiment dominates overall news coverage.
- Certain cities have higher news article frequency.
- Sentiment patterns vary across different locations.
- Some locations show stronger positive or negative trends compared to others.

💡 Business Value

This dashboard helps:

- Analyze public opinion trends
- Compare geographic impact of news
- Support data-driven decision-making
- Provide visual storytelling through interactive reports

⚠️ Limitations

- The dashboard relies on pre-classified sentiment labels and does not perform real-time NLP modeling.
- Sentiment classification may not capture sarcasm, context, or complex language patterns.
- The dataset is limited and may not represent all geographic regions.
- Location extraction depends on available named entities.
- Analysis is based on static data (no real-time refresh).
- Advanced NLP techniques such as topic modeling were not implemented.

🚀 Future Enhancements

- Integrate real-time news APIs for live data updates.
- Implement advanced NLP techniques like topic modeling and keyword extraction.
- Improve sentiment accuracy using machine learning models.
- Add time-series analysis to track sentiment trends over time.
- Include interactive map-based visualizations.
- Deploy dashboard to Power BI Service for online sharing and automated refresh.
- Add predictive analytics for forecasting sentiment patterns.

🔮 Future Scope

This project can be expanded into a real-time media intelligence system by integrating automated data pipelines and advanced NLP models. With enhanced predictive capabilities and broader geographic coverage, it can support analysts, researchers, and decision-makers in understanding public sentiment trends more effectively.

📸 Dashboard Screenshot
<img width="1306" height="738" alt="News Analysis" src="https://github.com/user-attachments/assets/21841aef-f0aa-4191-864b-9648d6b25a3d" />
