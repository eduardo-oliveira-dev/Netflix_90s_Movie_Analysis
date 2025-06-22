# Netflix 90s Movie Exploratory Data Analysis

This project performs exploratory data analysis (EDA) on a Netflix dataset to specifically investigate movies released in the 1990s. The goal is to understand trends and characteristics of films from this nostalgic decade available on the platform.

## Dataset

The dataset used in this project is `netflix_data.csv`, provided by DataCamp. It contains information about movies and TV shows on Netflix, including titles, directors, release years, durations, and genres.

## Analysis Performed

* Data loading and initial inspection using Pandas.
* Filtering the dataset to include only movies.
* Further filtering to focus on movies released between 1990 and 1999 (inclusive).
* Visualization of movie durations from the 1990s using a histogram to identify common movie lengths.
* Identification of the most frequent movie duration in the 90s.
* Counting the number of short action movies (duration < 90 minutes) released in the 1990s.

## Key Findings

* The most frequent movie duration for films released in the 1990s and available on Netflix was **94 minutes**.
* There were **[Insert `short_movie_count` value here]** action movies from the 1990s with a duration of less than 90 minutes in the dataset.
* [Add other relevant insights you gained from the histogram or other explorations]

## How to Run

1.  Clone this repository:
    ```bash
    git clone https://github.com/eduardo-oliveira-dev/Netflix_90s_Movie_Analysis.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd Netflix_90s_Movie_Analysis
    ```
3.  Ensure you have Python, Pandas, and Matplotlib installed. You can install them via pip:
    ```bash
    pip install pandas matplotlib jupyter
    ```
4.  Open the Jupyter Notebook:
    ```bash
    jupyter notebook notebook.ipynb
    ```
    This will open the notebook in your web browser, and you can run the cells to reproduce the analysis.

## Technologies Used

* Python
* Pandas
* Matplotlib

## Acknowledgements

This project was developed as part of the "Data Analyst in Python" career track on DataCamp.