# Zed - Blog

## Coverage
`index-only`

## Route
- Namespace: `zed`
- Namespace Name: `Zed`
- Route Path: `/blog`
- Route Name: `Blog`
- Example: `/zed/blog`
- URL: `zed.dev`
- Language: `en`
- Categories: `programming`
- Maintainers: `cscnk52`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/zed/blog.ts')`

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
  - `zed.dev`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "Provides a better reading experience (full articles) over the official ones.",
  "example": "/zed/blog",
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
  "module": "() => import('@/routes/zed/blog.ts')",
  "name": "Blog",
  "parameters": {},
  "path": "/blog",
  "radar": [
    {
      "source": [
        "zed.dev"
      ],
      "target": "/blog"
    }
  ],
  "url": "zed.dev",
  "view": 5
}
```
