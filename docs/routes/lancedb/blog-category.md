# LanceDB - Blog

## Coverage
`index-only`

## Route
- Namespace: `lancedb`
- Namespace Name: `LanceDB`
- Route Path: `/blog/:category?`
- Route Name: `Blog`
- Example: `/lancedb/blog`
- URL: `lancedb.com/blog`
- Language: `en`
- Categories: `programming`
- Maintainers: `HUSTERGS`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/lancedb/blog.ts')`

## Description
_None_

## Parameters
- `category`: filter blog post by category, return all posts if not specified


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
  - `lancedb.com/blog`
  - `lancedb.com/blog/category/:category`
- `target`: `/blog/:category`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/lancedb/blog",
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
    "HUSTERGS"
  ],
  "module": "() => import('@/routes/lancedb/blog.ts')",
  "name": "Blog",
  "parameters": {
    "category": "filter blog post by category, return all posts if not specified"
  },
  "path": "/blog/:category?",
  "radar": [
    {
      "source": [
        "lancedb.com/blog",
        "lancedb.com/blog/category/:category"
      ],
      "target": "/blog/:category"
    }
  ],
  "url": "lancedb.com/blog",
  "view": 0
}
```
