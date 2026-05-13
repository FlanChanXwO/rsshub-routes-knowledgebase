# 米哈游 - 米游社 - 用户关注

## Coverage
`index-only`

## Route
- Namespace: `mihoyo`
- Namespace Name: `米哈游`
- Route Path: `/bbs/follow-list/:uid`
- Route Name: `米游社 - 用户关注`
- Example: `/mihoyo/bbs/follow-list/77005350`
- URL: `genshin.hoyoverse.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `CaoMeiYouRen`
- Source Location: `bbs/follow-list.ts`
- Source Module: `() => import('@/routes/mihoyo/bbs/follow-list.ts')`

## Description
_None_

## Parameters
- `uid`: 用户uid


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
  "example": "/mihoyo/bbs/follow-list/77005350",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "bbs/follow-list.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "module": "() => import('@/routes/mihoyo/bbs/follow-list.ts')",
  "name": "米游社 - 用户关注",
  "parameters": {
    "uid": "用户uid"
  },
  "path": "/bbs/follow-list/:uid"
}
```
