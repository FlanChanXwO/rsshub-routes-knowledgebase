# 秋爸日字 - 分类

## Coverage
`index-only`

## Route
- Namespace: `qq88`
- Namespace Name: `秋爸日字`
- Route Path: `/:category?`
- Route Name: `分类`
- Example: `/qq88`
- URL: `qq88.info`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/qq88/index.ts')`

## Description
| 首页 | オトナの土ドラ | 日剧 | 日剧 SP |
| ---- | -------------- | ---- | ------- |
|      | 10             | 5    | 11      |

## Parameters
- `category`: 分类 id，见下表，默认为首页


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
    "multimedia"
  ],
  "description": "| 首页 | オトナの土ドラ | 日剧 | 日剧 SP |\n| ---- | -------------- | ---- | ------- |\n|      | 10             | 5    | 11      |",
  "example": "/qq88",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/qq88/index.ts')",
  "name": "分类",
  "parameters": {
    "category": "分类 id，见下表，默认为首页"
  },
  "path": "/:category?"
}
```
