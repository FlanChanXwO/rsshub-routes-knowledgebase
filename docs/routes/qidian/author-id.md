# 起点 - 作者

## Coverage
`index-only`

## Route
- Namespace: `qidian`
- Namespace Name: `起点`
- Route Path: `/author/:id`
- Route Name: `作者`
- Example: `/qidian/author/9639927`
- URL: `qidian.com`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `miles170, pseudoyu`
- Source Location: `author.tsx`
- Source Module: `() => import('@/routes/qidian/author.tsx')`

## Description
_None_

## Parameters
- `id`: 作者 id, 可在作者页面 URL 找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `my.qidian.com/author/:id`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/qidian/author/9639927",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "author.tsx",
  "maintainers": [
    "miles170",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/qidian/author.tsx')",
  "name": "作者",
  "parameters": {
    "id": "作者 id, 可在作者页面 URL 找到"
  },
  "path": "/author/:id",
  "radar": [
    {
      "source": [
        "my.qidian.com/author/:id"
      ]
    }
  ]
}
```
