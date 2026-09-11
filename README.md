# tmdb-movie-data-analysis
An exploratory data analysis (EDA) of the TMDb (The Movie Database) dataset using Python and Pandas.
# TMDb Movie Data Analysis

This repository contains a Python-based exploratory data analysis (EDA) of movie metadata sourced from **The Movie Database (TMDb)**. The project inspects financial metrics (budget and revenue, both raw and inflation-adjusted), ratings, genre distributions, and key metrics for top-performing films.

## Dataset Overview

The primary dataset used is `tmdb_movies.csv`, which contains information on **3,854 movies** released between 1960 and 2015.

Key attributes included in the dataset:
* `id` / `imdb_id`: Unique identifiers for TMDb and IMDb.
* `original_title`: Title of the movie.
* `budget` / `budget_adj`: Production budget (raw vs. adjusted for inflation).
* `revenue` / `revenue_adj`: Box office revenue (raw vs. adjusted for inflation).
* `popularity`: TMDb popularity score.
* `vote_count` / `vote_average`: User ratings and voting counts.
* `runtime`: Movie duration in minutes.
* `genres`: Associated film genres.
* `cast` / `director`: Key cast members and director(s).
* `release_year`: Year of release.

## Key Insights & Summary Statistics

* **Total Movies Analyzed:** 3,854
* **Average Budget:** ~$37.2 Million (Adjusted Mean: ~$44.2M)
* **Average Revenue:** ~$107.7 Million (Adjusted Mean: ~$137.0M)
* **Highest-Grossing Movies in Dataset (Raw Revenue):**
  1. *Avatar* — $2,781,505,847
  2. *Star Wars: The Force Awakens* — $2,068,178,225
  3. *Titanic* — $1,845,034,188
  4. *The Avengers* — $1,568,080,742
  5. *Jurassic World* — $1,513,528,810

## Requirements & Installation

To run the analysis notebook locally:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/tmdb-movie-data-analysis.git](https://github.com/your-username/tmdb-movie-data-analysis.git)
   cd tmdb-movie-data-analysis
