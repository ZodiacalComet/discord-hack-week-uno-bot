# Instar
A poor attempt at making a game of UNO in a Discord Bot using Python and [API wrapper for Discord](https://github.com/Rapptz/discord.py) made by Danny for the **Discord Hack Week #1** in the **Entertainment** category.

Since I can't host the bot, it was made to take care of everything itself. So you can host it, make a server, invite some friends and use the `uno.start` command.



For it to work, it needs the **Manage Channels**, **Manage Emojis**, **Manage Roles** and **Manage Messages** permissions. Or you can give it **Administrator** and be done with it, your choice.

**Current status:** `Work In Progress`

## Set up
- Have [Python 3.7.3](https://www.python.org), as of now the newest version, installed on PATH and a bot account created on the [Discord Application Page](https://discordapp.com/developers/applications).
- Pip install the `requirements.txt`.
- Rename the `token.example.json` to `token.json` and add your own bot token as the value of the only key in that file.

## Commands

### uno.start

The command that you'd use to start a UNO game, where it'll wait for other users to join to a max of six, which can be changed in the `config.py` file.
If it is the first time you use it, Instar will create everything it needs for the game (channels, roles and emojis) before starting.
![Image1](https://media.discordapp.net/attachments/592826120567652585/593890333251600393/unknown.png)

### uno.reset

You should not touch anything that Instar creates, if you want/need to delete them or have stumbled upon an error that needs a good old reset, this is what you should use.

### uno.info

Instar just sends a message, nothing else happens.