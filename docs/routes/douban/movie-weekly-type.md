# 豆瓣 - 一周口碑榜

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/movie/weekly/:type?`
- Route Name: `一周口碑榜`
- Example: `/douban/movie/weekly`
- URL: `www.douban.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `numm233, nczitzk`
- Source Location: `other/weekly-best.tsx`
- Source Module: `() => import('@/routes/douban/other/weekly-best.tsx')`

## Description
| 一周口碑电影榜      | 华语口碑剧集榜            |
| ------------------- | ------------------------- |
| movie_weekly_best | tv_chinese_best_weekly |

## Parameters
- `type`: 分类，可在榜单页 URL 中找到，默认为一周口碑电影榜


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
  "description": "| 一周口碑电影榜      | 华语口碑剧集榜            |\n| ------------------- | ------------------------- |\n| movie_weekly_best | tv_chinese_best_weekly |",
  "example": "/douban/movie/weekly",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "other/weekly-best.tsx",
  "maintainers": [
    "numm233",
    "nczitzk"
  ],
  "module": "() => import('@/routes/douban/other/weekly-best.tsx')",
  "name": "一周口碑榜",
  "parameters": {
    "type": "分类，可在榜单页 URL 中找到，默认为一周口碑电影榜"
  },
  "path": "/movie/weekly/:type?"
}
```
