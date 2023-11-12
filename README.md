# DayZ Killfeed Bot

A general purpose Discord Bot to handle DayZ Killfeed, stats, alarms and factions' armbands and more using Nitrado Log files.

* [Getting Started](#getting-started)  
  * [Prerequisites](#prerequisites)  
  * [Installation](#installation)

### Built With

* [Node.js](https://nodejs.org/en)
* [Discord.js](https://discord.js.org/#/)
* [MongoDB](https://www.mongodb.com/)

## Getting Started

The bot requires minimal setup to get started.

### Prerequisites

1. [Create your Discord Bot and get the private token](https://github.com/reactiflux/discord-irc/wiki/Creating-a-discord-bot-&-getting-a-token) for later configuration. Invite this bot to your desired discord server.

2. You'll need some important private information from your Nitrado account for later configuration.  
  i.   Your Nitrado user ID  
  ii.  Your DayZ Nitrado server ID  
  iii. Create and Copy your Nitrado authentication token.  

3. You'll need to setup an instance of MongoDB. You can use the cloud platform, MongoDB Atlas, or create your own instance locally.  
  i.  [Create your MongoDB Altas instance.](https://www.mongodb.com/docs/manual/tutorial/getting-started/)  
  ii. [Create your local MongoDB server instance.](https://www.mongodb.com/docs/manual/administration/install-community/)  

    After this, you'll need to get your MongoURI from your database instance, as well as your database name for later configuration.

### Installation

 Clone the repo
```
```
 Rename `.env.example` to `.env`
 Enter desired values into `.env`
```
    token='Your Discord Bot token'
    mongoURI='Your mongodb URI'
    dbo='Your mongodb database'
    SERVER_ID='Your Nitrado server ID'
    USER_ID='Your Nitrado user ID'
    AUTH_KEY='Your Nitrado Auth Token'
    GuildID='Your Discord Guild ID'
```
