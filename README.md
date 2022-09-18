# Hong-Kong-s-River-dataset-cleaning
The repository includes the dataset used in (Wang et. al, 2022)'s research paper on real time monitoring of water quality parameters. The dataset includes data from 2013 - 2018

## Crucial Water Quality Parameters in literature
Based on occurrence frequencies, the top-10 critical parameters consistof three physical and seven chemical parameters. The physical parameters include temperature, electrical conductivity (EC), and total suspended solids (TSS). Seven chemical parameters are frequently emphasized in a large body of literature, including dissolved oxygen (DO), NO3-N, PO4, NO2-N, pH, NH3-N, and BOD5 (5-day biological oxygen demand). Total nitrogen (TN) was classified into its main forms: NH3-N, NO3-N, and NO2-N. Total phosphorus (TP) can be dividedinto dissolved phosphorus (DP) and particulate phosphorus (PP).

## Objectives of the research paper
1) Identify crucial water quality parameters that affect
freshwater biodiversity.
2) Identify those water quality parameters that can be measured with available IoT sensors and develop an IoT system to measure these parameters simultaneously.
3) Develop artificial intelligence (AI) models to estimate parameters that cannot be measured by current IoT sensors using IoT-measurable parameters, based on a large
historical water quality monitoring database.
4) Evaluate the AI models using a case study.

## Algorithms used to estimate IoT unmesaurable parameters
1) GRNN
2) MPR

## Dataset
Includes the dataset used in (Wang et. al, 2022)'s research paper on real time monitoring of water quality parameters. The dataset includes data from 2013 - 2018. Separate files are provided in the repo. These .csv files are available at: https://data.gov.hk/en-data/dataset/hk-epd-riverteam-river-water-quality-historical-data-en.

### Cleaning
The dataset is cleaned and the 10 crucial parameters listed in (Wang et. al, 2022) are extracted. We can add more .csv files from the website mentioned above. The dataset can now be used to train models for the estimation of water quality parameters. (final_data.csv)  
