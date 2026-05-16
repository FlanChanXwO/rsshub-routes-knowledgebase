# 人人都是产品经理 - 用户文章

## Coverage
`index-only`

## Route
- Namespace: `woshipm`
- Namespace Name: `人人都是产品经理`
- Route Path: `/woshipm/user_article/:id`
- Route Name: `用户文章`
- Example: `/woshipm/user_article/324696`
- URL: `woshipm.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `LogicJake`
- Source Location: `user-article.ts`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "user-article.ts",
  "maintainers": [
    "LogicJake"
  ],
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
  ],
  "topFeeds": []
}
```
