# Tools for the analysis of movement data

A collection of open source projects in the upcoming field of **movement data science** (ordered by main language and first GitHub commit date).

**Note**: this repository only tracks projects related to movement data science. A general survey of spatiotemporal tools is provided by [Alam et al. 2021].



## Python

- [Stone Soup](https://github.com/dstl/Stone-Soup): A software project to provide the target tracking community with a framework for the development and testing of tracking algorithms. (first GH commit: 2017-07-23) [Hiscocks et al. 2023]
- [traffic](https://github.com/xoolive/traffic): A toolbox for processing and analysing air traffic data. (first GH commit: 2018-02-08)
- [PyMove](https://github.com/InsightLab/PyMove): Python library to simplify queries and visualization of trajectories and other spatial-temporal data. (first GH commit: 2018-09-09) [Sanches 2019],[Oliveira 2019]
- [MovingPandas](https://github.com/anitagraser/movingpandas): Trajectory classes and functions built on top of GeoPandas. (first GH commit: 2018-12-16) [Graser 2019]
- [Traja](https://github.com/traja-team/traja): Python tools for 2D spatial trajectory data. (first GH commit: 2019-01-13)
- [trackintel](https://github.com/mie-lab/trackintel): a framework for spatio-temporal analysis of movement trajectory and mobility data. (first GH commit: 2019-01-20) [Martin 2023]
- [scikit-mobility](https://github.com/scikit-mobility/scikit-mobility): Mobility analysis in Python. (first GH commit: 2019-04-28) [Pappalardo et al. 2019]
- [MovinPy](https://github.com/DataStories-UniPi/MovinPy): Process and analyze mobility data. (first GH commit: 2020-07-23)
- [ST-Visions](https://github.com/DataStories-UniPi/ST-Visions): A Python-based library for interactive spatio-temporal data visualization. (first GH commit: 2020-07-26)
- [HuMobi](https://github.com/SmolakK/HuMobi): a library for human mobility analyses implemented in Python. (first GH commit: 2021-06-02) [Smolak et al. 2021]
- [PTRAIL](https://github.com/YakshHaranwala/PTRAIL): parallel computation library for Mobility Data Preprocessing and feature generation. (first GH commit: 2021-05-31) [Haidri et al. 2022]
- [TransBigData](https://github.com/ni1o1/transbigdata): transportation spatio-temporal big data processing, analysis and visualization. (first GH commit: 2021-10-17) [Yu & Yuan 2022]
- [Mobilkit](https://github.com/mindearth/mobilkit): A Python Toolkit for Urban Resilience and Disaster Risk Management Analytics using High Frequency Human Mobility Data. (first GH commit: 2021-07-25) [Ubaldi et al. 2024]


[![Star History Chart](https://api.star-history.com/svg?repos=movingpandas/movingpandas,scikit-mobility/scikit-mobility,InsightLab/PyMove,traja-team/traja,mie-lab/trackintel,MobilityDB/MobilityDB,ni1o1/transbigdata,xoolive/traffic&type=Date)](https://star-history.com/#movingpandas/movingpandas&scikit-mobility/scikit-mobility&InsightLab/PyMove&traja-team/traja&mie-lab/trackintel&MobilityDB/MobilityDB&ni1o1/transbigdata&xoolive/traffic&Date)


## C++ 

- [Tracktable](https://github.com/sandialabs/tracktable) (with Python API): moving object trajectory analysis in C++ and Python. (first GH commit: 2016-04-10)
- [MEOS](https://github.com/adonmo/meos) (with Python API): Mobility Engine, Open Source is a C++ library which makes it easy to work with temporal and spatio-temporal data. (first GH commit: 2020-04-19)
- [MoveTK](https://github.com/heremaps/movetk): a library for computational movement analysis written in C++. (first GH commit: 2020-09-09)

## R

**Review paper:** [Joo, R., Boone, M. E., Clay, T. A., Patrick, S. C., Clusella‐Trullas, S., & Basille, M. (2020). Navigating through the **R packages** for movement. Journal of Animal Ecology, 89(1), 248-267.](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/1365-2656.13116)

- [moveVis](https://github.com/16eagle/moveVis) provides tools to visualize movement data (e.g. from GPS tracking) and temporal changes of environmental data (e.g. from remote sensing) by creating video animations. It works with move and raster class inputs and turns them into ggplot2 frames. (first GH commit: 2017-05-14)

## Databases
- [MobilityDB](https://github.com/MobilityDB/MobilityDB): A geospatial trajectory data management & analysis platform, built on PostgreSQL and PostGIS. (first GH commit: 2019-02-17)
    - [mobilitydb-python](https://github.com/MobilityDB/MobilityDB-python/): Python driver for MobilityDB.
    - [mobilitydb-sqlalchemy](https://github.com/adonmo/mobilitydb-sqlalchemy): MobilityDB extensions for SQLAlchemy.

## Platforms

- [MoveApps](https://www.moveapps.org): free analysis platform for animal tracking data hosted by the Max Planck Institute of Animal Behavior

## Distributed computing 

- [Apache Sedona](https://sedona.apache.org) (formerly known as GeoSpark) has announced plans to provide trajectory support at ApacheCon 2020.

Other libraries, that are cited in the literature but are not available as open source, include: TrajSpark [Zhang et al. 2017], DITA [Shang et al. 2018]

## Standards

https://www.ogc.org/standard/movingfeatures/


## References

- Alam, M. M., Torgo, L., & Bifet, A. (2021). A Survey on Spatio-temporal Data Analytics Systems. arXiv preprint arXiv:2103.09883. https://arxiv.org/abs/2103.09883
- Graser, A. (2019). MovingPandas: Efficient Structures for Movement Data in Python. GI_Forum ‒ Journal of Geographic Information Science 2019, 1-2019, 54-68. https://doi.org/10.1553/giscience2019_01_s54.
- Haidri, S., Haranwala, Y. J., Bogorny, V., Renso, C., da Fonseca, V. P., & Soares, A. (2022). PTRAIL—A python package for parallel trajectory data preprocessing. SoftwareX, 19, 101176.
- Hiscocks, S., Barr, J., Perree, N., Wright, J., Pritchett, H., Rosoman, O., ... & Oakes, B. (2023). Stone Soup: No longer just an appetiser. In 2023 26th International Conference on Information Fusion (FUSION) (pp. 1-8). IEEE.
- Joo, R., Boone, M. E., Clay, T. A., Patrick, S. C., Clusella‐Trullas, S., & Basille, M. (2020). Navigating through the **R packages** for movement. Journal of Animal Ecology, 89(1), 248-267. https://doi.org/10.1111/1365-2656.13116
- Martin, H., Hong, Y., Wiedemann, N., Bucher, D., & Raubal, M. (2023). Trackintel: An open-source Python library for human mobility analysis. Computers, Environment and Urban Systems, 101, 101938. https://doi.org/10.1016/j.compenvurbsys.2023.101938
- Oliveira, A. F. D. (2019). Uma arquitetura e implementação do módulo de visualização para biblioteca PyMove.
- Pappalardo, L., Simini, F., Barlacchi, G., & Pellungrini, R. (2019). scikit-mobility: A Python library for the analysis, generation and risk assessment of mobility data. arXiv preprint arXiv:1907.07062. https://arxiv.org/abs/1907.07062
- Sanches, A. D. J. A. M. (2019). Uma arquitetura e implementação do módulo de pré-processamento para biblioteca pymove.
- Shang, Z., Li, G., & Bao, Z. (2018). DITA: Distributed In-Memory Trajectory Analytics. In SIGMOD/PODS 18: 2018 International Conference on Management of Data. ACM. https://doi.org/10.1145/3183713.3183743
- Smolak, K., Siła-Nowicka, K., Delvenne, J. C., Wierzbiński, M., & Rohm, W. (2021). The impact of human mobility data scales and processing on movement predictability. Scientific Reports, 11(1), 1-10.
- Ubaldi, E., Yabe, T., Jones, N., Khan, M.F., Feliciotti, A., Di Clemente, R., Ukkusuri, S.V., & Strano, E. (2024) Mobilkit: A Python Toolkit for Urban Resilience and Disaster Risk Management Analytics using High Frequency Human Mobility Data, Journal of Open Source Software, 9, 95, 5201. Doi: 10.21105/joss.05201
- Yu, Q., & Yuan, J. (2022). TransBigData: A Python package for transportation spatio-temporal big data processing, analysis and visualization. Journal of Open Source Software, 7(71), 4021.
- Zhang, Z., Jin, C., Mao, J., Yang, X., & Zhou, A. (2017). TrajSpark: A Scalable and Efficient In-Memory Management System for Big Trajectory Data. In Asia-Pacific Web (APWeb) and Web-Age Information Management (WAIM) Joint Conference on Web and Big Data (pp. 11-26). Springer, Cham. https://doi.org/10.1007/978-3-319-63579-8_2

