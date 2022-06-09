# CS156: Machine Learning for Science and Profit
## Final Project
This project was created for my CS156 machine learning class final project at Minerva University. The project was open ended; students were told to choose a dataset and achieve a practical goal using concepts covered in the class. 

I chose to build various classifiers for cat breeds using images of cats and their associated breed labels. I achieved this using Python libraries such as Sci-Kit Learn, Pandas, Matplotlib, NumPy, and Tensorflow.

I created 10 different classifiers, each with a different machine learning method: Logistic Regression, Logistic Regression with PCA (Principal Component Analysis), Logistic Regression with LDA (Linear Discriminant Analysis), Linear SVM (Support Vector Machine), Polynomial SVM, Radial Basis Function SVM, VGG16 Neural Network, Inception Neural Network, ResNet50 Neural Network, Efficient Neural Network.

The training image dataset was taken from [Kaggle](https://www.kaggle.com/datasets/ma7555/cat-breeds-dataset), which included images that were self-classified by pet owners using various angles and lighting. Therefore, most of the classifiers had low accuracy scores. The model with the highest accuracy score was the Inception Neural Network model (34% accuracy), which could be improved with more epochs and better input data, but this would require more computational power.
