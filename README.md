# Data Analysis & Visualization Capstone Project

## Overview
This project investigates the reliability of online movie ratings, with a specific focus on Fandango's ratings. It aims to determine whether Fandango's ratings are biased, potentially inflating movie scores. The analysis is based on the article ["Be Suspicious Of Online Movie Ratings, Especially Fandango’s"](http://fivethirtyeight.com/features/fandango-movies-ratings/) published by FiveThirtyEight.

## Dataset
Two primary datasets are used in this project:

1. **all_sites_scores.csv**: Contains ratings from Rotten Tomatoes, Metacritic, IMDb, and Fandango for films with at least 30 fan reviews on Fandango.
   - **Columns:**
     - `FILM`: The title of the film.
     - `RottenTomatoes`: Tomatometer score from Rotten Tomatoes.
     - `RottenTomatoes_User`: User score from Rotten Tomatoes.
     - `Metacritic`: Metascore from Metacritic.
     - `Metacritic_User`: User score from Metacritic.
     - `IMDB`: Rating from IMDb.
     - `Fandango_Stars`: Star rating displayed on Fandango.
     - `Fandango_Ratingvalue`: Actual rating value used by Fandango.
     - `Fandango_votes`: Number of votes the movie received on Fandango.
     - `Fandango_Difference`: Difference between displayed stars and actual rating value.

2. **fandango_scrape.csv**: Contains the star ratings, actual rating values, and vote counts from Fandango for a set of movies.

## Project Structure

1. **Data Exploration**:
   - Initial exploration of the datasets to understand the structure and content.
   - Summary statistics and visualizations to identify trends or outliers.

2. **Data Cleaning**:
   - Handling missing values and merging datasets for analysis.
   - Ensuring consistency in data formatting and types.

3. **Visualization**:
   - Creation of various plots to visualize rating distributions across platforms.
   - Comparison of Fandango's ratings with other platforms to identify discrepancies.

4. **Analysis**:
   - Statistical tests and analysis to assess potential biases in Fandango's ratings.
   - Investigating whether Fandango's ratings are systematically higher than those of other platforms.

5. **Conclusion**:
   - Summarizes the findings from the analysis.
   - Discusses potential implications and recommendations based on the results.

## How to Use
To run the analysis and visualize the data:
1. Ensure you have the necessary Python packages installed, such as pandas, matplotlib, seaborn, and numpy.
2. Open the Jupyter Notebook file `Data Analysis and Visualization Capstone Project.ipynb`.
3. Run the notebook cells sequentially to reproduce the analysis.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- The datasets are publicly available from [FiveThirtyEight's GitHub repository](https://github.com/fivethirtyeight/data).
- Inspiration for this project was drawn from the FiveThirtyEight article linked above.
