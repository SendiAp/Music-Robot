# Music-Robot
A Simple Music Downloader Bot For Telegram with Youtube Music, Spotify & Deezer Support.

<p align="center">
    <a href="https://python.org">
        <img src="http://forthebadge.com/images/badges/made-with-python.svg" alt="made-with-python">
    </a>
    <a href="https://GitHub.com/SendiAp">
        <img src="http://ForTheBadge.com/images/badges/built-with-love.svg" alt="built-with-love">
    </a> <br>
    <img src="https://img.shields.io/github/license/SendiAp/Music-Robot?style=for-the-badge&logo=appveyor" alt="LICENSE">
    <img src="https://img.shields.io/github/contributors/SendiAp/Music-Robot?style=for-the-badge&logo=appveyor" alt="Contributors">
    <img src="https://img.shields.io/github/repo-size/SendiAp/Music-Robot?style=for-the-badge&logo=appveyor" alt="Repository Size"> <br>
    <img src="https://img.shields.io/badge/python-3.9-green?style=for-the-badge&logo=appveyor" alt="Python Version">
    <img src="https://img.shields.io/github/issues/SendiAp/Music-Robot?style=for-the-badge&logo=appveyor" alt="Issues">
    <img src="https://img.shields.io/github/forks/SendiAp/Music-Robot?style=for-the-badge&logo=appveyor" alt="Forks">
    <img src="https://img.shields.io/github/stars/SendiAp/Music-Robot?style=for-the-badge&logo=appveyor" alt="Stars">
</p>

## Deployment

To deploy this project run

### Easy Way (Local)
```bash
  cp sample_config.env config.env
  pip3 install -r requirements.txt
  python3 -m mbot
```
### Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https://github.com/SendiAp/Music-Robot/)

## Environment Variables

To run this project, you will need to add the following environment variables to your config.env file

`API_ID`
`API_HASH`
`BOT_TOKEN`
`SPOTIPY_CLIENT_ID`
`SPOTIPY_CLIENT_SECRET`
`UPDATES_CHANNEL`
`LOG_GROUP`
`DATABASE_URL`
`AUTH_CHATS`
