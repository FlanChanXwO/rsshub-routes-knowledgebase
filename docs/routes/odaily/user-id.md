# Odaily 星球日报 - 用户文章

## Coverage
`index-only`

## Route
- Namespace: `odaily`
- Namespace Name: `Odaily 星球日报`
- Route Path: `/user/:id`
- Route Name: `用户文章`
- Example: `/odaily/user/2147486902`
- URL: `odaily.news`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/odaily/user.ts')`

## Description
_None_

## Parameters
- `id`: 用户 id，可在用户页地址栏中找到


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
  - `0daily.com/user/:id`
  - `0daily.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/odaily/user/2147486902",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/odaily/user.ts')",
  "name": "用户文章",
  "parameters": {
    "id": "用户 id，可在用户页地址栏中找到"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "0daily.com/user/:id",
        "0daily.com/"
      ]
    }
  ]
}
```
