# Readhub - 每日早报

## Coverage
`index-only`

## Route
- Namespace: `readhub`
- Namespace Name: `Readhub`
- Route Path: `/daily`
- Route Name: `每日早报`
- Example: `/readhub/daily`
- URL: `readhub.cn/daily`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk, fashioncj`
- Source Location: `daily.ts`
- Source Module: `() => import('@/routes/readhub/daily.ts')`

## Description
_None_

## Parameters
_None_


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
  - `readhub.cn/daily`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/readhub/daily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "daily.ts",
  "maintainers": [
    "nczitzk",
    "fashioncj"
  ],
  "module": "() => import('@/routes/readhub/daily.ts')",
  "name": "每日早报",
  "parameters": {},
  "path": "/daily",
  "radar": [
    {
      "source": [
        "readhub.cn/daily"
      ]
    }
  ],
  "url": "readhub.cn/daily"
}
```
