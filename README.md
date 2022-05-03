# cs426 - RockFIIT

## Authors
Cyrille Bernabe, Louis Doherty, Juan Caridad, Rommel Macatlan Jr., Aitor Navarte

## About RockFIIT
Our creators all have a background in some sort of fitness, some of us are rock climbers, some of us are weightlifters, but some of us are both. The goal of RockFIIT, was to create an application that merged both these aspects of fitness together. Creating one centralized application where climbers and lifters could log their exercises, create their own programs and set their own fitness goals. 

1. RockFIIT Functionalities
   - Home Screen
     - Graph that displays data based on logged exercises
     - Timer, so the user is able to time their rest in between sets
     - Log Exercise button, that takes the user to a modal, containing a drop down list of all exercises in the database so the user can select and log a workout
     - Date and time
   - Login Screen
     - Basic login screen that has form validation so that it checks if the user has entered the required fields
     - If the user has created an account, when the login button is pressed the applicaiton will check within the database if the user exists
     - If user exists, then prior to loading into the application the program will grab all the users information from the database   
   - Signup Screen
     - Basic signup screen with form validation to check if the user has entered the fields correctly
     - Once the user hits sign up, the application checks if the user is not yet within the database, if not the user has successfully created an account 
   - Calendar
     - Grabs all of the users previously and current logged exercises, and displays them on the date that they were logged
   - Fitness Screen
     - Comes with preloaded default exercises from the database, that users are able to choose and add to their account
     - The user is also able to create their own custom programs using exercises from the database and add them to their account
     - When selecting on a program the user also has the ability to check the descriptions of each workout
   - Goals Screen
     - The user has the ability to create goals based on the exercises within the database
     - When a user logs an exercise, the application checks if one of their goals matches the logged exercise if so the goal is marked as completed
   - Settings Screen
     - Sign Out button that lets the user log out of their account
     - Change password button, allows the user to change their password and if password changed logs them out and has them resign in


IMPORTANT: In order to run...
  You will need node.js and expo installed. Clone repository (or simply download rockfiit folder), and enter the rockFIIT folder using your terminal. Run npm install to install expo to the project. Then simply run npm start, and open the project on an emulator or your mobile device.
  
NOTE: All of the dependencies should be included in the github folder. We have had some errors where some get uninstalled upon cloning, though. In this case, just run npm install ..., where ... is the dependency that the errors are saying could not be found. 
