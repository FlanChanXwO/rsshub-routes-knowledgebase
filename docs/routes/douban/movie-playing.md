# 豆瓣 - 正在上映的电影

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/movie/playing`
- Route Name: `正在上映的电影`
- Example: `/douban/movie/playing`
- URL: `www.douban.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `other/playing.ts`
- Source Module: `() => import('@/routes/douban/other/playing.ts')`

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
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/douban/movie/playing",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "other/playing.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/douban/other/playing.ts')",
  "name": "正在上映的电影",
  "parameters": {},
  "path": [
    "/movie/playing",
    "/movie/playing/:score"
  ]
}
```
