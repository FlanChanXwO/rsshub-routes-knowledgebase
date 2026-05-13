# 抖音直播 - 标签

## Coverage
`index-only`

## Route
- Namespace: `douyin`
- Namespace Name: `抖音直播`
- Route Path: `/hashtag/:cid/:routeParams?`
- Route Name: `标签`
- Example: `/douyin/hashtag/1592824105719812`
- URL: `douyin.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `hashtag.ts`
- Source Module: `() => import('@/routes/douyin/hashtag.ts')`

## Description
_None_

## Parameters
- `cid`: 标签 ID，可在标签页面 URL 中找到
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
  - `douyin.com/hashtag/:cid`
- `target`: `/hashtag/:cid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/douyin/hashtag/1592824105719812",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "hashtag.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/douyin/hashtag.ts')",
  "name": "标签",
  "parameters": {
    "cid": "标签 ID，可在标签页面 URL 中找到",
    "routeParams": "额外参数，query string 格式，请参阅上面的表格"
  },
  "path": "/hashtag/:cid/:routeParams?",
  "radar": [
    {
      "source": [
        "douyin.com/hashtag/:cid"
      ],
      "target": "/hashtag/:cid"
    }
  ]
}
```
