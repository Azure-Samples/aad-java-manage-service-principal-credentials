---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Authorization
  platforms: java
---

# Getting Started with Authorization - Manage Service Principal Credentials - in Java #


  Azure service principal sample for managing its credentials.
  - Create an application with 2 passwords and 1 certificate credentials
  - Create an associated service principal with contributor role
  - Verify all password credentials and certificate credentials are valid
  - Revoke access of a password credential
  - Verify the password credential is no longer valid
  - Revoke the role assignment
  - Verify the remaining password credential is invalid
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/aad-java-manage-service-principal-credentials.git

    cd aad-java-manage-service-principal-credentials

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.