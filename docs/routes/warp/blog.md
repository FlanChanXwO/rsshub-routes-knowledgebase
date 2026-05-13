# Warp - Blog

## Coverage
`index-only`

## Route
- Namespace: `warp`
- Namespace Name: `Warp`
- Route Path: `/blog`
- Route Name: `Blog`
- Example: `/warp/blog`
- URL: `warp.dev`
- Language: `en`
- Categories: `programming`
- Maintainers: `cscnk52`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/warp/blog.ts')`

## Description
Provides a better reading experience (full articles) over the official ones.

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
  - `www.warp.dev`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "Provides a better reading experience (full articles) over the official ones.",
  "example": "/warp/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "blog.ts",
  "maintainers": [
    "cscnk52"
  ],
  "module": "() => import('@/routes/warp/blog.ts')",
  "name": "Blog",
  "parameters": {},
  "path": "/blog",
  "radar": [
    {
      "source": [
        "www.warp.dev"
      ],
      "target": "/blog"
    }
  ],
  "url": "warp.dev",
  "view": 5
}
```
