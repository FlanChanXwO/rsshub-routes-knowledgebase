# 中证网 - 中证视频

## Coverage
`index-only`

## Route
- Namespace: `cs`
- Namespace Name: `中证网`
- Route Path: `/video/:category?`
- Route Name: `中证视频`
- Example: `/cs/video/今日聚焦`
- URL: `cs.com.cn`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `video.ts`
- Source Module: `() => import('@/routes/cs/video.ts')`

## Description
| 今日聚焦 | 传闻求证 | 高端访谈 | 投教课堂 | 直播汇 |
| -------- | -------- | -------- | -------- | ------ |

## Parameters
- `category`: 分类，见下表，默认为今日聚焦


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
    "finance"
  ],
  "description": "| 今日聚焦 | 传闻求证 | 高端访谈 | 投教课堂 | 直播汇 |\n| -------- | -------- | -------- | -------- | ------ |",
  "example": "/cs/video/今日聚焦",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "video.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/cs/video.ts')",
  "name": "中证视频",
  "parameters": {
    "category": "分类，见下表，默认为今日聚焦"
  },
  "path": "/video/:category?"
}
```
