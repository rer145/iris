# IRIS
The purpose of this repository is to get familiar with the IRIS dataset that is on [kaggle.com](http://www.kaggle.com/). This particular dataset is located [here](https://www.kaggle.com/uciml/iris). We will be using this dataset for Project 1 for DATA 550 at Mercyhurst University, in Erie, PA.

## File and Folder Structure

All data files are contained in the folder called ```input```. I have also created two Jupyter notebooks that connect to these data files, which are located in the ```notebooks``` folder.

The reasoning behind this structure is to match how things are on Kaggle, which makes switching between my local copy and the copy in Kaggle easier.

## Notebooks

The first notebook to look at is ```iris-experiments.ipynb```. This is the notebook that also located on my [Kaggle account](https://www.kaggle.com/rer145/iris-experiments/).  In this notebook, the goal was to follow along with an existing kernel to gain a better understanding of the data set.

The second notebook to look at is ```iris-pygal.ipynb```. This notebook is a smaller example of accessing the Iris data set, uses pygal for the visualizations.  This notebook is NOT on Kaggle, since Kaggle does not support the use of pygal on its site. This notebook is primarily used for my own experiments with using pygal against the data set.

The third notebook to look at is ```iris-data.ipynb```.  This notebook is a scratch file I used to explore the data in the Iris.csv data set. This notebook is where the data in the next section comes from.

## Data Familiarization

Pandas contains a very useful method called ```describe()```.  This method generates several statistics that summarize the data. In my opinion, this is a very quick and dirty way of finding out what sort of data you are using.  

#### Iris-setosa

Stat | Sepal Length | Sepal Width | Petal Length | Petal Width
--- | ---: | ---: | ---: | ---:
count | 50.0 | 50.0 | 50.0 | 50.0
mean | 5.006 | 3.418 | 1.464 | 0.244
std | 0.352490 | 0.381024 | 0.173511 | 0.107210
min | 4.3 | 2.3 | 1.0 | 0.1
max | 5.8 | 4.4 | 1.9 | 0.6

#### Iris-versicolor

Stat | Sepal Length | Sepal Width | Petal Length | Petal Width
--- | ---: | ---: | ---: | ---:
count | 50.0 | 50.0 | 50.0 | 50.0
mean | 5.006 | 3.418 | 1.464 | 0.244
std | 0.352490 | 0.381024 | 0.173511 | 0.107210
min | 4.3 | 2.3 | 1.0 | 0.1
max | 5.8 | 4.4 | 1.9 | 0.6




## Useful Links

* [My Kaggle Profile](https://www.kaggle.com/rer145)
* [Iris data set](https://www.kaggle.com/uciml/iris)
* [iris-experiments.ipynb on Kaggle](https://www.kaggle.com/rer145/iris-experiments/)