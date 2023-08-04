# DSM2DTM: Swiss Public Dataset for Digital Terrain Model Generation
DSM2DTM is a research project conducted by the Photogrammetry and Image analysis department at German Aerospace Center (DLR).
This repository contains dataset we used for training, validation and testing in our pablication "DSM2DTM: An End-to-End Deep Learning Approach for Digital Terrain Model Generation", ISPRS Geospatial Week 2023. Originally, the data is provided by the Federal Office of Topography of Switzerland and is freely available on the [Swisstopo Portal](https://www.swisstopo.admin.ch/en/geodata.html).

<p align="center">
  <img src="https://github.com/KseniaBittner/DSM2DTM/blob/main/img/FribourgMountain_DSM.jpg" alt>
  <em>Sample of area from our Fribourg test dataset illustrated input DSM</em>
</p>

<p align="center">
  <img src="https://github.com/KseniaBittner/DSM2DTM/blob/main/img/FribourgMountain_EffNet.jpg" alt>
  <em>Sample of area from our Fribourg test dataset illustrated resulted DTM</em>
</p>

+ Paper PDF: DSM2DTM: An End-to-End Deep Learning Approach for Digital Terrain Model Generation

+ Authors: Ksenia Bittner, Stefano Zorzi, Thomas Krauß, Pablo d’Angelo

## Getting started with dataset

The dataset folder provides collections of links to DSM and DTM images for four selected Cantons (Zuerich, St. Gallen, Vaud and Fribourg), packed in *.csv files. 

#### Training and validation
We used the data of the Cantons of Zuerich, St. Gallen, and Vaud for training and validation. The data for each Canton is provided in 2000×2000 px image patches out of which we have selected only eight random non-overlap samples of size 256×256 px. We took 10 % of images from each of those Cantons to perform a validation phase. The exact distribution of images and selected patches we used for training and validation is listed in corresponding train.txt and val.txt files for each Canton. 

#### Testing

The Canton of Fribourg was used for testing. The collection of selected images for both DSM and DTM is listed in dsm_test.txt and dgm_test.txt, respectively. 

## BibTeX citation
If you use this dataset to compare your findings with ours, please consider citing the following publication:
