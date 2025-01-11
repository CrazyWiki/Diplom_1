The final project of the Yandex course consisted of three parts:
Diploma 1 - Unit tests
Diploma 2 - API
Diploma 3 - Testing the web application

Diploma Project. Task 1: Unit Tests

Automated Tests for a Program That Helps Order Burgers at Stellar Burgers

Implemented Scenarios

Unit tests have been created covering the classes Bun, Burger, Ingredient, and Database.
Coverage percentage is 100% (report: htmlcov/index.html).
Project Structure

praktikum - package containing the program code
tests - package containing tests organized by class, e.g., bun_test.py, burger_test.py, etc.
Running Automated Tests

Installing Dependencies
$ pip install -r requirements.txt
Running Automated Tests and Generating HTML Coverage Report
$ pytest --cov=praktikum --cov-report=html
