# 色花堂 - 作者文章

## Coverage
`index-only`

## Route
- Namespace: `sehuatang`
- Namespace Name: `色花堂`
- Route Path: `/sehuatang/user/:uid`
- Route Name: `作者文章`
- Example: `/sehuatang/user/411096`
- URL: `sehuatang.net`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `JamYiz`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 uid, 可在用户主页 URL 中找到


## Features
- `requireConfig`: [{"description": "", "name": "SEHUATANG_COOKIE"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/sehuatang/user/411096",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "",
        "name": "SEHUATANG_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "JamYiz"
  ],
  "name": "作者文章",
  "parameters": {
    "uid": "用户 uid, 可在用户主页 URL 中找到"
  },
  "path": "/user/:uid",
  "topFeeds": []
}
```
