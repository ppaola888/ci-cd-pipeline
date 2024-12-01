
# CI/CD Project

This repository contains an example of a Python project with a CI/CD pipeline that has been set up by **GitHub Actions**.

## Features
- **Linting:** Uses `flake8` to check code quality.
- **Testing:** Uses `pytest` to run automated tests.
- **CI/CD:** Automates testing and checking of code at every `push` or `pull request` on the `main` branch.


## Configuration

**Clone the repository**: 

- git clone <repository-url>

- cd <repository-folder>

**Install the dependencies**:

    pip install -r requirements.txt

**Run the tests locally**
- pytest

## CI/CD pipeline
The pipeline is configured in the file .github/workflows/python-app.yml. At each push or pull request on the main branch, the pipeline:

- Performs linting with flake8.
- Runs tests with pytest.

## Project Structure

- main.py: Contains the main code 
- test_main.py:  Contains the tests for the code 
- requirements.txt: Project dependencies
- python-app.yml:  CI/CD pipeline configuration



























## 🛠 Skills
Python, Git



## 🚀 About Me
I'm a junior developer!

