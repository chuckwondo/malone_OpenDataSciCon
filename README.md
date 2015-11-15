Welcome to the repository hosting code for the end-to-end data analysis workflows in python workshop!  

Author: Katie Malone, data scientist @ Civis Analytics

Getting started:
There are two ipython notebooks containing all the relevant code: 

1. african\_wells.ipynb (starter code, and some relevant explanations/links)
2. african\_wells\_solutions.ipynb

The first has prompts only and will hopefully be the only one you need.  If you get stuck, or you are going through this workshop asynchronously, the second one might be a useful reference.  

In order to work through this example, you will need the training and testing data associated with the Pump it Up: Data Mining the Water Table hosted on [drivendata.org](http://www.drivendata.org/competitions/7/data/).  In the notebooks, we call the training feature and labels files ``well_data.csv`` and ``well_labels.csv``, respectively.

Software requirements are as follows:

1.  python 3 (2.x might work with minimal changes, but no guarantees)
2.  ipython
3.  pandas
4.  numpy
5.  scipy
6.  sklearn 

If you are starting from scratch, and have none of the above installed, consider getting them via 
[Anaconda](https://www.continuum.io/downloads), which includes all of the above (and more!) in an easy-to-use bundle. 


Last, as you get toward the bottom of the notebook and GridSearchCV, you may want to consider porting your notebook workflow into a python script that can be run via your terminal.  I have anecdotally found that some commands were running very slowly in the notebook, but faster when put in a script.

When you've made a workflow that you're satisfied with, I strongly suggest that you submit it to drivendata.org, and get involved in the competition!

