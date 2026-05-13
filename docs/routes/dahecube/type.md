# 大河财立方 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `dahecube`
- Namespace Name: `大河财立方`
- Route Path: `/:type?`
- Route Name: `新闻`
- Example: `/dahecube`
- URL: `dahecube.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `linbuxiao`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/dahecube/index.ts')`

## Description
| 推荐      | 党史    | 豫股  | 财经     | 投教      | 金融    | 科创    | 投融   | 专栏   |
| --------- | ------- | ----- | -------- | --------- | ------- | ------- | ------ | ------ |
| recommend | history | stock | business | education | finance | science | invest | column |

## Parameters
- `type`: 板块，见下表，默认为推荐


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
  "description": "| 推荐      | 党史    | 豫股  | 财经     | 投教      | 金融    | 科创    | 投融   | 专栏   |\n| --------- | ------- | ----- | -------- | --------- | ------- | ------- | ------ | ------ |\n| recommend | history | stock | business | education | finance | science | invest | column |",
  "example": "/dahecube",
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
    "linbuxiao"
  ],
  "module": "() => import('@/routes/dahecube/index.ts')",
  "name": "新闻",
  "parameters": {
    "type": "板块，见下表，默认为推荐"
  },
  "path": "/:type?"
}
```
