# CapstoneProject_MovieProfitMargin

Overview
------
Using a dataset of movies an attempt was made to build a model to predict box office success based on the people involved in the production of the film (actors, director, screenwriter, editor, and production company), specifics of the story (genre, duration, keywords), and user ratings.  The ultimate results showed that these features are unfortunately not good predictors for box office success.

Data
------
[Kaggle - The Movies Dataset] (https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset) - (cast, crew, genres, user ratings) 

[The Movie DB] (https://www.themoviedb.org/) - (revenue, budget)

[Box Office Mojo] (https://www.boxofficemojo.com/) - (Domestic Box Office sales) 


Regression Models Attempted
------ 
- Epsilon-Support Vector Regression (SVR)
- Stochastic Gradient Descent Regression (SGD)
- K Nearest Neighbors Regressor (kNN)
- Random Forest Regressor 
- Ada Boost Regressor 
- Bayesian Ridge Regressor
- Linear Regression

Bayesian Optimized Models
------
- Random Forest

Model Performance
------
**Output Feature:** 
Box Cox Logrithmic transformation of Box Office Profit Ratio (Box Office Revenue/ Budget)
Roughly normal distribution
- mean: 0
- std dev: 2.2

**Best Performance**
*Data Set*	*R^2*	*MSE*	*MAE*
Training	0.88	0.33	0.43
Test		0.16	2.76	1.19

Conclusion
-----
Ultimately, the gathered data cannot be used to accurately model Box Office Success.  There are simply not enough usable parameters listed in the dataset to model from, and the ones this capstone engineered and tested did not ultimately perform with a sufficient degree of success.  