# Loan Qualifier Application

This is a python command line interface program that allows users to plug in various kinds of information to evaluate their loan eligibility. The application will match the user data against a list of bank loans from 'daily_rate_sheet' and return to the user a list of loans that they qualify for. Then, the user will have the ability to save that list, or to leave the application.
---

## Technologies

This project leverages python 3.7 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

---

## Installation Guide

Before running the application the following must be installed.


```python
  pip install fire
  pip install questionary
```

## Usage

To use the loan qualifier application simply clone the repository and run the **app.py** with:

```python
python app.py
```
First, the user will be asked to enter a file path to a rate-sheet. The user should then input './data_daly_rate_sheet.csv'.
Then, the user will be asked a serious of questions to evaluate the user's loan eligibility.
If the user qualifies for loans, the user will be prompted to save the list of qualifying loans. If not, the user will be thanked for using the app.

---

## Contributors

just me, myself, and a little help from the ReadMe section in Module 2.

---

## License

None, feel free to copy the code and use anytime!