# **Diabteller**
## About Project

- This Application Predicts wether the user has diabetes or not based on users data
- The result will be shown to user if he or she has filled all the manadatory details in the form
- Based on the Probablity(chance of having diabetes), user will be able to see one of the following result:

  1. If Probablity is greater than 80% then result is: Alert! You seem to be at a very high risk of getting diabetes.Please seek immediate medical attention.
  2. If Probability is greater than 50% and less than 80% then result is: You are at a low risk of getting diabetes.
  3. If Probability is greater than 20% and less than 50% then result is: You currently are at low risk of being diagnosed with diabetes but it never hurts to take more care.
  4. If Probability is less than 20% then result is: All's fine! You seem to have very low chances of getting diabetes.

- Dataset used is PIMA India Dataset
- Before Training and Testing Data data cleaning is done
- 10 Machine Leaning Algorithms are used namely:
  1. K Nearest Neighbor Algorithm (KNN)
  2. Gausssian Naïve Bayes (Gaussian NB)
  3. Linear Discriminant Analysis (LDA)
  4. Adaboost
  5. Random Forest Classifier
  6. Perceptron
  7. Extra Tree Classifier
  8. Bagging
  9. Logistic regression
  10. Gradient Boost Classifier
- We Always used the highest Accuracy Machine Leaning Algorithm as our Model to test user's data and calculate final Probability
- The user's data has been saved inside csv file so that data points in dataset will increase which can give more accurate results
## Technologies used:
- Frontend: HTML,CSS,Bootstrap
- Backend: Python
- Framework: Flask
- Libraries: Pandas,Numpy,sklearn
## Installation:
- Clone or download the project in zip format
- Go through the guide.txt file for setting up flask server
- Go through the requirements.txt file for python libraries required
- open terminal and type python app.py
- open browser and type localhost:8000
## Team Members:
- [Gumutch Mishra](https://github.com/gumutch)
- [Kunal Thite](https://github.com/kunal170)
- [Harshit Prajapati](https://github.com/harshit08022001)
- [Tanish Rangnekar](https://github.com/tanish-cpu)