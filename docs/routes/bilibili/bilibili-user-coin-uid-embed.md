# 哔哩哔哩 bilibili - UP 主投币视频

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/user/coin/:uid/:embed?`
- Route Name: `UP 主投币视频`
- Example: `/bilibili/user/coin/208259`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `coin.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 id, 可在 UP 主主页中找到
- `embed`: 默认为开启内嵌视频, 任意值为关闭


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
- `target`: `/user/coin/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/user/coin/208259",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 18,
  "location": "coin.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "UP 主投币视频",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/coin/:uid/:embed?",
  "radar": [
    {
      "source": [
        "space.bilibili.com/:uid"
      ],
      "target": "/user/coin/:uid"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "大闲人贾白 的 bilibili 投币视频 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59183499828667392",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/549117578",
      "title": "大闲人贾白 的 bilibili 投币视频",
      "type": "feed",
      "url": "rsshub://bilibili/user/coin/549117578"
    },
    {
      "description": "哈喽的B站频道 的 bilibili 投币视频 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62853430730507264",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/383447486",
      "title": "哈喽的B站频道 的 bilibili 投币视频",
      "type": "feed",
      "url": "rsshub://bilibili/user/coin/383447486"
    }
  ]
}
```
