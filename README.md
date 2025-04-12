# Azure-Resume
My Azure Resume

## Section 1: Front-end

- Index.html in frontend folder contains the website.
- main.js contains visitor counter code. 

## Section 2: Back-end

- Created Cosmos DB in Azure Portal.
- GetResumeCounter.cs using HTTP Trigger and created Azure Function to interact with Cosmos DB counter.
- Counter.cs used in the GetResumeCounter.cs function.

## Section 3: Deploying to Azure

- Deployed Azure Function (getazresumecounter) to Azure, and grabs the URL and updated to main.js.
- Deployed static website to blob container.
- Set up Azure CDN for HTTPS and custom domain (e.tse.info) support.


## Section 4: CI/CD pipeline

- frontend.main.yml contains to Front-end workflows.
- backend.main.yml contains to Back-end workflows.
- Deployed static website in Azure Storage with GitHub Actions for front-end.
- Deployed to Azure Functions with GitHub Actions for back-end.

## Resources:

- GitHub account - https://github.com/join 
- Azure account - https://azure.microsoft.com/en-us/free 
- Visual Studio Code - https://code.visualstudio.com 
- Visual Studio Code Extensions - https://code.visualstudio.com/docs/introvideos/extend
- Git Bash - https://git-scm.com/downloads/win
- Co-Pilot - https://copilot.microsoft.com 
- Postman - https://www.postman.com/ 
- GitHub Copilot for Azure - https://marketplace.visualstudio.com/items/?itemName=ms-azuretools.vscode-azure-github-copilot
- Azure Functions Extensions - https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurefunctions
- Azure Functions Core Tools - https://learn.microsoft.com/en-us/azure/azure-functions/functions-run-local
- .NET 9.0 SDK - https://dotnet.microsoft.com/en-us/download 


## Front-end Resources:

- Azure Storage Explorer - https://azure.microsoft.com/en-us/products/storage/storage-explorer/
- Tutorial: Host a static website on Blob Storage - https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website-host
- API call with Javascript tutorial - https://www.freecodecamp.org/news/make-api-calls-in-javascript/


## Back-end Resources: 

- Create Cosmos DB in Azure - https://learn.microsoft.com/en-us/azure/cosmos-db/nosql/quickstart-portal
- Create a C# function in Azure using Visual Studio Code - https://learn.microsoft.com/en-us/azure/azure-functions/create-first-function-vs-code-csharp
- Develop Azure Functions by using VisualStudio Code - https://learn.microsoft.com/en-us/azure/azure-functions/functions-develop-vs-code?tabs=node-v4%2Cpython-v2%2Cisolated-process%2Cquick-create&pivots=programming-language-csharp
- HTTP triggered Azure Functions - https://learn.microsoft.com/en-us/azure/azure-functions/functions-bindings-http-webhook?tabs=isolated-process%2Cfunctionsv2&pivots=programming-language-csharp
- Azure Functions Cosmos DB trigger and bindings - https://learn.microsoft.com/en-us/azure/azure-functions/functions-bindings-cosmosdb-v2?tabs=isolated-process%2Cextensionv4&pivots=programming-language-csharp
- Azure Cosmos DB input binding - https://learn.microsoft.com/en-us/azure/azure-functions/functions-develop-vs-code?tabs=node-v4%2Cpython-v2%2Cisolated-process%2Cquick-create&pivots=programming-language-csharp
- Azure Cosmos DB output binding - https://learn.microsoft.com/en-us/azure/azure-functions/functions-bindings-cosmosdb-v2-output?tabs=python-v2%2Cisolated-process%2Cnodejs-v4%2Cextensionv4&pivots=programming-language-csharp


## CI/CD Resources

- Use GitHub Actions workflow to deploy static website in Azure Storage - https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-static-site-github-actions?tabs=openid
- Azure login with a Service Principal Secret - https://github.com/Azure/login#login-with-a-service-principal-secret
- GitHub Actions for deploying to Azure Function - https://github.com/Azure/functions-action

