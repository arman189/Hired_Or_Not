# Hired_Or_Not
Hired Or not is a predictive model using machine learning K Nearest Neighbour algorithm which predicts whether an employed is hired or not based on their interview experience.

<br/>**Objectives:-**  To predict whether a person is hired or not.
<br/>**Software Used:-** Anaconda, Jupyter Notebook, pyqt5
<br/>**Algorithm Used:-** K-Nearest Neighbour Algorithm
<br/>**Definition:-** K-Nearest Neighbors is one of the most basic yet essential classification algorithms in Machine Learning. It belongs to the supervised learning domain and finds intense application in pattern recognition, data mining and intrusion detection.It is widely disposable in real-life scenarios since it is non-parametric, meaning, it does not make any underlying assumptions about the distribution of data.
<br/>**How to:-**
<br/>1. Read the csv file using pandas opencv() function.
<br/>2. Divide the dataset into x and y, where x having input values and y having outputs value.
<br/>3. Further dividing x and y into x_test, x_train, and y_test, y_train respectively using train_test_split().
<br/>4. Initialize the model by importing  KNeighborsClassifier from sklearn.neighbors.
           <br/>-> from sklearn.neighbors import KNeighborsClassifier
           <br/>->  model=KNeighborsClassifier(n_neighbors=13)
<br/>5. Train the model.
           <br/>-> model.fit(x_train,y_train)
<br/>6. Predict whether the person is hired or not .

**OUTPUT**

![output](https://user-images.githubusercontent.com/70680425/135618399-05b99502-0d16-413a-a00e-414d82225e90.png)

