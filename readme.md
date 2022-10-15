# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
For future employee:
Steps for setting up new environment:
1. Create codespace 
2. Run the command: docker-compose up, Once docker-compose finishes loading up, the backend should be running and able to connect to the database.
3. After the server is up, make sure you test it by pointing your browser to https://obelusfamily-anythink-market-hh1b8-q7x4g6q94992j5w-3000.githubpreview.dev/api/ping 
4. If everything is working properly, you’ll be able to create a new user on https://obelusfamily-anythink-market-hh1b8-q7x4g6q94992j5w-3001.githubpreview.dev/register
5. 
