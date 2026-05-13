# 抖音直播 - 博主

## Coverage
`index-only`

## Route
- Namespace: `douyin`
- Namespace Name: `抖音直播`
- Route Path: `/user/:uid/:routeParams?`
- Route Name: `博主`
- Example: `/douyin/user/MS4wLjABAAAARcAHmmF9mAG3JEixq_CdP72APhBlGlLVbN-1eBcPqao`
- URL: `douyin.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `Max-Tortoise, Rongronggg9`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/douyin/user.ts')`

## Description
_None_

## Parameters
- `uid`: uid，可在用户页面 URL 中找到
- `routeParams`: 额外参数，query string 格式，请参阅上面的表格


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `douyin.com/user/:uid`
- `target`: `/user/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/douyin/user/MS4wLjABAAAARcAHmmF9mAG3JEixq_CdP72APhBlGlLVbN-1eBcPqao",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.ts",
  "maintainers": [
    "Max-Tortoise",
    "Rongronggg9"
  ],
  "module": "() => import('@/routes/douyin/user.ts')",
  "name": "博主",
  "parameters": {
    "routeParams": "额外参数，query string 格式，请参阅上面的表格",
    "uid": "uid，可在用户页面 URL 中找到"
  },
  "path": "/user/:uid/:routeParams?",
  "radar": [
    {
      "source": [
        "douyin.com/user/:uid"
      ],
      "target": "/user/:uid"
    }
  ]
}
```
