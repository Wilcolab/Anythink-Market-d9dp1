# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## Setup
1. Clone the repo
```
git clone https://github.com/ObelusFamily/Anythink-Market-d9dp1.git
```
2. [Install Docker](https://docs.docker.com/get-docker/)
3. Verify docker is ready by running the following commands in your terminal.
```
docker -v
```
4. In the terminal, change the directory to project's root directory,\
 eg. ```cd C:\Anythink-Market-d9dp1```
5. If you are having Windows OS, then firstly open `Docker Desktop`, and make sure Docker for Windows is up and running in the system tray.
6. In the terminal, run,
```
docker-compose up
```
7. If Docker is working correctly, the backend should be running and able to connect to your local database.\
Check this by pointing your browser to http://localhost:3000/api/ping
8. Now, it’s time to check the frontend and make sure it’s connected to the backend.\
If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register \
Create a new user. 

The Setup is ready now.
