[![Python application test with Github Actions](https://github.com/lhthienan23/azure-devops/actions/workflows/pythonapp.yml/badge.svg)](https://github.com/lhthienan23/azure-devops/actions/workflows/pythonapp.yml)

# Overview

A Python Flask web application using Azure to demonstrate Continuous Integration and Continuous Delivery

## Project Plan

* [Trello Board for the Project](https://trello.com/invite/b/6745ecde27f5d4035768ac1b)
* [Project Plan Spreadsheet](https://docs.google.com/spreadsheets/d/1ZzMOn_TED4mJ6rDOsSDvhyWhrwBc7Ht62aNbzpEAArw/edit?usp=sharing)

## Instructions

* Architectural Diagram: ![architectural](https://github.com/user-attachments/assets/8a750286-f971-4262-b267-cf38fc21aaa8)

* Project cloned into Azure Cloud Shell: ![clone](https://github.com/user-attachments/assets/d3854c4e-9f67-45e5-8897-47eefef712cf)

* Passing tests after running `make all` command:

   ![makeall1](https://github.com/user-attachments/assets/4e870c72-c40c-46c8-ab5a-c599a91be3c0)

  ![makeall2](https://github.com/user-attachments/assets/7f7ce027-7c35-4215-a060-de5edc7e6a89)

* Project running on Azure App Service

* Project cloned into Azure Cloud Shell

* Passing tests that are displayed after running the `make all` command from the `Makefile`

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



