Faculty Feedback is the feedback system in our college.So that we will collect the feedback for the lecturers from our students.After that only the admin should should watch the feedback of all members. On clicking sort button it will sort according to the percentages.

@echo off
:: ============================================================
::  Project Name: Feedback System
::  Description : A web application for submitting and viewing
::                user feedback. Built with Node.js and Express.
:: 
::  Technologies Used:
::    - Node.js
::    - Express.js
::    - MongoDB 
      - HTML
      - CSS
::    - EJS (Embedded JavaScript Templates)
:: 
::  Author: Anjani
::  Date: April 2025
:: ============================================================

:: Step 1: Navigate to project folder
cd /d "%~dp0Feedback"

:: Step 2: Install dependencies
echo Installing dependencies...
npm install

:: Step 3: Start the application
echo Starting the Feedback System...
node index.js

:: Step 4: Done
echo.
echo Feedback System is now running.
echo Open your browser and go to http://localhost:3000 (or the port mentioned in index.js).
echo.

pause
