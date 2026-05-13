# 人人都是产品经理 - 用户文章

## Coverage
`index-only`

## Route
- Namespace: `woshipm`
- Namespace Name: `人人都是产品经理`
- Route Path: `/user_article/:id`
- Route Name: `用户文章`
- Example: `/woshipm/user_article/324696`
- URL: `woshipm.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `LogicJake`
- Source Location: `user-article.ts`
- Source Module: `() => import('@/routes/woshipm/user-article.ts')`

## Description
_None_

## Parameters
- `id`: 用户 id


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
  - `woshipm.com/u/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/woshipm/user_article/324696",
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
    "LogicJake"
  ],
  "module": "() => import('@/routes/woshipm/user-article.ts')",
  "name": "用户文章",
  "parameters": {
    "id": "用户 id"
  },
  "path": "/user_article/:id",
  "radar": [
    {
      "source": [
        "woshipm.com/u/:id"
      ]
    }
  ]
}
```
