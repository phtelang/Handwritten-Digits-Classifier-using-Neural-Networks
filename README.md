## Handwritten Digits Classifier using Neural Networks
In this project, we will build models that can classify images of handwritten digits (0-9) using deep learning or neural networks.

The goal of this project is to:
1. Understand why image classification is a hard task
2. Observe the limitations of traditional machine learning models for image classification
3. Train, test, and improve a few different deep neural networks for image classification

A deep neural network is a specific type of neural network that excels at capturing nonlinear relationships in data. Deep learning is effective in image classification because of the models' ability to learn hierarchical representations. An effective deep learning model learns intermediate representations at each layer in the model and uses them in the prediction process. For example, in facial recocgnition, in the first hidden layer the network learns to represent edges and specific features of faces. In the second hidden layer, the weights represent higher level facial features like eyes and noses. Finally, the weights in the last hidden layer resemble faces. Each successive layer uses weights from previous layers to try to learn more complex representations.

We used below algorithms for prediction and getting the best accuracy:
1. K-Nearest Neighbors Model - The k-nearest neighbors algorithm compares every unseen observation in the test set to all (or many, as some implementations constrain the search space) training observations to look for similar (or the "nearest") observations. Then, the algorithm finds the label with the most nearby observations and assigns that as the prediction for the unseen observation.
2. Neural networks with multiple hidden layers and different activation methods.
3. Decision tree model - Decision trees can pick up nonlinear interactions between variables in the data that linear regression can't, but they also tend to overfit and prone to instability to small changes in input data.
4. Random forest model - Random Forest algorithm performs both classification and regression tasks using ensembling. Ensembling is done by training multiple decision trees on different data samples built by replacement. It combines the predictions of multiple models to create a more accurate final prediction. One of the major advantages of random forests over single decision trees is that they tend to overfit less.

### Summary of Results
Highest accuracy of 95.99% was achieved using two hidden layers and 95.5% using "relu" activation method.

To view the code and graphs accurately, please click here.

### Installation
- Download the .ipynb (Jupyter file).
- Install the requirements using pip install -r requirements.txt. (Make sure you use Python 3.)
