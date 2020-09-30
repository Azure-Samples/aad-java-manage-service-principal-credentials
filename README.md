---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Graphrbac
  platforms: java
---

# Getting Started with Graphrbac - Manage Service Principal Credentials - in Java #


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

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/aad-java-manage-service-principal-credentials.git

    cd aad-java-manage-service-principal-credentials

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.