# Radio Javan Downloader

Download [Radio Javan](https://play.radiojavan.com/) media only by its URL!

## Run

### Docker

I have built the project as a Docker image which is now available on [Docker Hub](https://hub.docker.com/repository/docker/alirezabrtn/radiojavan-dl).

In order to run the bot, you should have MongoDB installed on your OS and run the image with its environemnt variables:

```bash
docker run -d --network=host --restart always -e BOT_TOKEN=<your-bot-token> -e SPONSER_CHANNEL=<your-sponsel-channel-username> alirezabrtn/radiojavan-dl
```

## Features

Currently, this bot supports downloading:

- Tracks
- Podcasts
- Videos

## Use

I have this bot in production which you can use it for free [here](https://t.me/rjripbot).

## Credits

- [node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api)
- [mongoose](https://github.com/Automattic/mongoose)
- [Docker](https://docker.com)

