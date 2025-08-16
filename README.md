# Threat Modeling Assignment

This repository is a minimal starting point for a threat modeling exercise.

## Sample Web Application Scenario

The sample application to be modeled has the following features:

1. **Login Page**
   - Presents the user with a login form (username and password).
   - Credentials are sent to the web application for verification.

2. **Open-Source Authentication Component**
   - The application uses an open-source authentication component to validate user credentials.
   - Credentials are checked against records in a database.

3. **Message of the Day (MotD)**
   - If login is successful, the application retrieves a *Message of the Day* from the database.
   - The message is displayed to the user in the web browser.

4. **Commenting Feature**
   - Logged-in users may submit comments on the MotD.
   - Comments are stored in the database.

## Threat Modeling Tasks

This repository will serve as the home for artifacts created during the threat modeling process:

- A **ThreatDragon threat model** titled *Initial Threat Model*.
- A **data flow diagram (DFD)** named *Initial Threat Model Diagram*, showing:
  - **Actor:** User Web Browser  
  - **Processes:** Web Application and Open-Source Authentication Component  
  - **Data Store:** Database (Users, MotD, Comments)  
  - **Trust Boundaries:** Internet, Application/Backend, Database  
  - **Data Flows:** login request, credential check, MotD retrieval/display, comment submission  

## Purpose

This repository is intentionally minimal. It provides just enough context to begin creating and analyzing a threat model.  
The goal is to use this project to identify potential threats using the STRIDE model, consider risks introduced by the open-source component, and document possible mitigations.


*This repository is for academic use as part of a threat modeling assignment.*
