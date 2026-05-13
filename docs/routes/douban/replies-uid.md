# 豆瓣 - 日记最新回应

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/replies/:uid`
- Route Name: `日记最新回应`
- Example: `/douban/replies/xiaoyaxiaoya`
- URL: `www.douban.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `nczitzk`
- Source Location: `other/replies.ts`
- Source Module: `() => import('@/routes/douban/other/replies.ts')`

## Description
_None_

## Parameters
- `uid`: 用户id，可在用户日记页 URL 中找到


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
    "social-media"
  ],
  "example": "/douban/replies/xiaoyaxiaoya",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "other/replies.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/douban/other/replies.ts')",
  "name": "日记最新回应",
  "parameters": {
    "uid": "用户id，可在用户日记页 URL 中找到"
  },
  "path": "/replies/:uid"
}
```
