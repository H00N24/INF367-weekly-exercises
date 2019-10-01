## INF367 Selected Topics in Artificial Inteligence

Weekly exercices

### Solutions
Exercitses assigments and solutions are in  jupyter notebooks.
I was solving exercises with python 3.7. All used packages are specified in `requiriments.txt`.

### Prerequisities
* python >=3.7
* python venv/virtualenv package for creating virtual enviroment
* python packages specified in `requiriments.txt`

#### Dev req
* `pip-tools` package for creating `requirements.txt`


### Commands for installing & running notebooks
* Creating and activating python virtual enviroment
```sh
$ python -m virtualenv venv # python -m venv venv
$ source venv/bin/activate
```
* Installing python packages and ipykernel for jupyter notebook
```sh
[venv]$ pip install -r requiriments.txt
[venv]$ python -m ipykernel install --user --name inf367-exercises --display-name "INF367 Exercises"
[venv]$ jupyter notebook
```
