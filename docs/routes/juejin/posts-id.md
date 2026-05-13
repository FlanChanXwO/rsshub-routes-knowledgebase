# 掘金 - 用户文章

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/posts/:id`
- Route Name: `用户文章`
- Example: `/juejin/posts/3051900006845944`
- URL: `juejin.cn`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `Maecenas`
- Source Location: `posts.ts`
- Source Module: `() => import('@/routes/juejin/posts.ts')`

## Description
_None_

## Parameters
- `id`: 用户 id, 可在用户页 URL 中找到


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
  - `juejin.cn/user/:id`
  - `juejin.cn/user/:id/posts`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/juejin/posts/3051900006845944",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "posts.ts",
  "maintainers": [
    "Maecenas"
  ],
  "module": "() => import('@/routes/juejin/posts.ts')",
  "name": "用户文章",
  "parameters": {
    "id": "用户 id, 可在用户页 URL 中找到"
  },
  "path": "/posts/:id",
  "radar": [
    {
      "source": [
        "juejin.cn/user/:id",
        "juejin.cn/user/:id/posts"
      ]
    }
  ]
}
```
