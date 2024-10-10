For detail information, please read [Bachelor_Thesis_Chenhao_Huang_.pdf](https://github.com/HuangChenhao/3DCities_Evaluating_3D_building_reconstruction_tools_using_point_clouds/blob/98ec96cf488b6bd937f08f1fcfeb1738162cb16e/Bachelor_Thesis_Chenhao_Huang_.pdf)
# LoD1-TUM
LoD1 model of TUM main campus was done based on software from TU-Delft [3dfier](http://tudelft3d.github.io/3dfier/)
It use the ALS(airborne laser scanning) point cloud and buildings' footprint.
* AlS was downloaded from Bavarian State Mapping Agency via [GeoportalBayern](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=laserdaten)
* Buildings' footprint was converted from LoD2 model from [GeoportalBayern](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=laserdaten) by using [FME](https://fme.safe.com/)
* MLS(mobile laser scanning) point cloud was also used, but can not generate LoD1 model
* ALS+MLS combined point cloud was also used, but did not make results better
# LoD2-TUM
LoD2 model of TUM main campus was done based on software also from TU-Delft [Polyfit](https://3d.bk.tudelft.nl/liangliang/publications/2017/polyfit/polyfit.html)
It use ALS/MLS/ALS+MLS point clouds to compare the impact of different types of data on the reconstruction results
* MlS was given by [3D Mapping Solutions GmbH](https://www.3d-mapping.de/ueber-uns/3d-mapping-solutions-gmbh/)
* Georeference process was done inside CloudCompare
* Three different types of point clouds(ALS/MLS/ALS+MLS) data are used for reconstruction
* ALS+MLS shows obvious advantages
* Hausdorff-Distance is used to detect the quality of the reconstructed model and compared with the LoD2 model of [GeoportalBayern](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=laserdaten)
