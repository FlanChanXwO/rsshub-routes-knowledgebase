# 知乎 - 知乎日报

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/daily`
- Route Name: `知乎日报`
- Example: `/zhihu/daily`
- URL: `daily.zhihu.com/*`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `DHPO, pseudoyu`
- Source Location: `daily.ts`
- Source Module: `() => import('@/routes/zhihu/daily.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `daily.zhihu.com/*`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/daily",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "daily.ts",
  "maintainers": [
    "DHPO",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/zhihu/daily.ts')",
  "name": "知乎日报",
  "parameters": {},
  "path": "/daily",
  "radar": [
    {
      "source": [
        "daily.zhihu.com/*"
      ]
    }
  ],
  "url": "daily.zhihu.com/*"
}
```
