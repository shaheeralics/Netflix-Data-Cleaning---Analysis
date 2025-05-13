# Netflix Data Cleaning & Analysis

A comprehensive exploratory data analysis project examining Netflix's content library to uncover trends, patterns, and insights that could inform content strategy and viewer preferences.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Objectives](#objectives)
4. [Methodology](#methodology)
5. [Key Findings](#key-findings)
6. [Technologies Used](#technologies-used)
7. [Project Structure](#project-structure)
8. [Setup and Installation](#setup-and-installation)
9. [Usage](#usage)
10. [Visualizations](#visualizations)
11. [Future Work](#future-work)
12. [Contributor](#contributor)

## Project Overview

This project performs an in-depth exploratory data analysis (EDA) on Netflix's content library. The analysis examines various aspects of Netflix's content strategy, including content type distribution over time, country-wise distribution, genre preferences, content duration trends, and more. By understanding these patterns, we can gain valuable insights into Netflix's content acquisition and creation strategy, as well as viewer preferences across different markets.

## Dataset Description

The analysis is based on a comprehensive dataset containing information about movies and TV shows available on Netflix as of 2019. The dataset includes attributes such as:

| Column        | Description                                           |
|---------------|-------------------------------------------------------|
| show_id       | Unique identifier for each title                      |
| type          | Indicates whether the title is a movie or a TV show   |
| title         | Name of the movie or TV show                          |
| director      | Director of the movie or TV show                      |
| cast          | Actors featured in the title                          |
| country       | Country where the title was produced                  |
| date_added    | Date when the title was added to Netflix              |
| release_year  | Year of the title's original release                  |
| rating        | Content rating (e.g., TV-MA, PG-13)                   |
| duration      | Runtime (for movies) or number of seasons (for shows) |
| categories    | Genres or categories the title belongs to             |
| description   | Brief synopsis of the title                           |

## Objectives

The project seeks to answer the following key questions:

1. What is the distribution of content types (movies vs. TV shows) over the years?
2. Which countries produce the most content available on Netflix, and how has this changed over time?
3. What are the most common genres for movies and TV shows, and how do they differ?
4. How has the average duration of movies and TV shows changed over the years?
5. Which directors or actors have the most titles in the dataset, and are there any trends in their content?
6. Are there relationships between the rating, duration, and genre of Netflix titles?
7. How does the distribution of release years differ between movies and TV shows?
8. Can we identify any seasonal or monthly patterns in the release of new content on Netflix?
9. Are there notable differences in the distribution of titles among "Documentaries," "Dramas," and "Comedies"?
10. Can we find significant correlations between variables, and how might these insights be useful for content recommendation?

## Methodology

The analysis follows a systematic approach:

1. **Data Acquisition and Loading**: Importing libraries and loading the dataset
2. **Data Exploration**: Examining data types, missing values, unique values, and overall structure
3. **Data Preprocessing**:
   - Renaming columns for clarity
   - Converting data types (e.g., converting date_added to datetime format)
   - Handling missing values appropriately for each column
   - Creating separate dataframes for movies and TV shows for specific analyses
   - Extracting features from existing columns (like separating genre lists)
4. **Exploratory Data Analysis**: Analyzing and visualizing patterns related to our key questions
5. **Drawing Conclusions**: Summarizing insights and their implications

## Key Findings

- **Content Type Distribution**: Movies significantly outnumber TV shows in the Netflix library, though both categories have shown growth over time.
- **Country Contributions**: The United States, India, and the United Kingdom are the top content producers for Netflix.
- **Genre Preferences**: International Movies, Dramas, and Comedies are the most common genres on the platform.
- **Content Duration Trends**: The average movie duration has fluctuated over the years, with a slight decrease in recent years.
- **Release Patterns**: There appears to be a seasonal pattern in content additions, with certain months showing higher volumes of new content.
- **Rating Correlations**: Certain ratings are associated with longer or shorter durations, depending on the content type.

## Technologies Used

- **Python** - Primary programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib & Seaborn** - Data visualization
- **Plotly Express** - Interactive visualizations
- **Jupyter Notebook** - Development environment

## Project Structure

The project is contained in a Jupyter Notebook with the following main sections:

1. Introduction
2. Acquiring & Loading Data
3. Data Preprocessing
4. Data Analysis (answering the 10 key questions)
5. Conclusion

## Setup and Installation

1. Clone this repository
2. Ensure you have Python installed (preferably version 3.7+)
3. Install required packages:
   ```
   pip install pandas numpy matplotlib seaborn plotly jupyter ipywidgets skimpy
   ```
4. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```
5. Open the "Exploratory Data Analysis on Netflix Dataset.ipynb" file

## Usage

To use this project:

1. Run the Jupyter Notebook cells sequentially to follow the analysis process
2. Modify the code to explore additional questions or adapt the analysis to your needs
3. Use the interactive visualizations to explore the data from different perspectives

## Visualizations

The project includes various visualizations:

- Bar charts comparing movies vs. TV shows over time
- Geographic distribution of content production
- Trend analysis of content duration over the years
- Genre distribution and popularity analysis
- Monthly and yearly content addition patterns

## Future Work

Potential extensions to this analysis could include:

- Sentiment analysis of show descriptions to understand content themes
- Network analysis of actor and director collaborations
- Incorporating viewer rating data to correlate content features with popularity
- Building a recommendation system based on content features
- Expanding the dataset to include more recent Netflix additions

## Contributor

- **Shaheer Ali** - Data Scientist / ML Engineer
  - [GitHub](https://github.com/shaheeralics)
  - [LinkedIn](https://www.linkedin.com/in/shaheer-ali-2761aa303/)
  - [Portfolio](https://www.sak.kesug.com)
