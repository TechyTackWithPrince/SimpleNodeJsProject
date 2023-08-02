# Simple Node.js App

This is a simple Node.js application that demonstrates basic routing using Express. It has three endpoints: '/', '/demo', and a default error response for any other routes.

## Prerequisites

Before running the application, make sure you have the following installed on your machine:

- Node.js (at least version 10)

## Installing Node.js

### macOS and Linux

1. Open your terminal.
2. Check if Node.js is already installed by running the following command:
3. If Node.js is not installed, you can download it using a package manager:

```node -v
For macOS using Homebrew:
brew install node
```

```
For Linux using a package manager like apt:
sudo apt update
sudo apt install nodejs
```


Alternatively, you can download the Node.js installer from the official website: https://nodejs.org/

### Windows

1. Open your browser and go to the official Node.js website: https://nodejs.org/
2. Download the latest LTS version (recommended for most users) for Windows.
3. Double-click the installer and follow the installation wizard.

## Clone and Run the App

1. Clone this repository to your local machine using Git:

```
https://github.com/TechyTackWithPrince/SimpleNodeJsProject.git
```

2. Change directory to the project folder:

```
cd simple-nodejs-app
```

3. Install the project dependencies using npm:

```
npm install
```


4. Run the server:

```
node app.js
```


5. The server will start running at http://localhost:7000
- Visit http://localhost:7000/ for the "Hello, world!" response.
- Visit http://localhost:7000/demo for the "Demo world!" response.
- Any other route will return an error message with a 404 status code.

## Contributing

Feel free to fork this repository and make your own changes.

