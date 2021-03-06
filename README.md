# lightfeather-coding-challenge
This coding challenge is for the Lightfeather application process. 

# Requirements
- Node 8
- Git

# Setup
Clone the repo and install the dependencies.

```
git clone https://github.com/rking8888/lightfeather-coding-challenge  
cd lightfeather-coding-challenge
```
```
npm install
```

## Question 1 - Webserver
This solution was built using Express, a Node.js framework.

The following assumptions were made:
* All errors, including invalid JSON requests, will return a 500 and empty string.
* Successful encoded messages are stored in the encodedmessage.txt file - this is overwritten with every request.
* Requests where Shift is given a numerical String (i.e. "1") will be converted to an Integer before shift is done.

Steps to run:
1. Navigate to root folder.
1. Run `node server.js` - you should see "Server listening on port 23456..."
1. Post a request to http://localhost:23456/api/encode with JSON object to receive an encoded message.

## Question 2 - Web Component
This solution was built using React + Material UI framework. While an entire react app is a bit heavier than necessary for this challenge, I approached it as a real world problem with additional extendability in mind. 

The following assumptions were made:
* Submit button does not do anything when enabled and clicked on. 
* Form data is not stored anywhere.

Steps to run:
1. Navigate to **client/** folder.
1. `npm install` to install additional dependencies
1. Run `npm start`
1. Go to http://localhost:3000 to view web component
