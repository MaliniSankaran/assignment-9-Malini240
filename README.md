[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/g07vwLwr)

# React Reminder App

This project involves converting Assignment 6 into a React application using Vite as the build tool and integrating it with REST APIs from Assignment 7. The application will serve as a reminder app where users can create, view, edit, and delete meeting notes.

## User Requirements:
- The application should allow users to view existing meeting notes fetched from the server.
- Each meeting note should display its title, truncated content, and action items.
- Users should be able to click on a meeting note to expand its content and view action items.
- Users should be able to toggle action items between open and completed states.
- Users should have the ability to edit the content and action items of a meeting note.
- Users should be able to add new meeting notes.
- Meeting notes should persist in the database through REST APIs.

## Technical Requirements:
- The project will be built using React.js, incorporating features such as expressions, lists, useState, props, and effects.
- Data will be fetched from the Node.js server using the fetch API.
- MaterialUI will be utilized for styling the application.
- Vite will be used as the build tool for the project.
- All data operations will interact with the server through REST APIs to ensure persistence in the database.

## Tech Stack Used:
- **Frontend:**
  - React.js: A JavaScript library for building user interfaces.
  - Vite: A fast build tool that provides a modern development experience for React applications.
  - MaterialUI: A popular React UI framework for building visually appealing and responsive web applications.
  - Fetch API: Used for making HTTP requests to fetch data from the server.
  
- **Backend:**
  - Node.js: A JavaScript runtime for building scalable server-side applications.
  - Express.js: A minimalist web framework for Node.js used for building APIs.
  - MongoDB: A NoSQL database for storing meeting notes and other data.
  
## Project Setup:
1. Clone the repository containing the project code.
2. Navigate to the project directory.
3. Install dependencies using `npm install`.
4. Start the development server using `npm run dev`.
5. Access the application in  browser at the provided URL.

## Usage:
1. Upon launching the application, users will be presented with a list of existing meeting notes.
2. Users can click on a meeting note to expand its content and view action items.
3. Action items can be toggled between open and completed states by clicking on checkboxes.
4. Users can edit the content and action items of a meeting note by clicking on the edit button.
5. New meeting notes can be added by clicking on the create button and filling out the necessary details.
