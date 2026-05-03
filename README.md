# Test Automation Assignment

## Project Description

This project is about automating tests for a system that translates Singlish to Sinhala. We are using Playwright and Python to do this.

## Things You Need

-need to have Python 3.11 on your computer

-need to have pip, which's a package manager for Python

## Steps to Get Started

1. Then you need to go to the project folder:

cd test-automation-assignment

2. Next you need to install some packages that the project needs:

pip install -U pip

pip install playwright openpyxl

3. After that you need to install the browsers that Playwright needs:

playwright install

## Running the Tests

To run the tests you need to run the following command:

py -3.11 test_automation.py --excel "Assignment 1. Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-

## What You Get

- The script will update the Excel file with the actual output and the status of each test which can be either pass or fail

## Files You Get

- test_automation.py

- Assignment 1. Test cases.xlsx

- README.md

## Link, to the Project

https://github.com/Samadhi632/test-automation-assignment-IT23637146.git
