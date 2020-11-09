# FEC Proxy Server Template

## Overview
This is an template proxy server that you can use to quickly display all four individual services on one page, and ensure that your client applications will be able to communicate with their corresponding API. It consists of some middleware that serve up static asset requests, proxy requests for your individual client application bundles, and proxy requests from running client applications to their respective service.

## Instructions
- Run `nvm use` to switch the version of node required for this project. If this version isn't currently installed, run `nvm install` to install this version
- Run `npm install` to install all the project dependencies
- Read the information and instructions in `server/config/services.js` to provide the required configuration information to enable the proxying functionality
- Run `npm start` or `npm start:dev` to start the server