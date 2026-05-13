# 晚点 LatePost - 报道

## Coverage
`index-only`

## Route
- Namespace: `latepost`
- Namespace Name: `晚点 LatePost`
- Route Path: `/:proma?`
- Route Name: `报道`
- Example: `/latepost`
- URL: `latepost.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/latepost/index.ts')`

## Description
| 最新报道 | 晚点独家 | 人物访谈 | 晚点早知道 | 长报道 |
| -------- | -------- | -------- | ---------- | ------ |
|          | 1        | 2        | 3          | 4      |

## Parameters
- `proma`: 栏目 id，见下表，默认为最新报道


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
    "new-media"
  ],
  "description": "| 最新报道 | 晚点独家 | 人物访谈 | 晚点早知道 | 长报道 |\n| -------- | -------- | -------- | ---------- | ------ |\n|          | 1        | 2        | 3          | 4      |",
  "example": "/latepost",
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
  "module": "() => import('@/routes/latepost/index.ts')",
  "name": "报道",
  "parameters": {
    "proma": "栏目 id，见下表，默认为最新报道"
  },
  "path": "/:proma?"
}
```
