# Bangumi 番组计划 - 用户日志

## Coverage
`index-only`

## Route
- Namespace: `bangumi.tv`
- Namespace Name: `Bangumi 番组计划`
- Route Path: `/user/blog/:id`
- Route Name: `用户日志`
- Example: `/bangumi.tv/user/blog/sai`
- URL: `bangumi.tv`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `nczitzk`
- Source Location: `user/blog.ts`
- Source Module: `() => import('@/routes/bangumi.tv/user/blog.ts')`

## Description
_None_

## Parameters
- `id`: 用户 id, 在用户页面地址栏查看


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
  - `bgm.tv/user/:id`
### Rule 2
- `source`:
  - `bangumi.tv/user/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/bangumi.tv/user/blog/sai",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user/blog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/bangumi.tv/user/blog.ts')",
  "name": "用户日志",
  "parameters": {
    "id": "用户 id, 在用户页面地址栏查看"
  },
  "path": "/user/blog/:id",
  "radar": [
    {
      "source": [
        "bgm.tv/user/:id"
      ]
    },
    {
      "source": [
        "bangumi.tv/user/:id"
      ]
    }
  ]
}
```
