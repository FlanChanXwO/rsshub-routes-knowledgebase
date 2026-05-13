# TikTok - Live

## Coverage
`index-only`

## Route
- Namespace: `tiktok`
- Namespace Name: `TikTok`
- Route Path: `/tiktok/live/:user`
- Route Name: `Live`
- Example: `/tiktok/live/@shinichifuku`
- URL: `tiktok.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `live.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: User ID, including @


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
  - `www.tiktok.com/:user/live`
- `target`: `/live/:user`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/tiktok/live/@shinichifuku",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "live.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Live",
  "parameters": {
    "user": "User ID, including @"
  },
  "path": "/live/:user",
  "radar": [
    {
      "source": [
        "www.tiktok.com/:user/live"
      ],
      "target": "/live/:user"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Se vuoi ridere sei nel posto giusto😎 If u wanna laugh u r in the right place😎 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "242665903234866176",
      "image": "https://p16-common-sign.tiktokcdn-us.com/tos-useast2a-avt-0068-euttp/e755d298d36b3175a2ca87d603b5dc2d~tplv-tiktokx-cropcenter:1080:1080.webp?dr=9640&refresh_token=4e2b34d6&x-expires=1773518400&x-signature=KnDtPySYG1vrMD%2FAZV7KKSXOh2s%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=fdd36af4&idc=useast5",
      "ownerUserId": null,
      "siteUrl": "https://www.tiktok.com/@khaby.lame/live",
      "title": "Khabane lame (@khaby.lame)'s Live Stream - TikTok",
      "type": "feed",
      "url": "rsshub://tiktok/live/%40khaby.lame"
    }
  ]
}
```
