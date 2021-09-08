# FORKED !

### How to run!
_Windows 10 steps_

Open up cmd as Administrator and move to this repo directory

Create Python virtual environment
> python -m venv sd-venv

Run virtual environment
> sd-venv/Scripts/activate

Install the library
> pip install -r requirements.txt
_If above command result an error, run the cmd as Administrator and then re run the above command_

Run the models
> python src\performance_check.py

- [Create venv Windows](https://docs.python.org/3/library/venv.html)
- [Activate venv Windows](https://stackoverflow.com/questions/65552171/how-to-activate-virtualenv-on-windows)

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
