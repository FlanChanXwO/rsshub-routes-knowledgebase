# 知乎 - 知乎书店 - 知乎周刊

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/weekly`
- Route Name: `知乎书店 - 知乎周刊`
- Example: `/zhihu/weekly`
- URL: `www.zhihu.com/pub/weekly`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `LogicJake`
- Source Location: `weekly.ts`
- Source Module: `() => import('@/routes/zhihu/weekly.ts')`

## Description
_None_

## Parameters
_None_


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
  - `www.zhihu.com/pub/weekly`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/weekly",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "weekly.ts",
  "maintainers": [
    "LogicJake"
  ],
  "module": "() => import('@/routes/zhihu/weekly.ts')",
  "name": "知乎书店 - 知乎周刊",
  "parameters": {},
  "path": "/weekly",
  "radar": [
    {
      "source": [
        "www.zhihu.com/pub/weekly"
      ]
    }
  ],
  "url": "www.zhihu.com/pub/weekly"
}
```
