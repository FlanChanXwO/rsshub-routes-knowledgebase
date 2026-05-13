# 猫眼电影 - 即将上映

## Coverage
`index-only`

## Route
- Namespace: `maoyan`
- Namespace Name: `猫眼电影`
- Route Path: `/maoyan/coming`
- Route Name: `即将上映`
- Example: `/maoyan/coming`
- URL: `maoyan.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `JackyST0`
- Source Location: `coming.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `www.maoyan.com/films?showType=2`
  - `www.maoyan.com/films`
- `target`: `/coming`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/maoyan/coming",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "coming.ts",
  "maintainers": [
    "JackyST0"
  ],
  "name": "即将上映",
  "parameters": {},
  "path": "/coming",
  "radar": [
    {
      "source": [
        "www.maoyan.com/films?showType=2",
        "www.maoyan.com/films"
      ],
      "target": "/coming"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "猫眼电影即将上映列表 - Powered by RSSHub",
      "errorAt": "2026-05-11T20:18:55.096Z",
      "errorMessage": "Failed to fetch\n",
      "id": "238109378186655744",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.maoyan.com/films?showType=2",
      "title": "猫眼电影 - 即将上映",
      "type": "feed",
      "url": "rsshub://maoyan/coming"
    }
  ]
}
```
