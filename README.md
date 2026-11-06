# Python_Selenium_Automation_Assignments

Practice scripts for Selenium WebDriver with Python. This repository is a fork of [ShivrajCodes/Python_Selenium_Automation_Assignments](https://github.com/ShivrajCodes/Python_Selenium_Automation_Assignments).

## What's here

The `main` branch only contains this README. The code is on the `master` and `simantini` branches:

| Branch | File | What it does |
|---|---|---|
| `master`, `simantini` | `simantini/multipleelements.py` | Opens the [Rahul Shetty Academy Automation Practice](https://rahulshettyacademy.com/AutomationPractice/) page in Chrome. It finds all `<a>` elements with `find_elements(By.TAG_NAME, "a")` and prints the total count and each link's text, labelling icon/image links that have no text. It then counts the checkboxes with the XPath `//input[@type='checkbox']`. |

## Run

Requirements: Python 3, Google Chrome, and Selenium 4 (which downloads ChromeDriver automatically through Selenium Manager).

```bash
pip install selenium
git checkout simantini
python simantini/multipleelements.py
```

## Tech

Python, Selenium WebDriver (Chrome), `By.TAG_NAME` and XPath locators.
