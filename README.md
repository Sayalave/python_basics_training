# Python basics training

## Objective
This training covers Python basics using examples from data analysis with a focus on the Pandas library, which is a powerful tool that can be used across multiple functions. The practical goal of the training is to replace any usage of Excel with Python, as well as to explore additional functionalities to load, transform, analyze, and visualize data. The training will use Jupyter to execute Python and if there is enough interest it can potentially cover GitHub basics.

## Prerequisites
The only prerequisites for the training is Python 3.7. Throughout the training, we will add libraries to requirements.txt for additional Python libraries that will be used. 

## Install Python 3.7
* Open the terminal. If you don’t know how to open the terminal, here is a [video](https://www.youtube.com/watch?v=zw7Nd67_aFw)
* Install Homebrew by running the following command in the terminal. This process may take a few minutes and may also ask for your computer password. It is also possible that is will ask you whether you want to install Xcode (just follow the instructions prompted in the terminal): 
``` 
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

* Install Python: 
```
brew install python
```

## Clone repository
* Open the terminal. 
* Install git:
```
brew install git
```
* Go to your home directory in the terminal: 
```
cd
```
* If you want your home directory to be shown in the Finder sidebar, you can follow this [video](https://www.youtube.com/watch?v=-A69alGX1Sk)
* Clone this repository in your local machine:
```
git clone https://github.com/Sayalave/python_basics_training
```

## Setup a virtual environment
- In the terminal, go to the training directory:
```
cd python_basics_training
```
* Install virtualenv
```
pip3 install virtualenv
```
* Create a virtual environment named “ve”: 
```
virtualenv ve
```
* Activate the virtual environment and install the requirements: 
```
source ve/bin/activate && pip install -r requirements.txt
```

## How to start Jupyter
* In the terminal, go to the training directory:
```
cd ~/python_basics_training
```
* Source your virtual environment and install requirements:
```
source ve/bin/activate && pip install -r requirements.txt
```
* Now that you are within your virtual environment, start Jupyter:
```
jupyter notebook
```
* Jupyter will now be available in you default browser in the URL: http://localhost:8888/tree
* Make sure that Jupyter works by opening your first notebook. In Jupyter, navigate to the *session_1* directory and open the file *session_1.ipynb*. 

## How to refresh your local copy of this repository
* Sometimes you will want to update the local copy of this repository. For example, to get the new homeworks. 
* In the terminal, go to the training directory:
```
cd ~/python_basics_training
```
* Tell git that you don't want to commit the changes you've made to the homework or session notebooks. This means that every time you run the following command you will restore the notebooks in the directories `homeworks` and `sessions` to the version in the repository.
```
git checkout -- . && git pull
```

## How to work on a homework 
* You should have a directory for your work named `mywork` within the python_basics_training directory. For example, mine should be `mywork_salvador`
* In the directory `homeworks` you will find the raw version of the homeworks. 
* Copy the notebook with the homework that you want to work on from the `homeworks` directory to the `mywork` directory.
* You can work on the notebooks that you just copied to `mywork`.









