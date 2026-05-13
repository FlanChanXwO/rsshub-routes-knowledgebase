# 开源中国 - 用户博客

## Coverage
`index-only`

## Route
- Namespace: `oschina`
- Namespace Name: `开源中国`
- Route Path: `/u/:uid`
- Route Name: `用户博客`
- Example: `/oschina/u/3920392`
- URL: `oschina.net`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `dxmpalb`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/oschina/user.ts')`

## Description
_None_

## Parameters
- `uid`: 用户 id，可通过查看用户博客网址得到，以 u/数字结尾，数字即为 id


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `my.oschina.net/u/:uid`
  - `my.oschina.net/:uid`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/oschina/u/3920392",
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
    "dxmpalb"
  ],
  "module": "() => import('@/routes/oschina/user.ts')",
  "name": "用户博客",
  "parameters": {
    "uid": "用户 id，可通过查看用户博客网址得到，以 u/数字结尾，数字即为 id"
  },
  "path": "/u/:uid",
  "radar": [
    {
      "source": [
        "my.oschina.net/u/:uid",
        "my.oschina.net/:uid"
      ]
    }
  ]
}
```
