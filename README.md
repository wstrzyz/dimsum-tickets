# How to Collaborate

## Request Access

Just send me a DM in Slack with your github email/username and I'll send you the invite

### Or just Fork

If you prefer just fork the repo, remember to keep your **master** branch updated.

## Add Prettier as your default code formatter in preference settings (**Workspace**):

`"editor.defaultFormatter": "esbenp.prettier-vscode"`

# Run

`npm ci`

`npm start`

# Summary

Each component in the left Tree View is mapped to a Jira ticket ID by name.

To add your ticket example just:

- Create your file in `src/YourDSComponent/YourTicketID`
- Add the file's path to `src/tickets.js`
- Test your changes in localhost
- Option 1 (master)
  - Push your branch and create the PR against **master**
  - Once merged it will automatically be deployed to https://dasm30.github.io/dimsum-tickets/
- Option 2 (develop)
  - Push your changes to develop no need for a PR (if you're a collaborator)
  - Automatic deployment will go to https://dimsum-tickets.herokuapp.com/