# Coding Assignment - Application for maintaining contact information
# Solution - Organization of Projects
  Solution contains 3 projects
1. Contact.API - Primary project which will expose the interface to client applications to consume Rest APIs to manage and maintain Contact information
2. Contact.Service - This project contains the business layer logic
3. Contact.Domain - This project contains Domain entities/data contracts which can be exchanged between REST application and client applications. Also this project has Contact Repository to interact with SQLExpress Database using Entity Framework (code first approach) 

# How to run the application
1. Unzip the ContactMIZ.zip and open Solution file with Visual Studio
2. Note that application uses SQLExpress local instance
3. Simply run the application; it will start the Contact.API project on IISExpress with Url http://localhost:57693/
4. Application is configured with Swagger UI to provide API documentation for entity Contact as well as UI interface to test APIs
