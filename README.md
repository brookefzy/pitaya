# Crash Tutorials on Urban Science/Modeling
This is a crash tutorial for researchers in urban studies to get a taste of machine learning tools.
This repo only contains sample codes for simple replication of current researches. Mathematical backgrounds are beyond the scope of this repo. Source of codes are included in each section.

## Installation
```
conda create -n piyata python=3.10
conda activate piyata
conda install pip
pip install -r requirements.txt
```
## Other requirements
1. Register a Gmail account for Colab
2. Register to get an openAI API key (optional)
3. VPN set up if a network blocker exists.

## Content
Each section will involve two parts. Part A is lab time, we dive into the details of ML and AI algorithm mechanics and use a python package to conduct basic analysis. Part B will show case a real project.

0. [Overview of ML/AI in urban studies](https://docs.google.com/presentation/d/1Qe5HpvrHvt2qUsnCyHGmEX-InD7OgYgSMav3nXh15ec/edit?usp=sharing)
1. [Housing Price Predictor](https://github.com/brookefzy/pitaya/tree/main/HousingPricePredictor)
* Data Exploration and Data Cleaning
* Linear Models
* Non-linear Models
2. [Cluster Space with Mobility Pattern](https://github.com/brookefzy/pitaya/tree/main/ClusterSpacewithMobility)
* Kmean and Fuzzy C-means
3. [Street Network](https://github.com/brookefzy/pitaya/tree/main/StreetNetwork)
* Use osmnx to download road network
* Network analysis
4. [AI baby steps - NLP](https://github.com/brookefzy/pitaya/tree/main/BabyAI-NLP)
* Word Frequency
* Word Embedding
* Prompt engineering
5. [AI baby steps - CV and deep learning](https://github.com/brookefzy/pitaya/tree/main/BabyAI-CV)
* OpenCV basics
* Image segmentation
* Object detection and tracking
* Unified model
* Data labelling tools

## Folder Structure
```
├───BabyAI-CV
│   ├───data
│   └───scripts
├───BabyAI-NLP
│   ├───data
│   └───figures
├───ClusterSpacewithMobility
│   ├───data
│   └───figures
├───HousingPricePredictor
│   └───data
└───StreetNetwork
    └───figures
```
