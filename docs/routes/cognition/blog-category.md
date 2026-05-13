# cognition - Blog

## Coverage
`index-only`

## Route
- Namespace: `cognition`
- Namespace Name: `cognition`
- Route Path: `/blog/:category?`
- Route Name: `Blog`
- Example: `/cognition/blog`
- URL: `cognition.ai/blog`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `Loongphy, ttttmr`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/cognition/blog.ts')`

## Description
_None_

## Parameters
- `category`: Category name, e.g., Research, Tutorials


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
  - `cognition.ai/blog/1`
  - `cognition.ai/blog/:category/1`
- `target`: `/blog/:category?`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/cognition/blog",
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
    "Loongphy",
    "ttttmr"
  ],
  "module": "() => import('@/routes/cognition/blog.ts')",
  "name": "Blog",
  "parameters": {
    "category": "Category name, e.g., Research, Tutorials"
  },
  "path": "/blog/:category?",
  "radar": [
    {
      "source": [
        "cognition.ai/blog/1",
        "cognition.ai/blog/:category/1"
      ],
      "target": "/blog/:category?"
    }
  ],
  "url": "cognition.ai/blog",
  "view": 0
}
```
