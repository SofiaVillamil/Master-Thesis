# Master-Thesis Instructions for the handelling of the Scripts
This is the complete guide to learning how to follow the order of the scripts, read before starting.

Important Note: The majority of the scripts require several days to gather all the data. Therefore, each data-scraping script will be configured to collect 10 observations to verify functionality without taking too long to display results. Additionally, all data sets, except for the first one (which is too large for GitHub), are saved in their respective folders in the case that you would like to check the complete data attained for each scrapping process. Additionally, the scripts at the end have a text to what is the next script will be.

Okey! So let's start.

1. The first folder you need to start with is the folder called "Scrapping Part 1". In there you will identify the first script you need to run that is called "Filtering code for the data_Part_1" This code is only to attain the base data set. You will need to follow the instructiong in that script getting the data from the link given and then running the script with the correct path to where the data set collected from keggel is. The code is set to save the filtered file in order to use it for the next script.

2. The next script is called "IMDb_Script_Part_2." In this script, you need to specify the correct path where the filtered dataset is saved and include your username to start the scraping process. As previously mentioned, all scraping scripts are configured to process 10 movies for verification purposes. However, if you want to examine the complete dataset, you need to look at the end of the script where the deactivated code for saving is located. This will show the name of the saved dataset, allowing you to identify and access the full data set you need to review.

3. The next script is called "BoxMojo_Variables_Scraping_Script_Part_3." In this script, you will need to input your user agent and run the code, which is already configured to scrape data for 10 movies. To review the complete dataset, look for the name in the deactivated code at the end of the script.

4. The next script is "Rotten Tomatoes variable scrapping_Part_4". In this script, you will need to input your user agent and run the code, which is already configured to scrape data for 10 movies. To review the complete dataset, look for the name in the deactivated code at the end of the script. This script marks the end of the first folder.

5. Now we go to the next folder called "Scrapping and Data Part 2". The first script will be "Generating Gen Ind Var_Part_1". This is not a scrapping script, its just the start of creating the first variables.

6. The next script we will go to will be "Data Cleaning_Part_2". This is another creationg and cleaning script.

7. The next script will be "Scrapping Rotten Romatoes selected movies_Part_3". Due to the complexity of this page URL's another instance of scrapping was needed. In this script the movies scrapped is set to 10 and you need to put your user agent.

8. The next script will be "Scrapping The Numbers selected movie_Part_4" this script involves scrapping for sepecific observations to reduce the amonts of Na's in the budget variable. Your user agent needs to be put here.

9. The next script is called "Data Cleaning_Part_5" an it is another organizing and cleaning script of the data.

10. The next script is "Scrapping TMDB selected movies_Part_6". Its the last scrapping script for the budget variable. It involves using an API. The steps to get it are in the script. This is the last script of this folder.

11. We now go to the next folder called "Modeling Part 3". The first script is "Creating the variables_Part_1".

12. The second script is "Creating the variable_Part_2" an its a scrapping script. You need to put your user name here.

13. Then we go to the next script called "Creating the variables_Part_3" its another organizing script to get to the pythong scripts.

14. The next script will be the Instagram Script_Part_4 python script. It is set to 10 movies,the user name needs to be put in. However, if you want to check the results. The complet scrapping results are located in the file Youtube and Instagram Data in the excel called "results_instagram_1"

15. The next script is the Youtube_Part_5 python script. It is set to 10 movies, you need to have selenium and set it up to run the code as it involves clicking and scrolling the page. The complete results are in the file Youtube and Instagram Data in the excel called "results_youtube_1". This is the final script for this file.

16. Now we continue to the next folder. Its called " Modelling Final Part 4". This scripts can be run in a matter of minutes. Does not involve hours and their respective data sets are in folders. The first script is called "Prepearing the variables_Part_1", then we have the "Model_Part_2" and finally the last script called "Extra Model with social media_Part_3".

This is the end of the manual. Good luck!






