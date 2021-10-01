# Microsoft Azure
# 06 - Azure Container Registry & Web App for containers.

### Instructions
Activity 1: You will create an **Azure Container Registry** and push an Image.

<ol>
<li>Create an Azure Container registry. You can use azure portal, Azure CLI or Azure Powershell. SKU: Basic.</li>

<li>Pull the Docker image ASP.NET Core applications sample: 

<code>docker pull mcr.microsoft.com/dotnet/core/samples:aspnetapp
</code>
</li>

<li>Push the docker image to your Azure container registry

<code>docker push</code>
</li>
</ol>

Activity 2: **Create a web app** and deploy from the Docker Image that you push to the ACR in the Activity. Create with Azure CLI is a nice to have.

### 1. Azure Container Registry 

- [Push your first image to your Azure container registry using the Docker CLI](https://docs.microsoft.com/en-us/azure/container-registry/container-registry-get-started-docker-cli?tabs=azure-cli)
- [Build a containerized web application with Docker](https://docs.microsoft.com/en-us/learn/modules/intro-to-containers/)

:warning:  The webpage from azure is a guide but be sure to also research in more sources the same information.

### 2. Azure Web app for containers

You can use the following resources or research others that you find convenient:

- [Deploy and run a containerized web app with Azure App Service](https://docs.microsoft.com/en-us/learn/modules/deploy-run-container-app-service/)


### Expected deliverables
- MD file including:

    - Document the commands that you used to achieve the instructions.
    - Take a screenshot of the resources in your resource group in the portal.
    - Take a screenshot of the Deployment center of your app with the Registry settings.
    - Take a screenshot of your site deployed in your app service, include url, that must match with the name of your web app.

# Evaluation
## Overall Evaluation

| Metric name        | % Value |
|:------------------ |:--:|
| Azure Container Registry |  50% |
| Azure Web app for containers |   50% |

## Break Down of the Evaluation per mind map

 Metric name        | Metric description                                | % Value |
|:------------------ |:--------------------------------------------------|:--:|
|  Azure Container Registry | Azure Container Registry deployed.  | 25% |
|  Azure Container Registry | Repository with the Docker Image  | 25% |
|  Azure Web app for containers | Web app created and docker image deployed | 50% |



## Clean up resources

Don't forget to delete your resources when the activity had done. Use the [portal]().