"CICD -Deployment using Azure-Templates

This code used for hosting azure webapp with Free tier deployment using azure devops CICD approach

Pre-prerequisite

1.Azure Account
2.existing resource group
3.existing azure App Service plan (default page)
4.Azure -service connecting (azure devops to existing resource group in which App Service plan deployed)
8.Github-Service connecting for github repo 
9.common repository for pipeline Templates # Please refer rajeshwarandevops/azdevops_pipeline_template
10.New repo which contains webapp code for build & deploy pipeline by referring existing pipeline-Templates
Please refer : rajeshwarandevops/azure_webapp_deploy_calling_pipeline_template/azure-pipelines.yml
11.Create variable groups by referring parameter on the common repository

Kindly Reach me kbrajeshwaran@gmail.com for any information related to this CICD deployment

Main Branch : Protected with branch policy to prevent direct push in to main branch
Pr request: Pr is required for merging from other branches to Main branch

Webapp url:   https://rajeshwarwebapp.azurewebsites.net/  

( Custom domain only support  D1 App Service plan plan and I'm using Free F1 plan so custom domain is not possible
if required please choose D1 App Service plan (Minimum) to host webapp using custom domain name)




