# 腾讯 - 作者

## Coverage
`index-only`

## Route
- Namespace: `tencent`
- Namespace Name: `腾讯`
- Route Path: `/news/author/:mid`
- Route Name: `作者`
- Example: `/tencent/news/author/5933889`
- URL: `tencent.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `LogicJake, miles170`
- Source Location: `news/author.tsx`
- Source Module: `() => import('@/routes/tencent/news/author.tsx')`

## Description
_None_

## Parameters
- `mid`: 企鹅号 ID


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `当前作者文章`
- `source`:
  - `news.qq.com/omn/author/:mid`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/tencent/news/author/5933889",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news/author.tsx",
  "maintainers": [
    "LogicJake",
    "miles170"
  ],
  "module": "() => import('@/routes/tencent/news/author.tsx')",
  "name": "作者",
  "parameters": {
    "mid": "企鹅号 ID"
  },
  "path": "/news/author/:mid",
  "radar": [
    {
      "source": [
        "news.qq.com/omn/author/:mid"
      ],
      "title": "当前作者文章"
    }
  ]
}
```
