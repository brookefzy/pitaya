# Cluster metro stations with mobility records
## Backgrounds
In this session, we will use a research project as a case to show the basic usage of clustering algorithm in urban studies.
Transit-oriented-development (TOD) is a community development model. Time-variant variables, dynamic human activities throughout different times of the day and week matter in further unpacking the characteristics of TODs. Given that this aspect has been under-discussed in most previous TOD literature, this research provides an activity-based framework to classify commuter transit station areas by considering the degree of local vibrancy - the temporal visiting pattern of all points of interest (POIs) that fall within the station areas. We apply a two-step semi-unsupervised clustering algorithm to classify 4,290 station areas from 54 metropolitan areas across the U.S. This method produces 13 distinct station area types.
Figure below show the simple presentation of all the POIs considered in this study.
<p align="center">
<img src="../asset/graphics_rev-01.png" alt="all POIs used in this project" style="width:50%; border:0;">
</p>

Figure below show how we assign each POI to the catchment area of a TOD. These steps are beyond our exercise today.
<p align="center">
<img src="../asset/graphics_rev-02.png" alt="all POIs used in this project" style="width:50%; border:0;">
</p>

## Course content
1. Explain supervised learning and unsupervised learning in concept (5 minutes).
2. Explain KMean clustering in concept (5 minutes)
3. Compare the KMean and Fuzzy CMean (5 minutes)
3. Lab time: use real data to create TOD location clusters (1 hour).

## Goal
After this chapter, the student should be able to:
1. explain the differences between supervised learning and unsupervised learning
2. explain the basic logic behind Kmean algorithm
3. use Kmean and Fuzzy Cmean in research
4. understand elbow method

## Readings
```
@software{dias2019fuzzy,
  author       = {Madson Luiz Dantas Dias},
  title        = {fuzzy-c-means: An implementation of Fuzzy $C$-means clustering algorithm.},
  month        = may,
  year         = 2019,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.3066222},
  url          = {https://git.io/fuzzy-c-means}
}
@article{fan2021rhythm,
  title={Rhythm of Transit Stations-Uncovering the Activity-Travel Dynamics of Transit-Oriented Development in the US},
  author={Fan, Zhuangyuan and Zhang, Fan and Loo, Becky PY},
  journal={IEEE Transactions on Intelligent Transportation Systems},
  volume={23},
  number={8},
  pages={12503--12517},
  year={2021},
  publisher={IEEE}
}
```
* Web material [Link](https://towardsdatascience.com/unsupervised-learning-and-data-clustering-eeecb78b422a)