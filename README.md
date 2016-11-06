<h1>November Hackathon</h1>

The purpose of this QuickStart template is to provision Azure resources within your own subscription, demonstrating core Azure capabilities that you are likely to adopy during the course of the Hackathon.

<h2>Pre-Requisites</h2>
Before you can initiate the deployment of resources within this script, you will need:

* An Azure Susbcription
* An identifier for your team that is no more than 6 chars long, lowercase and does not contain any symbols or numbers.

<h2>What does this script deploy?</h2>
Using your specified Team Identifer, the following resources are deployed:

* DevVM - An Azure Virtual Machine running Windows Server 2012 R2 with Visual Studio Community 2015 (Update 3) installed
        - A sample project will be copied down from Azure BLOB Storage and expanded as C:\Hackathon 


# November Hackathon
Scripts to help set-up November Hackathon




<h2>This ste deploys a Visual Studio 2015 Community Edition VM into Azure, copies down the source code from BLOB storage and expands the zip file </h2>
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdavesamuelson%2FNovemberHackathon%2Fmaster%2Fscripts%2F001%20Deploy%20Development%20Machine%2FQuickDeployDevelopmentMachine.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

<a href="http://armviz.io/#/?load=https://raw.githubusercontent.com/davesamuelson/NovemberHackathon/master/scripts/Deploy%20Development%20Machione%20QuickDeployDevelopmentMachine.json" target="_blank">
  <img src="http://armviz.io/visualizebutton.png"/>
</a>

https://github.com/DaveSamuelson/NovemberHackathon/blob/master/scripts/001%20Deploy%20Development%20Machine/QuickDeployDevelopmentMachine.json


**If your template does not Visualise, this usually indicates invalid JSON - try validating in http://jsonlint.com/**




