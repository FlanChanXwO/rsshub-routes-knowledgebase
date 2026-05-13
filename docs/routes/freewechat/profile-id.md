# 自由微信 - 公众号

## Coverage
`index-only`

## Route
- Namespace: `freewechat`
- Namespace Name: `自由微信`
- Route Path: `/profile/:id`
- Route Name: `公众号`
- Example: `/freewechat/profile/MzI5NTUxNzk3OA==`
- URL: `freewechat.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `profile.ts`
- Source Module: `() => import('@/routes/freewechat/profile.ts')`

## Description
_None_

## Parameters
- `id`: 公众号 ID，可在URL中找到


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
  - `freewechat.com/profile/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/freewechat/profile/MzI5NTUxNzk3OA==",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "profile.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/freewechat/profile.ts')",
  "name": "公众号",
  "parameters": {
    "id": "公众号 ID，可在URL中找到"
  },
  "path": "/profile/:id",
  "radar": [
    {
      "source": [
        "freewechat.com/profile/:id"
      ]
    }
  ]
}
```
