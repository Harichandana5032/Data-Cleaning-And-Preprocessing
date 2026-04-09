#  Medical Appointment No Shows – Data Cleaning Task

##  Overview

This task focuses on cleaning and preparing the *Medical Appointment No Shows* dataset using Excel Online. The primary objective was to transform raw, inconsistent data into a clean, structured, and analysis-ready format. This process is essential for ensuring accurate insights and effective decision-making in any data analysis workflow.

## 🧾 Data Cleaning Process

The dataset initially contained multiple issues, including inconsistent text formatting, unstructured datetime values, and hidden or missing data. To maintain data integrity, the workflow began by separating the dataset into two sheets: **raw_data**, which preserved the original dataset, and **cleaned_data**, where all transformations were applied. Column names were standardized by converting them to lowercase, removing special characters, and replacing spaces with underscores to ensure consistency and compatibility with analytical tools.

Text fields were cleaned using Excel functions such as `TRIM`, `CLEAN`, and `PROPER` to eliminate extra spaces, remove hidden characters, and standardize capitalization. A key transformation involved converting ISO 8601 datetime values (e.g., `2016-04-29T18:38:08Z`) into Excel-recognizable date formats using string manipulation and formatting techniques. This allowed proper handling of date and time data for further analysis.

##  Data Transformation & Feature Engineering

Missing and inconsistent values were identified using filtering techniques and handled appropriately based on context, either by replacement or removal. A new feature called **waiting_days** was created to calculate the difference between the scheduled date and the appointment date. Conditional logic was applied to ensure that negative values were replaced with zero and decimal values were rounded to whole numbers, improving interpretability.

Additional improvements included removing duplicate records, validating numerical ranges (such as age), and standardizing categorical variables like gender and binary indicators. These steps ensured that the dataset became consistent and reliable.

##  Final Outcome

The final cleaned dataset is well-structured, free from inconsistencies, and ready for analysis. It enables further exploration such as identifying patterns in patient no-shows, analyzing the impact of waiting time, and generating insights through visualization tools.

##  Key Learnings

This ptask demonstrates practical skills in data cleaning, preprocessing, and feature engineering using Excel. It highlights the importance of transforming raw data into a usable format and showcases problem-solving abilities in handling real-world datasets.

##  Tools Used

* Microsoft Excel Online

## Author

**Hari chandana Uggu**
