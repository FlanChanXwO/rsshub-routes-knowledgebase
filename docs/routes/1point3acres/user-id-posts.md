# 一亩三分地 - 用户回帖

## Coverage
`index-only`

## Route
- Namespace: `1point3acres`
- Namespace Name: `一亩三分地`
- Route Path: `/user/:id/posts`
- Route Name: `用户回帖`
- Example: `/1point3acres/user/1/posts`
- URL: `blog.1point3acres.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `Maecenas`
- Source Location: `user/post.ts`
- Source Module: `() => import('@/routes/1point3acres/user/post.ts')`

## Description
_None_

## Parameters
- `id`: 用户 id，可在 Instant 版网站的个人主页 URL 找到


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
  - `instant.1point3acres.com/profile/:id`
  - `instant.1point3acres.com/`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/1point3acres/user/1/posts",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user/post.ts",
  "maintainers": [
    "Maecenas"
  ],
  "module": "() => import('@/routes/1point3acres/user/post.ts')",
  "name": "用户回帖",
  "parameters": {
    "id": "用户 id，可在 Instant 版网站的个人主页 URL 找到"
  },
  "path": "/user/:id/posts",
  "radar": [
    {
      "source": [
        "instant.1point3acres.com/profile/:id",
        "instant.1point3acres.com/"
      ]
    }
  ]
}
```
