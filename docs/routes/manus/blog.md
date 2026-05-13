# Manus - Blog

## Coverage
`index-only`

## Route
- Namespace: `manus`
- Namespace Name: `Manus`
- Route Path: `/blog`
- Route Name: `Blog`
- Example: `/manus/blog`
- URL: `manus.im`
- Language: `en`
- Categories: `programming`
- Maintainers: `cscnk52`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/manus/blog.ts')`

## Description
Manus Blog

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
  - `www.manus.im`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "Manus Blog",
  "example": "/manus/blog",
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
  "module": "() => import('@/routes/manus/blog.ts')",
  "name": "Blog",
  "parameters": {},
  "path": "/blog",
  "radar": [
    {
      "source": [
        "www.manus.im"
      ],
      "target": "/blog"
    }
  ],
  "url": "manus.im",
  "view": 5
}
```
