# Simple Tutorials For Urban Science
This is a simple tutorials for students in urban studies to get a taste of machine learning tools.

## Installation
```
conda create -n piyata python=3.10
conda activate piyata
conda install pip
pip install -r requirements.txt
```
## Other requiremnets
1. Register a gmail account
2. Register to get an openai API key (optional)
3. VPN set up if a network blocker exists.

## Chapter
0. [Overview of ML/AI in urban studies](https://docs.google.com/presentation/d/1Qe5HpvrHvt2qUsnCyHGmEX-InD7OgYgSMav3nXh15ec/edit?usp=sharing)
1. [Housing Price Predictor](https://github.com/brookefzy/pitaya/tree/main/HousingPricePredictor)
* Data Exploration and Data Cleaning
* Linear Models
* Non-linear Models
2. [Cluster Space with Mobility Pattern](https://github.com/brookefzy/pitaya/tree/main/ClusterSpacewithMobility)
* Kmean and Fuzzy Cmeans
3. [Street Network](https://github.com/brookefzy/pitaya/tree/main/StreetNetwork)
* Use osmnx to download road network
* Network analysis
4. [AI baby steps - NLP](https://github.com/brookefzy/pitaya/tree/main/BabyAI-NLP)
* Word Frequency
* Prompt engineering
5. [AI baby steps - CV and deep learning](https://github.com/brookefzy/pitaya/tree/main/BabyAI-CV)
* OpenCV basics
* Image segmentation
* Object detection and tracking
* Unified model
* Data labeling tools

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
