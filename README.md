# selenium-python-framework
Modular Selenium Automation Framework using Python, Pytest, and Page Object Model (POM) – Built for Web App Testing

# Selenium Python Automation Framework

This is a modular Selenium test automation framework built using **Python**, **Pytest**, and **Page Object Model (POM)** design. It is designed to demonstrate real-world test structure for web application testing, including reusable components, reporting, and maintainability.

## Project Goals

- Automate web application testing using Python and Selenium
- Follow industry-standard framework structure (POM)
- Generate detailed reports and capture test results
- Easily extendable for real-time applications and interviews

## 🔧Technologies Used
- Python
- Selenium WebDriver
- Pytest (Test runner)
- Page Object Model (POM)
- HTMLTestRunner / Allure Reports (optional)
- Git + GitHub (version control)

## 📁 Project Structure

selenium-python-framework/
│
├── tests/ # All test cases
├── pages/ # Page classes for each UI page
├── utils/ # Reusable utilities (waits, config)
├── reports/ # Test reports
├── screenshots/ # Screenshots on failure
├── requirements.txt # Dependency list
├── conftest.py # Pytest config file
└── README.md # Project documentation

## ✅ Features
- Login test automation with validations
- Reusable locators and methods
- Pytest for test execution and fixtures
- Screenshots captured on failure
- HTML report generation
- Easily extendable for any web app

- ## 🚀 How to Run

1. Clone the repo  
2. Install dependencies:

pip install -r requirements.txt
bash
3. Run test

pytest --html=reports/report.html


## 📌 Author
**Madhavi Kunte**  
ISTQB Certified | Salesforce QA | MSc Information Systems – Kingston University  
