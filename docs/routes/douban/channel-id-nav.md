# 豆瓣 - 频道专题

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/channel/:id/:nav?`
- Route Name: `频道专题`
- Example: `/douban/channel/30168934/hot`
- URL: `www.douban.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `umm233`
- Source Location: `channel/topic.ts`
- Source Module: `() => import('@/routes/douban/channel/topic.ts')`

## Description
| 默认    | 热门 | 最新 |
| ------- | ---- | ---- |
| default | hot  | new  |

## Parameters
- `id`: 频道id
- `nav`: 专题分类，可选，默认为 default


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
  "description": "| 默认    | 热门 | 最新 |\n| ------- | ---- | ---- |\n| default | hot  | new  |",
  "example": "/douban/channel/30168934/hot",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "channel/topic.ts",
  "maintainers": [
    "umm233"
  ],
  "module": "() => import('@/routes/douban/channel/topic.ts')",
  "name": "频道专题",
  "parameters": {
    "id": "频道id",
    "nav": "专题分类，可选，默认为 default"
  },
  "path": "/channel/:id/:nav?"
}
```
