# Chatbot Project

This project is a chatbot application built using Node.js, HTML, CSS, and JavaScript. It includes both frontend and backend components.

## Project Structure

- index.html: Main webpage for the chatbot UI.
- script.js : Frontend script for chatbot interaction.
- server.js : Backend server script (Node.js + Express).
- styles.css : Styles for the chatbot UI.
- package.json : Project dependencies.

## Code Explanation

### Frontend

- index.html : This file contains the chatbot UI structure, including an input field and a display area for chatbot responses.
- styles.css : Defines the appearance of the chatbot interface.
- script.js :
  - Listens for user input.
  - Sends user messages to the backend via AJAX or Fetch API.
  - Displays the chatbot's responses dynamically.

### Backend

- server.js:
  - Sets up a Node.js server using Express.
  - Handles incoming requests from the frontend.
  - Processes user messages and returns responses.
  - May integrate with a chatbot AI or predefined responses.

- package.json : Defines dependencies such as Express and Nodemon (if used for development).

## Installation & Setup

### Prerequisites

- Install [Node.js](https://nodejs.org/)

### Steps to Run

1. Navigate to the project directory:
   ```sh
   cd intern
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the server:
   ```sh
   node server.js
   ```
4. Open the chatbot webpage in a browser:
   ```
   http://localhost:3000
   ```

## Result Web Page

Once the server is running, access the chatbot at: [http://localhost:3000](http://localhost:3000)


