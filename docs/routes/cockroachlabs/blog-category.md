# Cockroach Labs - Blogs

## Coverage
`index-only`

## Route
- Namespace: `cockroachlabs`
- Namespace Name: `Cockroach Labs`
- Route Path: `/blog/:category?`
- Route Name: `Blogs`
- Example: `/cockroachlabs/blog/engineering`
- URL: `cockroachlabs.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `CookiePieWw`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/cockroachlabs/blog.ts')`

## Description
_None_

## Parameters
- `category`: Blog category, e.g., engineering. Subscribe all recent articles if empty.


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
  - `cockroachlabs.com/blog/:category`
  - `cockroachlabs.com/blog`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/cockroachlabs/blog/engineering",
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
    "CookiePieWw"
  ],
  "module": "() => import('@/routes/cockroachlabs/blog.ts')",
  "name": "Blogs",
  "parameters": {
    "category": "Blog category, e.g., engineering. Subscribe all recent articles if empty."
  },
  "path": "/blog/:category?",
  "radar": [
    {
      "source": [
        "cockroachlabs.com/blog/:category",
        "cockroachlabs.com/blog"
      ],
      "target": "/blog"
    }
  ]
}
```
