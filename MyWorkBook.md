vagrant up  
vagrant ssh 

sudo apt-get install git  
git clone https://github.com/stat157/questionnaire.git  
cd questionnaire
cp example.cfg ~/stat157.cfg (in questionnaire directory)
vi ~/stat157.cfg (questionnaire directory)  
------ By pressing the 'i' key, you can switch to insert mode.  
------ Press 'Esc' to return to command mode, and :x to save and exit  

sudo apt-get install python-matplotlib  
sudo apt-get install python-tornado  
ipython notebook --no-browser --ip=0.0.0.0 --script  
ipython notebook --no-browser --ip=0.0.0.0 --pylab inline  
sudo apt-get update  
sudo apt-get install r-base  
sudo pip install rpy2

On Ipyhton notebook:  
-------------------------------------------------------------------------------------------------
import numpy as np  
import matplotlib
import matplotlib.pyplot as plt  
import pandas as pd  
from pylab import *  
%pylab inline


Useful links:  
-----------------
Matplotlib - 2D and 3D plotting in Python:  
http://nbviewer.ipython.org/urls/raw.github.com/jrjohansson/scientific-python-lectures/master/Lecture-4-Matplotlib.ipynb  

R formula: (regression)  
http://nbviewer.ipython.org/urls/raw.github.com/fperez/nipy-notebooks/master/exploring_r_formula.ipynb  

