# Netfix Movie Performance Analysis Over the Years

## Overview

This project analyzes movie performance trends over the years using Python. By exploring a dataset of movies, we aim to uncover insights into various aspects of the film industry, such as genre popularity, voting patterns, and release date distributions. This analysis can be valuable for understanding historical trends and potentially informing future predictions within the movie industry.

## Project Goals

* Analyze the distribution of movie release dates over time.
* Investigate the distribution of vote averages and identify popular movies.
* Explore the prevalence of different genres.
* Potentially identify trends in genre popularity over the years.
* Visualize key findings to communicate insights effectively.

## Data Source

The analysis is based on the `mymoviedb.csv` dataset (or specify your actual data source if different). This dataset contains information about movies, including:

* Release Date
* Vote Average
* Genre(s)
* (Mention other relevant columns you used)

## Libraries Used

* **Pandas:** For data manipulation and analysis.
* **NumPy:** For numerical operations. (Include if you used it)
* **Matplotlib:** For creating basic plots and visualizations.
* **Seaborn:** For creating more advanced and statistically informative visualizations.

## Setup and Installation

1.  **Clone the repository:**
    ```bash
    git clone [your-github-repository-url]
    cd [your-repository-name]
    ```

2.  **Install the required libraries:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
    (Include `numpy` if you used it)

3.  **Place the dataset:**
    Ensure the `mymoviedb.csv` file (or your data file) is located in the `data/` directory (or the path specified in your notebook/scripts).

## Usage

1.  **Navigate to the `notebooks/` directory:**
    ```bash
    cd notebooks/
    ```

2.  **Open and run the Jupyter Notebook:**
    ```bash
    jupyter notebook movie_performance_analysis.ipynb
    ```
    Follow the steps within the notebook to reproduce the analysis and visualizations.

   (If you have separate scripts, provide instructions on how to run them)

## Key Findings

Conclusion
Q1: What is the most frequent genre in the dataset?

Drama genre is the most frequent genre in our dataset and has appeared more than 14% of the times among 19 other genres.

Q2: What genres has highest votes?

We have 25.5% of our dataset with popular vote (6528 rows). Drama again gets the highest popularity among fans by being having more than   

Q3: What movie got the highest popularity? what's its genre?

Spider-Man: No Way Home has the highest popularity rate in our dataset and it has genres of Action, Adventure and Science Fiction.   

Q3: What movie got the lowest popularity? what's its genre?

'The United States, thread' has the highest lowest rate in our dataset and it has genres of music, drama, 'war', 'sci-fi' and hi
