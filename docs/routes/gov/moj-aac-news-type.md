# 国家能源局 - 最新消息

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/moj/aac/news/:type?`
- Route Name: `最新消息`
- Example: `/gov/moj/aac/news`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `TonyRL`
- Source Location: `moj/aac/news.ts`
- Source Module: `() => import('@/routes/gov/moj/aac/news.ts')`

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
  "location": "moj/aac/news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/gov/moj/aac/news.ts')",
  "name": "最新消息",
  "parameters": {
    "type": "資料大類，留空為全部"
  },
  "path": "/moj/aac/news/:type?"
}
```
