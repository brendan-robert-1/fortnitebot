# fortnitebot
This project is a simple Discord bot that sits on top of discord.py to provide simple messaging commands to display common fortnite stats. 
It utilizes the fortnite tracker API to query the information. See https://fortnitetracker.com/site-api for details.

These are the commands that are currently supported, all of which take either 2 or 3 positional arguments.

<b>!kills</b> [username] [scope] [game_mode]
  Shows 


[username] - Username as it appears in Epic Games. This is case insensivite but subject to change if fortnite tracker changes
[scope] - Scope of the timeframe. Currently only s3 and lifetime are supported options
[game_mode] - For which game mode? Currently solo, duo, and squad are supported options
