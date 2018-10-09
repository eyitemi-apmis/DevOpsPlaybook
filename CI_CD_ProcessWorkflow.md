CI/CD for Angular Apps on Azure

An alternative way of setting up Azure CI/CD process for Angular web applications without going the almost complicated method of Azure DevOps.

# TL;DR

* Set up CircleCI account.
* Link it with Github Account
* Create .circleci folder in target repo and add config.yml file.
* Push config to github repo to trigger first build
* Create Azure Container Registry
* Edit config.yml to build and push docker images to ACR.
* Set up an new or existing Azure web app for containers.
* Configure continuous development using Azure Webhooks
* Enable CI in the webapp.
* Puch to Github repo to trigger CI/CD pipeline.



For longer and well detailed method/description, this article is perfect.
https://www.ng-conf.org/build-deploy-angular-cloud/


