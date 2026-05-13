# 哔哩哔哩 bilibili - 会员购作品

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/mall/ip/:id`
- Route Name: `会员购作品`
- Example: `/bilibili/mall/ip/0_3000294`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `mall-ip.ts`
- Source Module: `() => import('@/routes/bilibili/mall-ip.ts')`

## Description
_None_

## Parameters
- `id`: 作品 id, 可在作品列表页 URL 中找到


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
  "example": "/bilibili/mall/ip/0_3000294",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "mall-ip.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/bilibili/mall-ip.ts')",
  "name": "会员购作品",
  "parameters": {
    "id": "作品 id, 可在作品列表页 URL 中找到"
  },
  "path": "/mall/ip/:id"
}
```
