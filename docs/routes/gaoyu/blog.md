# Yu Gao - Blog

## Coverage
`index-only`

## Route
- Namespace: `gaoyu`
- Namespace Name: `Yu Gao`
- Route Path: `/blog`
- Route Name: `Blog`
- Example: `/gaoyu/blog`
- URL: `www.gaoyu.me`
- Language: `zh-CN`
- Categories: `blog`
- Maintainers: `nczitzk`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/gaoyu/blog.ts')`

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
  - `www.gaoyu.me/blog`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/gaoyu/blog",
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
  "module": "() => import('@/routes/gaoyu/blog.ts')",
  "name": "Blog",
  "path": "/blog",
  "radar": [
    {
      "source": [
        "www.gaoyu.me/blog"
      ],
      "target": "/blog"
    }
  ],
  "url": "www.gaoyu.me",
  "view": 0
}
```
