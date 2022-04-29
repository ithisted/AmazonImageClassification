# Amazon Image Classification Project

This folder contains the work for an Amazon Satellite Image classification project. The goal of the machine learning model is to identify various types of atmospheric and land cover present in satelite images taken from the Amazon rainforest. The data was extracted from Kaggle: 

[Kaggle Amazon Satellite Image Data](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space/)  

## [Table of Contents](#table-of-contents)

 1. Docs  
    - [Final Report](https://github.com/ithisted/AmazonImageClassification/blob/master/docs/Capstone%202%20-%20Project%20Report%20Final.pdf)  
   Report containing data wrangling, exploratory data analysis, and machine learning explanation for the project
    - [Presentation](https://github.com/ithisted/AmazonImageClassification/blob/master/docs/Amazon%20Rainforest%20Image%20Classification%20Presentation.pdf)  
    Powerpoint Presentation containing complete summary and findings for the project.
2. Notebooks  
The notebooks below contain the data analysis and ML code used for this project. Due to the intensive computing requirements for running the neural networks, the ML models were broken down into separate notebooks so they could be run in parallel in a high performance cloud computing environment.
   - [Exploratory Data Analysis](https://github.com/ithisted/AmazonImageClassification/blob/master/notebooks/1_PlanetAmazonImageClassification%20-%20EDA.ipynb)
   - [Machine Learning - Random Forest, Baseline CNN and CNN Model variations](https://github.com/ithisted/AmazonImageClassification/blob/master/notebooks/2_PlanetAmazonImageClassification-Machine%20Learning.ipynb)
   - [Machine Learning - VGG16 transfer Model](https://github.com/ithisted/AmazonImageClassification/blob/master/notebooks/3_PlanetAmazonImageClassification-Machine%20Learning%20-%20Transfer.ipynb)
   - [Machine Learning - CNN w/ Upsampled Blow Down Model](https://github.com/ithisted/AmazonImageClassification/blob/master/notebooks/4_PlanetAmazonImageClassification-Machine%20Learning%20-%20Upsampling.ipynb)
   - [Machine Learning - Model Comparison](https://github.com/ithisted/AmazonImageClassification/blob/master/notebooks/https://github.com/ithisted/AmazonImageClassification/blob/master/notebooks/5_PlanetAmazonImageClassification-Machine%20Learning-%20Model%20Comparison.ipynb)
   - [CNN Filter Visualization](https://github.com/ithisted/AmazonImageClassification/blob/master/notebooks/6%20-%20ConvNetFilterVisualization.ipynb)

3. ML Models 
   - [H5 and TF files for neural networks](https://github.com/ithisted/AmazonImageClassification/tree/master/models/)
