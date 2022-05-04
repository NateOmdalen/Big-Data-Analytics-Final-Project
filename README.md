# Big Data Analytics Final Project
_________________________________________

This repository contains my work for the final project of CSCI 6502 Big Data Analytics.  The course was completed as part of my MS coursework in applied mathematics at the University of Colorado, Boulder.

__________________________________________

Abstract:

A machine text summarization system takes as input a piece of text and produces as output a summary of the text. Such systems have many applications, most notably in search engines. In my project, I use the deep neural network architecture T5 to investigate text summarization. I train the network on the WikiHow dataset. I explore and compare three fine-tuning techniques. In the first, all the parameters of the model are free to be tuned during the entire training process. In the second, gradual unfreezing, blocks of the encoder and decoder of the network are unfrozen one at a time throughout training. In the third, adapter tuning, special fully-connected modules are inserted into the network, and only these layers are free to be tuned. I also investigate the extent to which T5 still generalizes to other data after being fine-tuned by testing it on other datasets.

___________________________________________

Contents:

* FINAL-REPORT.pdf - This written portion of the final project
* FINAL-CODES-AND-RESULTS.ipynb - Jupyter notebook containg the implementations and results of the project

