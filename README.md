# bank_salary

## Goal

We are using the bank salary dataset to see if there are dependencies of the salary on different variables.



### Data Description

- SALARY: Yearly salary in US-dollars
- LOGSAL: Logarithmised salary
- EDUC: Education in years
- SALBEGIN: Starting salary
- LOGSALBEGIN: Logarithmised starting salary
- GENDER: Gender of the employee (0: female, 1: male)
- MINORITY: Minority affiliation (0: non minority, 1: minority)
- JOBCAT: Job category, with levels (1: admin, 2: custodial and 3: manage).

## Setup

```

pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt

```
