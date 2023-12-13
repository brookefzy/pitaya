# Crash Tutorials on Urban Science/Modeling
This is a 12-hour tutorial for students in urban studies to get a taste of machine learning tools.
This repo only contains lab work required for this course. Mathematical backgrounds are beyond the scope of this repo.

## Installation
```
conda create -n pitaya python=3.10
conda activate pitaya
conda install pip
pip install -r requirements.txt
```
## Other requirements
1. Register a Gmail account
2. Register to get an openAI API key (optional)
3. VPN set up if a network blocker exists.

## Course Content
Each section will involve two parts. Part A is lab time, we dive into the details of ML and AI algorithm mechanics and use a python package to conduct basic analysis. Part B will show case a real project.
0. [Overview of ML/AI in urban studies](https://docs.google.com/presentation/d/1Qe5HpvrHvt2qUsnCyHGmEX-InD7OgYgSMav3nXh15ec/edit?usp=sharing) (0.5 h)
1. [Housing Price Predictor](https://github.com/brookefzy/pitaya/tree/main/HousingPricePredictor) (3.5 h)
* Data Exploration and Data Cleaning (1 h)
* Linear Models (1 h)
* Non-linear Models (1.5 h)
2. [Cluster Space with Mobility Pattern](https://github.com/brookefzy/pitaya/tree/main/ClusterSpacewithMobility) (2 h)
* Kmean and Fuzzy C-means
3. [Street Network](https://github.com/brookefzy/pitaya/tree/main/StreetNetwork) (1.5 h)
* Use osmnx to download road network
* Network analysis
4. [AI baby steps - NLP](https://github.com/brookefzy/pitaya/tree/main/BabyAI-NLP) (2 h)
* Word Frequency
* Word Embedding
* Prompt engineering
5. [AI baby steps - CV and deep learning](https://github.com/brookefzy/pitaya/tree/main/BabyAI-CV)  (2.5 h)
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
