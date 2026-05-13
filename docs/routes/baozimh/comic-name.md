# 包子漫画 - 订阅漫画

## Coverage
`index-only`

## Route
- Namespace: `baozimh`
- Namespace Name: `包子漫画`
- Route Path: `/comic/:name`
- Route Name: `订阅漫画`
- Example: `/baozimh/comic/guowangpaiming-shiricaofu`
- URL: `www.baozimh.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `Fatpandac`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/baozimh/index.tsx')`

## Description
_None_

## Parameters
- `name`: 漫画名称，在漫画链接可以得到(`comic/` 后的那段)


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
  - `www.baozimh.com/comic/:name`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/baozimh/comic/guowangpaiming-shiricaofu",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/baozimh/index.tsx')",
  "name": "订阅漫画",
  "parameters": {
    "name": "漫画名称，在漫画链接可以得到(`comic/` 后的那段)"
  },
  "path": "/comic/:name",
  "radar": [
    {
      "source": [
        "www.baozimh.com/comic/:name"
      ]
    }
  ]
}
```
