# Note Taker (powered by Express.js)
Week-11 Challenge


## Table of Contents

 * [Description](#description)

 * [Technologies-Used](#technologies-used)

 * [Installation](#installation)

 * [Features](#features)

 * [Usage-Information](#usage-information)

 * [Contribution-Guidelines](#contribution-guidelines)

 * [Test-Instructions](#test-instructions)

 * [License](#license)

 * [Questions](#questions)

## Description

This application was designed to give users a place to store notes to help them organize their thoughts and to keep track of tasks they need to complete. It is powered by Express and JavaScript and implements an imitation database using a json file (db.json) to save and retrieve data.



## Technologies Used

This project is powered by Express.js, Node.js (v16.19.1), and JavaScript. It utilizes uuid (node package manager), and file system module (node package manager) as dependencies, and utilized an application called Insomnia to test GET, POST, and DELETE request routes without needing a front end framework built out.

## Installation

1. Clone the repo:
   git clone https://github.com/cqc0013/Note-Taker-Week-11.git

2. Open in VS Code. If you do not have VS code you must install it.

3. Using the terminal, install node.js v16.

4. Once node.js v16 is installed, in the terminal, utilize the command npm init -y to initialize and create a package.json where project files will be stored.

5. Next, use the terminal to run the command npm i to install the dependencies associated with this application (developers may need to install express and uuid directly from the command line, to do so the command for express will be npm i express to install the latests version of Express framework globally so that it can be used within the node terminal, and npm i uuid to install the latest version of uuid).

6. To run the server, within the terminal, type the command npm start or node server.js.

7. Once the server is running, users can then access the front end of the application within the browser to observe full functionality of the site.


## Features

Features of this application include the users ability to retrieve and save notes from/to a mock database.json file which will persist on page load unless deleted.  

## Usage Information

This application is powered by Express meaning for it to function properly, there needs to be a server running in the background. To start the server, navigate to the directory of the application, install all dependencies (npm i), then type the command npm start (or node index.js). A message should then display in the command line saying "App listening at http://localhost:3001 🚀". Once the server is running, then navigate to the front end of the application directly from the command line by holding command and clicking the link http://localhost:3001. From there, users can pull up any existing notes saved to the database or create new notes, which once saved will be pushed to the database and persisted.

## Contribution Guidelines

Open to collaboration, if you choose to do so open an issue and modify any changes you would like to see on a feature branch and wait for approval before merging to the main branch.


## Test Instructions

There is currently no unit testing yet written for this application.

## License

N/A

## Questions

Have additional questions? Click the links below to reach me through my GitHub account.

[Link to Github](https://github.com/cqc0013)

