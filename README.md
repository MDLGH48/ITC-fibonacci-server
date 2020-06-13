
```bash
 ___  _________  ________     
|\  \|\___   ___\\   ____\    
\ \  \|___ \  \_\ \  \___|    
 \ \  \   \ \  \ \ \  \       
  \ \  \   \ \  \ \ \  \____  
   \ \__\   \ \__\ \ \_______\
    \|__|    \|__|  \|_______|
```

# Fibonacci Server

This is a Fibonacci server, implement in Node.js

## Installation

Clone the repo (all commands are in the terminal in linux/mac or cmd in windows)

```bash
> git clone https://github.com/yonathan06/ITC-fibonacci-server.git
```

Then enter to the created folder

```bash
> cd ITC-fibonacci-server
```

Install the required dependencies with npm (make sure you have [Node.js](https://nodejs.org/) installed, npm comes with that)

```bash
> npm install
```

## Running The Server Locally

Then you can run the server

```bash
> node app.js
```

You should see something like this:

```bash
App listening on port 5050
Press Ctrl+C to quit.
```

# Milestone 4

### Features
Run the following local server: ITC-fibonacci-server (read the readme!)
Create a function that calls this server on this address: http://localhost:5050/fibonacci/:number, where :number is a parameter passed to the server to be calculated
The response is the calculated fibonacci, present it to the user.
Calling the server should replace your implementation of calculating fibonacci


# Milestone 5

### Features
Present a loader to the user when a call is made to the server (indicating the server is calculating)
Present an error to the user if the input number is more than 50, and do not send a server request
Try passing the number 42 to the server. The server will send back an error, present this error to the user. (read fetch() docs to see how to identify if the server sent an error)
Follow the second row of screens in the figma design

# Milestone 6

### Features
Create a function that calls the server with this url: http://localhost:5050/getFibonacciResults 
Call this function when the screen loads. You will get a list of fibonacci calculations that you previously submitted to the serverw
Present the list to the user under the calculator
The list should be updated every time the user makes a new calculation (suggestion: create a function the takes the data from the server response, and creates the html list to present to the user, and call this function after the user makes a new calculation)
Follow the third row of screens in the figma design

# Milestone 6.1 - Geekout

### Features
Transform all you functions with promises in them to async/await

# Milestone 7

### Features
Add a checkbox, under the calculator with “Save Calculation” text
If it is checked, calculate the fibonacci through the server (so it will save it to be presented in the list)
If it is not checked, calculate the fibonacci locally in your function (won’t sent a request to the server)
Follow the fourth row of screens in the figma design

# Milestone 7.1 - Geekout

### Features
Add a select box with sort by date asc or desc / number asc or desc
After the user is checking one of the items in the list, rearrange the list to match the sorting preferences
Follow the fifth row of screens in the figma design


## License

[MIT](https://choosealicense.com/licenses/mit/)

