# chlinlearn 的技术博客 - 值得一读技术博客

## Coverage
`index-only`

## Route
- Namespace: `chlinlearn`
- Namespace Name: `chlinlearn 的技术博客`
- Route Path: `/daily-blog`
- Route Name: `值得一读技术博客`
- Example: `/chlinlearn/daily-blog`
- URL: `daily-blog.chlinlearn.top`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `huyyi`
- Source Location: `daily-blog.ts`
- Source Module: `() => import('@/routes/chlinlearn/daily-blog.ts')`

## Description
_None_

## Parameters
_None_


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
  - `daily-blog.chlinlearn.top/blogs/*`
- `target`: `/chlinlearn/daily-blog`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/chlinlearn/daily-blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "daily-blog.ts",
  "maintainers": [
    "huyyi"
  ],
  "module": "() => import('@/routes/chlinlearn/daily-blog.ts')",
  "name": "值得一读技术博客",
  "path": "/daily-blog",
  "radar": [
    {
      "source": [
        "daily-blog.chlinlearn.top/blogs/*"
      ],
      "target": "/chlinlearn/daily-blog"
    }
  ]
}
```
