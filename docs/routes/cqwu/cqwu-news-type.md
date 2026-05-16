# 重庆文理学院 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `cqwu`
- Namespace Name: `重庆文理学院`
- Route Path: `/cqwu/news/:type?`
- Route Name: `通知公告`
- Example: `/cqwu/news/academiceve`
- URL: `www.cqwu.net`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 学术活动公告 |
| -------- | ------------ |
| notify   | academiceve  |

## Parameters
- `type`: 可选，默认为 academiceve


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
    "university"
  ],
  "description": "| 通知公告 | 学术活动公告 |\n| -------- | ------------ |\n| notify   | academiceve  |",
  "example": "/cqwu/news/academiceve",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "通知公告",
  "parameters": {
    "type": "可选，默认为 academiceve "
  },
  "path": "/news/:type?",
  "topFeeds": [
    {
      "description": "重文理学术活动公告 - Powered by RSSHub",
      "errorAt": "2025-09-10T18:06:01.259Z",
      "errorMessage": "[GET] \"https://www.cqwu.edu.cn/channel_24895.html\": 404 \n",
      "id": "89795888453668864",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cqwu.edu.cn/channel_24895.html",
      "title": "重文理学术活动公告",
      "type": "feed",
      "url": "rsshub://cqwu/news/academiceve"
    }
  ]
}
```
