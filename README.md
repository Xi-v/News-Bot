# Welcome to the News Bot GitHub Repo
### This is a Repo that open sources this discord bot so that the community can make their own changes to it, and add features, and so you can run the bot on your own server!

## Install

### Linux
To install first clone the github repo
You will need git installed to be able to do this
`git clone https://github.com/Xi-v/News-Bot.git`

Then enter the directory created
`cd ~/News-Bot`

Next you will need to install the requirements.txt
`pip install -r requirements.txt`
Some distros might require you to make a python virtual environment, please refer to the internet or documentation to install.

To run this on your own bot you will need to copy the API key for you bot, to edit the code so that it actually runs, please run 
`nano bot.py`
and scroll down to the bottom where the Bot Startup section is.
Replace the **[YOUR_API_KEY]** with the API key you copied from your discord applications bot.

After all of this your bot should be able to run so enter the command
`python3 bot.py`
and you should see the bot become active.

### Windows
To install clone the github repo.
Git will need to be installed
`git clone https://github.com/Xi-v/News-Bot.git`

Enter the directory `News-Bot` and then run `pip install -r requirements.txt` to install the required python libraries

Edit the python file to have your Discord API key using your ide or Notepad. 
Scroll down to the bottom where the Bot Startup section is.
Replace the **[YOUR_API_KEY]** with the API key you copied from your discord applications bot.
Save the file and exit

You can now run the bot by using your ide or powershell and enter the command `python bot.py`

The bot should now be active

### MacOS
fuh knows how to do it on MacOS, you're on your own lmaoo

