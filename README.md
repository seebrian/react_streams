This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

# React Streaming Application
A simple prototype of Streaming application using react, redux, node media server and json server. 
<img src="https://github.com/seebrian/seebrian-react_streams/blob/master/screenCapture.png">
#### Features:
* CRUD Stream Information
* Support Google Auth
* Allows users to directly stream video/audio

## Demo
Json Server: <a target="_blank" href="https://streams-jsonserver.herokuapp.com/">https://streams-jsonserver.herokuapp.com/</a>
<BR>
Client Application: <a target="_blank" href="https://streams-client.herokuapp.com/">https://streams-client.herokuapp.com/</a>
<BR><BR>
Please note that
*  Actual streaming is only available on localhost because Heroku support says that they only allow 80 and 443 HTTP/S ports and they do not officially support RTMP.
*  Users must sign in with google to create a stream.
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

What things you need to prepare

* OBS

### Installing

A step by step series of examples that tell you how to get a development env running

1. Clone the repository 

2. Enter to project directory

```
cd into the project folder
npm install
```
3. Start Json Server
```
cd api
npm start
```
4. Start client application
```
cd client
npm start
```
5. Start RTMP Server
```
cd rtmpserver
npm start
```
## Techologies
* React
* Redux
* Axios
* react-router-dom
* Redux-thunk
