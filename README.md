# Amazon Web Scraper
## Overview
This Python script serves as an Amazon web scraper designed to extract product information, specifically tailored for tracking the price of a selected item. The project utilizes the BeautifulSoup library for web scraping and incorporates functionality to store the data in a CSV file. Additionally, the script includes an option to set up automated periodic price checks and email notifications when the price drops below a specified threshold.

## Features
* Web Scraping: The script fetches data from a specified Amazon product page, extracting details such as the product title and current price.
* Data Storage: The collected data is organized and stored in a CSV file named "AmazonWebScraperDataset.csv" for easy tracking and analysis.
* Automated Price Checks: The script includes a function, check_price(), that can be scheduled to run at regular intervals, providing an automated way to monitor price changes over time.
* Email Notification: An optional feature allows the user to receive email notifications when the price drops below a specified level. The send_mail() function can be customized with your email credentials and desired price threshold.

## How to Use
1. Installation:

* Make sure you have the required libraries installed, including BeautifulSoup, requests, pandas, and smtplib.

2. Configuration:

* Adjust the 'URL' variable to the Amazon product page of interest.
* Customize the 'send_mail()' function with your email credentials and set the desired price threshold.

3. Run the Script:

* Execute the script to initiate the web scraping process. The collected data will be stored in the CSV file.

4. Automate Price Checks (Optional):

* Uncomment the relevant section in the script to enable automated price checks at specified intervals.

5. Email Notifications (Optional):

* Customize the 'send_mail()' function to include your email credentials and adjust the price threshold. Uncomment the function call in the script to activate email notifications.

## Notes

* Please use this script responsibly and adhere to Amazon's terms of service regarding web scraping.

Feel free to explore and modify the script to suit your specific needs. Happy scraping!

