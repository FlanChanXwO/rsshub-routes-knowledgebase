# 69书吧 - 章节

## Coverage
`index-only`

## Route
- Namespace: `69shu`
- Namespace Name: `69书吧`
- Route Path: `/article/:id`
- Route Name: `章节`
- Example: `/69shu/article/47117`
- URL: `www.69shuba.cx`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `eternasuno`
- Source Location: `article.ts`
- Source Module: `() => import('@/routes/69shu/article.ts')`

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
  - `www.69shuba.cx/book/:id.htm`
- `target`: `/article/:id`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/69shu/article/47117",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "article.ts",
  "maintainers": [
    "eternasuno"
  ],
  "module": "() => import('@/routes/69shu/article.ts')",
  "name": "章节",
  "parameters": {
    "id": "小说 id, 可在对应小说页 URL 中找到"
  },
  "path": "/article/:id",
  "radar": [
    {
      "source": [
        "www.69shuba.cx/book/:id.htm"
      ],
      "target": "/article/:id"
    }
  ],
  "url": "www.69shuba.cx"
}
```
