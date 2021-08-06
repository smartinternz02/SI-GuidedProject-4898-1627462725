This project is aimed at predicting car's mileage (mpg) using a dataset which contains multiple features like car name, horsepower, number of cylinders and many more. This project uses car-performance dataset, all the preprocessing steps are applied on the data, to prepare the data to train the model.

Multiple machine learning regression algorithms are trained and tested for r_2 score metric. Random Forest turned out to give the most accurate model for predicting of mpg values.

Then the notebook and the model was deployed on IBM cloud platform and was integrated with python flask network, which was connected to the end point of webpage, the webpage takes the values for attributes of a car and predicts it's mpg (miles per gallon) value and the car performance (Low/Moderate/High).

Extract the rar file.

To run the webpage, enter the following command on command prompt (run the python file app.py)-

python app.py

And then copy the localhost link and paste it on any browser to view the webpage
