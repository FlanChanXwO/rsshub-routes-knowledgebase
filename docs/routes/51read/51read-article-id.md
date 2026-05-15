# 51Read - 章节

## Coverage
`index-only`

## Route
- Namespace: `51read`
- Namespace Name: `51Read`
- Route Path: `/51read/article/:id`
- Route Name: `章节`
- Example: `/51read/article/152685`
- URL: `m.51read.org`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `lazwa34`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 小说 id, 可在对应小说页 URL 中找到


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
  - `m.51read.org/xiaoshuo/:id`
- `target`: `/article/:id`
### Rule 2
- `source`:
  - `51read.org/xiaoshuo/:id`
- `target`: `/article/:id`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/51read/article/152685",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 11,
  "location": "article.ts",
  "maintainers": [
    "lazwa34"
  ],
  "name": "章节",
  "parameters": {
    "id": "小说 id, 可在对应小说页 URL 中找到"
  },
  "path": "/article/:id",
  "radar": [
    {
      "source": [
        "m.51read.org/xiaoshuo/:id"
      ],
      "target": "/article/:id"
    },
    {
      "source": [
        "51read.org/xiaoshuo/:id"
      ],
      "target": "/article/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "杂谈小说《鹅绒锁》_完整目录在线全文阅读 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60329035500625920",
      "image": "https://cdn.tongjiba.top/public/image/nocover.jpg",
      "ownerUserId": null,
      "siteUrl": "https://m.51read.org/xiaoshuo/152685",
      "title": "鹅绒锁",
      "type": "feed",
      "url": "rsshub://51read/article/152685"
    },
    {
      "description": "冒姓琅琊小说阅读冒姓琅琊由作家东周公子南创作小兵提供冒姓琅琊免费最新章节冒姓琅琊最新更新章节0- - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "202284532302966784",
      "image": "https://cdn.tongjiba.top/public/image/nocover.jpg",
      "ownerUserId": null,
      "siteUrl": "https://m.51read.org/xiaoshuo/411029",
      "title": "冒姓琅琊",
      "type": "feed",
      "url": "rsshub://51read/article/411029"
    }
  ],
  "url": "m.51read.org"
}
```
