INPUT: https://drive.google.com/open?id=1GjkWCbpUCAVaIMR7omZAXx35E2UC0OGo/Distracted-driver-detection.zip

OUTPUT: 
https://drive.google.com/open?id=1GjkWCbpUCAVaIMR7omZAXx35E2UC0OGo/Predictions.csv
https://drive.google.com/open?id=1GjkWCbpUCAVaIMR7omZAXx35E2UC0OGo/vgg.hdf5 

How to Run:

1) Open the 'project.ipynb' and run to mount the google drive to access the dataset.

2) The dataset is unzipped and stored in the local google colab environment.

3) Train data is extracted and converted to numpy array for further use.

4) Different models are used for training the train samples and the weights of the models are stored in '.hdf5' format for further use.

5) A few test samples are plotted by using the previously saved model.

6) Finally all the test data is extracted for prediction and the final predicted data is stored in 'Predictions.csv'

Note: Only the best model is used for test samples and predictions.(VGG16 - No Extra Layers)
