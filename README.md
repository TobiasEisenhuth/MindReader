# MindReader

Simple rigged memory game in ASP.NET, created to explore the development and deployment of Cloud hosted applications.

# Deployed Instances

> [!IMPORTANT]
> In case the instances are down due to cutting costs, please get in touch to get them up and running!

| Techstack | URL |
|--|--|
| Azure - nativ Web App | https://mindreader-huf5dmb2g2hmdmg0.germanywestcentral-01.azurewebsites.net/ |
| Azure - Docker + Web App | https://mindreaderdocker-habjhga2ckgfbmdm.germanywestcentral-01.azurewebsites.net/ |
| AWS - nativ Elastic Beanstalk | http://gs-app-web-env.eba-vtswrdpw.us-east-1.elasticbeanstalk.com/ |
| AWS - Docker + Elastic Beanstalk | http://mindreader-aws-docker-container-env.eba-pqzrj4wf.us-east-1.elasticbeanstalk.com/ |

# Run Locally

Within the root folder level:

**>_** `dotnet run`

or

**>_** `HOSTING_PLATFORM=Azure dotnet run`

**>_** `HOSTING_PLATFORM=AWS dotnet run`
