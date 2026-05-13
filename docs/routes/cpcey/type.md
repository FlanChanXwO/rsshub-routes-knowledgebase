# 台湾行政院消费者保护会 - 消费资讯

## Coverage
`index-only`

## Route
- Namespace: `cpcey`
- Namespace Name: `台湾行政院消费者保护会`
- Route Path: `/:type?`
- Route Name: `消费资讯`
- Example: `/cpcey/xwg`
- URL: `cpc.ey.gov.tw`
- Language: `zh-TW`
- Categories: `government`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/cpcey/index.ts')`

## Description
| 新闻稿 | 消费资讯 |
| :----: | :------: |
|   xwg  |   xfzx   |

## Parameters
- `type`: 默认为 `xwg`


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
  "description": "| 新闻稿 | 消费资讯 |\n| :----: | :------: |\n|   xwg  |   xfzx   |",
  "example": "/cpcey/xwg",
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
    "Fatpandac"
  ],
  "module": "() => import('@/routes/cpcey/index.ts')",
  "name": "消费资讯",
  "parameters": {
    "type": "默认为 `xwg`"
  },
  "path": "/:type?"
}
```
