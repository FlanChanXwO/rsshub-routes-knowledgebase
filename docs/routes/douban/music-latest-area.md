# 豆瓣 - 最新增加的音乐

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/music/latest/:area?`
- Route Name: `最新增加的音乐`
- Example: `/douban/music/latest/chinese`
- URL: `www.douban.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `fengkx, xyqfer`
- Source Location: `other/latest-music.ts`
- Source Module: `() => import('@/routes/douban/other/latest-music.ts')`

## Description
| 华语    | 欧美    | 日韩        |
| ------- | ------- | ----------- |
| chinese | western | japankorean |

## Parameters
- `area`: 区域类型，默认全部


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
  "description": "| 华语    | 欧美    | 日韩        |\n| ------- | ------- | ----------- |\n| chinese | western | japankorean |",
  "example": "/douban/music/latest/chinese",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "other/latest-music.ts",
  "maintainers": [
    "fengkx",
    "xyqfer"
  ],
  "module": "() => import('@/routes/douban/other/latest-music.ts')",
  "name": "最新增加的音乐",
  "parameters": {
    "area": "区域类型，默认全部"
  },
  "path": "/music/latest/:area?"
}
```
