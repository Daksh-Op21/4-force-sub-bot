<img src="https://backiee.com/static/wallpapers/1000x563/221292.jpg" alt="logo" target="/blank">

<h1 align="center">
 <b><a href="https://t.me/DarkHumorHub_bot" target="/blank"> File Sharing Premium Bot </a></b>
</h1>

<p align="center">🩵 Thanks for Being Here 🩵</p>

### SETUP

1. **Download Repository:** First, download the repository to your local machine.

2. **Open in VS Code:** Open the downloaded repository in Visual Studio Code (VS Code).

3. **Install Requirements:** Open the terminal in VS Code and run the following command to install required packages:

4. **Update .env File:**

   Update your .env file with the following variables:

      - **`TG_BOT_TOKEN`**=&lt;Your Telegram Bot Token&gt;
      - **`APP_ID`**=&lt;Your Telegram API ID&gt;
      - **`API_HASH`**=&lt;Your Telegram API Hash&gt;
      - **`OWNER_ID`**=&lt;Your Telegram User ID&gt;
      - **`DB_URL`**=&lt;Your MongoDB URL&gt;
      - **`DB_NAME`**=&lt;Your MongoDB Database Name&gt;
      - **`CHANNEL_ID`**=&lt;Your Channel ID&gt;
      - **`FORCE_SUB_CHANNEL1`**=&lt;Optional: Your ForceSub Channel 1 ID&gt;
      - **`FORCE_SUB_CHANNEL2`**=&lt;Optional: Your ForceSub Channel 2 ID&gt;

   Make sure not to change the HTTP port; it should remain `8080`, because it only runs on **`localhost:8080`**

5. **Run the Bot:** In the terminal, run the following command to start the bot:  python main.py

6. **Access Localhost:** Open your web browser and type `localhost:8080` to access the running bot locally. If you see the bot interface, your setup is complete and ready for deployment.

**Note:** These .env variables are only for local development. When deploying, you must configure these variables again on your deployment server.

<div align="center">
    <strong>Happy Coding!</strong>
</div>

### CONFIGS VARIABLES FOR DEPLOYMENT

* `API_HASH` Your API Hash from my.telegram.org
* `APP_ID` Your API ID from my.telegram.org
* `TG_BOT_TOKEN` Your bot token from @BotFather
* `OWNER_ID` Must enter Your Telegram Id
* `CHANNEL_ID` Your Channel ID eg:- -100xxxxxxxx
* `DB_URL` Your mongo db url
* `DB_NAME` Your mongo db session name
* `ADMINS` Optional: A space separated list of user_ids of Admins, they can only create links
* `START_MESSAGE` Optional: start message of bot
* `FORCE_SUB_MESSAGE`Optional:Force sub message of bot, use HTML and Fillings
* `FORCE_SUB_CHANNEL1` Optional: ForceSub Channel 1 ID, leave 0 if you want disable force sub
* `FORCE_SUB_CHANNEL2` Optional: ForceSub Channel 2 ID, leave 0 if you want disable force sub
* `PROTECT_CONTENT` Optional: True if you need to prevent files from forwarding



### EXTRA VARIABLES

* `CUSTOM_CAPTION` put your Custom caption text if you want Setup Custom Caption, you can use HTML and <a href='https://github.com/JishuDeveloper/File-Sharing-Premium-Bot/blob/main/README.md#custom_caption'>fillings</a> for formatting (only for documents)
* `DISABLE_CHANNEL_BUTTON` Put True to Disable Channel Share Button, Default if False
* `BOT_STATS_TEXT` put your custom text for stats command, use HTML and <a href='https://github.com/JishuDeveloper/File-Sharing-Premium-Bot/blob/main/README.md#custom_stats'>fillings</a>
* `USER_REPLY_TEXT` put your text to show when user sends any message, use HTML


### Getting Help

<summary>Support</summary>
<p>
If you need assistance or have any questions, you can contact the admin of this bot:

[![Contact Admin on Telegram](https://img.shields.io/badge/Contact%20Admin-on%20Telegram-blue?style=for-the-badge&logo=telegram)](https://t.me/DarkHumorHub_bot)

</p>


### DEPLOYEMENT SUPPORT

<summary>Deploy To Koyeb</summary>
<p>
<br>                 
<a target="/blank" href="https://app.koyeb.com/deploy?type=git&repository=github.com/JishuDeveloper/File-Sharing-Premium-Bot&branch=main&name=file-sharing-bot" >
  <img src="https://www.koyeb.com/static/images/deploy/button.svg" alt="Deploy">
</a>
</p>

<summary>Deploy To Heroku</summary>
<p>
<br>
<a href="https://heroku.com/deploy?template=https://github.com/JishuDeveloper/File-Sharing-Premium-Bot">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
</p>



### FEATURES
- Fully customisable.
- Auto Delete Added.
- main Branch Means 2 force subs.
- Customisable welcome & Forcesub messages.
- More than one Posts in One Link.
- Can be deployed on heroku directly.
- Deploy to Koyeb + Heroku + Railway + Render
- Developer Service 24x7.



### SETUP

- Add the bot to Database Channel with all permission
- Add bot to ForceSub channel as Admin with Invite Users via Link Permission if you enabled ForceSub


### FILLINGS
#### START_MESSAGE | FORCE_SUB_MESSAGE

* `{first}` - User first name
* `{last}` - User last name
* `{id}` - User ID
* `{mention}` - Mention the user
* `{username}` - Username

#### CUSTOM_CAPTION

* `{filename}` - file name of the Document
* `{previouscaption}` - Original Caption

#### CUSTOM_STATS

* `{uptime}` - Bot Uptime


### ALL COMMANDS

```
Bot Command Descriptions:
start - Start the bot or get posts.
batch - Create a link for more than one post.
genlink - Create a link for one post.
customBatch - Create a link for a custom batch of posts.
users - View bot statistics.
broadcast - Broadcast any message to bot users.
stats - Check the bot uptime.
```
