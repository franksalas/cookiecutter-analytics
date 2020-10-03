# {{cookiecutter.project_name}}

- Created by {{cookiecutter.full_name}}
- version: {{cookiecutter.version}}
- Date: {{cookiecutter.release_date}}
- username : {{cookiecutter.github_username}}

## Description
{{cookiecutter.project_short_description}}

## Setup environment
Create enviroment from file
```bash
conda env create -f base_environment.yml
```
## Activate environment

```bash
conda activate environments/{{cookiecutter.env_name}}
```

## Update environment

```bash
$ conda env update --prefix ./env --file environment.yml  --prune

pip freeze > requirements.txt
```
## Folder Structure
```
.
├── data
│   ├── final
│   ├── interim
│   └── raw
├── environments
│   ├── base_environment.yml
│   └── README.md
├── notebooks
│   └── EXAMPLES.ipynb
├── notes
├── README.md
├── report
│   └── graphs
└── src
    └── start.py

```