# 金十数据 - 市场快讯

## Coverage
`index-only`

## Route
- Namespace: `jin10`
- Namespace Name: `金十数据`
- Route Path: `/:important?`
- Route Name: `市场快讯`
- Example: `/jin10`
- URL: `jin10.com/`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `laampui`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/jin10/index.ts')`

## Description
_None_

## Parameters
- `important`: 只看重要，任意值开启，留空关闭


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
  - `jin10.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/jin10",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "laampui"
  ],
  "module": "() => import('@/routes/jin10/index.ts')",
  "name": "市场快讯",
  "parameters": {
    "important": "只看重要，任意值开启，留空关闭"
  },
  "path": "/:important?",
  "radar": [
    {
      "source": [
        "jin10.com/"
      ],
      "target": ""
    }
  ],
  "url": "jin10.com/",
  "view": 5
}
```
