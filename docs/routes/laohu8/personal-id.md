# 老虎社区 - 个人主页

## Coverage
`index-only`

## Route
- Namespace: `laohu8`
- Namespace Name: `老虎社区`
- Route Path: `/personal/:id`
- Route Name: `个人主页`
- Example: `/laohu8/personal/3527667596890271`
- URL: `laohu8.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `Fatpandac`
- Source Location: `personal.ts`
- Source Module: `() => import('@/routes/laohu8/personal.ts')`

## Description
_None_

## Parameters
- `id`: 用户 ID，见网址链接


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
  - `laohu8.com/personal/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/laohu8/personal/3527667596890271",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "personal.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/laohu8/personal.ts')",
  "name": "个人主页",
  "parameters": {
    "id": "用户 ID，见网址链接"
  },
  "path": "/personal/:id",
  "radar": [
    {
      "source": [
        "laohu8.com/personal/:id"
      ]
    }
  ],
  "view": 0
}
```
