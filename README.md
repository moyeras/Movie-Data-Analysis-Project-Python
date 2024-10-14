# Movie Data Analysis Project

This project focuses on analyzing a dataset containing information about movies, such as ratings, genres, directors, budgets, and more. The analysis is done using Python, leveraging popular data manipulation and visualization libraries.

## Project Overview

The goal of this project is to explore relationships within the dataset and gain insights into factors such as movie ratings, budgets, and gross earnings. The project uses various data visualization techniques to present these insights.

## Dataset

The dataset used in this project (`movies.csv`) contains the following columns:

- `name`: Movie title
- `rating`: Rating of the movie (e.g., PG-13, R)
- `genre`: Movie genre
- `year`: Year the movie was released
- `released`: Exact release date
- `score`: IMDb score
- `votes`: Number of IMDb votes
- `director`: Name of the director
- `writer`: Name of the writer(s)
- `star`: Lead actor/actress
- `country`: Country of origin
- `budget`: Budget of the movie
- `gross`: Gross earnings
- `company`: Production company
- `runtime`: Movie runtime in minutes

## Libraries Used

- **pandas**: For data manipulation and analysis
- **numpy**: For numerical operations
- **matplotlib**: For creating static, animated, and interactive visualizations
- **seaborn**: For data visualization based on matplotlib

## How to Run

1. Clone this repository.
    ```bash
    git clone https://github.com/moyeras/Movie_Data_Analysis_Python.git
    ```
   
2. Install the required Python libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```

3. Run the Jupyter notebook to see the data analysis in action:
    ```bash
    jupyter notebook MovieProject.ipynb
    ```

## Visualizations

The project includes various visualizations, such as:
- Scatter plots to show the relationship between budget and gross earnings.
- Bar charts to display the distribution of movie genres.
- Heatmaps to show correlations between different numerical features.

## Conclusion

This project provides a comprehensive analysis of the movie dataset and presents key insights about movie ratings, budgets, and earnings. You can extend this project by adding further analyses, such as exploring the influence of directors or actors on a movie’s success.
