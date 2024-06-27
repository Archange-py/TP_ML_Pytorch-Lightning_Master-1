<p align="center" width="100%">
<img src=".\pictures\pytorch_lightning.png" alt="TP-ML">
</p>

# TP of Machine Learning with Pytorch Lightning for Master 1

###
Welcome ! This directory contains [Laurent Risser](http://laurent.risser.free.fr)'s practical exercises, originally written in pytorch, which I have been implemented in pytorch lightning with python. 
They are the result of work carried out during the second week of the Seconde course, at IMT (Institut de Mathématiques de Toulouse). 

## Table of Contents
***
1. [General Info](#general-info)
2. [Packages](#packages)
3. [Google Colab](#google-colab)

## General Info
***

Lightning is a library descended from Pytorch. It retains its object-oriented writing style, but in which model training is automatically managed. If you want to get to the bottom of this, you'll need a good knowledge of object-oriented programming.

> I recommend that you use [Google Colab](https://colab.research.google.com) to run Jupiter Notebooks and thus be able to use a GPU or TPU for free.

## Packages
***

You will need to install differently python packages:  
* [Numpy](https://numpy.org/install/) :
```
pip install numpy
```
* [Matplotlib](https://pypi.org/project/matplotlib/) :
```
pip install matplotlib
```
* [Pandas](https://pypi.org/project/pandas) :
```
pip install pandas
```
* [Torch](https://pypi.org/project/torch/) :
```
pip install torch
```
* [Torchvision](https://pypi.org/project/torchvision/) :
```
pip install torchvision
```
* [Lightning](https://pypi.org/project/lightning/) :
```
pip install lightning
```

## Google Colab
***

To use a Jupiter Notebook in Google Colab, Lightning needs to be installed directly on the Notebook. Type this command on the first line of your Notebooks in a separate cell :  
```
!pip install lightning -qq
```