# kbot
devops app from scratch

TODO  
Install Golang and configure the development environment.  
Create a new project on GitHub and configure Git.  
Add a dependency to the github.com/spf13/cobra library using import.  
Create a Telegram bot using BotFather.  
Get the bot token and store it in the TELE_TOKEN environment variable.  
Import required libraries.  
Install the gopkg.in/telebot.v3 library using go get.  
Get the bot token from an environment variable.  
Create a bot object using telebot.NewBot().  
Add a message handler using kbot.Handle(telebot.OnText, func(m telebot.Context).  
Describe the handler function that will respond to the message.  
Build, run and test the bot.  

My bot is   
t.me/sdrvadim_bot

How to use

add bot token from BotFather with command:  
$ read -s TELE_TOKEN  
then export variable:   
$ export TELE_TOKEN   
and run:  
$ ./kbot start  
kbot v1.0.2 started  

Open kbot in Telegram and put start:  
$ ./kbot start  
kbot v1.0.2 started2023/11/16 15:45:40 start  

In Telegram:  
/start hello  
Hello I`m Kbot v1.0.2!  


