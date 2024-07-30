# AutomatiPython


Project Description
This project is a Python script that automates the process of logging into a website and entering data from an Excel spreadsheet into a web form using Selenium WebDriver. It utilizes a specific Chrome profile to maintain session data and pre-configured browser settings.
Explanation
Setup and Initialization:
Import necessary libraries including Selenium, time, and openpyxl.
Define the path to a specific Chrome profile to maintain user session and preferences.
Configure Selenium to use this Chrome profile.
Web Navigation:
Open the specified URL using Selenium WebDriver.
Wait until the email input field is present on the page.
Input the email and password, and click the login button to access the protected area of the website.
Excel Integration:
Load an Excel workbook containing company data.
Define a function preencher_campo to input text into form fields with a slight delay between keystrokes to mimic human behavior.
Form Filling:
Iterate through the rows of the Excel sheet, extracting the data for each company.
For each company, locate the corresponding input fields on the web form and fill them with the data from the Excel sheet.
Submit the form by clicking the register button.
Finalization:
Close the browser once all data entries have been processed and submitted.
