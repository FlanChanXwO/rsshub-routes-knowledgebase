# 哔哩哔哩 bilibili - 用户所有视频

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/user/video-all/:uid/:embed?`
- Route Name: `用户所有视频`
- Example: `/bilibili/user/video-all/2267573`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `None`
- Source Location: `video-all.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 id, 可在 UP 主主页中找到
- `embed`: 默认为开启内嵌视频, 任意值为关闭


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/user/video-all/2267573",
  "heat": 1266,
  "location": "video-all.ts",
  "maintainers": [],
  "name": "用户所有视频",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/video-all/:uid/:embed?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "技术爬爬虾 的 bilibili 所有视频 - Powered by RSSHub",
      "errorAt": "2026-02-20T11:45:38.308Z",
      "errorMessage": "[GET] \"https://space.bilibili.com/316183842/video?tid=0&page=1&keyword=&order=pubdate\": 412 Precondition Failed\nCannot read properties of undefined (reading 'vlist')\n",
      "id": "82801159002601472",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/316183842/video",
      "title": "技术爬爬虾",
      "type": "feed",
      "url": "rsshub://bilibili/user/video-all/316183842"
    },
    {
      "description": "小Lin说 的 bilibili 所有视频 - Powered by RSSHub",
      "errorAt": "2026-02-20T14:10:00.367Z",
      "errorMessage": "[GET] \"https://space.bilibili.com/520819684/video?tid=0&page=1&keyword=&order=pubdate\": 412 Precondition Failed\n[GET] \"https://space.bilibili.com/520819684/video?tid=0&page=1&keyword=&order=pubdate\": 412 Precondition Failed\nCannot read properties of undefined (reading 'vlist')\nCannot read properties of undefined (reading 'vlist')\n",
      "id": "69028952282503168",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/520819684/video",
      "title": "小Lin说",
      "type": "feed",
      "url": "rsshub://bilibili/user/video-all/520819684"
    }
  ]
}
```
