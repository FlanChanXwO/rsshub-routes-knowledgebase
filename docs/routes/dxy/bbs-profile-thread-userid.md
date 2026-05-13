# 丁香园 - 个人帖子

## Coverage
`index-only`

## Route
- Namespace: `dxy`
- Namespace Name: `丁香园`
- Route Path: `/bbs/profile/thread/:userId`
- Route Name: `个人帖子`
- Example: `/dxy/bbs/profile/thread/8335054`
- URL: `dxy.cn`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `profile/thread.ts`
- Source Module: `() => import('@/routes/dxy/profile/thread.ts')`

## Description
_None_

## Parameters
- `userId`: 个人 ID，可在 URL 中找到


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
  - `dxy.cn/bbs/newweb/pc/profile/:userId/threads`
  - `dxy.cn/bbs/newweb/pc/profile/:userId`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/dxy/bbs/profile/thread/8335054",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "profile/thread.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/dxy/profile/thread.ts')",
  "name": "个人帖子",
  "parameters": {
    "userId": "个人 ID，可在 URL 中找到"
  },
  "path": "/bbs/profile/thread/:userId",
  "radar": [
    {
      "source": [
        "dxy.cn/bbs/newweb/pc/profile/:userId/threads",
        "dxy.cn/bbs/newweb/pc/profile/:userId"
      ]
    }
  ]
}
```
