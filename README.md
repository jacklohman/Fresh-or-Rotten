README

FRESH OR ROTTEN

By: Bryce Stepanuik and Jack Lohman


Project Statement: 

The purpose of this project is to use critic sentiment in combination with film data to create a model capable of predicting Rotten Tomatoes critic scores, also known as the "Tomatometer." 


Motivation:

This project was created for Denison Data Analytics 352 class, taught by Dr. Alexandre Scarcioffolo. Creators Bryce Stepanuik and Jack Lohman set out to use Rotten Tomatoes critic sentiment and film data to model and predict the critic score or "Tomatometer" score of future releases. With an interest in who--or what--shapes critic reviews, this project was undertaken using publicly available data from Kaggle.com, (more information on the data below) and cleaned for use. The goal of the creators was to create a model accurate enough to compete with other conventional forecasts.  

Build Status:

The project, overseen by Dr. Scarcioffolo, reached its conclusion in December 2024. Further ideas, additions, revisions, and recommendations are welcome. 


Requirements:

Required hardware includes RStudio version 2024.09.0+375, with the following packages: tidyverse, kableExtra, Random Forest, rpart, caret, and plotly


Data Files:

There were two original datasets, one movie information up to the year 2020, and another containing movie review information up to the year 2020. These datasets are parsed down within the r document, removing variables that do not contribute to analysis. The film dataset is named “rotten_tomatoes_movies.csv,” which can be found in the main file along with its counterpart "rotten_tomatoes_critic_reviews.csv." The datasets are linked by the column "rotten_tomatoes_link," so that each review can be matched to a title. See the metadata file for further information on the datasets. 


Code Files:

	Fresh_or_Rotten.rmd:
	The main coding file, used for data cleaning, and statistical analysis, machine 		learning, and all visualizations

 
How to Use:

	Fresh_or_Rotten.rmd:
	*Open in RStudio, making sure that source files are in proper directory
	*Import packages in file header
	*Navigate to the "Run" menu and run all to see output
	
		Score Prediction Function:
		function name: run_rotten_tomatoes_prediction()
		*Navigate to the bottom of the document, or click "Score Prediction Function" in 		the glossary
		*In the code block containing the function, input your values in accordance with 		the variable types listed. 
		*Call the function below to run, and output a score

 
Contribute:

Any contributions with the intention of genuine improvement on the base product is permitted and encouraged. 


License:
	
This data was downloaded off of Kaggle.com and is listed as public domain. 
