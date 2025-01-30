# Neural Network Challenge 1

Repository: neural-network-challenge-1

Files: 
* student_loans_with_deep_learning.ipynb
* student_loans.keras
* README.md
     

## What it does

* Predict student loan repayment based on dataset of previous loans.
* Apply machine learning and neural networks to predict liklihood of repayment.
* Preprocess dataset using test_train_split and StandardScaler.
* Compile and evaluate using a neural network using two hidden layers.
* Save and export model  to student_loans.keras
* Predict loan repayment by reloading saved model.
* Generate classification_report.

## Usage
* TensorFlow.
* binary_crossentropy loss function.
* adam optimmizer.
* accuracy evaluation metric.

## Discussion questions
* Provided in code and below:

**1. Data includes financial background, loan preferences, educational information, and student demographics.  This data ensures the system recommends loans tailored to a student's financial situation, needs and educational path.  Government or private loans may be preferable.**


**2. Content-based filtering would be most appropriate, using attributes like student profiles and past loans.  Collaborative filtering would also help, based on what similar students have chosen.  A combination of the two filtering methods would be used based on the student's personal data and historical behavior of past students**


**3. a. Data privacy challenge.  Unauthorized access of sensitive financial and educational data requires privacy measures.  The system has to be compliant with various government regulations to main trust.  b. Bias challenge.  The training data may be biased to the advantage of certain student demographics or loan providers.  This could result in discriminatory loan recommendations.**



