# Expedia

A website that reads data from JSON file, and filters them based on user-input filters.

## Getting Started

The website is deployed to: https://expfinal.herokuapp.com/

### Prerequisites

To run the project, All you need is to make sure you have Java JDK 8, an IDE for Java (preferably Intellij), maven-3, and Tomcat9.0.0.M20 installed on your local machine.

### Running the app


Checkout all code using the command:

  git clone https://github.com/Ala1000/Expedia.git
  
Run the following command:
 mvn clean package

  
Open Intellij and choose Import Project.

Select the directory where you cloned the project.

From the "Import Project" From, select "Maven".

Follow Intellij's form, then click finish.

Make sure to mark main--> Java as "Sources root"

Edit Run configurations to Run via Tomcat.

## Technologies used

For the project purposes, Java Servlet-JSP was used. 
For testing on local machine, I used Tomcat9.0.0.M20.

### And coding style tests

Code tests can be found in com.Servlets.Test folder.
All tests were passed.

## Deployment

Website is deployed to Heroku and can be accessed via: https://expfinal.herokuapp.com

## Issues 
The application is very simple, and it focuses more on the backend.
Deployed successfully, but still not working.

