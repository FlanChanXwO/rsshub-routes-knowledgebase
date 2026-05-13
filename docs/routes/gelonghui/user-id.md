# 格隆汇 - 用户文章

## Coverage
`index-only`

## Route
- Namespace: `gelonghui`
- Namespace Name: `格隆汇`
- Route Path: `/user/:id`
- Route Name: `用户文章`
- Example: `/gelonghui/user/5273`
- URL: `gelonghui.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/gelonghui/user.ts')`

## Description
_None_

## Parameters
- `id`: 用户编号，可在用户页 URL 中找到


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
  - `gelonghui.com/user/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/gelonghui/user/5273",
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
  "module": "() => import('@/routes/gelonghui/user.ts')",
  "name": "用户文章",
  "parameters": {
    "id": "用户编号，可在用户页 URL 中找到"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "gelonghui.com/user/:id"
      ]
    }
  ],
  "view": 0
}
```
