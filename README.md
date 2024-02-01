# Type Detection on Amazon: Movie or TV Series?

This project focuses on developing a machine learning model capable of automatically classifying products listed on Amazon as either movies or TV series. Leveraging a dataset of Amazon product titles and descriptions, natural language processing techniques and machine learning algorithms are employed to predict the type of content each product represents. The automation of this classification task enhances the efficiency of content categorization, making it easier for users to find and purchase their desired movies and TV series on the platform.

## Getting Started

### Prerequisites

Ensure you have the following libraries installed:

- pandas==1.3.3
- seaborn==0.11.2
- matplotlib==3.4.3
- numpy==1.21.2
- scikit-learn==0.24.2

You can install them using:

```bash
pip install -r requirements.txt
```

## Notebooks Overview

### 1. Import Libraries

This section includes the necessary Python libraries for the project.

### 2. Uploading CSV

Demonstrates the process of uploading a CSV file, storing it in a DataFrame, and displaying the first 5 entries.

### 3. Renaming and Dropping

Covers the steps of renaming a column and dropping another column from the DataFrame.

### 4. Features Types

Displays the data types of the features in the DataFrame.

### 5. Missing Data Analysis

Calculates and analyzes missing data in the DataFrame.

### 6. Duplicated Data Analysis

Analyzes duplicated data in the DataFrame.

### 7. Missing Value Imputation

Addresses missing data by creating a new DataFrame and filling missing values with a specified placeholder.

### 8. Initial Data Preview

Displays the top rows of the DataFrame after removing high-missing-value columns.

### 9-14. Visualizations

Various visualizations are presented, including genre distribution, content type percentage, release year intervals, and top movies and TV shows.

### 15-16. Correlation Heatmap and Bar Chart

Visualizes the correlation between content type, release year, and duration using a heatmap and bar chart.

### 17-18. Text Data Preprocessing

Demonstrates text data preprocessing functions and vectorization using CountVectorizer.

### 19-22. Model Training and Testing

Applies three different classifiers (SVM, Random Forest, MLP) to the dataset and evaluates their accuracy on both testing and training sets.

## Conclusion

This project provides insights into the classification of products on Amazon and serves as a foundation for further improvements and enhancements in content categorization.