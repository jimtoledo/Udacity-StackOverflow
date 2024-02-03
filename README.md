# Udacity-StackOverflow
Analysis on languages in the 2023 Stack Overflow Developer Survey dataset

## Installation
The Jupyter notebook should run with the Anaconda distribution of Python. For best results, run with Python version >=3.9 and packages: numpy, pandas, matplotlib, sklearn, statsmodels, searborn, and scipy.

## Project Motivation

For this project, I was interested in analyzing programming language trends within professional developers using Stack Overflow's 2023 survey data.

- What are the most popular languages?
- What languages have the greatest impact on salary?
- What languages are represented more/less by industry?
- What languages are typically worked with together? What language combinations do developers want to work on?

## Files
- `StackOverflow2023.ipynb` is a Jupyter notebook that contains code, comments, markdown sections, and visualizations for all of my analysis on the developer survey dataset
- `survey_results_public.csv` is the Stack Overflow developer survey data file
- `survey_results_schema.csv` and `StackOverflowREADME_2023.txt` were also provided by Stack Overflow and describe the survey methodology, questions asked, and data format

## Summary of Results
The main findings of the results are found in the post [here](https://medium.com/@jimalistairtoledo/programming-languages-you-should-work-on-in-2023-93263581fc50).
- JavaScript continues to be the most popular programming language among professional developers, although not the most lucrative.
- Python is an example of a language is both popular and somewhat lucrative.
- Many of the popular languages (typically those you encounter in web development) are used together.
- Python, SQL, and JavaScript are among the most desired languages to work on next from developers currently working with a different language


## License
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Acknowledgements

Thanks to Stack Overflow for providing their developer survey [dataset](https://insights.stackoverflow.com/survey/) and all those who helped populate that data with their survey responses.