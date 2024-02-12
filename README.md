# datafun-06-eda
Project 6 is an opportunity to create your own custom exploratory data analysis (EDA) project using GitHub, Git, Jupyter, pandas, Seaborn and other popular data analytics tools.

## Create Project Virtual Environment

On Windows, create a project virtual environment in the .venv folder. 

```shell

py -m venv .venv
.venv\Scripts\Activate
py -m pip install pyarrow pandas requests jupyterlab matplotlib seaborn

```
## Freeze Requirements

```shell
py -m pip freeze > requirements.txt
```

## Git add and commit 

```shell
git add .
git commit -m "add .gitignore, cmds to readme"
git push origin main
```

## Datasets used

https://github.com/mwaskom/seaborn-data
I haven't gotten far enough in the project to determine exactly which if not all of these csv's will be used, first impression is to use:
https://github.com/mwaskom/seaborn-data/blob/master/geyser.csv

If more csv's are used I will update later on.