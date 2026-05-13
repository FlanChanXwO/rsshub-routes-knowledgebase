# 方格子 - 用户个人文章

## Coverage
`index-only`

## Route
- Namespace: `vocus`
- Namespace Name: `方格子`
- Route Path: `/user/:id`
- Route Name: `用户个人文章`
- Example: `/vocus/user/tsetyan`
- URL: `vocus.cc`
- Language: `zh-TW`
- Categories: `social-media`
- Maintainers: `LogicJake`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/vocus/user.ts')`

## Description
_None_

## Parameters
- `id`: 用户 id，可在用户主页的 URL 找到


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
  "example": "/vocus/user/tsetyan",
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
    "LogicJake"
  ],
  "module": "() => import('@/routes/vocus/user.ts')",
  "name": "用户个人文章",
  "parameters": {
    "id": "用户 id，可在用户主页的 URL 找到"
  },
  "path": "/user/:id"
}
```
