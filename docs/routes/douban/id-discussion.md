# 豆瓣 - 豆瓣读书论坛

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/:id/discussion`
- Route Name: `豆瓣读书论坛`
- Example: `/douban/36328704/discussion`
- URL: `www.douban.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `nightmare-mio`
- Source Location: `other/discussion.ts`
- Source Module: `() => import('@/routes/douban/other/discussion.ts')`

## Description
_None_

## Parameters
- `id`: 书本id;默认论坛文章使用"按回应时间排序",仅第一页文章


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
  - `book.douban.com/:id/discussion`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/douban/36328704/discussion",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "other/discussion.ts",
  "maintainers": [
    "nightmare-mio"
  ],
  "module": "() => import('@/routes/douban/other/discussion.ts')",
  "name": "豆瓣读书论坛",
  "parameters": {
    "id": "书本id;默认论坛文章使用\"按回应时间排序\",仅第一页文章"
  },
  "path": "/:id/discussion",
  "radar": [
    {
      "source": [
        "book.douban.com/:id/discussion"
      ]
    }
  ]
}
```
