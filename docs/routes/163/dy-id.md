# 网易公开课 - 更新

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/dy/:id`
- Route Name: `更新`
- Example: `/163/dy/W4983108759592548559`
- URL: `163.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `HendricksZheng`
- Source Location: `dy.ts`
- Source Module: `() => import('@/routes/163/dy.ts')`

## Description
1.  在[网易号搜索页面](https://dy.163.com/v2/media/tosearch.html) 搜索想要订阅的网易号。
  2.  打开网易号的任意文章。
  3.  查看源代码，搜索 `data-wemediaid`，查看紧随其后的引号内的属性值（类似 `W1966190042455428950`）即为网易号 ID。

## Parameters
- `id`: 网易号 ID


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
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
  "description": "1.  在[网易号搜索页面](https://dy.163.com/v2/media/tosearch.html) 搜索想要订阅的网易号。\n  2.  打开网易号的任意文章。\n  3.  查看源代码，搜索 `data-wemediaid`，查看紧随其后的引号内的属性值（类似 `W1966190042455428950`）即为网易号 ID。",
  "example": "/163/dy/W4983108759592548559",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "dy.ts",
  "maintainers": [
    "HendricksZheng"
  ],
  "module": "() => import('@/routes/163/dy.ts')",
  "name": "更新",
  "parameters": {
    "id": "网易号 ID"
  },
  "path": "/dy/:id"
}
```
