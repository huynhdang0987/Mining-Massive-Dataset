# Mining Massive Data Sets – Final Project

This repository contains the implementation of four advanced data mining tasks completed as part of the *Mining Massive Data Sets* course at Ton Duc Thang University. The tasks demonstrate practical applications of big data techniques using PySpark and custom algorithms.

## Team Members
- **Huynh Dang Khoa** – 522h0104@student.tdtu.edu.vn  
- **Chau Bao Nhan** – 522h0093@student.tdtu.edu.vn  
- **Nguyen Le Hai Long** – 522h0125@student.tdtu.edu.vn  
- **Instructor:** MSc. Nguyen Thanh An – nguyenthanhan@tdtu.edu.vn

## Overview of Tasks

### Task 1: Hierarchical Clustering in Non-Euclidean Spaces
- Implemented custom agglomerative clustering using Jaccard distance and 4-shingle tokenization.
- Clusters are evaluated using average intra-cluster distances and clustroids.
- Visualized results using bar charts.

### Task 2: Linear Regression for Gold Price Prediction
- Time series forecasting of daily gold prices in Vietnam using 10-day lag features.
- Implemented with PySpark’s MLlib linear regression model.
- Evaluated using RMSE on both training and test sets.
- Output includes line plots comparing actual vs predicted prices.

### Task 3: CUR Matrix Decomposition for Dimensionality Reduction
- Reduced feature space from 10D to 5D using a custom CUR algorithm.
- Selected rows/columns using probabilistic norms.
- Projected feature vectors to a low-dimensional space and retrained regression models.
- Compared RMSE before and after dimensionality reduction.

### Task 4: PageRank – The Google Algorithm
- Crawled the `it.tdtu.edu.vn` domain and built a directed graph of internal links.
- Cleaned and preprocessed URLs.
- Implemented the PageRank algorithm in PySpark using power iteration.
- Ranked web pages based on importance scores.

## Technologies Used
- **Language:** Python  
- **Framework:** Apache Spark (PySpark)  
- **Libraries:** NumPy, Matplotlib, scikit-learn (CUR), pandas  
- **Tools:** Jupyter Notebook, Git, PDF Report (IEEE format)

## Results & Observations
- Jaccard-based clustering grouped similar strings with good compactness.
- Linear regression captured gold price trends with acceptable RMSE (≈ 0.4–0.5).
- CUR dimensionality reduction slightly increased RMSE but reduced complexity.
- PageRank scores correctly highlighted key university pages.

## Acknowledgments
We would like to thank **MSc. Nguyen Thanh An** for his continuous support and guidance throughout this project.

## License
This project is developed for educational purposes only as part of the course *Mining Massive Data Sets*.

