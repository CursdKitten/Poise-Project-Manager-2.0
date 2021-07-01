# Poise-Project-Manager

## Description

A simple project managememt program designed for a for a small structural engineering firm. The program takes in user information with regard to the project name, costs involved, contractors' information and the like.

### Dependencies

The libraries imported are:  
* java.sql
* java.util
* java.text
* java.time

The program is made up of the following src files:
* Project.java
* Person.java
* UpdateProject.java
* DataManip.java
* ProjectPersonMain.java

The program works with the poisepms mysql database containing the following tables:
 * project table
 * participants table
 * participant_details table
 * invoices table

### Executing program

The user will be prompted to enter the following information:
* The corresponding number of the action they would like to take from the main menu
  - 1 - Enter project
  - 2 - Update project
  - 3 - Search projects
  - 4 - View incomplete projects
  - 5 - View overdue projects
  - 6 - Finalise project
  - 7 - Add participant
  - 8 - Update participant details
  - 0 - Exit
  
* If the user chooses to enter a new project, they will be prompted to enter the following information
  - Customer name 
  - Customer telephone number
  - Customer email
  - Customer address
  - Project manager assigned to the project
  - Architect assigned to the project
  - Engineer assigned to th eproject
  - Project name assigned to the project
  - The type of building that is being designed i.e. house, apartment etc.
  - The address of the building to be designed
  - The ERF number
  - The total fee charged for the development
  - The amount paid by the client to date
  
* If the user chooses to enter a new participant, they will be prompted to enter the following information
  - The participant type i.e. project manager/engineer/architect/customer
  - The name of the participant
  - The telephone number of the participant
  - The email address of the participant
  - The physical address of the participant
  
* All the above information is then pushed to various tables in the poisepms database.
 
 The rest of the menu options gives the user the option to uodate the above details for existing projects/participants, search projects, view incomplete
 or overdue projects and finalise projects which changes the status to "Finalised" with the date of finalisation listed and generates an invoice if the 
 customer still has outsanding balance due.

## Authors

* Kirsten Forrester

## Contributors names and contact info

Tel: 071 872 0132

Email: forrestermkirsten@gmail.com
