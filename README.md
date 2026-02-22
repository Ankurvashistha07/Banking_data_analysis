# Banking_data_analysis
Exploratory Data Analysis (EDA) of the Bank Marketing dataset using Python, Pandas, Seaborn, and Matplotlib to visualize data patterns and understand factors affecting term deposit subscription.

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Bank Marketing dataset using Python. The goal is to understand customer data, identify important patterns, and explore factors that influence whether a customer subscribes to a term deposit offered by a bank.

EDA is a critical first step in any data science workflow because it helps uncover data structure, detect anomalies, and prepare the dataset for future machine learning modeling.

## Project Objectives

### The main objectives of this project are:

• Understand the dataset structure and features
• Check for missing values and verify data types
• Analyze the distribution of the target variable
• Explore relationships between numerical variables
• Identify trends, patterns, and correlations in the data
• Visualize insights using professional charts and graphs

## Dataset Description

The dataset contains information related to direct marketing campaigns conducted by a bank. Each row represents a customer, and each column contains attributes describing the customer’s profile, financial status, and interaction history.

🔹 Key Types of Features

• Customer Demographics

  • Age
  • Job
  • Marital status
  • Education

• Financial Information
  • Balance
  • Housing loan status
  • Personal loan status
  
• Campaign Information

  • Contact communication type
  • Duration of last contact
  • Number of contacts performed
  • Previous campaign outcomes

• Target Variable

  • y → Indicates whether the customer subscribed to a term deposit:
  • Yes = Subscribed
  • No = Did not subscribe

## Technologies & Tools Used

This project uses the following tools and libraries:

• Python – Programming language
• Pandas – Data manipulation and analysis
• NumPy – Numerical operations
• Matplotlib – Data visualization
• Seaborn – Statistical visualization
• Jupyter Notebook – Interactive analysis environment

## Analysis Performed

1️⃣ Data Inspection

• Loaded the dataset
• Viewed sample rows
• Checked column names and data types

2️⃣ Data Cleaning

• Identified missing values
• Verified data consistency

3️⃣ Target Variable Analysis

• Plotted distribution of the target variable
• Observed class imbalance between subscription outcomes

4️⃣ Numerical Feature Analysis

• Selected numerical columns
• Generated correlation matrix
• Visualized relationships using heatmaps

5️⃣ Data Visualization

• Created count plots for categorical data
• Generated histograms for numeric distributions
• Built heatmaps to identify feature relationships

## Key Insights

Some insights discovered during analysis include:

• Most customers did not subscribe to the term deposit, indicating class imbalance.
• Certain numerical features show weak correlations, suggesting independent behavior.
• Campaign-related features (such as contact duration) appear to strongly influence outcomes.

## How to Run This Project

### Follow these steps to run the analysis locally:

Step 1: Clone the Repository

git clone <your-repo-link>

Step 2: Navigate to the Project Folder

cd your-repo-name

Step 3: Install Required Libraries

pip install pandas numpy matplotlib seaborn

Step 4: Run the Notebook

Open the Jupyter Notebook and execute the cells step-by-step.

## Project Structure
├── Bank_Marketing_Inspection_test.ipynb
├── README.md
└── dataset file

## Skills Used

Python | Pandas | NumPy | Matplotlib | Seaborn | Data Visualization | EDA

## Learning Outcomes

Through this project, the following skills were developed:

• Data preprocessing and inspection
• Exploratory Data Analysis techniques
• Data visualization best practices
• Understanding of correlation and feature relationships
• Practical experience with Python data science libraries

## Future Improvements

Possible next steps for this project include:

• Handling categorical encoding
• Feature engineering
• Building machine learning classification models
• Evaluating model performance
• Deploying predictive models
