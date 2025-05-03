
# Netflix Data Cleaning, Analysis, and Visualization

This project involves cleaning, exploring, and visualizing the Netflix dataset using Python. It aims to provide insights into the content available on Netflix, including trends in movie and TV show releases, genre distribution, and more.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Key Steps](#key-steps)
- [Visualizations](#visualizations)
- [Insights](#insights)
- [How to Run](#how-to-run)
- [License](#license)

## Project Overview
This notebook performs the following:
- Cleans Netflix titles dataset (handling nulls, duplicates, formatting).
- Analyzes data distribution across genres, years, countries, and content types.
- Visualizes the data using informative plots to uncover viewing and production trends.

## Dataset
- **Source**: [Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Attributes**: Show ID, Type, Title, Director, Cast, Country, Date Added, Release Year, Rating, Duration, Genre, Description

## Technologies Used
- **Language**: Python
- **Libraries**: 
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - plotly (if used)
  - datetime

## Key Steps
1. **Data Loading**: Import CSV into DataFrame.
2. **Data Cleaning**:
   - Remove duplicates and nulls.
   - Standardize column formats.
3. **Exploratory Data Analysis (EDA)**:
   - Count of movies vs. TV shows.
   - Most common genres.
   - Release trends over years.
   - Country-wise content production.
   - Top-rated content.
4. **Visualization**:
   - Bar charts, pie charts, and heatmaps to represent trends visually.

## Visualizations
- Number of movies and TV shows
- Top countries producing content
- Year-wise trend of content release
- Most frequent genres
- Rating-wise distribution

## Insights
- Movies dominate the platform compared to TV shows.
- The US, India, and the UK contribute the most content.
- Significant growth in Netflix’s content since 2015.
- TV Shows tend to be added more in recent years.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/netflix-data-analysis.git
   cd netflix-data-analysis
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook netflix-data-cleaning-analysis-and-visualization.ipynb
   ```

## License
This project is licensed under the [MIT License](LICENSE).
