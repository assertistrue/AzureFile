---
services: storage
platforms: nodejs
author: yaxia
---

# Getting Started with Azure File Service in Node.js

Demonstrates how to use the File Storage service.
File storage stores unstructured data such as text, binary data, documents or media files.
Files can be accessed from anywhere in the world via HTTP or HTTPS.

If you don't have a Microsoft Azure subscription you can
get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

## Running this sample

This sample can be run using either the Azure Storage Emulator that installs as part of this SDK - or by
updating the app.config file with your account name and key.

To run the sample using the Storage Service

1. Open the app.config file and set the connection string for the emulator ("useDevelopmentStorage":false) and set the connection string for the storage service ("connectionString":"...")
2. Create a Storage Account through the Azure Portal
3. Provide your connection string for the storage service ("connectionString":"...") in the app.config file. 
4. Run the sample by: node ./fileSample.js

## More information
- [What is a Storage Account](http://azure.microsoft.com/en-us/documentation/articles/storage-whatis-account/)
- [Getting Started with Files](https://azure.microsoft.com/en-us/documentation/articles/storage-dotnet-how-to-use-files/)
- [File Service Concepts](https://msdn.microsoft.com/en-us/library/dn166972.aspx)
- [File Service REST API](https://msdn.microsoft.com/en-us/library/dn167006.aspx)
- [File Service Node API](http://azure.github.io/azure-storage-node/FileService.html)
- [Delegating Access with Shared Access Signatures](http://azure.microsoft.com/en-us/documentation/articles/storage-dotnet-shared-access-signature-part-1/)
