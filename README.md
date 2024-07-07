**Logistic_Regression.ipynb**
-----------------------------------------------------------------------------------------

This code is an example to identify breast cancer cell samples as "benign" and "malignant" using the machine learning algorithm of Logistic Regression.

There are eight factors considered significant in determining this classification. Initially, two factors—(i) cell size and (ii) marginal adhesion—are used as dependent variables for the classification, achieving an accuracy of 96%. However, the inclusion of additional variables can improve the efficiency to 98.8%.
Logistic Regression is used for the classification and evaluation metrics such as (i) F-score and (ii) ROC AUC was used to determine the accuracy of this model. 

Source Data : UCI Repository on breast cancer cells. 

You can read the complete article at :

https://shtech-techfortheyouth.wordpress.com/2024/06/16/logistic-regression-recap/

--------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------

**Gradient_Optimization.ipynb**
Gradient descent optimization is an algorithm used in machine learning to identify the minimum or maximum of a function. It is primarily important because it minimizes the “loss function,” which measures how well the model’s predictions match the actual data. By iteratively adjusting the model parameters to reduce the loss function, gradient descent helps improve the accuracy and performance of the machine learning model.
Though the inbuilt .fit uses "Binary Cross Entropy" for gradient optimization, this code shows the steps to create your own gradient optimization function to minimize loss and improve accuracy.

It uses the same dataset as "Logistic_regression.ipynb"

You can read the complete article at:

https://shtech-techfortheyouth.wordpress.com/2024/06/18/gradient-descent-optimization/

---------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------

**Copy_of_Rotten_Food_Images.ipynb**

Oftentimes, we need to train our AI models with readily available images from the internet to optimize them for prediction accuracy. 
Accessing a large number of images and storing them on your disk is computationally expensive. 
Therefore, FlickrAPI can be a useful tool to train your models with access to thousands of images from their database.

You can read the complete article at :

https://shtech-techfortheyouth.wordpress.com/

---------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------

**Support_Vector_Machine.ipynb**

Support vector machines utilize hyperplanes to find the optimal boundary that maximizes the margin between different classes.

In SVM, the hyperplane (line) is chosen so that it best separates the input variables by their class ['0' or '1'].

MNIST is a database of handwritten digits that are used for training image processing systems. The MNISt contains 60,000 training and 10,000 test images of handwritten digits. 

We would compare the accuracy of prediction of the handwritten MNIST datasets with and without the SVC (Support Vector Classifier). 

As you can see without the SVC classifier the accuracy of prediction is only 88% however,the support vector classifier improves the accuracy to approximately 91%.

You can read the complete article at:



