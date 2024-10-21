# Chaintoolz bot discord


This bot works best running as close to the ME API as possible (as the API is in beta testing and is therefore not the most efficient) using AWS or something similiar. 

To set up this bot, install the libraries required, enter the token for your discord bot and find the channel ID for the channel you would like the alerts to be sent to and enter this at the top of main.py at the variable name mainChannel.

I've included a sample sqlite3 database with some collections and to show how data is stored within this application. If you would like to start from fresh, delete the database and the api_call library will create a new one on startup.

<strong>Below are some screenshots of how alerts are printed:</strong>

The message sent every time an NFT in a collection in the alerts list is bought/sold.

<img src="/example_screenshots/activity.png">

A message sent every 24 hours updating users on a collection in the watch list.

<img src="/example_screenshots/stats.png">





