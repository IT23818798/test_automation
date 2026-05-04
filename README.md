# Assignment 1 - Test Automation

## Description
This project automates transliteration accuracy testing of the Chat Sinhala function at https://www.pixelssuite.com/chat-translator using Playwright.

## Prerequisites
- Python 3.11 or 3.12
- Google Chrome

## Installation
pip install playwright openpyxl
python -m playwright install

## Run Tests
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

## Results
Results are saved automatically in the Excel file under Actual output and Status columns.