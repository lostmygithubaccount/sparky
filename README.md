# Azure ML and Spark

## Introduction

### This repo

This is an informal collection of demos around Spark on Azure ML via Azure Synapse. I do not know how to write code. Do not take a production dependency on code I write. Use Microsoft official repos and documentation instead. 

### Data overview

The data is a copy of the [NOAA Integrated Surface Data (ISD)](https://azure.microsoft.com/services/open-datasets/catalog/noaa-integrated-surface-data/) moved from [Azure Open Datasets](https://azure.microsoft.com/services/open-datasets/catalog/) moved to the Azure ML workspace's default storage account. 

The data is stored in both compressed parquet files and uncompressed CSV files which are ~20 GB and ~150 GB respectively. There are >1000 individual files. Loaded in a dataframe, the data is ~750 GB. There are ~1.4 B rows.

## Prerequisites

* [Azure Machine Learning Workspace](https://aka.ms/azureml/workspace)
* [Azure Synapse Workspace](https://aka.ms/azureml/synapse/workspace)

### Create a Synapse Spark Pool

### Create and setup compute instance

### Launch JupyterLab, Jupyter, or use in inline notebook editor

### Clone repository
