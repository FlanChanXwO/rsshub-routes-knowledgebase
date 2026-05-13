# TheBrain - Blog

## Coverage
`index-only`

## Route
- Namespace: `thebrain`
- Namespace Name: `TheBrain`
- Route Path: `/blog`
- Route Name: `Blog`
- Example: `/thebrain/blog`
- URL: `www.thebrain.com`
- Language: `en`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `blog.tsx`
- Source Module: `() => import('@/routes/thebrain/blog.tsx')`

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
  - `www.thebrain.com/blog`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/thebrain/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "blog.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/thebrain/blog.tsx')",
  "name": "Blog",
  "path": "/blog",
  "radar": [
    {
      "source": [
        "www.thebrain.com/blog"
      ],
      "target": "/blog"
    }
  ],
  "url": "www.thebrain.com",
  "view": 0
}
```
