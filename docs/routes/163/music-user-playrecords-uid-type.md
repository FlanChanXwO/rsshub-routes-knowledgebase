# 网易公开课 - 用户听歌排行

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/music/user/playrecords/:uid/:type?`
- Route Name: `用户听歌排行`
- Example: `/163/music/user/playrecords/45441555/1`
- URL: `163.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `alfredcai`
- Source Location: `music/userplayrecords.tsx`
- Source Module: `() => import('@/routes/163/music/userplayrecords.tsx')`

## Description
_None_

## Parameters
- `uid`: 用户 uid, 可在用户主页 URL 中找到
- `type`: 排行榜类型，0所有时间(默认)，1最近一周


## Features
- `requireConfig`: [{"description": "网易云音乐登陆后的 cookie 值，可在浏览器控制台通过`document.cookie`获取。", "name": "NCM_COOKIES", "optional": true}]
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
    "multimedia"
  ],
  "example": "/163/music/user/playrecords/45441555/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "网易云音乐登陆后的 cookie 值，可在浏览器控制台通过`document.cookie`获取。",
        "name": "NCM_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "music/userplayrecords.tsx",
  "maintainers": [
    "alfredcai"
  ],
  "module": "() => import('@/routes/163/music/userplayrecords.tsx')",
  "name": "用户听歌排行",
  "parameters": {
    "type": "排行榜类型，0所有时间(默认)，1最近一周",
    "uid": "用户 uid, 可在用户主页 URL 中找到"
  },
  "path": "/music/user/playrecords/:uid/:type?"
}
```
