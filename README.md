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

1. Install [direnv](https://github.com/direnv/direnv) (e.g. brew install direnv)
1. Register Google Cloud Platform
1. Create new project and note project's ID
1. Register LINE Messaging API(LMA) and edit Webhook URL (e.g. https://gae-project-id.appspot.com/callback)
1. Note LMA's "Channel Secret" and "Channel Access Token"
1. Store your LMA's QR code as qrcode.png
1. Install sdk (e.g. brew install app-engine-go-64 )
1. Clone this repository
1. go get libraries
1. Move qrcode.png to app/img/
1. Edit app/index.html
1. Create "line.env"
1. goapp deploy -application <gae-project-id> -version 1

## line.env

```text:line.env
LINE_BOT_CHANNEL_SECRET=<Channel Secret>
LINE_BOT_CHANNEL_TOKEN=<Channel Access Token>
```
