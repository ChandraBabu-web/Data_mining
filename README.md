**Data mining with selinium and BeautifulSoup**

Install and import the libraries :
!pip install selenium
from selenium import webdriver
from selenium.webdriver.common.by import By
import os
import time
import csv
import pandas as pd
from bs4 import BeautifulSoup

Make sure to download the Chromedriver executable file which is compatable with the chrome browser version.

The program will generate Job_Postings_new.csv file first which contains all the inforamtion related to the job posts globally.

Next it uses the extracted data links in Job_Postings_new.csv to go through each job post page to extract the relavant information of the job posts.
