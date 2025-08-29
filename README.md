
🎼🎶Spotify & YouTube Music Data Cleaning Project

⭐Project Overview
This project focuses on cleaning a raw, merged dataset containing track information from both Spotify and YouTube Music. The dataset suffered from numerous data quality issues, including merged columns, inconsistent formatting, missing values, and invalid entries. This process transformed the raw data into a structured, analysis-ready dataset.

🔍Objectives
The primary objective was to perform a comprehensive data cleaning operation to ensure the dataset is accurate, consistent, and reliable for downstream analysis, visualization, or machine learning tasks. Specific goals included:
-Identifying and resolving missing and invalid data.
-Deconstructing merged columns into their original, logical components.
-Standardizing formats and data types across all columns.
-Removing duplicates and irrelevant information.

⚙️Tools Used
Power BI Desktop
Power Query Editor for all data cleaning operations
No external tools, scripts, or programming languages were used

📁 Dataset
Source:[Google Drive](https://drive.google.com/file/d/1qanyuwEzkwEJ73vDJHk4ZlWE0JUG7udb/view)
Format: CSV
Contents: Artist info, track titles, albums, Spotify metrics (e.g., danceability, energy), YouTube metrics (e.g., views, likes)

🧹 Key Cleaning Tasks
Step	                Description
1. Missing Values	Replaced or removed missing/null values in numerical fields
2. Merged Columns	Split Spotify_Info and Youtube_Info using delimiters and cleaned the outputs
3. Naming Consistency	Renamed columns using snake_case for uniformity
4. Irrelevant Columns	Removed columns with random or unusable data
5. Data Types	        Converted text-based numeric fields to proper number format
6. Invalid Entries	Replaced "invalid_data" and cleaned up inconsistent entries
7. Duplicates	        Identified and removed duplicate records
8. Reordering	        Reorganized columns for logical flow and readability

📊 Final Output
Cleaned dataset ready for use in Power BI reports and dashboards
Well-structured column naming and ordering
Reliable metrics for streaming data analysis
