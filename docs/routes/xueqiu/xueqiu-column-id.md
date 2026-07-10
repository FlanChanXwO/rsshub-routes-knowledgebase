# 雪球 - 用户专栏

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/xueqiu/column/:id`
- Route Name: `用户专栏`
- Example: `/xueqiu/column/9962554712`
- URL: `danjuanapp.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `TonyRL, pseudoyu`
- Source Location: `column.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 用户 id, 可在用户主页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `xueqiu.com/:id/column`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/xueqiu/column/9962554712",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "column.ts",
  "maintainers": [
    "TonyRL",
    "pseudoyu"
  ],
  "name": "用户专栏",
  "parameters": {
    "id": "用户 id, 可在用户主页 URL 中找到"
  },
  "path": "/column/:id",
  "radar": [
    {
      "source": [
        "xueqiu.com/:id/column"
      ]
    }
  ],
  "topFeeds": []
}
```
