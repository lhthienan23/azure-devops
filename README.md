[![Python application test with Github Actions](https://github.com/lhthienan23/azure-devops/actions/workflows/pythonapp.yml/badge.svg)](https://github.com/lhthienan23/azure-devops/actions/workflows/pythonapp.yml)
[![Build Status](https://dev.azure.com/odluser270113/azure-devops/_apis/build/status%2Flhthienan23.azure-devops?branchName=main)](https://dev.azure.com/odluser270113/azure-devops/_build/latest?definitionId=1&branchName=main)
# Overview

A Python Flask web application using Azure to demonstrate Continuous Integration and Continuous Delivery.

## Project Plan

* [Trello Board for the Project](https://trello.com/b/G8qe45rY/azure-devops)
* [Project Plan Spreadsheet](https://docs.google.com/spreadsheets/d/1ZzMOn_TED4mJ6rDOsSDvhyWhrwBc7Ht62aNbzpEAArw/edit?usp=sharing)

## Instructions

* Architectural Diagram:

  ![architectural](https://github.com/user-attachments/assets/8a750286-f971-4262-b267-cf38fc21aaa8)

* Project running on Azure App Service
  
  ![app](https://github.com/user-attachments/assets/64b28760-6f03-472f-bf8a-764bf4df01dd)

* Project cloned into Azure Cloud Shell

  ![clone](https://github.com/user-attachments/assets/d3854c4e-9f67-45e5-8897-47eefef712cf)

* Passing tests that are displayed after running the `make all` command from the `Makefile`

  ![makeall1](https://github.com/user-attachments/assets/4e870c72-c40c-46c8-ab5a-c599a91be3c0)

* Output of a test run

   ![makeall2](https://github.com/user-attachments/assets/7f7ce027-7c35-4215-a060-de5edc7e6a89)

* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).

  ![image](https://github.com/user-attachments/assets/eb45cd40-0ddf-44c7-8153-7d658d26815a)

* Running Azure App Service from Azure Pipelines automatic deployment

  ![image](https://github.com/user-attachments/assets/b09ef3e1-23d3-4eb7-8183-b74137469449)

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
The output should look similar to this:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```
![image](https://github.com/user-attachments/assets/af3d6151-2bfa-4b45-8830-242a540001d4)

* Output of streamed log files from deployed application
  
![image](https://github.com/user-attachments/assets/b18531c5-2fb9-4b95-ad11-04093bae68ed)

> 

## Enhancements

- Add Automated Testing
- Enable Rollback Mechanisms
- Integrate Static Code Analysis
- Integrate a Load Balancer

## Demo 

[Azure Devops Demo](https://youtu.be/8l9cBu1NOTo)



