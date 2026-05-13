# Cursor - Blog

## Coverage
`index-only`

## Route
- Namespace: `cursor`
- Namespace Name: `Cursor`
- Route Path: `/blog/:topic?/:locale?`
- Route Name: `Blog`
- Example: `/cursor/blog`
- URL: `cursor.com`
- Language: `en`
- Categories: `blog`
- Maintainers: `johan456789`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/cursor/blog.ts')`

## Description
_None_

## Parameters
- `locale`: Locale appended to the route path, e.g. `ja`
- `topic`: Topic: all | product | research | company | news


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
  - `cursor.com/blog`
- `target`: `/blog`
### Rule 2
- `source`:
  - `cursor.com/blog/topic/:topic`
- `target`: `/blog/:topic`
### Rule 3
- `source`:
  - `cursor.com/:locale/blog`
- `target`: `/blog/all/:locale`
### Rule 4
- `source`:
  - `cursor.com/:locale/blog/topic/:topic`
- `target`: `/blog/:topic/:locale`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/cursor/blog",
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
    "johan456789"
  ],
  "module": "() => import('@/routes/cursor/blog.ts')",
  "name": "Blog",
  "parameters": {
    "locale": "Locale appended to the route path, e.g. `ja`",
    "topic": "Topic: all | product | research | company | news"
  },
  "path": "/blog/:topic?/:locale?",
  "radar": [
    {
      "source": [
        "cursor.com/blog"
      ],
      "target": "/blog"
    },
    {
      "source": [
        "cursor.com/blog/topic/:topic"
      ],
      "target": "/blog/:topic"
    },
    {
      "source": [
        "cursor.com/:locale/blog"
      ],
      "target": "/blog/all/:locale"
    },
    {
      "source": [
        "cursor.com/:locale/blog/topic/:topic"
      ],
      "target": "/blog/:topic/:locale"
    }
  ],
  "url": "cursor.com",
  "view": 0
}
```
