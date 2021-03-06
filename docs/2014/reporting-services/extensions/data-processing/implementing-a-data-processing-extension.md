---
title: "Implementing a Data Processing Extension | Microsoft Docs"
ms.custom: ""
ms.date: "06/13/2017"
ms.prod: "sql-server-2014"
ms.reviewer: ""
ms.technology: reporting-services
ms.topic: "reference"
helpviewer_keywords: 
  - "custom data processing extensions [Reporting Services]"
  - "data sources [Reporting Services], data processing extensions"
  - "data processing extensions [Reporting Services]"
  - "extensions [Reporting Services], data processing"
ms.assetid: 8dc2b44e-5ad9-411d-a29f-7213e29321a9
author: maggiesMSFT
ms.author: maggies
manager: kfile
---
# Implementing a Data Processing Extension
  Data processing extensions in [!INCLUDE[ssRSnoversion](../../../includes/ssrsnoversion-md.md)] enable you to connect to a data source and retrieve data. They also serve as a bridge between a data source and a dataset. [!INCLUDE[ssRSnoversion](../../../includes/ssrsnoversion-md.md)] data processing extensions are modeled after a subset of the [!INCLUDE[msCoName](../../../includes/msconame-md.md)] [!INCLUDE[dnprdnshort](../../../includes/dnprdnshort-md.md)] data provider interfaces.  
  
## In This Section  
 [Data Processing Extensions Overview](data-processing-extensions-overview.md)  
 Introduces how to write a custom data processing extension for [!INCLUDE[ssRSnoversion](../../../includes/ssrsnoversion-md.md)].  
  
 [Preparing to Implement a Data Processing Extension](preparing-to-implement-a-data-processing-extension.md)  
 Describes the interfaces available when implementing an [!INCLUDE[ssRSnoversion](../../../includes/ssrsnoversion-md.md)] data processing extension, as well as when you are required to implement a particular interface.  
  
 [Creating a Data Processing Extension Library](creating-a-data-processing-extension-library.md)  
 Describes assigning a namespace for your [!INCLUDE[ssRSnoversion](../../../includes/ssrsnoversion-md.md)] data processing extension and compiling your data processing extension into a library DLL.  
  
 [Implementing a Connection Class for a Data Processing Extension](implementing-a-connection-class-for-a-data-processing-extension.md)  
 Describes the attributes of a connection and how to implement your own **Connection** class for your data processing extension.  
  
 [Implementing a Command Class for a Data Processing Extension](implementing-a-command-class-for-a-data-processing-extension.md)  
 Describes the attributes of a command, and how to implement your own **Command** class for your data processing extension.  
  
 [Implementing a DataReader Class for a Data Processing Extension](implementing-a-datareader-class-for-a-data-processing-extension.md)  
 Describes the attributes of a data reader and how to implement your own **DataReader** class for your data processing extension.  
  
 [Using an External Dataset with Reporting Services](using-an-external-dataset-with-reporting-services.md)  
 Describes how to expose your custom **DataSet** objects to the report server for consumption.  
  
 [Deploying a Data Processing Extension](deploying-a-data-processing-extension.md)  
 Describes how to deploy your data processing extension.  
  
 [Debugging Data Processing Extension Code](debugging-data-processing-extension-code.md)  
 Describes how to debug code in your data processing extensions.  
  
 [Removing a Data Processing Extension](removing-a-data-processing-extension.md)  
 Describes how to remove a data processing extension from a report server or Report Designer.  
  
 For a sample of a fully implemented data processing extension, see [SQL Server Reporting Services Product Samples](https://go.microsoft.com/fwlink/?LinkId=177889).  
  
## See Also  
 [Reporting Services Extensions](../reporting-services-extensions.md)   
 [Reporting Services Extension Library](../reporting-services-extension-library.md)  
  
  
