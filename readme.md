# Project: Ml Currency Portoflio 

Based on the financial advisor bot template (CM3020 Artificial Intelligence, Project Idea 2: Financial Advisor Bot).

## Information

The project consists of three repositories:
- ML
- Backend
- Frontend

### Current Repository: ML

The current repository is the one related to preapring the data and training the models.

This repository contains:
- Jupyter notebooks
- A data folder (with the csv files used throughout the process)
- A models folder (with the models that were trained thoughout the many experiments and training runs)
- A genetic-algorithms folder (with the genetic algrotihms saved)
- a tuner_results folder (with the results from the tuner)
- a .gitignore file
- a readme.md file
- a requirements.txt file

The Jupyter Notebooks related to the process have the following order: experiment[number] (for the 19 experiments), ml_process, genetic_algorithm, ml_project_iteration, ml_project_iteration_two.

The models exported are in the models folder, but if you want to start from scratch and generate new models, you would need to delete the models from the models folder, create a virtual environment using ```pip -m venv .venv```, use the requirements file using ```pip install -r requirements.txt```, and the go the notebook you want to run and run it.

### Other repositories of the project

The GitHub links for the other repositories can be found in the final report.