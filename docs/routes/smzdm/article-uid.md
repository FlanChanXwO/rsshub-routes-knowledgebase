# 什么值得买 - 用户文章

## Coverage
`index-only`

## Route
- Namespace: `smzdm`
- Namespace Name: `什么值得买`
- Route Path: `/article/:uid`
- Route Name: `用户文章`
- Example: `/smzdm/article/6902738986`
- URL: `post.smzdm.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `xfangbao`
- Source Location: `article.ts`
- Source Module: `() => import('@/routes/smzdm/article.ts')`

## Description
_None_

## Parameters
- `uid`: 用户 id，网址上直接可以看到


## Features
- `requireConfig`: [{"description": "什么值得买登录后的 Cookie 值", "name": "SMZDM_COOKIE"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `zhiyou.smzdm.com/member/:uid/article`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/smzdm/article/6902738986",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "什么值得买登录后的 Cookie 值",
        "name": "SMZDM_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "article.ts",
  "maintainers": [
    "xfangbao"
  ],
  "module": "() => import('@/routes/smzdm/article.ts')",
  "name": "用户文章",
  "parameters": {
    "uid": "用户 id，网址上直接可以看到"
  },
  "path": "/article/:uid",
  "radar": [
    {
      "source": [
        "zhiyou.smzdm.com/member/:uid/article"
      ]
    }
  ]
}
```
