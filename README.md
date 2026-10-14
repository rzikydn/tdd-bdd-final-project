# Product Catalog Microservice (TDD & BDD Final Project)

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python 3.9](https://img.shields.io/badge/Python-3.9-green.svg)](https://www.python.org/)

This repository contains the backend and BDD acceptance test suite for an eCommerce Product Catalog Microservice, implemented as the final capstone project for the IBM DevOps and Software Engineering Professional Certificate / Test and Behavior Driven Development course.

## Overview
- **TDD (Test-Driven Development)**: Built model and REST API endpoints using Python `unittest`, Flask, and SQLAlchemy.
- **BDD (Behavior-Driven Development)**: Validated Administrative Web UI using `behave` (Gherkin syntax) and Selenium WebDriver.

## Project Structure
- `service/models.py`: SQLAlchemy Product database model with CRUD operations and filtering methods.
- `service/routes.py`: Flask REST API endpoints (`GET`, `POST`, `PUT`, `DELETE`).
- `tests/factories.py`: Fake data generator using `factory_boy` and `Faker`.
- `tests/test_models.py`: TDD test suite for testing `Product` model.
- `tests/test_routes.py`: TDD test suite for testing REST API endpoints.
- `features/products.feature`: BDD Gherkin specifications for user acceptance testing.
- `features/steps/load_steps.py`: Step definition to seed background data before BDD scenarios.
- `features/steps/web_steps.py`: Step definitions implementing Selenium web automation.
