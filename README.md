# FORKED !

### How to run!
_Windows 10 steps_

Create Python virtual environment
> python -m venv sd-venv

Run virtual environment
> sd-venv/Scripts/activate.bat

Install the library
> pip install -r requirements.txt

Run the models
> python performance_check.py

[Activate venv Windows](https://stackoverflow.com/questions/65552171/how-to-activate-virtualenv-on-windows)
[Create venv Windows](https://docs.python.org/3/library/venv.html)

# Software-Defect-Prediction
Software Defect Prediction is an
important aspect in order to ensure software
quality. Deep Learning techniques can also be
used for the same.

In this project we use Random forest, Convolutional Neural Networks,
SVM, Decision Tree, Naive Bayes and Artificial Neural Network to train the model with the data.
After getting different results from these techniques, we combine them through
Logistic Regression and get the final output.

We use different open source datasets from NASA
Promise Data Repository to perform this
comparative study.

For evaluation, three widely used metrics:
Accuracy, F1 scores and Areas under Receiver
Operating Characteristic curve are used. It is found
that Artificial Neural Network outperformed all the
other dimensionality reduction techniques.
