# 中央通讯社 - 分类 (网页爬虫方法)

## Coverage
`index-only`

## Route
- Namespace: `cna`
- Namespace Name: `中央通讯社`
- Route Path: `/cna/web/:id?`
- Route Name: `分类 (网页爬虫方法)`
- Example: `/cna/web/aall`
- URL: `cna.com.tw`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `dzx-dzx`
- Source Location: `web/index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 分类 id，见上表。此參數默认为 aall


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
    "traditional-media"
  ],
  "example": "/cna/web/aall",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "web/index.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "name": "分类 (网页爬虫方法)",
  "parameters": {
    "id": "分类 id，见上表。此參數默认为 aall"
  },
  "path": "/web/:id?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "證券 | 中央社 CNA - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70128456816328704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cna.com.tw/list/asc.aspx",
      "title": "證券 | 中央社 CNA",
      "type": "feed",
      "url": "rsshub://cna/web/asc"
    }
  ]
}
```
