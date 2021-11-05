# HCDS-Bechdel-Test-Final-Project

CDAD-UH - 1044Q Human Centered Data Science | Fall 2021 | Final Project

## Description

## Datasets

1. [Bechdel test data](https://bechdeltest.com/) (API supported):
   `Data/Bechdel_detailed.csv`.

   Code for API usage is in the notebook `Data/Bechdel_api.ipynb`.

   Detailed explanation and active discussion about this dataset can be found on [Kaggle](https://www.kaggle.com/alisonyao/movie-bechdel-test-scores).

2. [Crew & Cast Gender data](https://www.kaggle.com/rounakbanik/the-movies-dataset?select=credits.csv) from Kaggle:

## Code

- `Data/Bechdel_api.ipynb` shows you how to use the API to fetch data from https://bechdeltest.com/.

- `Data/all_cast_crew_gender.ipynb` is an example of how to clean the cast and crew info from the original Kaggle dataset.

## Packages

Since a large proportion of crew members have their gender labeled unknown in the original Kaggle dataset, I used a [gender prediction package](https://pypi.org/project/gender-guesser/) called gender-guesser to predict the unknowns.
