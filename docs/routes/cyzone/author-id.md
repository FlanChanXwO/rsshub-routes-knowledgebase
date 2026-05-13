# 创业邦 - 作者

## Coverage
`index-only`

## Route
- Namespace: `cyzone`
- Namespace Name: `创业邦`
- Route Path: `/author/:id`
- Route Name: `作者`
- Example: `/cyzone/author/1225562`
- URL: `cyzone.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `author.ts`
- Source Module: `() => import('@/routes/cyzone/author.ts')`

## Description
_None_

## Parameters
- `id`: 作者 id，可在对应作者页 URL 中找到


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
  - `cyzone.cn/author/:id`
  - `cyzone.cn/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/cyzone/author/1225562",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/cyzone/author.ts')",
  "name": "作者",
  "parameters": {
    "id": "作者 id，可在对应作者页 URL 中找到"
  },
  "path": "/author/:id",
  "radar": [
    {
      "source": [
        "cyzone.cn/author/:id",
        "cyzone.cn/"
      ]
    }
  ]
}
```
