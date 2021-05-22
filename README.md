# Machine Learning Exoplanet Exploration



### Background
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

The project goal is to train two machine learning (ML) models that are intended to classify candidate exoplanets.


### Models
### Two Techniques
Logistic Regression (LR)
Random Forest Classifier (RFC)



### Model Design Approach
Build a base model using the original dataset and all its 40 features.
Use the base model to evaluate feature importance, and filter the data to include relevant features only.
Build a second model (select features model) using the filtered data.
Tune the model parameters using GridSearchCV.
Build the final model using the tuned parameters.


### Model Comparison
The RFC model was the more accurate of the two by a small margin.


![image](https://user-images.githubusercontent.com/68763904/119240476-98a2c700-bb04-11eb-916f-ed95d6fef8a6.png)


### Conclusions
With relatively high accuracy, the Random Forest Classifier Model  is  a reasonable predictor of exoplanet candidacy. 
Iniatially the approach of using Random Forest Classifier, Logistic Regression, K Nearest Neighbors and Support Vector Machine were planned to apply during the work on the challenge.  
