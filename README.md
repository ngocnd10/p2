# Overview

This project uses GitHub Actions and Azure Pipeline to build a CI/CD Pipeline to deploy Machine Learning Microservices API using Python Flask.

## Project Plan

* A link to a Trello board for the project
https://trello.com/b/QA6wHbmo/p2
* A link to a spreadsheet that includes the original and final project plan
https://docs.google.com/spreadsheets/d/1Ne7JwKaWu5Rlz_zxjueZKr-4lACrVTAuxI7p3jBMKtQ/edit?usp=sharing

## Instructions

* Architectural Diagram (Shows how key parts of the system work)
![Architectural Diagram](cd-diagram.png)

<TODO:  Instructions for running the Python project.  How could a user with no context run this project without asking you for any help.  Include screenshots with explicit steps to create that work. Be sure to at least include the following screenshots:

* Project running on Azure App Service
![Alt text](Project%20running%20on%20Azure%20App%20Service.png)

* Project cloned into Azure Cloud Shell
![Alt text](Project%20cloned%20into%20Azure%20Cloud%20Shell.png)

* Passing tests that are displayed after running the `make all` command from the `Makefile`
![Alt text](Output%20Make%20File.png)

* Output of a test run

* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).

* Running Azure App Service from Azure Pipelines automatic deployment

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
The output should look similar to this:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```

* Output of streamed log files from deployed application

> 

## Enhancements

<TODO: A short description of how to improve the project in the future>

## Demo 

<TODO: Add link Screencast on YouTube>


