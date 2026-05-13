# Kiro - Blog

## Coverage
`index-only`

## Route
- Namespace: `kiro`
- Namespace Name: `Kiro`
- Route Path: `/blog`
- Route Name: `Blog`
- Example: `/kiro/blog`
- URL: `kiro.dev`
- Language: `en`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/kiro/blog.ts')`

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
  - `kiro.dev`
  - `kiro.dev/blog/`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/kiro/blog",
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
  "module": "() => import('@/routes/kiro/blog.ts')",
  "name": "Blog",
  "path": "/blog",
  "radar": [
    {
      "source": [
        "kiro.dev",
        "kiro.dev/blog/"
      ],
      "target": "/blog"
    }
  ],
  "url": "kiro.dev",
  "view": 0
}
```
