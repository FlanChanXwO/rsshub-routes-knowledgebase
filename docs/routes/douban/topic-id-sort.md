# 豆瓣 - 话题

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/topic/:id/:sort?`
- Route Name: `话题`
- Example: `/douban/topic/48823`
- URL: `www.douban.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `LogicJake, pseudoyu, haowenwu`
- Source Location: `other/topic.ts`
- Source Module: `() => import('@/routes/douban/other/topic.ts')`

## Description
_None_

## Parameters
- `id`: 话题id
- `sort`: 排序方式，hot或new，默认为new


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
  "example": "/douban/topic/48823",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "other/topic.ts",
  "maintainers": [
    "LogicJake",
    "pseudoyu",
    "haowenwu"
  ],
  "module": "() => import('@/routes/douban/other/topic.ts')",
  "name": "话题",
  "parameters": {
    "id": "话题id",
    "sort": "排序方式，hot或new，默认为new"
  },
  "path": "/topic/:id/:sort?"
}
```
