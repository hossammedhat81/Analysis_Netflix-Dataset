# Netflix Dataset Analysis

## Overview
This project explores the Netflix dataset, containing metadata for over 7,700 movies and TV shows, to uncover insights about content distribution, genres, ratings, and more. Using Python and pandas, the analysis includes data cleaning, exploratory data analysis (EDA), and visualizations to reveal trends in Netflix's content catalog.

## Objectives
- Perform comprehensive EDA to understand the dataset's structure and content.
- Identify patterns in genres, release dates, ratings, and regional content distribution.
- Visualize key insights, such as the top 10 most popular genres on Netflix.
- Provide a foundation for further advanced analyses (e.g., NLP, recommendation systems).

## Dataset
The dataset (`Netflix Dataset.csv`) includes 7,789 rows and 11 columns:
- **Columns**: `Show_Id`, `Category`, `Title`, `Director`, `Cast`, `Country`, `Release_Date`, `Rating`, `Duration`, `Type`, `Description`.
- Source: Publicly available dataset (assumed for this project).


## Prerequisites
- Python libraries: pandas, matplotlib
- Jupyter Notebook or JupyterLab for running the .ipynb file
- Dataset: Place Netflix Dataset.csv in the project directory

## Usage
- Open practising_Netflix.ipynb in Jupyter Notebook or JupyterLab.
- Ensure the dataset (Netflix Dataset.csv) is in the same directory.
- Run the notebook cells sequentially to reproduce the analysis and visualizations.
- Explore the code comments and markdown for detailed explanations of each step.

## Analysis Highlights
- Data Cleaning: Handled missing values and duplicates to ensure data quality.
- EDA: Examined dataset structure (shape, size, columns), previewed data with head() and tail(), and checked for nulls/unique values.
- Visualizations: Created a bar plot of the top 10 most popular genres, highlighting trends in content types (e.g., dominance of dramas and international content).

## Key Findings
- Genre Popularity: Dramas and International Movies are among the most common genres, reflecting Netflix's focus on diverse, narrative-driven content.
- Data Quality: Significant missing values in Director and Cast columns, requiring careful handling for robust analysis.
- Content Distribution: Movies dominate over TV shows, with a wide range of durations and ratings catering to varied audiences.

## Future Improvements
- Implement NLP to analyze Description for sentiment or thematic clustering.
- Build a content-based recommendation system using Type and Description.
- Perform time-series analysis on Release_Date to study content release trends.

## Contributing
Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request with your improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Author
Hossam Medhat Shokry  
Connect with me on LinkedIn: [(https://www.linkedin.com/in/hossammed7at/)]  
GitHub: [https://github.com/hossammedhat81]
