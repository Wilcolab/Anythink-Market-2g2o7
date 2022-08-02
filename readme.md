# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

#### This section Goes through the Installation of the project in your Local Machine.

* First, clone this repository to your local machine. (Recommended using Git)

```bash
  git clone `https://github.com/ObelusFamily/Anythink-Market-2g2o7.git
```

* Now download Docker from their official website. After downloading, install Docker as given on their website.

 * To Check whether the Docker was installed correctly. Please type the below code in the terminal
```bash
docker --version
```
You might get a Similar type of output.
```bash
Docker version 20.10.8,
```
#### Now Open Docker Desktop on our machine. ( If you face an error in opening Docker, uninstall it and reinstall the lower version of Docker)

* Now, go to the directory where you cloned the repository. In this repository, open the terminal. Type following command

```bash
docker-compose up
```
If everything goes right, you will find docker images in our Docker Desktop, and a Container will start running.

* To test Backend is running. Go to the following link

```bash
http://localhost:3000/api/ping
```
#### If you see the message  "Pong! Seems like Everything is working, great job!" 
#### you successfully installed Backend.

* To check whether Frontend is working, go to the following link and register

```bash
http://localhost:3001/register
```
### If you  are Logged in, then you have successfully installed the program on your Local computer