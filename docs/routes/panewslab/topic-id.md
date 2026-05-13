# PANews - 专题

## Coverage
`index-only`

## Route
- Namespace: `panewslab`
- Namespace Name: `PANews`
- Route Path: `/topic/:id`
- Route Name: `专题`
- Example: `/panewslab/topic/1629365774078402`
- URL: `panewslab.com/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/panewslab/topic.ts')`

## Description
_None_

## Parameters
- `id`: 专题 id，可在地址栏 URL 中找到


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
  "example": "/panewslab/topic/1629365774078402",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "topic.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/panewslab/topic.ts')",
  "name": "专题",
  "parameters": {
    "id": "专题 id，可在地址栏 URL 中找到"
  },
  "path": "/topic/:id",
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
