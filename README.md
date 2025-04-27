
# 🎵 Spotify Data Analysis and Visualization Project

This project analyzes Spotify streaming data to uncover trends about top tracks, artists, genres, and musical features.  
It leverages AWS services for data transformation and visualization, following a cloud-native architecture.

---

## 📦 Dataset Source

- **Kaggle Dataset:** [Spotify Dataset 2023](https://www.kaggle.com/datasets/tonygordonjr/spotify-dataset-2023)
- **Data Includes:** Track metadata, artist information, popularity scores, musical attributes like tempo, danceability, and energy.

---

## 📚 Project Overview

- Ingested Spotify data into AWS S3.
- Applied ETL transformations using AWS Glue.
- Cataloged clean datasets via AWS Glue Crawler.
- Queried structured data using Amazon Athena.
- Built final dashboards and visualizations in Amazon QuickSight.
- Analyzed track features, top artists, popular genres, and yearly trends.

---

Flow:
- **S3 Staging** → **Glue ETL** → **S3 Data Warehouse** → **Glue Crawler** → **Athena Queries** → **QuickSight Dashboard**

---

## 🛠️ Tools and Technologies Used

**AWS S3**, **AWS Glue**, **AWS Glue Crawler**, **Amazon Athena**, **Amazon QuickSight**, **Python**, **Pandas**, **Matplotlib**, **Seaborn**

---

## 🔍 Key Insights

- 🎤 Top streamed artists across years and genres.
- 🎵 Genre-wise streaming patterns and seasonal popularity.
- 🔥 Popular track attributes: high danceability, medium tempo.
- 📈 Yearly growth in streaming activity and music diversity.

---

## 🖼 Example Visualizations

- **Top Artists Bar Charts**
- **Genre Distribution Pie Charts**
- **Correlation Matrix of Song Features**
- **Year-over-Year Popularity Trends**

---

## 🚀 Outcomes

- Built an end-to-end cloud-based analytics pipeline.
- Gained actionable insights into Spotify listening behaviors.
- Mastered cloud data ingestion, transformation, and visualization at scale.

---

## 📌 Future Enhancements

- Add predictive analysis: Will a new track become a hit?
- Build a recommendation engine based on audio features.
- Deploy real-time dashboards refreshing directly from S3 updates.

---

## 📑 Notes

- This project is educational and analytical, based on publicly available data.
- AWS Free Tier services were primarily used to control project costs.

---
