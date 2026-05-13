# 虎嗅 - 文集

## Coverage
`index-only`

## Route
- Namespace: `huxiu`
- Namespace Name: `虎嗅`
- Route Path: `/collection/:id`
- Route Name: `文集`
- Example: `/huxiu/collection/212`
- URL: `huxiu.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `AlexdanerZe, nczitzk`
- Source Location: `collection.ts`
- Source Module: `() => import('@/routes/huxiu/collection.ts')`

## Description
更多文集请参见 [文集](https://www.huxiu.com/collection)

## Parameters
- `id`: 文集 id，可在对应文集页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "更多文集请参见 [文集](https://www.huxiu.com/collection)",
  "example": "/huxiu/collection/212",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "location": "collection.ts",
  "maintainers": [
    "AlexdanerZe",
    "nczitzk"
  ],
  "module": "() => import('@/routes/huxiu/collection.ts')",
  "name": "文集",
  "parameters": {
    "id": "文集 id，可在对应文集页 URL 中找到"
  },
  "path": "/collection/:id"
}
```
