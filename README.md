---
page_type: sample
languages:
- java
products:
- azure
- azure-app-service
description: "Azure App Service sample for managing web apps."
urlFragment: app-service-java-manage-web-apps-on-linux-with-custom-domains
---

# Manage Linux Web App With Domain SSL (Java)

Azure App Service sample for managing web apps.

- App Service plan, web app
 - Create 2 web apps under the same new app service plan
- domain
 - Create a domain
- certificate
 - Upload a self-signed wildcard certificate
 - update both web apps to use the domain and the created wildcard SSL certificate
 

## Running this sample

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

```bash
git clone https://github.com/Azure-Samples/app-service-java-manage-web-apps-on-linux-with-custom-domains.git
cd app-service-java-manage-web-apps-on-linux-with-custom-domains
mvn clean compile exec:java
```

## More information

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
