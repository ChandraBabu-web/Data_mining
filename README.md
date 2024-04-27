
**Data Mining with Selenium and BeautifulSoup**

Introduction
This repository contains a Python script for extracting job postings using Selenium and BeautifulSoup. The script navigates through job listing websites, retrieves relevant information, and stores it in a CSV file.

Installation
Ensure you have Python installed, then install the required libraries:
-from selenium import webdriver
-from selenium.webdriver.common.by import By
-import os
-import time
-import csv
-import pandas as pd
-from bs4 import BeautifulSoup


!pip install selenium
Additionally, you need to download the compatible Chromedriver executable file for your Chrome browser version.

Usage
Clone the repository or download the script.
Install the required libraries as mentioned above.
Run the script.
The script will generate a Job_Postings_new.csv file containing global job posting information.
It will then utilize the extracted data links in Job_Postings_new.csv to extract relevant information from each job post page.
Libraries Used
Selenium: For automating web browser interaction.
BeautifulSoup: For parsing HTML content.
