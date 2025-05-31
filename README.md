# 📱 Google Play Store Data Preprocessing

This project focuses on preprocessing a dataset of applications from the Google Play Store. The dataset includes a variety of metadata such as user ratings, install counts, prices, content types, and technical specifications. The preprocessing pipeline aims to clean, format, and prepare the data for accurate analysis or modeling tasks.

---

## 📄 Dataset Description

Each row in the dataset represents a single app and includes the following fields:

| Column           | Description |
|------------------|-------------|
| **App** | Name of the application |
| **Category** | Category the app belongs to |
| **Rating** | Overall user rating of the app |
| **Reviews** | Number of user reviews |
| **Size** | Size of the app (e.g., in MB, KB, or ‘Varies with device’) |
| **Installs** | Total number of installs/downloads |
| **Type** | Indicates if the app is *Free* or *Paid* |
| **Price** | Price of the app in USD |
| **Content Rating** | Target age group (e.g., Everyone, Teen, Adults) |
| **Genres** | One or more genres describing the app |
| **Last Updated** | Date of the last update |
| **Current Version** | Version number as text |
| **Android Version** | Minimum required Android version |

---

## 🔧 Objectives

The preprocessing tasks performed in this project include:

- ✅ Handling inconsistent and missing data
- ✅ Converting categorical data into analyzable formats
- ✅ Parsing and converting string-based numbers (e.g., '1M+' installs)
- ✅ Standardizing column formats (dates, prices, versions)
- ✅ Cleaning size fields (e.g., converting 'M', 'K', or 'Varies with device')
- ✅ Removing duplicates and irrelevant records

---

## 📁 Files Included

- `GooglePlayStore.csv`: The original dataset (attached in the repository)
- `Data preprocessing 1.py`: Python code that executes all preprocessing steps

---

## 🧠 Skills Demonstrated

- Pandas data manipulation  
- Data type normalization  
- Regex for pattern extraction  
- Handling missing values  
- Feature engineering

---

## 🚀 Outcome

The cleaned and structured dataset is ready for exploratory data analysis (EDA), visualization, and machine learning tasks such as app popularity prediction, pricing strategy, or user segmentation.

---

## 📬 Contact

For any questions or collaboration ideas, feel free to reach out via GitHub.

