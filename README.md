# Pytorch-Deep-Learning
## About
This repo contains boilerplate code interleaved with tutorials to get ML algorithms running using the PyTorch framework
Every file is a jupyter notebook so one needs to install jupyter through conda or pip and use command `jupyter notebook` in the repo folder to interact with the tutorials and run the code.

## Contents
**Intro Pytorch.ipynb** - Necessary functionality and patterns in PyTorch to get a new PyTorch user who knows ML going fast 

**Basic NN.ipynb** - Skeleton of a PyTorch Neural Net Architecture and boiler-plate code that cbe edited into any required Neural Net

## Install Instructions for Jupyter

If you are using pip:

```git clone https://github.com/jaks19/Pytorch-Deep-Learning.git;
cd introdeeplearning;
pip install virtualenv;
virtualenv pytorchy;
source pytorchy/bin/activate;
pip install --upgrade pip;
pip install tensorflow;
pip install matplotlib;
pip install pandas;
pip install jupyter;
python -m ipykernel install --user --name=pytorchy
echo 'done';
jupyter notebook
```
From within jupyter, in the top-right corner, select the kernel named "pytorchy" to activate your virtual env

Or if you are using Conda:

```
git clone https://github.com/jaks19/Pytorch-Deep-Learning.git;
cd introdeeplearning;
conda create -n pytorchy;
source activate pytorchy;
conda install -c conda-forge tensorflow;
pip install matplotlib;
pip install pandas;
conda install jupyter;
echo 'done';
jupyter notebook
```
