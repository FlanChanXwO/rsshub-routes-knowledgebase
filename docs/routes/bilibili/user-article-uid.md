# 哔哩哔哩 bilibili - UP 主图文

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/user/article/:uid`
- Route Name: `UP 主图文`
- Example: `/bilibili/user/article/334958638`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `lengthmin, Qixingchen, hyoban`
- Source Location: `article.ts`
- Source Module: `() => import('@/routes/bilibili/article.ts')`

## Description
_None_

## Parameters
- `uid`: 用户 id, 可在 UP 主主页中找到


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

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/user/article/334958638",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "article.ts",
  "maintainers": [
    "lengthmin",
    "Qixingchen",
    "hyoban"
  ],
  "module": "() => import('@/routes/bilibili/article.ts')",
  "name": "UP 主图文",
  "parameters": {
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/article/:uid",
  "radar": [
    {
      "source": [
        "space.bilibili.com/:uid"
      ]
    }
  ]
}
```
