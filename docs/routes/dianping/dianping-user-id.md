# 大众点评 - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `dianping`
- Namespace Name: `大众点评`
- Route Path: `/dianping/user/:id`
- Route Name: `用户动态`
- Example: `/dianping/user/808259118`
- URL: `dianping.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `pseudoyu`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
获取用户点评、签到、攻略等动态。

## Parameters
- `id`: User id，打开网页端从 URL 中获取，在 `/member/:id` 中


## Features
- `requireConfig`: [{"description": "大众点评的 Cookie", "name": "DIANPING_COOKIE", "optional": false}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `dianping.com/member/:id`
- `target`: `/dianping/user/:id`
### Rule 2
- `source`:
  - `m.dianping.com/userprofile/:id`
- `target`: `/dianping/user/:id`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "获取用户点评、签到、攻略等动态。",
  "example": "/dianping/user/808259118",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "大众点评的 Cookie",
        "name": "DIANPING_COOKIE",
        "optional": false
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
    "pseudoyu"
  ],
  "name": "用户动态",
  "parameters": {
    "id": "User id，打开网页端从 URL 中获取，在 `/member/:id` 中"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "dianping.com/member/:id"
      ],
      "target": "/dianping/user/:id"
    },
    {
      "source": [
        "m.dianping.com/userprofile/:id"
      ],
      "target": "/dianping/user/:id"
    }
  ],
  "topFeeds": []
}
```
