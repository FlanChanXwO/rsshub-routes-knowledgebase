# 洛谷 - 用户博客

## Coverage
`index-only`

## Route
- Namespace: `luogu`
- Namespace Name: `洛谷`
- Route Path: `/user/blog/:name`
- Route Name: `用户博客`
- Example: `/luogu/user/blog/ftiasch`
- URL: `luogu.com.cn`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `ftiasch`
- Source Location: `user-blog.ts`
- Source Module: `() => import('@/routes/luogu/user-blog.ts')`

## Description
_None_

## Parameters
- `name`: 博客名称


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
  - `luogu.com/blog/:name`
### Rule 2
- `source`:
  - `luogu.com.cn/blog/:name`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/luogu/user/blog/ftiasch",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user-blog.ts",
  "maintainers": [
    "ftiasch"
  ],
  "module": "() => import('@/routes/luogu/user-blog.ts')",
  "name": "用户博客",
  "parameters": {
    "name": "博客名称"
  },
  "path": "/user/blog/:name",
  "radar": [
    {
      "source": [
        "luogu.com/blog/:name"
      ]
    },
    {
      "source": [
        "luogu.com.cn/blog/:name"
      ]
    }
  ]
}
```
