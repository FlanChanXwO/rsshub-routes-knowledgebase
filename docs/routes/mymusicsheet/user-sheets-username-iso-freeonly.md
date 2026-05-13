# mymusic5 (MyMusicSheet) - User Sheets

## Coverage
`index-only`

## Route
- Namespace: `mymusicsheet`
- Namespace Name: `mymusic5 (MyMusicSheet)`
- Route Path: `/user/sheets/:username/:iso?/:freeOnly?`
- Route Name: `User Sheets`
- Example: `/mymusicsheet/user/sheets/HalcyonMusic/USD/1`
- URL: `mymusicfive.com`
- Language: `en`
- Categories: `shopping`
- Maintainers: `Freddd13`
- Source Location: `usersheets.tsx`
- Source Module: `() => import('@/routes/mymusicsheet/usersheets.tsx')`

## Description
Please refer to [Wikipedia](https://en.wikipedia.org/wiki/ISO_4217#Active_codes) for ISO 4217.

## Parameters
- `username`: Username, can be found in the URL
- `iso`: ISO 4217 currency code for displaying prices, defaults to `USD`
- `freeOnly`: Only return free scores, any value to enable


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `mymusicfive.com/:username/*`
  - `mymusicfive.com/:username`
- `target`: `/user/sheets/:username`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "Please refer to [Wikipedia](https://en.wikipedia.org/wiki/ISO_4217#Active_codes) for ISO 4217.",
  "example": "/mymusicsheet/user/sheets/HalcyonMusic/USD/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "usersheets.tsx",
  "maintainers": [
    "Freddd13"
  ],
  "module": "() => import('@/routes/mymusicsheet/usersheets.tsx')",
  "name": "User Sheets",
  "parameters": {
    "freeOnly": "Only return free scores, any value to enable",
    "iso": "ISO 4217 currency code for displaying prices, defaults to `USD`",
    "username": "Username, can be found in the URL"
  },
  "path": "/user/sheets/:username/:iso?/:freeOnly?",
  "radar": [
    {
      "source": [
        "mymusicfive.com/:username/*",
        "mymusicfive.com/:username"
      ],
      "target": "/user/sheets/:username"
    }
  ]
}
```
