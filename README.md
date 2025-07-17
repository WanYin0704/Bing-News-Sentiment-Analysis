# Malaysia News Sentiment Analytics

## Overview
This project leverages **Microsoft Fabric** to automate the ingestion, processing, sentiment analysis, and reporting of Malaysia news data. Using **Bing News Search API v7**, the solution retrieves up to **100 news articles daily**, based on a dynamic search term (defaulting to trending news), targeting the **English-Malaysia (en-MY)** market.

The end-to-end data engineering project is orchestrated within Microsoft Fabric, providing centralized data management, processing, modeling, and visualization.

## Architecture Overview
1. **Data Collection**: Bing News Search API v7 via scheduled pipeline.

2. **Data Storage**: Microsoft Fabric Lakehouse (Delta format)..

3. **Data Processing**: PySpark Notebooks (process_bing_news, transform_bing_news).

4. **Semantic Modeling**: Lakehouse semantic model and SQL analytics endpoint.

5. **Reporting**: Power BI Dashboard.

6. **Monitoring**: Real-time negative sentiment detection via Data Activator.

## Dashboard Overview


