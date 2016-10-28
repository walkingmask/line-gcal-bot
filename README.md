# line-gcal-bot

LINE Bot and Google Calendar with GAE/Go

## Environment

- go version go1.6.2 (appengine-1.9.40) 
- line-bot-sdk-go

## Go libraries

- google.golang.org/appengine
- golang.org/x/net/context
- github.com/joho/godotenv
- github.com/line/line-bot-sdk-go

## Usage

[Here](https://github.com/walkingmask/line-gcal-bot/wiki/Usage)
[日本語](https://github.com/walkingmask/line-gcal-bot/wiki/Usage_ja)

## Function

- Monitoring the change of the registered gcal
- Confirming the schedule of the day in the morning
  - cron.yaml
- Replaying the schedule of the day for all users actions such a message, sticker...

## TODO

- Create functions
- Slove the management of dependent libraries

