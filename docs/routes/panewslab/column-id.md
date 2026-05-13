# PANews - 专栏

## Coverage
`index-only`

## Route
- Namespace: `panewslab`
- Namespace Name: `PANews`
- Route Path: `/column/:id`
- Route Name: `专栏`
- Example: `/panewslab/author/166`
- URL: `panewslab.com/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `author.ts`
- Source Module: `() => import('@/routes/panewslab/author.ts')`

## Description
_None_

## Parameters
- `id`: 专栏 id，可在地址栏 URL 中找到


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
  - `panewslab.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/panewslab/author/166",
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
  "module": "() => import('@/routes/panewslab/author.ts')",
  "name": "专栏",
  "parameters": {
    "id": "专栏 id，可在地址栏 URL 中找到"
  },
  "path": [
    "/author/:id",
    "/column/:id"
  ],
  "radar": [
    {
      "source": [
        "panewslab.com/"
      ]
    }
  ],
  "url": "panewslab.com/"
}
```
