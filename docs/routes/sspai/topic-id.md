# 少数派 sspai - 专题内文章更新

## Coverage
`index-only`

## Route
- Namespace: `sspai`
- Namespace Name: `少数派 sspai`
- Route Path: `/topic/:id`
- Route Name: `专题内文章更新`
- Example: `/sspai/topic/250`
- URL: `sspai.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `SunShinenny`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/sspai/topic.ts')`

## Description
_None_

## Parameters
- `id`: 专题 id，可在专题主页URL中找到


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
  - `sspai.com/topic/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/sspai/topic/250",
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
    "SunShinenny"
  ],
  "module": "() => import('@/routes/sspai/topic.ts')",
  "name": "专题内文章更新",
  "parameters": {
    "id": "专题 id，可在专题主页URL中找到"
  },
  "path": "/topic/:id",
  "radar": [
    {
      "source": [
        "sspai.com/topic/:id"
      ]
    }
  ]
}
```
