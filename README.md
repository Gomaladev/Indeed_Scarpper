_**INDEED SCRAPPER WITH APIFY**_
    This repository contains a Python script for scraping job listings from Indeed using Apify. The script collects job details for specified parameters and exports the data into a CSV file.
**FEATURES**:
    Scrapes job listings based on specified criteria (job position, country, and location).
    Extracts job information, including job title, company name, salary, location, and page URL.
    Saves data in a CSV format for easy analysis and storage.
**USAGE**:
    **Initialize the ApifyClient**: Replace the placeholder API token in the script with my Apify API token
    **Specify Search Criteria**: Update the run_input dictionary to customize my search.
    **Run the Script**: Run the script to start scraping data. The results will be stored in job_listings.csv.
    **Output**: The job listings are saved in a CSV file with the following columns:
          Job Title
          Company
          Salary
          Location
          Page URL
**FILE STRUCTURE**:
    indeed_job_scraper.py: Main Python script for scraping job listings and saving them to a CSV file.
**TROBULESHOOTING**
    If you encounter a ModuleNotFoundError for apify_client, ensure that it is installed correctly by running:
    **Code**
        pip install apify-client
 **LICENSE**
    This project is licensed under the MIT License.   
