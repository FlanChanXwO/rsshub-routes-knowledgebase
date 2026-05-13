# 豆瓣 - 电影即将上映

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/movie/coming`
- Route Name: `电影即将上映`
- Example: `/douban/movie/coming`
- URL: `www.douban.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `reonokiy`
- Source Location: `movie/coming.tsx`
- Source Module: `() => import('@/routes/douban/movie/coming.tsx')`

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
- `title`: `豆瓣电影-即将上映`
- `source`:
  - `movie.douban.com/coming`
- `target`: `/movie/coming`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/douban/movie/coming",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "movie/coming.tsx",
  "maintainers": [
    "reonokiy"
  ],
  "module": "() => import('@/routes/douban/movie/coming.tsx')",
  "name": "电影即将上映",
  "path": "/movie/coming",
  "radar": [
    {
      "source": [
        "movie.douban.com/coming"
      ],
      "target": "/movie/coming",
      "title": "豆瓣电影-即将上映"
    }
  ]
}
```
