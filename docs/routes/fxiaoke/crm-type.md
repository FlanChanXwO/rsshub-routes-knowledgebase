# 纷享销客 CRM - 文章

## Coverage
`index-only`

## Route
- Namespace: `fxiaoke`
- Namespace Name: `纷享销客 CRM`
- Route Path: `/crm/:type`
- Route Name: `文章`
- Example: `/fxiaoke/crm/news`
- URL: `fxiaoke.com`
- Language: `zh-CN`
- Categories: `blog`
- Maintainers: `akynazh`
- Source Location: `crm.ts`
- Source Module: `() => import('@/routes/fxiaoke/crm.ts')`

## Description
| 全部文章 | 文章干货 | CRM 知识 | 纷享动态        | 签约喜报  |
| -------- | -------- | -------- | --------------- | --------- |
| news     | blog     | articles | about-influence | customers |

## Parameters
- `type`: 文章类型, 见下表


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
    "blog"
  ],
  "description": "| 全部文章 | 文章干货 | CRM 知识 | 纷享动态        | 签约喜报  |\n| -------- | -------- | -------- | --------------- | --------- |\n| news     | blog     | articles | about-influence | customers |",
  "example": "/fxiaoke/crm/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "crm.ts",
  "maintainers": [
    "akynazh"
  ],
  "module": "() => import('@/routes/fxiaoke/crm.ts')",
  "name": "文章",
  "parameters": {
    "type": "文章类型, 见下表"
  },
  "path": "/crm/:type"
}
```
