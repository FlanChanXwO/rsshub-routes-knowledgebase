# MIUI - 小米社区用户发帖

## Coverage
`index-only`

## Route
- Namespace: `miui`
- Namespace Name: `MIUI`
- Route Path: `/community/user/:uid`
- Route Name: `小米社区用户发帖`
- Example: `/miui/community/user/1200057564`
- URL: `miui.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `abc1763613206`
- Source Location: `community/user.ts`
- Source Module: `() => import('@/routes/miui/community/user.ts')`

## Description
_None_

## Parameters
- `uid`: 小米用户 UID，可于网页版用户主页链接中 `uid` 项获取


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
  - `web.vip.miui.com/page/info/mio/mio/homePage`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/miui/community/user/1200057564",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "community/user.ts",
  "maintainers": [
    "abc1763613206"
  ],
  "module": "() => import('@/routes/miui/community/user.ts')",
  "name": "小米社区用户发帖",
  "parameters": {
    "uid": "小米用户 UID，可于网页版用户主页链接中 `uid` 项获取"
  },
  "path": "/community/user/:uid",
  "radar": [
    {
      "source": [
        "web.vip.miui.com/page/info/mio/mio/homePage"
      ]
    }
  ]
}
```
