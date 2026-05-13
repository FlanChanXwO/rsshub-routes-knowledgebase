# 即刻 - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `jike`
- Namespace Name: `即刻`
- Route Path: `/user/:id`
- Route Name: `用户动态`
- Example: `/jike/user/3EE02BC9-C5B3-4209-8750-4ED1EE0F67BB`
- URL: `m.okjike.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `DIYgod, prnake`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/jike/user.ts')`

## Description
_None_

## Parameters
- `id`: 用户 id, 可在即刻分享出来的单条动态页点击用户头像进入个人主页，然后在个人主页的 URL 中找到，或者在单条动态页使用 RSSHub Radar 插件


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
  - `web.okjike.com/u/:uid`
- `target`: `/user/:uid`
### Rule 2
- `source`:
  - `m.okjike.com/users/:uid`
- `target`: `/user/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/jike/user/3EE02BC9-C5B3-4209-8750-4ED1EE0F67BB",
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
    "DIYgod",
    "prnake"
  ],
  "module": "() => import('@/routes/jike/user.ts')",
  "name": "用户动态",
  "parameters": {
    "id": "用户 id, 可在即刻分享出来的单条动态页点击用户头像进入个人主页，然后在个人主页的 URL 中找到，或者在单条动态页使用 RSSHub Radar 插件"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "web.okjike.com/u/:uid"
      ],
      "target": "/user/:uid"
    },
    {
      "source": [
        "m.okjike.com/users/:uid"
      ],
      "target": "/user/:uid"
    }
  ],
  "view": 1
}
```
