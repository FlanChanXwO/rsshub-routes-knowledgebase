# 少数派 sspai - 标签订阅

## Coverage
`index-only`

## Route
- Namespace: `sspai`
- Namespace Name: `少数派 sspai`
- Route Path: `/tag/:keyword`
- Route Name: `标签订阅`
- Example: `/sspai/tag/apple`
- URL: `sspai.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `Jeason0228`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/sspai/tag.ts')`

## Description
_None_

## Parameters
- `keyword`: 关键词


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
  - `sspai.com/tag/:keyword`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/sspai/tag/apple",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tag.ts",
  "maintainers": [
    "Jeason0228"
  ],
  "module": "() => import('@/routes/sspai/tag.ts')",
  "name": "标签订阅",
  "parameters": {
    "keyword": "关键词"
  },
  "path": "/tag/:keyword",
  "radar": [
    {
      "source": [
        "sspai.com/tag/:keyword"
      ]
    }
  ]
}
```
