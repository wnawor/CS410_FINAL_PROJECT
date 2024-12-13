# Pitchfork Recommender System
This repository contains the scripts used to create a Pitchfork album recommender system with simple user interface.
The original data set can be found here: https://huggingface.co/datasets/mattismegevand/pitchfork
The scripts require the following python packages: pandas, numpy, and PySimpleGUI

## data_preprocess
This script contains the step to pre process the data. These steps include:
- Filtering the album reviews
- Calculating Term Frequency and Inverse Document Frequency for the reviews
- Using cosine similarity to calculate a similarity matrix for all of the reviews

## recommender_system
This scripts contains the actual recommender system and simple user interface.
The recommender system suggests the top 3 albums based on the album chosed in the drop down of the user interface.
The user interface then displays the top 3 albums along with the artists and short descriptions.
