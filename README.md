# Steam-Card-Bot-PRO
An free open source, fully automated Level Up Bot with all features and support + much more !


![GitHub package version](https://img.shields.io/github/package-json/v/Refloow/Steam-Card-Bot-PRO.svg)
[![GitHub forks](https://img.shields.io/github/forks/Refloow/Steam-Card-Bot-PRO.svg?style=plastic)](https://github.com/Refloow/Steam-Card-Bot-PRO/network)
[![GitHub stars](https://img.shields.io/github/stars/Refloow/Steam-Card-Bot-PRO.svg?style=plastic)](https://github.com/Refloow/Steam-Card-Bot-PRO/stargazers)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=plastic)](https://raw.githubusercontent.com/Refloow/Steam-Card-Bot-PRO/master/LICENSE)
[![Steam](https://img.shields.io/badge/steam-donate-yellow.svg)](https://steamcommunity.com/tradeoffer/new/?partner=392773011&token=CncehZti)


- This project will receive constant updates and new features added !

- Here is an announcements:
1. Code isnt perfect rn it has some issues (*not critical errors*), i have some more work to do tomorrow il release some patches
Hope you all having a great day !
2. Tomorrow new detailed tutorial on seting the bot up will be added to this file.


# DISCORD Support Server

https://discord.gg/XxvjjPs

# Unique Features

- Endless customization
- Each command can be disabled or enabled inside of the config file
- Commands are not case sensitive
- Has readable and understandable deb console logs


# Current Features

- Auto accepting friend request
  1. Uppon accepting friend request sending an welcome message        (Message can be set or disabled in config)
  2. Uppon accepting friend request adding user to the selected group (Group can be set or inviting disabled inside of the config)

- Chat spam protection (can be disabled or enabled in config)
  1. Uppon removing user sending him message (message can be set or disabled in config)
  2. Notifing admin when user get removed for spaming -sending user id (user can get blocked via admin command !block) (notifications can be disabled in config)
  3. Setting limit of messages per sec to count as spam

- Bot clearing friendlist (feature can be disabled in config)
  1. Sending message to the user which is removed (message can be set or disabled in config)
  2. Setting timer for removing inactive users (time can be set at config)

- CHAT LOGS
  1. Daily chat logs (can be disabled in config)
  2. Chat logs per user (can be disabled in config)
  
- Responding to incoming group invites (can be totaly disabled in config)
  1. Auto declining incoming group invites
  2. Auto accepting incoming group invites

- Commenting after trade (comment can be set or commenting disabled in config)


## INFO COMMANDS such as:

- !info (custom command)
- !owner (showing owner profile)
- !sellhelp (custom command)

- !commands (- Gives out list of the commands) - List of the commands automaticaly update depends on your config and display only commands which are enabled
- !help - Same command as !commands but it is !help instead of !commands

(You have option to disable one, or both of them, also both can be enabled, customize it how you like it !)

- INTERACTION COMMANDS such as:

## Checking commands
- !check (Displays amount of sets bot has to offer to user (not counting sets that user already crafted))
- !sellcheck (can be disabled in config) (// This command when called checks user inventory and gives info about sets he can sell to bot) 
- !buyonecheck (can be disabled in config) 
- !buyanycheck -soon (next update)
- !stock (Displays stock of the bot)

## Calculation commands

- !level dream_level


## BUY COMMANDS:

- !buy - - - (can be disabled in config) - - - - (// This command when called sell sets for keys (main currecy that you set default is cs go keys) following current bot rate)
- !buyany - - - (can be disabled in config) - - - - (// This command when called sell any sets for keys to user without checking badges)
- !buyone - - - (can be disabled in config) - - - - (// This command when called sell sets for keys but (gives user 1 set from each game that he hasnt crafted) - For badge collectors

- !buyref - - - (can be disabled in config) - - - - (// This command when called sell sets to user for ref metal)
- !buyhydra - - - (can be disabled in config) - - - - (// This command when called sell sets for user hydra keys)
- !buycsgo - - - (can be disabled in config) - - - - (// This command when called sell sets to user for csgo keys)
- !buytf2 - - - (can be disabled in config) - - - - (// This command when called sell sets to user for tf2 keys)
- !buygems - - - (can be disabled in config) -soon (next update)
- !buypubg - - - (can be disabled in config) -soon (next update)

- !buyoneref - - - (can be disabled in config) -soon (next update)
- !buyonehydra - - - (can be disabled in config) -soon (next update)
- !buyonecsgo - - - (can be disabled in config) -soon (next update)
- !buyonetf2 - - - (can be disabled in config) -soon (next update)
- !buyonegems - - - (can be disabled in config) -soon (next update)
- !buyonepubg - - - (can be disabled in config) -soon (next update)

- !buyanyref - - - (can be disabled in config) -soon (next update)
- !buyanyhydra - - - (can be disabled in config) -soon (next update)
- !buyanycsgo - - - (can be disabled in config) -soon (next update)
- !buyanytf2 - - - (can be disabled in config) -soon (next update)
- !buyanygems - - - (can be disabled in config) -soon (next update)
- !buyanypubg - - - (can be disabled in config) -soon (next update)

## SELL COMMANDS:

- !sell - - - (can be disabled in config) - - - -  (// This command when called sell keys for sets) - Uses main currency set at: KEYSFROMGAME

- !sellref - - - (can be disabled in config)
- !sellhydra - - - (can be disabled in config) - - - - (// This command when called sell hydra cs go keys for sets to user)
- !sellcsgo - - - (can be disabled in config) - - - - (// This command when called sell csgo keys for sets to user)
- !selltf2 - - - (can be disabled in config) - - - - (// This command when called sell tf2 keys for sets to user)
- !sellgems - - - (can be disabled in config) -soon (next update)
- !sellpubg - - - (can be disabled in config) -soon (next update)

## Admin commands:

- !block user_id (admin command to block user from using bot due spaming)
- !usercheck
- !withdraw (command for admin to withdraw keys)
- !donatesets

## Others

- !donatesets


# Prerequisites (What bot require to start)
- Node.js (https://nodejs.org/en/)
- Text editor (recommend sublime: https://www.sublimetext.com/3)

# Essentials
- Steam Account
- Shared Secret code ([What is ?](https://searchsecurity.techtarget.com/definition/shared-secret) | [How to get it on IOS ?](https://forums.backpack.tf/topic/45995-guide-how-to-get-your-shared-secret-from-ios-device-steam-mobile/) | [How to get it on android ?](https://forums.backpack.tf/topic/46354-guide-how-to-find-the-steam-identity_secret-on-an-android-phone/))

# Detailed YouTube Video Tutorial

Comming soon.

# Setup Guide (Step By Step)

To setup bot follow next steps.

Step 1 (Get the files)
- Click clone or download, get the files unzip them. 

Step 2 (Install requirements)
- Next thing to install if previously not installed is node.js and text editor
- GET NODE.JS HERE: https://nodejs.org/en/
- To edit config file you need text editor by choice you can use notepad ++, visual studio code and many more...
- MY CHOICE IS SUBLIME text editor
- GET SUBLIME HERE: https://www.sublimetext.com/3

Step 3 (Fill config)
- Fill the config with sensitive data such as steam username, password, shared secret.
- Fill the group id (can be found in browser go to group page and inspect element)
- Fill the welcome custom message for bot to sent custom message when request is accepted.
- Personalize configuration in config

Step 4 (install bot modules)
- Double click install.bat file for modules to be installed.

Step 5 (run the bot)
- Click start.bat file to run bot.

If there is any questions feel free to ask me on: https://steamcommunity.com/id/MajokingGames/

# Support the project
- If you like the project and the fact that is free you can support us by giving an donation.
- We are accepting donations on:

1. Steam: https://steamcommunity.com/tradeoffer/new/?partner=392773011&token=CncehZti


# Want Improvements ?

If you have some requests feel free to contact me : https://steamcommunity.com/id/MajokingGames/ i can code custom features to the Bot.

This project is licensed under the MIT License - see the LICENSE file for more details
