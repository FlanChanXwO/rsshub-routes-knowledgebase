# AIbase - AI日报

## Coverage
`index-only`

## Route
- Namespace: `aibase`
- Namespace Name: `AIbase`
- Route Path: `/daily`
- Route Name: `AI日报`
- Example: `/aibase/daily`
- URL: `www.aibase.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `3tuuu`
- Source Location: `daily.ts`
- Source Module: `() => import('@/routes/aibase/daily.ts')`

## Description
获取 AI 日报

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.aibase.com/zh/daily`
- `target`: `/daily`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "获取 AI 日报",
  "example": "/aibase/daily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "daily.ts",
  "maintainers": [
    "3tuuu"
  ],
  "module": "() => import('@/routes/aibase/daily.ts')",
  "name": "AI日报",
  "path": "/daily",
  "radar": [
    {
      "source": [
        "www.aibase.com/zh/daily"
      ],
      "target": "/daily"
    }
  ],
  "url": "www.aibase.com"
}
```
