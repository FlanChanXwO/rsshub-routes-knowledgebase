# Lofter - User

## Coverage
`index-only`

## Route
- Namespace: `lofter`
- Namespace Name: `Lofter`
- Route Path: `/user/:name?`
- Route Name: `User`
- Example: `/lofter/user/i`
- URL: `www.lofter.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `hondajojo, nczitzk, LucunJi`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/lofter/user.ts')`

## Description
_None_

## Parameters
- `name`: Lofter user name, can be found in the URL


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
  "example": "/lofter/user/i",
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
    "hondajojo",
    "nczitzk",
    "LucunJi"
  ],
  "module": "() => import('@/routes/lofter/user.ts')",
  "name": "User",
  "parameters": {
    "name": "Lofter user name, can be found in the URL"
  },
  "path": "/user/:name?",
  "view": 0
}
```
