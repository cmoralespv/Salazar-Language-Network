# Salazar: Video Chat Language Exchange Application

## Summary
   This application was designed to connect students that speak different languages with each other in order to facilitate language exchange. This is done by allowing students to schedule video calls with each other that have live translation. Allowing students to have conversations with each other in different languages and the ability to convert it into a language of their choice that they can understand. 
   Since the students speak a variety of different languages the application offers the user a preference of language to display from the home page before signing in.
## Getting Started
```Config.js
enter example setup
```
```.env
.env example
```
## Features
### Sign Up
   - Google authentication is implemented using firebase.
   - Users profiles are created with information from their gmail account
   - Users can select multiple languages
       - Identify their profiency of a language using 4 skill levels
       - These fields are important for the search feature aloowing users to easily find other students of a specific language and proficiency.  
##
### Multi-Language Support
 - il8 Package provides support translating page for following languages.
     - English
     - Spanish
     - Portugues
     - French
     - Chinese
     - Korean
     - German
     - Swedish
     - Italian
##
### Messaging
 - Send text messages to other students
 - Translate them into another language!
##
### Scheduling
- Select Time, Date, and Language you want to practice with another student.
- Add a message with your invitation.
- Events are tracked using Google Calendar
    - Links are provided to specified calendar events
- Time until future calls are displayed from the Days ==> Hours ==> Minutes.
##
### Video Chat
- Students can select languages they want to translate
- As well as language they want to translate to.
- Original transcript from other student is displayed first
- Followed by translated transcription.
- Supported transcript languages
    - English
    - Spanish
    - French
    - German
    - Russion
    - Portuguese
    - Swedish
    - Korean
    - Italian
