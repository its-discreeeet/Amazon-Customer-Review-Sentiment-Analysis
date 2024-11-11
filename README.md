# Amazon Customer Reviews Analysis Using Apache Spark

## Project Overview

This mini-project involves analyzing Amazon customer reviews for jewelry products using Apache Spark and Python on Google Colab. The primary goal is to perform sentiment analysis to understand customer feedback patterns.

---

## Problem Statement

**Objective**: Conduct Amazon Customer Sentiment Analysis using Spark and Python on Google Colab.

---

## Requirements

- **Spark**: 3.1.1
- **Hadoop**: 2.7
- **Primary Library**: PySpark
- **Target Platform**: Cloud systems (implemented on Google Colab)
- **Programming Language**: Python

---

## Dataset

- **Dataset Name**: Amazon Jewelry Reviews
- **Download Link**: [Amazon Jewelry Reviews Dataset on Kaggle](https://www.kaggle.com/datasets/loorsawalhi/amazon-jewelry-reviews)

---

## Steps to Run the Program

1. **Download the Dataset**: Download the Amazon Jewelry Reviews dataset from the link above and upload it to a location in your Google Drive.

2. **Set Up Spark on Google Colab**:
   - Install Java JVM and configure PySpark to set up the environment.

3. **Start a Spark Session**:
   - Initialize a Spark session to enable distributed data processing in Colab.

4. **Load the Dataset**:
   - Load the dataset into the notebook using the following command:
     ```python
     loaded_info = spark.read.csv('path_to_downloaded_dataset', sep='\t', inferSchema=True, header=True)
     ```
   - Replace `'path_to_downloaded_dataset'` with the actual path where the dataset is mounted in Google Drive.

5. **Analyze Columns as Needed**:
   - Explore and analyze the columns to gain insights into customer sentiment.

---

## Additional Notes

- Ensure Spark and Hadoop are correctly set up before proceeding with data analysis.
- Refer to PySpark documentation if any issues arise during setup or processing.

---

## License

This project is for educational purposes only.

---

## Acknowledgments

- Thanks to [Kaggle](https://www.kaggle.com/) for providing the dataset.
