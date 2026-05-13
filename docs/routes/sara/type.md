# 上海业余无线电协会 - 新闻资讯

## Coverage
`index-only`

## Route
- Namespace: `sara`
- Namespace Name: `上海业余无线电协会`
- Route Path: `/:type`
- Route Name: `新闻资讯`
- Example: `/sara/announcement`
- URL: `www.sara.org.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `HChenZi`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/sara/index.ts')`

## Description
| 协会动态 | 通知公告 |行业动态 |
| -------- | ------------ | -------- |
| dynamic | announcement | industry |

## Parameters
- `type`: dynamic | announcement | industry


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 协会动态 | 通知公告 |行业动态 |\n| -------- | ------------ | -------- |\n| dynamic | announcement | industry |",
  "example": "/sara/announcement",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "HChenZi"
  ],
  "module": "() => import('@/routes/sara/index.ts')",
  "name": "新闻资讯",
  "parameters": {
    "type": "dynamic | announcement | industry"
  },
  "path": "/:type"
}
```
