# Azure Analytics Accelerator

The following accelerators can be used to deploy an `Azure Databricks Workspace` into an Azure Resource Group.  It will allow you to explore some of the Data Lake, Data Lakehouse capabilities available on Microsoft Azure.

## I am in. Lets go Deploy!

Jump to [Deploy an Azure Databricks Workspace](https://github.com/DataSnowman/c-change#deploy-an-azure-databricks-workspace)

## Purpose

The purpose of this Analytics Accelerator is to help you learn and grow through Hands-on common use cases that show you how to use things like ADF data integration pipelines, and Azure Databricks notebooks.

This [GitHub Repository](https://github.com/DataSnowman/c-change) along with an Azure Subscription [No Azure Subscription click here](https://azure.microsoft.com/en-us/free/synapse-analytics/) should allow you to accelerate:

* Business Value
* Time-to-insight
* Modernization
* Skilling
* Proof of Concepts
* Architecture choice
* Infrastructure as code for PoC, Dev, Test, Prod

## Presentation of Content

| Event | Title | Presentation | Demo |
| :------------- | :----------: | :----------: | :----------: |
|DevDays2021 | Accelerate business value and time-to-insight with Azure Analytic | [Deck with Recording](https://1drv.ms/p/s!AmFpgz3VMIP0ifp5SuWniGXKYL_qRg?e=2XjfuO) | [Demo Recording](https://1drv.ms/v/s!AmFpgz3VMIP0ifp4hDOimkMrx4jViw?e=pHqG9n) |


## Common Use Cases

This accelerator provides an examples of common use cases using things like [Seattle Public Library](https://data.seattle.gov/browse?q=Seattle%20Public%20Libraries&sortBy=most_accessed&utf8=%E2%9C%93) public csv datasets (and other datasets), that are captured on ADLS and composed into parquet files, Spark tables, Serverless external tables, and Dedicated SQL pool tables, then consumed using SQL. 

| Deployment | Use Case Name | Use Case Type | Dataset | Description | Code | Instruction Steps |
| :------------- | :----------: | :----------: | :----------: | :----------: | :----------: | :----------: |
| [Azure Databricks](https://github.com/DataSnowman/c-change#deploy-an-azure-databricks-workspace) | Covid-19 | Azure Databricks | JHU Covid-19 | TBD | TBD [Code]() | TBD [Steps]() |

## Azure Analytics Services

This accelerator should allow you more time to focus on hands on keyboard and learn about these Azure Analytics Services:

* [Azure Databricks](https://github.com/DataSnowman/c-change#deploy-an-azure-databricks-workspace)

Use your own data, the [Common Use Cases](https://github.com/DataSnowman/c-change#common-use-cases) above, or the Getting Started wizard inside of the workspace is recommended to use sample data if you do not have your own.

## Prerequisites

- Owner to the Azure Subscription being deployed. This is for creation of a separate Analytics Accelerator Resource Group(s) and to delegate roles necessary for this deployment.

## Deploy an Azure Databricks Workspace

`Together with Azure Data Lake Storage Gen2, Azure Data Factory, and Azure SQL Database`

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FDataSnowman%2Fc-change%2Fmain%2Fworkspace%2Fadb-workspace%2Fazuredeploy.json) [![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FDataSnowman%2Fc-change%2Fmain%2Fworkspace%2Fadb-workspace%2Fazuredeploy.json)

This template deploys the following:

- Azure Databricks Workspace
- Azure Data Lake Storage Gen2
- Azure Data Factory
- Azure SQL Database
