# X 漫画 - 最新动态

## Coverage
`index-only`

## Route
- Namespace: `xmanhua`
- Namespace Name: `X 漫画`
- Route Path: `/:uid`
- Route Name: `最新动态`
- Example: `/xmanhua/73xm`
- URL: `xmanhua.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `Ye11`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/xmanhua/index.ts')`

## Description
_None_

## Parameters
- `uid`: 漫画 id,在浏览器中可见，例如鬼灭之刃对应的 id 为 `73xm`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `xmanhua.com/:uid`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/xmanhua/73xm",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "Ye11"
  ],
  "module": "() => import('@/routes/xmanhua/index.ts')",
  "name": "最新动态",
  "parameters": {
    "uid": "漫画 id,在浏览器中可见，例如鬼灭之刃对应的 id 为 `73xm`"
  },
  "path": "/:uid",
  "radar": [
    {
      "source": [
        "xmanhua.com/:uid"
      ]
    }
  ]
}
```
