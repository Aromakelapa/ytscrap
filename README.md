# Youtube Video & Audio Downloader Scrapper
Scrap data from a Youtube video & audio downloader site and get direct info & url links.

## Install
```
npm install ytscrap
```

## Changelog
- #### v1.0.0
  - Initial commit

## Usage
```
const ytscrap = require('ytscrap')

ytscrap('https://www.youtube.com/watch?v=36uDReSdFDU')
  .then((res) => {
    console.log(res)
  })
  .catch((err) => {
    console.log(err)
  })
```

## Issues & Contact
- Create issue session in [Github Repo](https://github.com/Aromakelapa/ytscrap/issues)

- You can reach me on [Telegram](https://t.me/Aromakelapa)

### Thanks for using my module, Hope you forgive me if it shows an error, because I'm newbie at this :>