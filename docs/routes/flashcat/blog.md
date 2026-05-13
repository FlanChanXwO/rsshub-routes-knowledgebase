# Flashcat - 快猫星云博客

## Coverage
`index-only`

## Route
- Namespace: `flashcat`
- Namespace Name: `Flashcat`
- Route Path: `/blog`
- Route Name: `快猫星云博客`
- Example: `/flashcat/blog`
- URL: `flashcat.cloud`
- Language: `zh-CN`
- Categories: `blog`
- Maintainers: `chesha1`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/flashcat/blog.ts')`

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
  - `flashcat.cloud/blog`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/flashcat/blog",
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
    "chesha1"
  ],
  "module": "() => import('@/routes/flashcat/blog.ts')",
  "name": "快猫星云博客",
  "parameters": {},
  "path": "/blog",
  "radar": [
    {
      "source": [
        "flashcat.cloud/blog"
      ],
      "target": "/blog"
    }
  ]
}
```
