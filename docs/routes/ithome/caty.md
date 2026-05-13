# iThome 台灣 - 分类资讯

## Coverage
`index-only`

## Route
- Namespace: `ithome`
- Namespace Name: `iThome 台灣`
- Route Path: `/:caty`
- Route Name: `分类资讯`
- Example: `/ithome/it`
- URL: `ithome.com`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `luyuhuang`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/ithome/index.ts')`

## Description
| it      | soft     | win10      | win11      | iphone      | ipad      | android      | digi     | next     |
| ------- | -------- | ---------- | ---------- | ----------- | --------- | ------------ | -------- | -------- |
| IT 资讯 | 软件之家 | win10 之家 | win11 之家 | iphone 之家 | ipad 之家 | android 之家 | 数码之家 | 智能时代 |

## Parameters
- `caty`: 类别


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
  "description": "| it      | soft     | win10      | win11      | iphone      | ipad      | android      | digi     | next     |\n| ------- | -------- | ---------- | ---------- | ----------- | --------- | ------------ | -------- | -------- |\n| IT 资讯 | 软件之家 | win10 之家 | win11 之家 | iphone 之家 | ipad 之家 | android 之家 | 数码之家 | 智能时代 |",
  "example": "/ithome/it",
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
    "luyuhuang"
  ],
  "module": "() => import('@/routes/ithome/index.ts')",
  "name": "分类资讯",
  "parameters": {
    "caty": "类别"
  },
  "path": "/:caty"
}
```
