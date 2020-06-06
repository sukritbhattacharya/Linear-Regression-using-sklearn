# Linear-Regression-using-sklearn
In this the simplest Linear Regression model has been implemented using Python's **sklearn** library. Also, here the python's **pydataset** library has been used which provides instant access to many datasets right from Python (in pandas DataFrame structure). For this project, PIMA women dataset has been used. The parameters, *skin* (representing the tricep skin fold thickness) and *bmi* (representing the bmi) of the women have been considered for the analysis that whether the tricep skin fold measurements can predict body mass index (BMI).

# Usage
To install pydataset : `pip install pydataset`. And with this you are good to go.
Import data using pydataset : `from pydataset import data`
To import the PIMA women dataset: `pima = data('Pima.tr')`. Now you have the dataset imported. 
Also, feel free to try out other parameters for predictions. In this case, my model has achieved a score of ~50%.
