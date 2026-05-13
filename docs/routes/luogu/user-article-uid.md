# 洛谷 - 用户文章

## Coverage
`index-only`

## Route
- Namespace: `luogu`
- Namespace Name: `洛谷`
- Route Path: `/user/article/:uid`
- Route Name: `用户文章`
- Example: `/luogu/user/article/1`
- URL: `luogu.com.cn`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `TonyRL`
- Source Location: `user-article.ts`
- Source Module: `() => import('@/routes/luogu/user-article.ts')`

## Description
_None_

## Parameters
- `name`: 用户 UID


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
  - `luogu.com/user/:uid`
### Rule 2
- `source`:
  - `luogu.com.cn/user/:uid`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/luogu/user/article/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user-article.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/luogu/user-article.ts')",
  "name": "用户文章",
  "parameters": {
    "name": "用户 UID"
  },
  "path": "/user/article/:uid",
  "radar": [
    {
      "source": [
        "luogu.com/user/:uid"
      ]
    },
    {
      "source": [
        "luogu.com.cn/user/:uid"
      ]
    }
  ]
}
```
