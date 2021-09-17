# Phase 1 Project
   ### Chris O'Malley
   ### Mustafa Furkan Kolanci
   ### Andrew Schmeck   
   
   
# Project Overview
   ## Business Understanding
   Microsoft the multinational tech company that already has a streaming service called Microsoft Movies and TV would like to leverage their position by starting a movie studio. Competetitors like Amazon and Netflix have already done so to the tune of billions of dollars. Microsoft would like to gain marketshare and create a sustainable and profitable studio.
   
   ## Data Understanding
   With profitibility as the target variable we were interested any datasets that included financial information such as budget and revenue. We were also interested in features that correlate with profitibity such as genre, directors, and studio. 
   
   ### Source and Descriptions of Data
   We were able to collect studio information from Box Office Mojo. We ingested unique identifiers for directors and titles in relationship to genre from IMDB. Most importantly we extracted production cost and revenue from The Numbers.   
   
   ## Data Preparation
   Aggregated multiple dataframes and resolved merging conflicts by correcting entry formating issues or in few cases dropping unusable/missing/irrelevant data.
   
   
   ## Data Analysis
   By combing data for revenue and production cost we were able to formulate profit margins. We then ran genre, directors, and studio against profitibilty to determine the top 10 candidates in each category for our recommendations.
   
   
   ## Plots
   Through plotting Average Profit Margin against Genres, Directors and Studio we found the top candidate of each feature to be Comedy/Family, Kyle Balda and Lionsgate Studios.
   
   
   ## Conclusion
   Our conclusions were Comedy/Family as a genre, Kyle Balda as a leading and profitable director in that genre, and Lionsgate Studios as a suitable choice for a potential partnership or acquisition.


### student.ipynb - Jupyter Notebook Project Submission located in Main Branch.
### data  - Unzipped dataframes folder located on Main Branch.
### presentation.pdf - Presentation as PDF located on Main Branch.

