# ChixaBaeBot - Discord Troll Bot

## Overview
ChixaBaeBot is a Discord bot built with discord.js v14, designed to provide various trolling functionalities for server administrators to use on their servers.

## Owner
- Owner Discord ID: 926191576659677205

## Features

### Core Troll Features
- **Message Mirroring**: Repeat every message and sticker sent by specific targeted users
- **Insult Generator**: Send random insults to selected users with API
- **Chat Injection**: Ability for admins to make the bot send specific messages in specific channels
- **Voice Channel Trolling**: Join voice channels and play annoying sounds

### Administration
- **Target Selection**: Commands to add/remove users from the troll target list
- **Troll Level**: Set intensity level of trolling for each targeted user
- **Cooldown Settings**: Configure frequency of troll actions
- **Whitelist Channels**: Set channels where the bot will never troll

### User Experience
- **Custom Responses**: Ability to add custom insults or responses
- **Random Timing**: Option to add randomness to when trolling occurs
- **Reaction Trolling**: Add random reactions to messages from targeted users

## Command Structure
- All administrative commands will require administrator permissions
- Regular users will not be able to control troll features
- Commands will use a prefix (e.g., `$troll`)

## Technical Requirements
- discord.js v14
- Node.js environment
- Persistent storage for configuration