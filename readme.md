# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

### Tips for Smooth Running of the project

After setting up docker on your machine. Run the command below to setup and run the project

```
 docker-compose up
```

```
If you encounter any issue, ensure that the package manager in the docker-compose yaml file is same with the one on your machine.

For example, if you're using yarn, you don't have any issue. But if you're using npm, you may need to change the yarn in the docker-compose file to npm.

### For package dependency issue with npm
You would need to update the yaml file to take the flag --legacy-peer-deps for npm machine


```
