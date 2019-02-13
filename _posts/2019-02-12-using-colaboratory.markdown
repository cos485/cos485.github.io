---
layout: post_2019
title:  "Using Colaboratory"
date:   2019-02-12 14:00:00 EST
author: "Sven Dorkenwald"
---

# Using Colaboratory  
[Colaboratory](https://colab.research.google.com) is Google's Jupyter notebook environment that requires no setup and runs entirely in the cloud. It's like a Google doc for Jupyter notebooks, and it's where you should work on the problem sets. It's free to use, and it provides an easy way to make sure everyone has access to the same hardware, packages, and dependencies.

## Requirements
* Google account with an associated Google Drive
* Connect Colaboratory to your Google Drive (see below)

## How to open Colaboratory files
* Click on the link we provide to the Jupyter notebook file. This should take you to a Google drive page where the notebook is stored.
* From the Google Drive page, look to open the file with Colaboratory (no need to download the file). 
	* If Colaboratory has not been connected to your Google Drive, click on the 'Open with' menu at the top of the page. Select 'Connect more apps', then select Colaboratory from the window that opens. 
	* If Colaboratory has already been connected, you should be able to select it from the list of 'Connected apps' below the Download button.

## How to work on a homework assignment's Colaboratory notebook
* The homework Colaboratory notebooks we provide for the programming exercises are read-only, so you will need to make a copy of each notebook to your own Google Drive (`File > Save a copy in Drive`). 
* Work from your copied notebooks to complete the assignment.

## Tutorials on Colab + Jupyter notebooks
* [Hello, Colaboratory](https://colab.research.google.com/notebooks/welcome.ipynb)
* [Overview of Colaboratory Features](https://colab.research.google.com/notebooks/basic_features_overview.ipynb)

## Useful things to note
* Jupyter includes access to common shell operations by starting a line with `!`. This is how you can use `pip` to install any required packages, like PyTorch.
* If you let your environment sit idle for a while (90 minutes), the virtual machine the notebook is running on will be recycled, so be sure to save periodically.
* Your virtual machine has a lifetime of 12 hrs before it will be forced to recycle.
* You can attach a GPU to your virtual machine.

## Troubleshooting
* Make sure you toolbar says CONNECTED, so you can execute your code.
* Message one of the TAs or post to Piazza if you run into any problems.
