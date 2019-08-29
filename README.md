# Unpacking the Nuances of London's Neighbourhood Change Gentrification Trajectories Codes

This Github repository comprises the Python codes used for undertaking data analysis as part of the research - 'Unpacking the Nuances of London's Neighbourhood Change Gentrification Trajectories'. The codes are presented in iPython notebook formats, and include both the inputs and outputs of the analysis.

As a relatively extensive workflow was adopted, for legibility and coherence, the iPython notebooks have been labelled based on the stage at which the data analysis was conducted. Hence, it is recommended that one views / uses the notebooks in sequence. A brief summary of each notebook and their contribution to the workflow is outlined below:
  > 1 Data Pre-processing for Scoring LSOAs
  >> Raw data had to be pre-processed prior to their utilisation as input variables to conduct the analysis. For this stage, 4 pairs of  neighbourhood attributes which were specifically chosen as proxies to quantify neighbourhood states were explored, cleaned and prepared for Principal Component Analysis (PCA). Further examination of the PCA outputs is done thereafter. 
  
  > 2 Scoring Analysis
  >> The outputs of the PCA, specifically the 1st Principal Component, was adopted as the Composite Index to score LSOAs in 2001 and 2011. This notebook incorporates the scripts used to analyse the scores for each LSOA and apply the pre-set criteria to determine whether a LSOA was to be considered as being in ascent, decline or stable between 2001 and 2011. 
  
  > 3 Analysis on states of LSOAs
  >> The next stage of the analysis entailed an in-depth investigation into the states of all LSOAs. This notebook consists the codes used to yield insights on which were the leading Local Authorities (LA) that had the greatest share of ascending and descending LSOAs.   
  
  > 4 Data Preparation for Clustering
  >> Similar to the 1st notebook, this notebook includes the Python scripts which were utilised to prepare raw data to be clustered in the following sections. Much wrangling had to be undertaken to ensure consistency between different datasets in order to ensure seamlessness in analysis downstream - this included steps to curate the datasets for varying rounds of clustering, etc. 
  
  > 5a Clustering Ascending LSOAs
  >> This notebook comprises codes that enabled data transformation and re-scaling on the curated input variables to obtain various dataset permutations that could be put through for deriving the optimal clusters. K-Means clustering was adopted as the clustering technique of choice to uncover the various typologies of neighbourhood ascent. 
  
  > 5b Clustering Gentrifying LSOAs
  >> Predominantly similar to the preceding stage, this notebook is composed of codes to transform, re-scale and cluster the input variables for understanding the gentrification typologies present. 
  
  > 6 Data Prep for Modelling
  >> Preparation had to be done on the entire range of raw data to ensure consistency between the datasets to be used for modelling and prediction. Thus, the notebook comprises code to re-name feature columns so that they are consistent across the board, re-arrange their sequences for intelligiblity and standardisation for comparability, etc. 
  
  > 7a Model & Predict Ascending LSOAs
  >> This stage entailed the training, tuning and evaluation of Machine Learning algorithms (i.e. Random Forest and AdaBoost) to model current trends and predict which LSOAs may potentially gentrify in future. 
  
  > 7b Model & Predict Gentrifying LSOAs
  >> Similar in procedure to the preceding stage, this notebook contained the codes that facilitated the model building process for modelling and predicting the gentrification typologies of gentrifying LSOAs. 
  
