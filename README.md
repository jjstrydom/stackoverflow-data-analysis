# stackoverflow-data-analysis
My daughter is adopted. As a result we are a multi-racial family. I would like to know what the developer community has in store for her if she chooses to pursue that career one day.

The questions answered in this analysis is:
- Is diversity improving in the developer community?
- Are things improving for minority groups?
- Is the road to success the same for those coming from privilege than those who are not?

The [full blog post is published on medium](https://jurgen-strydom.medium.com/minorities-and-the-developer-community-7abe922f8ccb).


## Environment
The analysis uses python. The environment is managed using `pipenv`. [This link](https://realpython.com/pipenv-guide/) will help you get started with `pipenv`.

This project uses `python 3.7` and the following packages:
- `jupyter`
- `pandas`
- `requests`

## Dataset

The datasets are all [stackoverflow surveys](https://insights.stackoverflow.com/survey) from 2011 to 2020. To download the datasets and format them for use in this project automatically run the `get_the_data` notebook.

Note the analysis only relies on the 2017 and 2020 datasets, but they are all made available for completeness.

If there is a need to do this manually, download each zip from the website, extract the csv in the /data/ folder, and rename each csv to the respective year, e.g. `2011.csv` for the first survey conducted in 2011.

## Files
#### analysis.ipynb
- Jupyter notebook containing the main analysis for this work.  

#### get_the_data.ipynb
- Jupyter notebook that assists with collecting the data and storing it correctly for use in the analysis.  

#### LICENSE
- MIT. Read for information on re-use and sharing. Usage of this software, analysis or anything else in this repository is subject to the license.

#### Pipfile & Pipfile.lock
- Files for `pipenv` to recreate the environment used for the analysis

#### README.md
- This file.

# The End
