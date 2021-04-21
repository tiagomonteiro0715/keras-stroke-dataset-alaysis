# keras-stroke-dataset-alaysis

![stroke scan image](https://images.unsplash.com/photo-1559757175-5700dde675bc?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1189&q=80)

-----

Add description

-----

Dataset used: https://www.kaggle.com/fedesoriano/stroke-prediction-dataset

-----

Install dependencies:

Upgrade pip and install [pipenv](https://pipenv.pypa.io/en/latest/)

```
pip install --upgrade --user pip

pip install --upgrade pipenv
```

Create and activate the virtual enviroment.The python version already needs to be installed in your pc

I am using this python version because at the moment this python version is  compatible with tensorflow and keras

```
pipenv install --python 3.7.8
```

Install necessary modules and activate it

```
pipenv install tensorflow==2.4.1 pandas==1.2.4 numpy==1.2

pipenv shell
```

Install modules to make sure the code runs on a jupyter notebook

```
pipenv install ipykernel
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
