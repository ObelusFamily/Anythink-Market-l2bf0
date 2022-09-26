# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

1. Install Docker first from https://docs.docker.com/get-docker/.
2. Check the successful installation by command docker -v and docker-compose -v
3. From PowerShell or Command Prompt go to root directory of project you cloned before and run command docker-compose up.
4. Thats all you are ready to aceess frontend at localhost:3001 and backend at localhost:3000/api/ping.
5. On successful installation go to localhost:3001/register and Create one (choose a cool nickname and everything) and you’ll be able to move to the next task.

##Thank You.
