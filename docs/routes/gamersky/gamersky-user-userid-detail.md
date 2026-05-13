# GamerSky - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `gamersky`
- Namespace Name: `GamerSky`
- Route Path: `/gamersky/user/:userId/:detail?`
- Route Name: `用户动态`
- Example: `/gamersky/user/4009731/detail`
- URL: `gamersky.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `hualiong`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `userId`: 用户 ID。在用户个人主页，打开“开发者工具”中的“元素”标签页，搜索 data-userid 即可找到
- `detail`: 是否获取文章详情。只要该参数不为空，就会获取全文内容


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
  "example": "/gamersky/user/4009731/detail",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "hualiong"
  ],
  "name": "用户动态",
  "parameters": {
    "detail": "是否获取文章详情。只要该参数不为空，就会获取全文内容",
    "userId": "用户 ID。在用户个人主页，打开“开发者工具”中的“元素”标签页，搜索 data-userid 即可找到"
  },
  "path": "/user/:userId/:detail?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
