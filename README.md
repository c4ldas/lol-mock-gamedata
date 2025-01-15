# About

League of Legends `allgamedata.json` file example for use in mock requests.

This repository contains a copy of the allgamedata.json file generated locally by League of Legends. The file can be accessed during a live game via `https://127.0.0.1:2999/liveclientdata/allgamedata`. It updates in real time whenever a new event occurs in the game.

This file is only accessible locally and has CORS enabled, making it challenging to access directly from frontend applications.

Once the game ends and the client returns to the post-game screen, the URL becomes inaccessible until a new game begins.

The example file in this repository represents the JSON data generated at the end of a game. It includes all event types that may occur during gameplay.

# Justification

The primary purpose of uploading this file is to support mock requests for a widget I created called [League of Legends Scoreboard](https://github.com/c4ldas/streamelements-widgets/tree/main/league-of-legends-scoreboard).

# How to access

In order to access the .json file, do a GET request to `https://raw.githubusercontent.com/c4ldas/lol-mock-gamedata/main/allgamedata.json`. As the repository is public, no authentication is required (unless Github changes that in the future).
