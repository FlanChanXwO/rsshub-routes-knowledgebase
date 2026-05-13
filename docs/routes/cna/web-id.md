# 中央通讯社 - 分类 (网页爬虫方法)

## Coverage
`index-only`

## Route
- Namespace: `cna`
- Namespace Name: `中央通讯社`
- Route Path: `/web/:id?`
- Route Name: `分类 (网页爬虫方法)`
- Example: `/cna/web/aall`
- URL: `cna.com.tw`
- Language: `zh-TW`
- Categories: `traditional-media`
- Maintainers: `dzx-dzx`
- Source Location: `web/index.ts`
- Source Module: `() => import('@/routes/cna/web/index.ts')`

## Description
_None_

## Parameters
- `id`: 分类 id，见上表。此參數默认为 aall


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
    "traditional-media"
  ],
  "example": "/cna/web/aall",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "web/index.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "module": "() => import('@/routes/cna/web/index.ts')",
  "name": "分类 (网页爬虫方法)",
  "parameters": {
    "id": "分类 id，见上表。此參數默认为 aall"
  },
  "path": "/web/:id?"
}
```
