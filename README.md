# ChatGPT clone using OpenAI API
This clone is made with React and Node and uses OpenAI API.

- get your api key from  https://openai.com/api/

## Prerequisites
Make sure you have installed all of the following prerequisites on your development machine:
* Git - [Download & Install Git](https://git-scm.com/downloads). OSX and Linux machines typically have this already installed.
* Node.js - [Download & Install Node.js](https://nodejs.org/en/download/) and the npm package manager. If you encounter any problems, you can also use this [GitHub Gist](https://gist.github.com/isaacs/579814) to install Node.js.

## Environment variables setup example
```
OPENAI_API_KEY = YOU_API_KEY_HERE
MONGO_URI = mongodb://0.0.0.0:27017/chatGPT
```


## Cloning The GitHub Repository
The recommended way to get ChatGPT clone is to use git to directly clone the repository:

```bash
$ git clone https://github.com/nisabmohd/ChatGPT.git
```

## Running Your Application

open terminal/bash in this repo and enter below commands to start the application

&#8594; To start the server
```bash
$ node server
```

&#8594; To start the client app
```bash
$ cd client
$ npm run dev
```



* Your client application should run on port 3000 with the *development* environment configuration, so in your browser just go to [http://localhost:5173](http://localhost:5173)

* Your server application should run on port 8000, so in your browser just go to [http://localhost:8000](http://localhost:3000)


<img width="100%" src="img/home.png" />
<img width="100%" src="img/chat.png" />
