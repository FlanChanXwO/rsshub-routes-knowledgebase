# 台灣角川 - 角編新聞台

## Coverage
`index-only`

## Route
- Namespace: `kadokawa`
- Namespace Name: `台灣角川`
- Route Path: `/blog`
- Route Name: `角編新聞台`
- Example: `/kadokawa/blog`
- URL: `kadokawa.com.tw`
- Language: `zh-TW`
- Categories: `blog`
- Maintainers: `nczitzk`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/kadokawa/blog.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `kadokawa.com.tw/blog/posts`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "",
  "example": "/kadokawa/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "blog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/kadokawa/blog.ts')",
  "name": "角編新聞台",
  "path": "/blog",
  "radar": [
    {
      "source": [
        "kadokawa.com.tw/blog/posts"
      ],
      "target": "/blog"
    }
  ],
  "url": "kadokawa.com.tw"
}
```
