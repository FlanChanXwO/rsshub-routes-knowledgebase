# 中国环球电视网 - 播客

## Coverage
`index-only`

## Route
- Namespace: `cgtn`
- Namespace Name: `中国环球电视网`
- Route Path: `/cgtn/podcast/:category/:id`
- Route Name: `播客`
- Example: `/cgtn/podcast/ezfm/4`
- URL: `cgtn.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `5upernova-heng`
- Source Location: `podcast.ts`
- Source Module: `_None_`

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
  "description": "> 类型名与播客 id 可以在播客对应的 URL 中找到\n> 如 URL `https://radio.cgtn.com/podcast/column/ezfm/More-to-Read/4` ，其 `category` 为 `ezfm` ，`id` 为 `4`，对应的订阅路由为 [`/podcast/ezfm/4`](https://rsshub.app/podcast/ezfm/4)",
  "example": "/cgtn/podcast/ezfm/4",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "podcast.ts",
  "maintainers": [
    "5upernova-heng"
  ],
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
  ],
  "topFeeds": [
    {
      "description": "中英双语美文欣赏，感受聆听文学之美，享受学习语言之乐。 - Powered by RSSHub",
      "errorAt": "2026-03-08T16:29:16.624Z",
      "errorMessage": "Cannot read properties of undefined (reading 'content')\n",
      "id": "86255766295882752",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cgtn.com/radio/",
      "title": "中国环球电视网 CGTN Podcast - 中英双语美文欣赏，感受聆听文学之美，享受学习语言之乐。",
      "type": "feed",
      "url": "rsshub://cgtn/podcast/ezfm/4"
    }
  ]
}
```
