# 小黑盒 - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `xiaoheihe`
- Namespace Name: `小黑盒`
- Route Path: `/user/:id`
- Route Name: `用户动态`
- Example: `/xiaoheihe/user/30664023`
- URL: `xiaoheihe.cn`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `tssujt`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/xiaoheihe/user.ts')`

## Description
_None_

## Parameters
- `id`: 用户 ID


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
    "game"
  ],
  "example": "/xiaoheihe/user/30664023",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.ts",
  "maintainers": [
    "tssujt"
  ],
  "module": "() => import('@/routes/xiaoheihe/user.ts')",
  "name": "用户动态",
  "parameters": {
    "id": "用户 ID"
  },
  "path": "/user/:id"
}
```
