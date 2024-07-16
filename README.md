# Speech_recognition_website

We worked as a group the group members: • Cady Alali • Dana Alghofaily • Kady Aldughaim

Speech to Text (Save to Database) This is a simple web application that allows you to convert speech into text using the browser's speech recognition API and save the recognized text to a phpMyAdmin database.

## Features
Start and stop speech recognition with a single button click.
Display the recognized text in real-time.
Save the recognized text to a phpMyAdmin database for future reference.

## Prerequisites
To run this application, you need to have the following:

Web browser with speech recognition support (Google Chrome recommended).
PHP installed on your local machine.
A phpMyAdmin database to store the recognized text.

## Setup
Clone or download this repository to your local machine.
Import the speech_to_text_db.sql file into your phpMyAdmin database to create the necessary texts table.
Update the credentials in the save_to_database.php file with your phpMyAdmin database credentials.
Start a local PHP server or configure your web server to serve the files in the project directory.
Access the application through the web server using a web browser.

## Usage
Open the application in a web browser.
Click the "Start" button to begin speech recognition.
Start speaking, and your speech will be converted to text in real-time.
Click the "Stop" button to end speech recognition.
The recognized text will be displayed below the button, and it will be saved to the database.

## Acknowledgements
This project was inspired by the speech recognition functionality provided by modern web browsers.
