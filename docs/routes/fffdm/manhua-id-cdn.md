# 风之动漫 - 在线漫画

## Coverage
`index-only`

## Route
- Namespace: `fffdm`
- Namespace Name: `风之动漫`
- Route Path: `/manhua/:id/:cdn?`
- Route Name: `在线漫画`
- Example: `/fffdm/manhua/93`
- URL: `manhua.fffdm.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `zytomorrow`
- Source Location: `manhua/manhua.tsx`
- Source Module: `() => import('@/routes/fffdm/manhua/manhua.tsx')`

## Description
_None_

## Parameters
- `id`: 漫画ID。默认获取全部，建议使用通用参数limit获取指定数量
- `cdn`: cdn加速器。默认5，当前可选1-5


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
  - `www.fffdm.com/manhua/:id`
  - `www.fffdm.com/:id`
- `target`: `/manhua/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/fffdm/manhua/93",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "manhua/manhua.tsx",
  "maintainers": [
    "zytomorrow"
  ],
  "module": "() => import('@/routes/fffdm/manhua/manhua.tsx')",
  "name": "在线漫画",
  "parameters": {
    "cdn": "cdn加速器。默认5，当前可选1-5",
    "id": "漫画ID。默认获取全部，建议使用通用参数limit获取指定数量"
  },
  "path": "/manhua/:id/:cdn?",
  "radar": [
    {
      "source": [
        "www.fffdm.com/manhua/:id",
        "www.fffdm.com/:id"
      ],
      "target": "/manhua/:id"
    }
  ]
}
```
