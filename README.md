 # SideProjectPlanner

SideProjectPlanner is simply an organisation tool to help with keeping record of ongoing side-projects you may have. 


## But Why ?

I have multiple notebooks with side project ideas, some of which I started, some I even completed. I don't read those notebooks much however. 

I could deploy a project management system, Jira, Basecamp nifty etc. 
They're not tailored to 'off the cuff' ideas though. They require a lot of input just to create a project/idea. 

This project is solely for developers to have their own area to store their versions of the notebook. 

Come back later, add notes, extra ideas etc all before you start writing. 

It's a simple TODO of side projects. 


## Structure

The structure is broken up into 2 sections. 

1) Server 
2) Client

**Server** :  Multiple server options will be available. Plans are for NodeJS, C#, go and Python.  (Please feel free to add more) API documentation will be done via Swagger schemas as per release versions. 

**Client** : As the server is REST the client is arbitrary however we will provide an Angular based front end which will provide all feature access.  


## Synchronization & Parity

One of the goals in terms of 'ease of use' is to also have the ability to import side projects you have decided to focus on in a more serious way. 
This means being able to export your data into a format the tracking systems like Jira can consume. 

We offer all data in the current known standards for import however we will allow the export of data and the format to be defined by you too. 


# Installation

## **Server**

### NodeJS

#### Requirements
	 - NodeJS

#### Instructions

 - cd to the server/node directory 
 - edit the config.json file with your settings
 - npm install 
 - node main

Your basic server should be up and running. 
