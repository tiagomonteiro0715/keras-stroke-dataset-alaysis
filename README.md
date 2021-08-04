# keras-stroke-dataset-alaysis

[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.png?v=103)](https://opensource.org/licenses/mit-license.php)


![stroke scan image](https://images.unsplash.com/photo-1559757175-5700dde675bc?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1189&q=80)

-----
### What this is

Using the TensorFlow framework, this is a machine learning model written in Python.

### What this does

Basically, it creates a machine learning model for classifying structure data. Depending on certain values (age, hypertension, work type), it can predict the likelihood of someone having a stroke.

### Motivation and what I have learned

The purpose of this project was to gain a deeper understanding of Tensorflow 2.4. and to serve as a model for future projects of the same type and also to explore my interest in the topic.

Besides learning a lot about the framework and machine learning, I also understood more about programming and how it works in real time. 

### Main difficulties and how it stand out

It was difficult to comprehend every line of code. In addition, it is necessary to figure out why certain code lines behaved in the manner that they did and not in an alternative manner. 

By writing the code in a concise manner, the project stands out. Additionally, the model is easy to use and intuitive. 

-----

### Install dependencies

#### Upgrade pip and install [pipenv](https://pipenv.pypa.io/en/latest/)

```
pip install --upgrade --user pip

pip install --upgrade virtualenv
```



Create and activate the virtual enviroment.The python version already needs to be installed in your pc

I am using this python version because at the moment this python version is  compatible with tensorflow and keras

```
virtualenv envname
```



#### Activate it:

Windows:
```
envname\Scripts\activate
```
macOS/Linux:
```
envname/bin/activate
```
#### Install necessary modules and activate it

```
pip install tensorflow==2.4.1 pandas==1.2.4 numpy==1.2 ipykernel
```

#### Make sure the code runs on a jupyter notebook

```
python -m ipykernel install --name=envname
```
#### Start jupyter notebook

```
cd ../..

jupyter notebook
```

-----

Dataset used: https://www.kaggle.com/fedesoriano/stroke-prediction-dataset

Code inspired from: https://keras.io/examples/structured_data/structured_data_classification_from_scratch/
