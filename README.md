Question 1 Assignment 03
This is a simple Express.js application that serves a webpage with multiple forms to perform various operations. The application provides four functionalities: summation of numbers, modifying text, finding average and median, and searching for four-digit numbers in a string.

Table of Contents
Installation
Usage
Endpoints
Form Details
License
Installation
To run this application locally, follow these steps:

Clone the repository (if applicable) or download the project files.

Navigate to the project directory using your terminal.

Install the necessary dependencies by running:

bash
Copy code
npm install
Start the server by running:

bash
Copy code
npm start
The server will start running at http://localhost:3000.

Usage
Once the server is running, you can interact with the application through the provided forms in the index.html file. Open your browser and navigate to http://localhost:3000 to access the application.

Endpoints
The application has the following endpoints:

GET /summation - Calculates the summation of a positive integer.
GET /uppercaseFirstandLast - Modifies the input text by capitalizing the first and last letters of each word.
GET /findAverageAndMedian - Calculates the average and median of a sequence of numbers separated by commas.
GET /find4Digits - Finds the first 4-digit number in a string of numbers separated by spaces.
Form Details
Summation:
Action: /summation
Method: GET
Input: A positive number.
Uppercase First and Last Letters:
Action: /uppercaseFirstandLast
Method: GET
Input: A text string where each word's first and last letters will be capitalized.
Find Average and Median:
Action: /findAverageAndMedian
Method: GET
Input: A sequence of numbers separated by commas (e.g., 1,2,3,4,5).
Find 4-Digit Number:
Action: /find4Digits
Method: GET
Input: A string of numbers separated by spaces (e.g., 22 33 454 1000 2345 32).
