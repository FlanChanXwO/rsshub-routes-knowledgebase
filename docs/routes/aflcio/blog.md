# AFL-CIO - Blog

## Coverage
`index-only`

## Route
- Namespace: `aflcio`
- Namespace Name: `AFL-CIO`
- Route Path: `/blog`
- Route Name: `Blog`
- Example: `/aflcio/blog`
- URL: `aflcio.org`
- Language: `en`
- Categories: `other`
- Maintainers: `nczitzk`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/aflcio/blog.ts')`

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
  - `aflcio.org/blog`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/aflcio/blog",
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
  "module": "() => import('@/routes/aflcio/blog.ts')",
  "name": "Blog",
  "path": "/blog",
  "radar": [
    {
      "source": [
        "aflcio.org/blog"
      ],
      "target": "/blog"
    }
  ],
  "url": "aflcio.org",
  "view": 0
}
```
