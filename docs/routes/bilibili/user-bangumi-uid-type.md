# 哔哩哔哩 bilibili - 用户追番列表

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/user/bangumi/:uid/:type?`
- Route Name: `用户追番列表`
- Example: `/bilibili/user/bangumi/208259`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `wdssmq`
- Source Location: `user-bangumi.ts`
- Source Module: `() => import('@/routes/bilibili/user-bangumi.ts')`

## Description
_None_

## Parameters
- `uid`: 用户 id
- `type`: 1为番，2为剧，留空为1


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
  - `space.bilibili.com/:uid`
- `target`: `/user/bangumi/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/user/bangumi/208259",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user-bangumi.ts",
  "maintainers": [
    "wdssmq"
  ],
  "module": "() => import('@/routes/bilibili/user-bangumi.ts')",
  "name": "用户追番列表",
  "parameters": {
    "type": "1为番，2为剧，留空为1",
    "uid": "用户 id"
  },
  "path": "/user/bangumi/:uid/:type?",
  "radar": [
    {
      "source": [
        "space.bilibili.com/:uid"
      ],
      "target": "/user/bangumi/:uid"
    }
  ]
}
```
