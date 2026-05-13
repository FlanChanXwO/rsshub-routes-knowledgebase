# Goldman Sachs - Goldman Sachs Developer Blog

## Coverage
`index-only`

## Route
- Namespace: `gs`
- Namespace Name: `Goldman Sachs`
- Route Path: `/developer/blog`
- Route Name: `Goldman Sachs Developer Blog`
- Example: `/gs/developer/blog`
- URL: `goldmansachs.com`
- Language: `en`
- Categories: `blog`
- Maintainers: `chesha1`
- Source Location: `developer/blog.ts`
- Source Module: `() => import('@/routes/gs/developer/blog.ts')`

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
  - `developer.gs.com/blog/posts`
- `target`: `/developer/blog`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/gs/developer/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "developer/blog.ts",
  "maintainers": [
    "chesha1"
  ],
  "module": "() => import('@/routes/gs/developer/blog.ts')",
  "name": "Goldman Sachs Developer Blog",
  "parameters": {},
  "path": "/developer/blog",
  "radar": [
    {
      "source": [
        "developer.gs.com/blog/posts"
      ],
      "target": "/developer/blog"
    }
  ],
  "zh": {
    "name": "高盛开发者博客"
  }
}
```
