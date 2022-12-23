# azure_web-app


"CICD -One click azure webapp deployment"

This code used for hosting azure webapp with Free tier deployment using azure devops CICD approach

Pre-prerequisite

1.Azure Account
2.existing resource group
3.existing azure App Service plan (default page)
4.Azure -service connecting (azure devops to existing resource group in which App Service plan deployed)
8.Github-Service connecting for github repo 


CICD:

Please refer azure-pipelines.yml for CICD -Work flow 
Reach me @kbrajeshwaran@gmail.com for any information related to this one click CICD deployment

Main Branch : Protected with branch policy to prevent direct push in to main branch
Pr request: Pr is required for merging from other branches to Main branch

Webapp url:   https://rajeshwarwebapp.azurewebsites.net/  

( Custom domain only support  D1 App Service plan plan and I'm using Free F1 plan so custom domain is not possible
if required please choose D1 App Service plan (Minimum) to host webapp using custom domain name)
