# Hangzhou People's Government - 最新消息

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `Hangzhou People's Government`
- Route Path: `/gov/moj/aac/news/:type?`
- Route Name: `最新消息`
- Example: `/gov/moj/aac/news`
- URL: `hangzhou.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `TonyRL`
- Source Location: `moj/aac/news.ts`
- Source Module: `_None_`

## Description
| 全部 | 其他 | 採購公告 | 新聞稿 | 肅貪 | 預防 | 綜合 | 防疫專區 |
| ---- | ---- | -------- | ------ | ---- | ---- | ---- | -------- |
|      | 02   | 01       | 06     | 05   | 04   | 03   | 99       |

## Parameters
- `type`: 資料大類，留空為全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 全部 | 其他 | 採購公告 | 新聞稿 | 肅貪 | 預防 | 綜合 | 防疫專區 |\n| ---- | ---- | -------- | ------ | ---- | ---- | ---- | -------- |\n|      | 02   | 01       | 06     | 05   | 04   | 03   | 99       |",
  "example": "/gov/moj/aac/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "moj/aac/news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "最新消息",
  "parameters": {
    "type": "資料大類，留空為全部"
  },
  "path": "/moj/aac/news/:type?",
  "topFeeds": []
}
```
