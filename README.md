This Project is a continuation to the scraper fot Linkedin Job Postings, aimed to cleanup, normalize and analyze the data.

### Running

## R script
1. Using the Job Posting CSV file we first need to run the R script to cleanup - fill, remove NAs and normalize categorical variables.
2. The script also uses segmentation and classificaion of words from description into individual words and extract skills.
3. We also use a similarity check to identify the Job Market sector based on the title and finally save it into an Excel file

## Tableau Prep Builder
1. Load the csv file generated in R into Tableau prep builder to split and pivot skills listed for a job into multiple table entries
2. Split and store the csv into multiple sheets/tables for better ease of use in Tableau

## Tableau
1. Using the cleaned up data tables we created dashboards for analysis that the user can make use of.
