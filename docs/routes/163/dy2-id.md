# 网易公开课 - 网易号（通用）

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/dy2/:id`
- Route Name: `网易号（通用）`
- Example: `/163/dy2/T1555591616739`
- URL: `163.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `mjysci, lyqluis`
- Source Location: `dy2.ts`
- Source Module: `() => import('@/routes/163/dy2.ts')`

## Description
优先使用方法一，若是网易号搜索页面搜不到的小众网易号（文章页面不含`data-wemediaid`）则可使用此法。
触发反爬会只抓取到标题，建议自建。

## Parameters
- `id`: id，该网易号主页网址最后一项 html 的文件名


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "优先使用方法一，若是网易号搜索页面搜不到的小众网易号（文章页面不含`data-wemediaid`）则可使用此法。\n触发反爬会只抓取到标题，建议自建。",
  "example": "/163/dy2/T1555591616739",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "dy2.ts",
  "maintainers": [
    "mjysci",
    "lyqluis"
  ],
  "module": "() => import('@/routes/163/dy2.ts')",
  "name": "网易号（通用）",
  "parameters": {
    "id": "id，该网易号主页网址最后一项 html 的文件名"
  },
  "path": "/dy2/:id"
}
```
