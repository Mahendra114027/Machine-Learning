# Machine Learning using Scikit-Learn

## Introduction

The following repository contains notebooks which are based on the material used by me during the BangPypers July meetup. These notebooks are made keeping in mind that the intended audience has very little or no experience with scikit-learn and/or machine learning but have some knowledge of python.

## Installation

* Clone this repo `git clone https://github.com/pfrcks/BangPypers-SKLearn.git`
* If you don't have `python-dev` install it using `sudo apt-get install python-dev` or whatver equivalent command you have for your distribution.
* Installation is a non-trivial process generally. However we have the wonderful **conda** environment manager, a part of Anaconda Scientific Distribution. The best course of action is downloading and installing [miniconda](http://conda.pydata.org/miniconda.html).
    * Once you have minconda installed issue the following command on your shell
    * `conda install numpy scipy matplotlib scikit-learn ipython-notebook seaborn`
    * `conda install -c conda-forge ipywidgets`
    * **Note**: The above process requires a good net connection and time. Please do this before coming to the workshop.
* If you want to further simplify the process you can go for the fullfledged package [Anaconda](https://docs.continuum.io/anaconda/install) instead of the above method. (This is the most preferred method)
    * After installing issue `conda install -c conda-forge ipywidgets`
* **fetch_data.py** fetches the data required for the Facial Recognition Example. The dataset is ~230MB. If you want to follow along during the workshow you can execute `python fetch_data.py` after cd'ing into the repo directory. In case you don't want to download it, you are welcome to look at the example during the workshop.
* **NOTE** : This repo is a work in process. To keep yourself updated issue a `git pull` before attending the workshop to be on the latest version.
* **NOTE** : If you face any problems during installation, please create an issue on github.
* That's it.

## Requirements

* Python-2.7
* Working knowledge of Python

## Notes

* This workshop has been developed with the intended audience as people with little or no experience of scikit-learn and/or machine learning. 
* Please download the repo and fetch the dependencies before coming to the workshop. The installation takes time which can be spent on the workshop instead.

## Credits where credit's due

* These notebooks owe a lot to the notebooks published by [Jake Vanderplas](https://github.com/jakevdp/sklearn_tutorial) and [Andreas Muller](https://www.youtube.com/watch?v=80fZrVMurPM), who have a much more extensive coverage of the topics. If you want to go further in regards to the black box approach with scikit-learn, I would highly recommend going through their notebooks and screencasts. These tutorials helped me a lot in understanding scikit-learn and it's application.

## Where to go from here?

* Kaggle
* Andrew-Ng
* KD-Nuggets post
* Dive into
* Awesome notebooks
* [A visual intro to ML](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
