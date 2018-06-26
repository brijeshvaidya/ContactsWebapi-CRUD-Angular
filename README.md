# ContactsWebapi-CRUD-Angular
Contacts CRUD WEBAPI angular EF
Angular 5 With Web API - CRUD Operations
This is an Angular 5 App With Web API to Demonstrate CRUD Operations Insert Update and Delete With SQL Server, Entity framework db first, Generic Repository Pattern, Dependency Injection using Microsoft Unity for WebAPI, AutoMapper, Angular, TypeScript, Observable, Rxjs, npm, nodejs.
Before Running this Project
Install npm packages using 'npm install' command for ContactUI project.
Step By Step Explanation
Open ContactUI project in Visual studio code and from the command terminal (ctrl + ~ ) 
run commad 'npm install'
after installing all required node modules need to run 'npm start' command
before that open contactWebAPI project and run that project.
Now for running webapi project go to contactWebAPI project, right click and goto debug and start new instance.
We have Domain data model project that contains the Entity framework classes
We have DTO objects for business project entities that will transform domain objects to view model classes so directly not expose our domain data classes for security
we have Business services project that will call by webapi and  this services classes can communicate with domain data model classes UnitOfWork and repository classes.
Create table script.sql file also attached herewith, need to run script in sql server and change the connection string based on sql server connection 
connection string in UserContact.DataModel project's App.config file as below:
 


