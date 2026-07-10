# 片源网 - 最新资源

## Coverage
`index-only`

## Route
- Namespace: `pianyuan`
- Namespace Name: `片源网`
- Route Path: `/pianyuan/index/:media?`
- Route Name: `最新资源`
- Example: `/pianyuan/index`
- URL: `pianyuan.org/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `greatcodeeer, jerry1119`
- Source Location: `app.ts`
- Source Module: `_None_`

## Description
| 电影 | 剧集 |
| ---- | ---- |
| mv   | tv   |

## Parameters
- `media`: 类别，见下表，默认为首页


## Features
- `requireConfig`: [{"description": "", "name": "PIANYUAN_COOKIE"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `pianyuan.org/`
- `target`: `/index`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "| 电影 | 剧集 |\n| ---- | ---- |\n| mv   | tv   |",
  "example": "/pianyuan/index",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "PIANYUAN_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "app.ts",
  "maintainers": [
    "greatcodeeer",
    "jerry1119"
  ],
  "name": "最新资源",
  "parameters": {
    "media": "类别，见下表，默认为首页"
  },
  "path": "/index/:media?",
  "radar": [
    {
      "source": [
        "pianyuan.org/"
      ],
      "target": "/index"
    }
  ],
  "topFeeds": [],
  "url": "pianyuan.org/"
}
```
