# 唱吧 - 用户

## Coverage
`index-only`

## Route
- Namespace: `changba`
- Namespace Name: `唱吧`
- Route Path: `/:userid`
- Route Name: `用户`
- Example: `/changba/skp6hhF59n48R-UpqO3izw`
- URL: `changba.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `kt286, xizeyoupan, pseudoyu`
- Source Location: `user.tsx`
- Source Module: `() => import('@/routes/changba/user.tsx')`

## Description
_None_

## Parameters
- `userid`: 用户ID, 可在对应分享页面的 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `changba.com/s/:userid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/changba/skp6hhF59n48R-UpqO3izw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "location": "user.tsx",
  "maintainers": [
    "kt286",
    "xizeyoupan",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/changba/user.tsx')",
  "name": "用户",
  "parameters": {
    "userid": "用户ID, 可在对应分享页面的 URL 中找到"
  },
  "path": "/:userid",
  "radar": [
    {
      "source": [
        "changba.com/s/:userid"
      ]
    }
  ],
  "view": 4
}
```
