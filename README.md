# Robot Spreadsheet

A bot that listens in for a command, and returns a different spreadsheet depending on which group it is listening to.

Original credit and project here [https://github.com/ACMatUC/groupme-bot-starter](https://github.com/ACMatUC/groupme-bot-starter)

I only added a modification to the command to get this to work.


## To Setup

1. Set the BOT_ID in the .env
2. Change the key value pairs in the group_spreadsheets.js to match whichever groups you're in.

Read the bot_instruction_readme.


## Running the Bot

After importing the new information, run the following:

1. cd /path/to/project_dir
1. npm install
2. npm install -g forever
3. forever start app.js

