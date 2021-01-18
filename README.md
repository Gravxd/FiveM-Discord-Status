# FiveM-Discord-Status
 Updated Version of Live Status from my previous repo (https://github.com/Gravxd/FiveM-Server-Status-Bot)

**Note: Only members with administrator perms can setup the live status!** 


`Setup`

First, navigate to the channel you want to have the live status display into.
Then use !setup.

This will send a message from the bot into the channel you used the command in. 
Once the bot sends the message, right click this message and copy the id. This will be the `messageID` that we need for the `settings.json`.

Fill in all sections of the `settings.json` file.

Once this is done, go to `token.json` and put your discord bot token into it.
If you do not know how to get a bot token, go to https://discord.dev

Once the token is entered, the bot can be launched by opening the `startBot.bat` file!

**Any issues, please join the [support server.](https://discord.gg/ZYHxxba)**

`Example`

This is an example of how a completed `settings.json` file should look like:

![Example Settings](https://drive.google.com/file/d/1LkqV9ldtMOVZv1bhwxN_p5x-OZYURGLC/view?usp=sharing)

The last two options are for if you want a channel name to be updated with the player count.

If you set the enableChannelStatus to 'No.', then it will disable this.

channelID & channelStatusID do not have to the be the same.


`Final Products`

![How it looks!](https://imgur.com/a/8vWK4Sx)
