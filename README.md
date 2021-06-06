# keras-stroke-dataset-alaysis

[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.png?v=103)](https://opensource.org/licenses/mit-license.php)


![stroke scan image](https://images.unsplash.com/photo-1559757175-5700dde675bc?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1189&q=80)

-----

The motivation behind this project was to gain a better understanding of tensorflow 2.4 and to serve as an example for future projects of the same type. 

Mainly, it creates a machine lerning model for structure data classification. For when given some values(age, hypertension, work type), it gives the probability of an individual having an stroke.

Not only I lerned a lot about this framework, but also learned in a pratical way machine lerning. This projects standout by the code being writeen in a way that is easy to understand. And also creates a model that is easy and intuitive to use. 

-----

Dataset used: https://www.kaggle.com/fedesoriano/stroke-prediction-dataset

-----

Code inspired from: https://keras.io/examples/structured_data/structured_data_classification_from_scratch/

-----

Install dependencies:

Upgrade pip and install [pipenv](https://pipenv.pypa.io/en/latest/)

```
pip install --upgrade --user pip

pip install --upgrade virtualenv
```

Create and activate the virtual enviroment.The python version already needs to be installed in your pc

I am using this python version because at the moment this python version is  compatible with tensorflow and keras

```
virtualenv --python=/usr/bin/python3.7 envname
```

Activate it:

```
cd envname/Scripts

activate
```

Install necessary modules and activate it

```
pip install tensorflow==2.4.1 pandas==1.2.4 numpy==1.2 ipykernel
```

Install modules to make sure the code runs on a jupyter notebook

```
python -m ipykernel install --user --name ENVNAME --display-name "Python (whatever you want to call it)"
```
After all this, start jupyter notebook

```
jupyter notebook
```

-----

Started on 21/04/2021

Ended 

Archived
