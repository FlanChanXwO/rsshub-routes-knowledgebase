# 少数派 sspai - 作者

## Coverage
`index-only`

## Route
- Namespace: `sspai`
- Namespace Name: `少数派 sspai`
- Route Path: `/author/:id`
- Route Name: `作者`
- Example: `/sspai/author/796518`
- URL: `sspai.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `SunShinenny, hoilc`
- Source Location: `author.ts`
- Source Module: `() => import('@/routes/sspai/author.ts')`

## Description
_None_

## Parameters
- `id`: 作者 slug 或 id，slug 可在作者主页URL中找到，id 不易查找，仅作兼容


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `sspai.com/u/:id/posts`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/sspai/author/796518",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "author.ts",
  "maintainers": [
    "SunShinenny",
    "hoilc"
  ],
  "module": "() => import('@/routes/sspai/author.ts')",
  "name": "作者",
  "parameters": {
    "id": "作者 slug 或 id，slug 可在作者主页URL中找到，id 不易查找，仅作兼容"
  },
  "path": "/author/:id",
  "radar": [
    {
      "source": [
        "sspai.com/u/:id/posts"
      ]
    }
  ]
}
```
