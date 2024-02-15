# Job-Analytics-
# Job Analytics

This project is designed to scrape job data from the professional networking platform LinkedIn and analyze it to provide insights into job distribution, company details, and industry trends. It utilizes web scraping techniques with Python libraries such as BeautifulSoup and Selenium.

## Project Overview

The main goal of this project is to collect job data from LinkedIn, organize it into structured tables, and perform data analysis to generate insights for job seekers and recruiters. The project consists of the following components:

1. **Web Scraping**: The script uses Selenium to automate the process of logging into LinkedIn and scraping job listings. It collects information such as job title, company name, location, number of applicants, job nature, company size, and other relevant details.

2. **Data Collation**: The scraped data is collated into three tables: `jobs`, `company`, and `details`, as specified in the project requirements. These tables store information about job listings, companies, and job details, respectively.

3. **Data Analysis**: Once the database is populated with job data, the script performs various aggregations and generates insights from the data. It creates tables and visualizations to compare job distribution across different cities, industries, company sizes, and job levels.

## Getting Started

To use this project, follow these steps:

1. **Prerequisites**: Ensure you have Python installed on your system along with the required libraries (Selenium, BeautifulSoup, pandas).

2. **ChromeDriver**: Download the ChromeDriver executable and place it in the same directory as the script.

3. **LinkedIn Login**: Update the script with your LinkedIn login credentials (email and password).

4. **Run the Script**: Execute the Python script to start the web scraping process. Make sure you're logged into LinkedIn in the browser opened by the script.

5. **Data Analysis**: Once the scraping is complete, the script will generate CSV files containing the scraped data. You can then use these files for further analysis and insights generation.

## Data Analysis Insights

After scraping and collating the data, the script generates insights to help users better understand the job market. Some of the insights include:

- Comparison of job distribution across different cities and job levels.
- Analysis of job distribution by industry, highlighting the number of openings in various sectors.
- Comparison of job openings in companies of different sizes.
- Additional insights based on user requirements or preferences.

## Notes

- Ensure that you have more than 300 job listings available for scraping.
- All scraped job locations should be in India as per project requirements.
- Make sure you're logged into LinkedIn in the browser opened by the script to access job listings.

Feel free to customize the script and analysis based on your specific requirements and preferences.
