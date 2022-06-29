# Minesweeper-Telegram-Bot-

## Description
Simple chat bot to play minesweeper based on [pyTelegramBotAPI](https://github.com/eternnoir/pyTelegramBotAPI) library.The choice of field size and difficulty level (number of mines) is implemented in this project.

## How to run
```
docker build . -t tgbot
docker run -e API_KEY={YOUR_API_KEY} tgbot
```
## Testing
For testing [telethon](https://pypi.org/project/Telethon/) library could be used. However automated tests are out of the scope
of this basic project.
