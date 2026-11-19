# Netflix Data Analysis

Cleaning and exploring 8,800+ Netflix movies and TV shows with Python to answer four questions about the catalogue.

👉 **[Open the notebook](netflix_analysis.ipynb)** to see the code and charts.

## Questions and findings
1. **Movies or TV shows?** Netflix has about 6,100 movies and 2,700 TV shows, so roughly 70% of the catalogue is movies.
2. **Titles added per year:** additions peaked in 2019. The data stops in September 2021, so 2021 is incomplete.
3. **Top countries:** the United States produces the most content, followed by India and the United Kingdom.
4. **Movie length:** a typical Netflix movie is about 100 minutes long.

## What I did
- Explored the data and found the problems: missing directors, cast and countries, dates stored as text, and 3 durations typed into the rating column
- Filled missing text values with "Unknown"
- Removed 17 broken rows
- Extracted the year from the date text and the number from the duration text
- Answered each question with Pandas and a chart

## Tools
Python · Pandas · Matplotlib · JupyterLab

## Data
[Netflix Movies and TV Shows](https://www.kaggle.com/shivamb/netflix-shows) on Kaggle.
To run the notebook, download the dataset and place `archive.zip` in the same folder.

## Author
Hassan Yerima Ahmad · [GitHub](https://github.com/hassanyerima)
