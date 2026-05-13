# 得到 - 得到文章

## Coverage
`index-only`

## Route
- Namespace: `dedao`
- Namespace Name: `得到`
- Route Path: `/articles/:id?`
- Route Name: `得到文章`
- Example: `/articles/9`
- URL: `www.igetget.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `Jacky-Chen-Pro`
- Source Location: `articles.ts`
- Source Module: `() => import('@/routes/dedao/articles.ts')`

## Description
_None_

## Parameters
- `id`: 文章类型 ID，8 为得到头条，9 为得到精选，默认为 8


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
  - `igetget.com`
- `target`: `/articles/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/articles/9",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "articles.ts",
  "maintainers": [
    "Jacky-Chen-Pro"
  ],
  "module": "() => import('@/routes/dedao/articles.ts')",
  "name": "得到文章",
  "parameters": {
    "id": "文章类型 ID，8 为得到头条，9 为得到精选，默认为 8"
  },
  "path": "/articles/:id?",
  "radar": [
    {
      "source": [
        "igetget.com"
      ],
      "target": "/articles/:id"
    }
  ],
  "url": "www.igetget.com"
}
```
