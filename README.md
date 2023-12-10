
# AgriPredictor
It is a Machine Learning predictive model for predicting the best crop to yeild under given atmoshperic conditions like rain_percentage, humidity, temperature and also based on amount of nitrogen, phosphourous, potassium, ph of soil, temperature & humidity of atmosphere and percentage of rainfall.
It is a supervised learning model. First I have trained the model using the past data with all mentioned feature and label for the name of crop that previously yeild best under the given conditions by considering 5 cross validations.
I have used the random forest classifier to predict the best crop for new input.
Once the model are trained, they can predict which crops are likely to thrive in specific environmental and soil conditions. The system generates recommendations based on these predictions.
Score of confusion matrix of this model is around 99%.
