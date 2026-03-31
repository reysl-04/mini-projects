# Command Line Interface (CLI) Quiz Game
A terminal-based quiz game that fetches questions from the public Open Trivia APi. Built to practice concepts of async/await, Promises, error handling and working with externals API'.

## Tech Stack
- Node.js
- readline (built-in) - terminal input/output
- he - HTML entity decode 
- Open Trivia API - question data source

Used `he` to decode HTML entities in API responses since the Open Trivia API returns encoded characters like &amp; and &#039; in question text.

## Set up
1. **Install dependencies**
```
npm install
```
2. **Run Quiz Game**
```
node main.js
```

## Usage
After running the file. You need to press enter to start the game.
To enter the correct answer, you need to copy/paste the answer. Do not enter the number because it will not work. Have fun!

If you find any bugs or ideas I can implement to expand this project, let me know! I would really appreciate it. Have a great day!

## Author
Alexander Reyes / reysl-04