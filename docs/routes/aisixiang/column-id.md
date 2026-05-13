# 爱思想 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `aisixiang`
- Namespace Name: `爱思想`
- Route Path: `/column/:id`
- Route Name: `栏目`
- Example: `/aisixiang/column/722`
- URL: `aisixiang.com`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `HenryQW, nczitzk`
- Source Location: `column.ts`
- Source Module: `() => import('@/routes/aisixiang/column.ts')`

## Description
_None_

## Parameters
- `id`: 栏目 ID, 可在对应栏目 URL 中找到


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
    "reading"
  ],
  "example": "/aisixiang/column/722",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "column.ts",
  "maintainers": [
    "HenryQW",
    "nczitzk"
  ],
  "module": "() => import('@/routes/aisixiang/column.ts')",
  "name": "栏目",
  "parameters": {
    "id": "栏目 ID, 可在对应栏目 URL 中找到"
  },
  "path": "/column/:id"
}
```
