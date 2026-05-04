Setup Instructions

1.	Install Python 3.13
  
3.	Install dependencies:
•	pip install -U pip
•	pip install playwright openpyxl

5.	Install Playwright browsers:
•	playwright install

7.	Project setup:
	Place the following files in the same folder:
•	test_automation.py
•	Assignment 1 - Test cases.xlsx

9.	Open Command Prompt
10.	Navigate to the project folder using cd: Example:
•	cd C:\Users\Kaushini\Documents\test_automation

11.	Run the script using the following command:
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --header-row 1 --input-col "Input" --expected-col "Expected output" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

Notes
•	Make sure the Excel file name matches exactly
•	Do not move the Excel file to another folder
•	Keep both files in the same directory
•	Press CTRL + C to stop the script after execution
