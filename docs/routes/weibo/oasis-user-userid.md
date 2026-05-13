# 微博 - 绿洲用户

## Coverage
`index-only`

## Route
- Namespace: `weibo`
- Namespace Name: `微博`
- Route Path: `/oasis/user/:userid`
- Route Name: `绿洲用户`
- Example: `/weibo/oasis/user/1990895721`
- URL: `weibo.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `kt286`
- Source Location: `oasis/user.ts`
- Source Module: `() => import('@/routes/weibo/oasis/user.ts')`

## Description
_None_

## Parameters
- `userid`: 用户 id, 可在用户主页 URL 中找到


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
  - `m.weibo.cn/u/:uid`
  - `m.weibo.cn/profile/:uid`
- `target`: `/user/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/weibo/oasis/user/1990895721",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "oasis/user.ts",
  "maintainers": [
    "kt286"
  ],
  "module": "() => import('@/routes/weibo/oasis/user.ts')",
  "name": "绿洲用户",
  "parameters": {
    "userid": "用户 id, 可在用户主页 URL 中找到"
  },
  "path": "/oasis/user/:userid",
  "radar": [
    {
      "source": [
        "m.weibo.cn/u/:uid",
        "m.weibo.cn/profile/:uid"
      ],
      "target": "/user/:uid"
    }
  ]
}
```
