# 科学网 - 精选博客

## Coverage
`index-only`

## Route
- Namespace: `sciencenet`
- Namespace Name: `科学网`
- Route Path: `/blog/:type?/:time?/:sort?`
- Route Name: `精选博客`
- Example: `/sciencenet/blog`
- URL: `blog.sciencenet.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/sciencenet/blog.ts')`

## Description
类型

| 精选      | 最新 | 热门 |
| --------- | ---- | ---- |
| recommend | new  | hot  |

  时间

| 36 小时内精选博文 | 一周内精选博文 | 一月内精选博文 | 半年内精选博文 | 所有时间精选博文 |
| ----------------- | -------------- | -------------- | -------------- | ---------------- |
| 1                 | 2              | 3              | 4              | 5                |

  排序

| 按发表时间排序 | 按评论数排序 | 按点击数排序 |
| -------------- | ------------ | ------------ |
| 1              | 2            | 3            |

## Parameters
- `type`: 类型，见下表，默认为推荐
- `time`: 时间，见下表，默认为所有时间
- `sort`: 排序，见下表，默认为按发表时间排序


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
    "new-media"
  ],
  "description": "类型\n\n| 精选      | 最新 | 热门 |\n| --------- | ---- | ---- |\n| recommend | new  | hot  |\n\n  时间\n\n| 36 小时内精选博文 | 一周内精选博文 | 一月内精选博文 | 半年内精选博文 | 所有时间精选博文 |\n| ----------------- | -------------- | -------------- | -------------- | ---------------- |\n| 1                 | 2              | 3              | 4              | 5                |\n\n  排序\n\n| 按发表时间排序 | 按评论数排序 | 按点击数排序 |\n| -------------- | ------------ | ------------ |\n| 1              | 2            | 3            |",
  "example": "/sciencenet/blog",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/sciencenet/blog.ts')",
  "name": "精选博客",
  "parameters": {
    "sort": "排序，见下表，默认为按发表时间排序",
    "time": "时间，见下表，默认为所有时间",
    "type": "类型，见下表，默认为推荐"
  },
  "path": "/blog/:type?/:time?/:sort?"
}
```
