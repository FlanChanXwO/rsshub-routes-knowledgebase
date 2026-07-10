# 西安交通大学 - 电气学院

## Coverage
`index-only`

## Route
- Namespace: `xjtu`
- Namespace Name: `西安交通大学`
- Route Path: `/xjtu/ee/:id?`
- Route Name: `电气学院`
- Example: `/xjtu/ee/1114`
- URL: `ee.xjtu.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `DylanXie123`
- Source Location: `ee.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 栏目id，默认请求`1124`，可在 URL 中找到


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
  - `ee.xjtu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/xjtu/ee/1114",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "ee.ts",
  "maintainers": [
    "DylanXie123"
  ],
  "name": "电气学院",
  "parameters": {
    "id": "栏目id，默认请求`1124`，可在 URL 中找到"
  },
  "path": "/ee/:id?",
  "radar": [
    {
      "source": [
        "ee.xjtu.edu.cn/"
      ]
    }
  ],
  "topFeeds": [],
  "url": "ee.xjtu.edu.cn/"
}
```
