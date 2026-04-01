# NodeJS Assignment 2 - Submission Ready

Student Name: Nandini
Repository: https://github.com/nandinireddy-02/nandini-node-exercises
Render Deployment: https://nandini-node-exercises.onrender.com/

## Live URL Checks

- Home URL: https://nandini-node-exercises.onrender.com/
- Landing Page URL: https://nandini-node-exercises.onrender.com/landing.html
- Home Page URL: https://nandini-node-exercises.onrender.com/home.html
- About Page URL: https://nandini-node-exercises.onrender.com/about.html
- Contact Page URL: https://nandini-node-exercises.onrender.com/contact.html

## Required Project Structure

Nandini-NodeJS-Assignment2/
- exercise1.js
- exercise2.js
- exercise3.js
- exercise4.js
- package.json
- lib/
  - index.html
  - users.txt
  - home.html
  - contact.html
  - about.html
- public/
  - HTML, CSS, JavaScript files

## Exercise Endpoint Summary

### Exercise 1
- Endpoint: /api/exercise1
- Reads and returns lib/index.html
- Content type: text/html
- Status: 200

### Exercise 2
- Endpoint: /api/exercise2
- Reads lib/users.txt and renders HTML table
- Content type: text/html
- Status: 200

### Exercise 3
- Endpoint: /api/exercise3/pages/home
- Endpoint: /api/exercise3/pages/about
- Endpoint: /api/exercise3/pages/contact
- Returns matching HTML file from lib
- Content type: text/html
- Status: 200

### Exercise 4
- Serves static files from public using Express static middleware
- No hardcoded per-page routes
- Supports direct file access:
  - /home.html
  - /about.html
  - /contact.html

## Final Upload Note

For LMS upload zip, include only assignment files and folders.
Do not include .git or node_modules.
