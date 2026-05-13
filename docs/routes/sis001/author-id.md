# 第一会所 - 作者

## Coverage
`index-only`

## Route
- Namespace: `sis001`
- Namespace Name: `第一会所`
- Route Path: `/author/:id?`
- Route Name: `作者`
- Example: `/sis001/author/13131575`
- URL: `sis001.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `keocheung`
- Source Location: `author.ts`
- Source Module: `() => import('@/routes/sis001/author.ts')`

## Description
_None_

## Parameters
- `id`: 作者 ID，可以在作者的个人空间地址找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/sis001/author/13131575",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "author.ts",
  "maintainers": [
    "keocheung"
  ],
  "module": "() => import('@/routes/sis001/author.ts')",
  "name": "作者",
  "parameters": {
    "id": "作者 ID，可以在作者的个人空间地址找到"
  },
  "path": "/author/:id?"
}
```
