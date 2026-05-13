# 中国环球电视网 - 播客

## Coverage
`index-only`

## Route
- Namespace: `cgtn`
- Namespace Name: `中国环球电视网`
- Route Path: `/podcast/:category/:id`
- Route Name: `播客`
- Example: `/cgtn/podcast/ezfm/4`
- URL: `cgtn.com`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `5upernova-heng`
- Source Location: `podcast.ts`
- Source Module: `() => import('@/routes/cgtn/podcast.ts')`

## Description
> 类型名与播客 id 可以在播客对应的 URL 中找到
  > 如 URL `https://radio.cgtn.com/podcast/column/ezfm/More-to-Read/4` ，其 `category` 为 `ezfm` ，`id` 为 `4`，对应的订阅路由为 [`/podcast/ezfm/4`](https://rsshub.app/podcast/ezfm/4)

## Parameters
- `category`: 类型名
- `id`: 播客 id


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
  - `cgtn.com/podcast/column/:category/*/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "> 类型名与播客 id 可以在播客对应的 URL 中找到\n  > 如 URL `https://radio.cgtn.com/podcast/column/ezfm/More-to-Read/4` ，其 `category` 为 `ezfm` ，`id` 为 `4`，对应的订阅路由为 [`/podcast/ezfm/4`](https://rsshub.app/podcast/ezfm/4)",
  "example": "/cgtn/podcast/ezfm/4",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "podcast.ts",
  "maintainers": [
    "5upernova-heng"
  ],
  "module": "() => import('@/routes/cgtn/podcast.ts')",
  "name": "播客",
  "parameters": {
    "category": "类型名",
    "id": "播客 id"
  },
  "path": "/podcast/:category/:id",
  "radar": [
    {
      "source": [
        "cgtn.com/podcast/column/:category/*/:id"
      ]
    }
  ]
}
```
