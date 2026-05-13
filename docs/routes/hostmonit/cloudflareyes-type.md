# 全球主机监控 - CloudFlareYes

## Coverage
`index-only`

## Route
- Namespace: `hostmonit`
- Namespace Name: `全球主机监控`
- Route Path: `/cloudflareyes/:type?`
- Route Name: `CloudFlareYes`
- Example: `/hostmonit/cloudflareyes`
- URL: `stock.hostmonit.com`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `nczitzk`
- Source Location: `cloudflareyes.tsx`
- Source Module: `() => import('@/routes/hostmonit/cloudflareyes.tsx')`

## Description
| v4 | v6 |
| -- | -- |
|    | v6 |

## Parameters
- `type`: 类型，见下表，默认为 v4


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "| v4 | v6 |\n| -- | -- |\n|    | v6 |",
  "example": "/hostmonit/cloudflareyes",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cloudflareyes.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/hostmonit/cloudflareyes.tsx')",
  "name": "CloudFlareYes",
  "parameters": {
    "type": "类型，见下表，默认为 v4"
  },
  "path": "/cloudflareyes/:type?"
}
```
