##################################################################### 

**README**

This file gives a description of all files uploaded for the final project of BMKG

The custom ontology developed in this report can be found at the following link:

https://github.com/tomdooney95/internetuse_socioecodevkg/tree/KG 

##################################################################### 

##Folder: Original Datasets

A folder containing the original datasets downloaded from the internet. 

Includes csv files for CPI, Geonames, EDI, GDP Per Capita, GDP Per Capita Growth (not used in investigation), Health Expenditure per capita, Internet Usage, HDI, PSI, Unemployment.

**Please note that anywhere only GDP is referenced, this actually corresponds to GDP Per Capita. Normal GDP was not used in the investigation.


##################################################################### 

##Folder: Processed Datasets

A folder containing processed csv files used in mappings to RDF. All datasets are the same as referenced above

##################################################################### 

##Folder: Mappings Files

A folder containing 5 mapping files corresponding to Worldbank data (bar unemployment and PSI), Unemployment Data (Worldbank), United Nations Data (HDI, EDI), Geonames, and finally one for both CPI (Transparency International) and PSI (Worldbank)


##################################################################### 

##Folder: Triples Files

A folder containing N-Triples files corresponding to the mappings referenced above. 

An extra triples file; average_triples.nt, consists of handcrafted triples (using Reg. Expression) for average values of variables considered in the project for each year


##################################################################### 

##Folder: LimesLinks+xml

A folder containing the limes configuration files for datasets without ISO3 codes; CPI, EDI and HDI.

This folder also contains accepted and review files resulting from LIMES


##################################################################### 

##Folder: SPARQL Data

Contains two folders; All_Countries+allvariables, which contains data for each year for all countries and Developing which contains similar data for developing countries only. This data was generated from SPARQL queries.


##################################################################### 

##Folder: Cases

A folder containing datasets for each country considered in the case study, with four files for each country, one for 2000-2015, one for 2001 (As PSI was not available in this year), one for 2016 (CPI only available until 2015 and finally one for 2017(Health expenditure only available until 2016.


##################################################################### 

##Folder: Cases(Processed)

A folder containing datasets  which are compilations of each of the 4 datasets described above into one dataset for each country


##################################################################### 

##Folder: Python Files

Folder contains two Python scrips for calculating average slopes and intercepts over 17 years (2000-2017).

Also contains three other folders

	##Folder: All_Countries+Data
		Contains processed data for all countries (removing zero values) used for statistical analysis 		and Python scripts corresponding to individual years where all countries were analysed. These  		scripts contain plots, correlation calculations, and linear model coefficients computed. Also 		observed is second order polynomial fits to the data that were not used in the investigation. 		Please also note that GDP Per Capita Growth was not used in the investigation

	##Folder: Developing(all variables)
		Contains processed data for developing countries (removing zero values) used for statistical 		analysis and Python 	scripts corresponding to individual years where all countries were 		analysed. These  scripts contain plots, correlation calculations, and linear model 		coefficients computed. Also observed is second order polynomial fits to the data that were not 		used in the investigation. Please also note that GDP Per Capita Growth was not used in the 		investigation

	##Folder: Case Studies
		Contains processed data for case studies considered in the investigation (removing zero 		values) used for statistical 	analysis and Python 	scripts corresponding to 12 different countries 		investigated from 2000-2017. These  scripts contain plots, correlation calculations, and linear 		model coefficients computed. Please also note that GDP Per Capita Growth was not used in 		the investigation


##################################################################### 


##File: SPARQLQueries

A text file containing some of the queries used in the investigation


##################################################################### 

##File:Tom_Dooney(6230256)_Final_Report.pdf

A final report detailing the research carried out for BMKG Final Project

