# Heroku Deploy Guide
##  WhatsApp Botto: KAOI 🖤️<br>
### Pre-requisite
 - 🌐️ Internet 🌐️️
- 🧠️ Brain 🧠️
- 🎵️ Music 🎵️
- 💫 Chill 💫
1. [Whatsapp-Botto-Kaoi](https://github.com/PrajjwalDatir/Kaoi) - Go there
2. Scroll down a bit and you will see the "Deploy To Heroku" button in purple color (sorry if you are color blind)
3. Click on it and login or sign up for Heroku
4. Enter the following fields
    | KEY | VALUE |
    | --- | ----------- |
    | BOTNAME | Kaoi |
    | CHAT_BOT_URL | 'Instructions below for getting url' |
    | CRON | 'null' |
    | GOOGLE_API_KEY | 'Read below to get the API Key |
    | PREFIX | ! |
    | SESSION | Any text you want but make sure to remember and don't share it |
    | MODS |  |
    | MONGO_URI | YOUR CLUSTER URI |
 
`NAME` The name of the Bot <br>
`CHAT_BOT_URL` A BOT WITH A BRAIN ROCKS! Click=> [Get ChatBot Url](https://github.com/Hiroto77/Kaoi-Guides/blob/main/Chat_Bot_Url.md)<br>
`CRON` Cron schedule for clearing all chats (Default: `"0 */6 * * *"`. Every 6 Hours). change this field to `null` if you don't want to schedule. [Learn More](https://www.npmjs.com/package/node-cron) <br>
`GOOGLE_API_KEY` Custom Search JSON API requires the use of an API key. [Get API key here](https://developers.google.com/custom-search/v1/introduction). After getting the API key, insert it while deploying on HEROKU. <br>
`PREFIX` The Prefix of the Bot <br>
`SESSION` A string to keep track of your session. <br>
`MODS` The phone numbers of users who you want to be the bot's Admins separated by a comma and must the numbers must be in the following format: `[cc][number]`. eg: `919744******`<br>
`MONGO_URI` is the Connection URL to your DB ([Mongo-Atlas-Guide](https://github.com/Synthesized-Infinity/Whatsapp-Botto-Void/blob/main/Guides/Mongo-Atlas-guide.md))<br> 
5. Wait for the building to finish, you should always keep an eye on log messages, you can find log messages in the Dashboard -> More -> View logs.<br>
6. After it builds, click on the "View" or "Open App".<br>
7. Authenticate By Providing Your SESSION_ID and a QR Code Will Show Up.<br>
8. Open WhatsApp on your phone -> Click on the 3 Dots on the top Right -> Click on WhatsApp Web -> Click on "Link a Device" and scan the QR from the previous step.<br>
9. Your heroku app can fall asleep so for keeping it awaken add your app to "https://kaffeine.herokuapp.com/". It pings your Heroku app every 30 minutes so it will never go to sleep.<br>
10. Profit! Ultimate!

### 😼️ Enjoy and make sure to study!
### 🐼 More Indeed features Soon!
### ⭐️ Do not forget to give it a Star!
