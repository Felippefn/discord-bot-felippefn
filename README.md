# discord-bot-py-V2

A Discord bot app made in Python for fun

## Discord Bot + E-Commerce Application

This bot serves as a support tool for Discord servers with multiple features.

Using the command `!help`, the bot will show all available commands to try and use.

### Commands:

- 💬`!ticket`📋
  - This command sends an embed UI to a chat (if there isn't one already) allowing users to select the type of ticket they want.
  > **Options**: 
        **Support**, **Financial**, **Bugs**, **Others**
  - **For each option**:
    1. The bot will create a channel that only the user and MODs can see and send messages.
    2. The bot will DM the user to remind them of the channel and provide a link to the ticket channel.
    3. The bot will send a message into the ticket channel.

- 💬`!match`🕹
  - This command allows users to set up a match before gameplay/service.
  > **Steps**:
    1. The bot will ask what game they are going to play/do.
    2. The bot will ask for the number of players for the match.
    3. The bot sends an embed UI and adds a reaction (✅) so users can react to join the match.
  - **Status**:
    - When all users react, the status of the embed will show: **Complete** with all the spots filled.
    - If the number of spots are not filled by gamers, the status will show: **Ended** and it will start the match with the users that reacted.

- 💬`!poll`📊
  - This command creates a poll so users can decide what task to do and setup a poll to decide with emoji numbers on the discord.Ui.
  - Based on the numbers of the tasks/games, the bot will add the numbers of reaction based on that.
  > **Steps**:
    1. Use `!poll` in any chat and type the task/game you want
    2. Wait for the bot to send the UI and add your reaction to compute your vote
    3. The *poll* will be open for **30 seconds** and then will show the game chosen for everyone

- 💬`!clear` + `int` 🧹
  - This command will clear the chat based on the numbers the user chose to.
  - After clearing the chat the bot will send a confirmation of how many messages were deleted.

- 💬`!games` 🎮
  - This command is for users that are not sure what games/tasks to play. Imagine you have 4 options of games but you don't know which one to play
  - *With this function you are able to let the bot decide with a **random.choice** from the list of games you gave*
  > **Steps**:
    1. Send `!games` to any chat you want
    2. Send the list of games (using "," to separate them) and just wait for the bot to decide.

- 💬`!daily` 📆
  - This command, for users, are only able to use once a day.
  - Users get use this command to get random items for <a href="" target="_blank"> !market</a> option


---

Feel free to use the bot in your server in **DISCORD_LINK**
@Felippefn - Ⓒ 
