Covid-19 Detection with Chest X-RAY using PyTorch
=================================================

Download the Data set from:

- [Kaggle](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database)
- [Covid-19 Radiography Dataset](https://github.com/VivekCR7/Detecting-Covid-19-with-chest-X-RAY-using-PyTorch/tree/master/COVID-19%20Radiography%20Database)



Install Conda:
==============
-[Windows](https://problemsolvingwithpython.com/01-Orientation/01.03-Installing-Anaconda-on-Windows/)
-[Linux](https://problemsolvingwithpython.com/01-Orientation/01.05-Installing-Anaconda-on-Linux/)
-[MacOS](https://problemsolvingwithpython.com/01-Orientation/01.04-Installing-Anaconda-on-MacOS/)
    
 Install PyTorch:
 ===============
 
    $ conda config --set auto_activate_base false
    $ conda install pytorch torchvision cpuonly -c pytorch
    
Check pytorch is installed or not?
=================================
    $ python3
    >>>import torch
    >>>torch.__version__
    
Run jupyter notebook:
====================
    
    $ jupyter notebook
    
    Then open .ipynb file and run on the jupyter server


![screenshot](img/output.png)


The above model(Restnet18) gives the accuracy of 97 %.


Contributor:
==

- [Vivek Dubey](http://github.com/VivekCR7)
