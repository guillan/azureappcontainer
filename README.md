# azurecontainerapps-helloworld
This repository is part of the [Azure container apps Workshop](https://aka.ms/aca-workshop)

This sample is a very simple NodeJS application used to demonstrate [Azure Container Apps](https://docs.microsoft.com/en-us/azure/container-apps/). The packaged version of the application is available on [Docker Hub](https://hub.docker.com/r/mavilleg/acarevision-helloworld).

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.


az ad sp create-for-rbac \
--name containerapp-principal \
--role "contributor" \
--scopes /subscriptions/9fa2345c-0bcb-46d6-8cb8-b0ce1705115b/resourceGroups/rg-my-container-apps \
--sdk-auth
