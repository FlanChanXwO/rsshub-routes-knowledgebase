# 知乎 - 知乎日报 - 合集

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/daily/section/:sectionId`
- Route Name: `知乎日报 - 合集`
- Example: `/zhihu/daily/section/2`
- URL: `daily.zhihu.com/*`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `ccbikai`
- Source Location: `daily-section.ts`
- Source Module: `() => import('@/routes/zhihu/daily-section.ts')`

## Description
_None_

## Parameters
- `sectionId`: 合集 id，可在 https://news-at.zhihu.com/api/7/sections 找到


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
- `target`: `/daily`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/daily/section/2",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "daily-section.ts",
  "maintainers": [
    "ccbikai"
  ],
  "module": "() => import('@/routes/zhihu/daily-section.ts')",
  "name": "知乎日报 - 合集",
  "parameters": {
    "sectionId": "合集 id，可在 https://news-at.zhihu.com/api/7/sections 找到"
  },
  "path": "/daily/section/:sectionId",
  "radar": [
    {
      "source": [
        "daily.zhihu.com/*"
      ],
      "target": "/daily"
    }
  ],
  "url": "daily.zhihu.com/*"
}
```
