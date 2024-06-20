# Master-Thesis 
## Instructions for Handling the Scripts

This is the complete guide to learning how to follow the order of the scripts, read before starting.

**Important Note:** The majority of the scripts require several days to gather all the data. Therefore, each data-scraping script will be configured to collect 10 observations to verify functionality without taking too long to display results. Additionally, all data sets, except for the first one (which is too large for GitHub), are saved in their respective folders in case you would like to check the complete data attained for each scraping process. Additionally, the scripts at the end have a text indicating what the next script will be.

Okay! So let's start. 

1. Once the zip is downloaded, open the project that is set up in it. It's called "Master Thesis".

2. The first folder you need to start with is the folder called "Scraping Part 1." In there, you will identify the first script you need to run, which is called "Filtering code for the data_Part_1." This code is only to attain the base dataset. You will need to follow the instructions in that script, getting the data from the link given, and then running the script with the correct path to where the dataset collected from Kaggle is. The code is set to save the filtered file in order to use it for the next script.

3. The next script is called "IMDb_Script_Part_2." In this script, you need to specify the correct path where the filtered dataset is saved and include your username to start the scraping process. As previously mentioned, all scraping scripts are configured to process 10 movies for verification purposes. However, if you want to examine the complete dataset, you need to look at the end of the script where the deactivated code for saving is located. This will show the name of the saved dataset, allowing you to identify and access the full dataset you need to review.

4. The next script is called "BoxMojo_Variables_Scraping_Script_Part_3." In this script, you will need to input your user agent and run the code, which is already configured to scrape data for 10 movies. To review the complete dataset, look for the name in the deactivated code at the end of the script.

5. The next script is "Rotten Tomatoes variable scraping_Part_4." In this script, you will need to input your user agent and run the code, which is already configured to scrape data for 10 movies. To review the complete dataset, look for the name in the deactivated code at the end of the script. This script marks the end of the first folder.

6. Now we go to the next folder called "Scraping and Data Part 2." The first script will be "Generating Gen Ind Var_Part_1." This is not a scraping script, it’s just the start of creating the first variables.

7. The next script we will go to will be "Data Cleaning_Part_2." This is another creation and cleaning script.

8. The next script will be "Scraping Rotten Tomatoes selected movies_Part_3." Due to the complexity of this page's URLs, another instance of scraping was needed. In this script, the movies scraped are set to 10, and you need to input your user agent.

9. The next script will be "Scraping The Numbers selected movie_Part_4." This script involves scraping for specific observations to reduce the amounts of Na's in the budget variable. Your user agent needs to be input here.

10. The next script is called "Data Cleaning_Part_5," and it is another organizing and cleaning script for the data.

11. The next script is "Scraping TMDB selected movies_Part_6." It’s the last scraping script for the budget variable. It involves using an API. The steps to get it are in the script. This is the last script of this folder.

12. We now go to the next folder called "Modeling Part 3." The first script is "Creating the variables_Part_1."

13. The second script is "Creating the variable_Part_2," and it’s a scraping script. You need to input your username here.

14. Then we go to the next script called "Creating the variables_Part_3." It’s another organizing script to get to the Python scripts.

15. The next script will be the Instagram Script_Part_4 Python script. It is set to 10 movies, and the username needs to be input. However, if you want to check the results, the complete scraping results are located in the file "Youtube and Instagram Data" in the Excel file called "results_instagram_1."

16. The next script is the Youtube_Part_5 Python script. It is set to 10 movies. You need to have Selenium and set it up to run the code as it involves clicking and scrolling the page. The complete results are in the file "Youtube and Instagram Data" in the Excel file called "results_youtube_1." This is the final script for this file.

17. Now we continue to the next folder. It’s called "Modeling Final Part 4." These scripts can be run in a matter of minutes. They do not involve hours, and their respective datasets are in folders. The first script is called "Preparing the variables_Part_1," then we have the "Model_Part_2," and finally, the last script called "Extra Model with social media_Part_3."

This is the end of the manual. Good luck!





