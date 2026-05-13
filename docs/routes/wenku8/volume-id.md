# 轻小说文库 - 最新卷

## Coverage
`index-only`

## Route
- Namespace: `wenku8`
- Namespace Name: `轻小说文库`
- Route Path: `/volume/:id`
- Route Name: `最新卷`
- Example: `/wenku8/volume/1163`
- URL: `www.wenku8.net`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `huangliangshusheng`
- Source Location: `volume.ts`
- Source Module: `() => import('@/routes/wenku8/volume.ts')`

## Description
_None_

## Parameters
- `id`: 小说 id, 可在对应小说页 URL 中找到


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
  "example": "/wenku8/volume/1163",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "volume.ts",
  "maintainers": [
    "huangliangshusheng"
  ],
  "module": "() => import('@/routes/wenku8/volume.ts')",
  "name": "最新卷",
  "parameters": {
    "id": "小说 id, 可在对应小说页 URL 中找到"
  },
  "path": "/volume/:id"
}
```
