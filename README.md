# fastai_learn
My notebooks from fast ai learning

## Pre-requisites

* Available GPU computer with CUDA (tested on 10.1)
* Python 3.6+ (tested with 3.7)
* pip package manager installed
* Following pip packages
  * pytorch
  * fastai
  * jupyterlab
  * Dependencies like: numpy, matplotlib, etc. should get installed with above

## Getting started

### bollywood notebook

* Attempts to use a pre-trained resnet to classify Indian movie actors: AK, SRK, SK
* To test notebook, un-tar data.tgz into local directory, and confirm that path variable in notebook is properly set
* To check inference quality, create directory called test and store few sample images - see last few cells of notebook
