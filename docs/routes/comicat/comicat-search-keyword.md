# Comicat - 搜索关键词

## Coverage
`index-only`

## Route
- Namespace: `comicat`
- Namespace Name: `Comicat`
- Route Path: `/comicat/search/:keyword`
- Route Name: `搜索关键词`
- Example: `/comicat/search/喵萌奶茶屋+跃动青春+720P+简日`
- URL: `comicat.org`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `Cyang39`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 关键词，请用`+`号连接


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/comicat/search/喵萌奶茶屋+跃动青春+720P+简日",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "search.ts",
  "maintainers": [
    "Cyang39"
  ],
  "name": "搜索关键词",
  "parameters": {
    "keyword": "关键词，请用`+`号连接"
  },
  "path": "/search/:keyword",
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-09-18T21:34:16.244Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "191615269219045376",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://comicat/search/%E6%97%A0%E8%81%8C%E8%BD%AC%E7%94%9F"
    }
  ]
}
```
