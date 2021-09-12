# Weather Bot for Telegram 🌦
This [Weather bot](https://t.me/WeatherShelk_bot) allows you to find out what the weather in the city today, tomorrow and the day after tomorrow. 

___

## How to operate application? 

  Starting a bot on server  
`
pm2 start WeatherBot_telegram.py --interpreter python3
`  
  
   Reboot the bot   
`
pm2 restart WeatherBot_telegram
`  
  
  Stop bot  
`
pm2 stop WeatherBot_telegram
` 
  
  End bot process  
`
pm2 delete WeatherBot_telegram
`

## How to run 

  Add to environment variables (create an .env file) Telegram API key (get it from [@BotFather](https://telegram.me/botfather) when creating a new bot with /newbot command).  
`  
token='BotFather_token'
`  

To connect to the database, add and fill the fields database, user, password, host, port in the .env file.  
If you do not want to connect to the database, comment out the connect, db_users and actions functions and their calls.


Python 3,7 or higher is required to run. 

   Install libraries:  

`  
pip install -r requirements.txt  
`  

   Launch the bot:

`  
python3 WeatherBotTelegram.py  
`  
