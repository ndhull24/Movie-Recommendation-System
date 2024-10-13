# Movie-Recommendation-System

This project demonstrates how to build a Movie Recommendation System using Python and various data analysis libraries. The system computes correlations between user ratings for movies to generate movie recommendations.

Files
Movie Recommendations Systems.ipynb: The main Jupyter Notebook containing the code, explanations, and visualizations for the movie recommendation system.
Project Overview
The recommendation system analyzes user ratings for movies and finds correlations to recommend movies that a user may like. Key components include:

Data Preprocessing: Cleaning and preparing the data for analysis.
Calculating Correlations: Using Pearson correlation to find movies similar to the one a user has rated.
Generating Recommendations: Recommending top-rated movies with sufficient user ratings.
Libraries Used
Pandas: For data manipulation and analysis.
NumPy: For numerical computations.
Jupyter Notebook: To run the code interactively.
Usage
Setup:

Make sure Python and the required libraries are installed. You can install the necessary packages using:
bash
Copy code
pip install pandas numpy
Run the Notebook:

Open the notebook using Jupyter:
bash
Copy code
jupyter notebook "Movie Recommendations Systems.ipynb"
Execute the cells step-by-step to generate movie recommendations.
Saving Recommendations:

After generating recommendations, the results are saved to a CSV file using:
python
Copy code
ratings.to_csv('MovieRecommendations.csv', encoding='utf-8', index=False)
Expected Output
A CSV file named MovieRecommendations.csv containing personalized movie recommendations for users based on their ratings.
Error Handling
Warning: Degrees of freedom <= 0 for slice: Ensure there are enough data points for calculating correlations.
AttributeError: 'DataFrame' object has no attribute 'to_cv': Use to_csv() to save the DataFrame.
Contributing
Feel free to submit issues or pull requests for improvements.
