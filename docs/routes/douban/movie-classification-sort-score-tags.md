# 豆瓣 - 豆瓣电影分类

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/movie/classification/:sort?/:score?/:tags?`
- Route Name: `豆瓣电影分类`
- Example: `/douban/movie/classification/R/7.5/Netflix,2020`
- URL: `www.douban.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `zzwab`
- Source Location: `other/classification.ts`
- Source Module: `() => import('@/routes/douban/other/classification.ts')`

## Description
排序方式可选值如下

| 近期热门 | 标记最多 | 评分最高 | 最近上映 |
| -------- | -------- | -------- | -------- |
| U        | T        | S        | R        |

## Parameters
- `sort`: 排序方式，默认为U
- `score`: 最低评分，默认不限制
- `tags`: 分类标签，多个标签之间用英文逗号分隔，常见的标签到豆瓣电影的分类页面查看，支持自定义标签


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
  "description": "排序方式可选值如下\n\n| 近期热门 | 标记最多 | 评分最高 | 最近上映 |\n| -------- | -------- | -------- | -------- |\n| U        | T        | S        | R        |",
  "example": "/douban/movie/classification/R/7.5/Netflix,2020",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "other/classification.ts",
  "maintainers": [
    "zzwab"
  ],
  "module": "() => import('@/routes/douban/other/classification.ts')",
  "name": "豆瓣电影分类",
  "parameters": {
    "score": "最低评分，默认不限制",
    "sort": "排序方式，默认为U",
    "tags": "分类标签，多个标签之间用英文逗号分隔，常见的标签到豆瓣电影的分类页面查看，支持自定义标签"
  },
  "path": "/movie/classification/:sort?/:score?/:tags?"
}
```
