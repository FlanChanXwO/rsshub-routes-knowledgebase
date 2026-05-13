# 豆瓣 - 频道书影音

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/channel/:id/subject/:nav`
- Route Name: `频道书影音`
- Example: `/douban/channel/30168934/subject/0`
- URL: `www.douban.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `umm233`
- Source Location: `channel/subject.ts`
- Source Module: `() => import('@/routes/douban/channel/subject.ts')`

## Description
| 电影 | 电视剧 | 图书 | 唱片 |
| ---- | ------ | ---- | ---- |
| 0    | 1      | 2    | 3    |

## Parameters
- `id`: 频道id
- `nav`: 书影音分类


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
  "description": "| 电影 | 电视剧 | 图书 | 唱片 |\n| ---- | ------ | ---- | ---- |\n| 0    | 1      | 2    | 3    |",
  "example": "/douban/channel/30168934/subject/0",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "channel/subject.ts",
  "maintainers": [
    "umm233"
  ],
  "module": "() => import('@/routes/douban/channel/subject.ts')",
  "name": "频道书影音",
  "parameters": {
    "id": "频道id",
    "nav": "书影音分类"
  },
  "path": "/channel/:id/subject/:nav"
}
```
