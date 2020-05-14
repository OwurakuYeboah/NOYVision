# N.O.Y. Vision Data Layer

This is the data layer for the HealthC(AR) application.

## Getting Started

These instructions will get you a copy of the database up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the database on a live system.

### Prerequisites

You will need:

SQL Server 2017 Express Edition(can upgrade to 2019). Make sure you download the Management Studio as well. Here's a link to install:

https://www.microsoft.com/en-us/sql-server/sql-server-downloads


### Installing

Download the BACPAC file from this repo.

Open your SQL Server Management Studio.

After signing into your desktop, right-click on 'Databases' in the Object Explorer.

Follow the instructions to import the BACPAC file into a new database.

Your database is now set up! You can change your SQL authentication to match up with the service layer.

## Running the tests

You can run queries on the database by right-clicking the new database and clicking 'New Query'


## Deployment

These are the steps to take to deploy the database onto Azure:

First, you must create an Azure SQL database to deploy the database onto. Refer to the Azure documentation for the instructions.

After your Azure SQL Database is created, open your SQL Server Management Studio.

Right-click on the database created, and go to Tasks.

Select the 'Deploy Database to Azure SQL Database' option.

The wizard will walk you through deploying your database onto Azure.

Your database is now deployed on Azure! You can also run queries from your SQL Server Management Studio. (option provided in wizard)

## Built With

* [SQL Server 2017](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)



