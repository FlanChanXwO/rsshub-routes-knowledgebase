# 哔哩哔哩 bilibili - 分区视频排行榜

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/partion/ranking/:tid/:days?/:embed?`
- Route Name: `分区视频排行榜`
- Example: `/bilibili/partion/ranking/171/3`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `lengthmin`
- Source Location: `partion-ranking.ts`
- Source Module: `() => import('@/routes/bilibili/partion-ranking.ts')`

## Description
_None_

## Parameters
- `tid`: 分区 id, 见上方表格
- `days`: 缺省为 7, 指最近多少天内的热度排序
- `embed`: 默认为开启内嵌视频, 任意值为关闭


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
  "example": "/bilibili/partion/ranking/171/3",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "partion-ranking.ts",
  "maintainers": [
    "lengthmin"
  ],
  "module": "() => import('@/routes/bilibili/partion-ranking.ts')",
  "name": "分区视频排行榜",
  "parameters": {
    "days": "缺省为 7, 指最近多少天内的热度排序",
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "tid": "分区 id, 见上方表格"
  },
  "path": "/partion/ranking/:tid/:days?/:embed?"
}
```
