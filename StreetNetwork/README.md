# Intro to graph of streets
## Backgrounds
The street network is one of the core assets in Urban analysis. A large amount of research relies on network analysis.

## Installation
```
conda create -n pitaya_spatial python=3.10
conda activate pitaya_spatial
conda install pip
pip install geopandas GDAL osmnx seaborn matplotlib
```
## Goal
1. Use OSMnx package to download street network for a neighborhood
2. Use OSMnx package to download POI
3. Understand the basic terms used in Graph theory
4. Understand centrality basics
5. We will demo one research project using the street network to understand social segregation at street level [Interactive module](http://greatstreets.mit.edu/html/maps.html)

## Reading
```
@article{boeing2017osmnx,
  title={OSMnx: New methods for acquiring, constructing, analyzing, and visualizing complex street networks},
  author={Boeing, Geoff},
  journal={Computers, Environment and Urban Systems},
  volume={65},
  pages={126--139},
  year={2017},
  publisher={Elsevier}
}

@article{fan2023diversity,
  title={Diversity beyond density: Experienced social mixing of urban streets},
  author={Fan, Zhuangyuan and Su, Tianyu and Sun, Maoran and Noyman, Ariel and Zhang, Fan and Pentland, Alex ‘Sandy’ and Moro, Esteban},
  journal={PNAS nexus},
  volume={2},
  number={4},
  pages={pgad077},
  year={2023},
  publisher={Oxford University Press US}
}
@article{xue2022quantifying,
  title={Quantifying the spatial homogeneity of urban road networks via graph neural networks},
  author={Xue, Jiawei and Jiang, Nan and Liang, Senwei and Pang, Qiyuan and Yabe, Takahiro and Ukkusuri, Satish V and Ma, Jianzhu},
  journal={Nature Machine Intelligence},
  volume={4},
  number={3},
  pages={246--257},
  year={2022},
  publisher={Nature Publishing Group UK London}
}
```
