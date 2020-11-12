# Acupuncture for chronic headache in primary care: large, pragmatic, randomised trial
### Andrew J Vickers, Rebecca W Rees, Catherine E Zollman, Rob McCarney, Claire Smith, Nadia Ellis, Peter Fisher, Robbert Van Haselen

## This repository serves as a means to distribute the raw data, code, and research to researchers, in a respository which can be downloaded and contributed to. 

## I. Contents

- README.md: An index for repository contents
- Documentation Folder: 
	- Acupuncture Final Published Paper
	- SF-36 Data Questionnaire where 
- Images: Images populating the Jupyter Notebook
- Data: 
	- 13063_2006_152_MOESM1_ESM.xls Clinical Trials input data
	- acupuncture_analysis_input Output from script 1, which will be the input for Script 2, the analysis file.
- Notebook Scripts

	- Script 1: Data Inspection and Cleaning 
		- Introduces the research 
		- Names hypotheses
		- Imports python libraries
		- Inspects data input
		- Calculates the amounts of null data
		- Summarizes statistics for key features
		- Filters the data 
		- Outputs processed data to excel

	- Script 2: 
		- Imports libraries
		- Reads in data from Script 1
		- Inspects data
		- Names hypothesis: There is a stastically significant difference in the slef-reported headache relief from those who receive acupuncture treatment vs those who don't.
		- Separates populations into treatment and control groups
		- Visualizes the distribution of groups using PyPlot
		- Runs Fisher's T Test to calculate the statistical significance of the groups. 
		- Repeats the hypothesis test on a non-normally distributed variable (The number of sick days taken per year)
		
- NERT Papers
	- Not relevant to Acupuncture Paper, examples of some of the research which could be distributed in this format. 