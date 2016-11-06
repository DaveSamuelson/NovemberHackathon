
<h1>November Hackathon</h1>

The purpose of this QuickStart template is to provision Azure resources within your own subscription, demonstrating core Azure capabilities that you are likely to adopy during the course of the Hackathon.

<h2>Pre-Requisites</h2>
Before you can initiate the deployment of resources within this script, you  need:

* An Azure Susbcription
* An identifier for your team that is no more than 6 chars long, lowercase and does not contain any symbols or numbers.

<h2>What does this script deploy?</h2>
Using your specified Team Identifer, the following resources are deployed:

* DevVM - An Azure Virtual Machine running Windows Server 2012 R2 with Visual Studio Community 2015 (Update 3) 
* A sample project will be copied down from Azure BLOB Storage and expanded as C:\Hackathon on the DevVM
* An Azure Web App for hosting the e-commerce web application
* An Azure SQL DB instance for hosting the database
* A classic storage account that will be used for queuing receipt generator requests
* Another Azure Web App for hosting the e-commerce Admin application
* An Azure API App for hosting the Payment Gateway
* An Azure API App for hosting the Offers API


<h2>Deploy to Azure</h2>
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdavesamuelson%2FNovemberHackathon%2Fmaster%2Fscripts%2F001%20Deploy%20Development%20Machine%2FQuickDeployDevelopmentMachine.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

<h2>Visualise the Template</h2>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fdavesamuelson%2FNovemberHackathon%2Fmaster%2Fscripts%2F001%20Deploy%20Development%20Machine%2FQuickDeployDevelopmentMachine.json" target="_blank">

  <img src="http://armviz.io/visualizebutton.png"/>
</a>



<h3>NOTE</h3>
If you are creating templates that fail to Visualise, this usually indicates invalid JSON - try validating in http://jsonlint.com/




