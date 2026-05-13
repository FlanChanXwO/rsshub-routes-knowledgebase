# Claude - Blog

## Coverage
`index-only`

## Route
- Namespace: `claude`
- Namespace Name: `Claude`
- Route Path: `/blog`
- Route Name: `Blog`
- Example: `/claude/blog`
- URL: `claude.com/blog`
- Language: `en`
- Categories: `programming`
- Maintainers: `zhenlohuang`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/claude/blog.ts')`

## Description
_None_

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
  - `claude.com/blog`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/claude/blog",
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
    "zhenlohuang"
  ],
  "module": "() => import('@/routes/claude/blog.ts')",
  "name": "Blog",
  "parameters": {},
  "path": "/blog",
  "radar": [
    {
      "source": [
        "claude.com/blog"
      ],
      "target": "/blog"
    }
  ],
  "url": "claude.com/blog"
}
```
