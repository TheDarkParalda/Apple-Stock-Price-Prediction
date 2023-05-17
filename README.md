# Apple-Stock-Price-Prediction

### Goal
Predict the last 60 close values of Apple stock using the previous open-close values given and the day's open value.

### Dataset
Dataset given by Yahoo Finance on Apple.

### Description
In this project I created an LSTM based Model to predict the images given.

### Work Done
* Importing pytorch, mathplotlib for the solution
* Creating the function that returns the LSTM based Model
* Importing the data, Splitting the dataset to Train and Test (Validation) data and normalising them.
* Training the model.
* Plotting the accuracy and loss per epoch
* Plotting the close values and checking how close it is to the actual prices.

### Model Used

#### LSTM 
![LSTM](Apple-Stock-Price-Prediction/images/LSTM_cell.png)

### Libraries used
* pytorch
* Mathplotlib
* os

### Loss-Epoch Curve
![lossepoch](Apple-Stock-Price-Prediction/images/Loss_Epoch_curve.png)

### Prediction Curve
![pred](Apple-Stock-Price-Prediction/images/Prediction%20curve.png)
