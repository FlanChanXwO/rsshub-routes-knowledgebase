# 南京信息工程大学 - NUIST AS（南信大大气科学学院）

## Coverage
`index-only`

## Route
- Namespace: `nuist`
- Namespace Name: `南京信息工程大学`
- Route Path: `/cas/:category?`
- Route Name: `NUIST AS（南信大大气科学学院）`
- Example: `/nuist/cas/xxgg`
- URL: `bulletin.nuist.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `gylidian`
- Source Location: `cas.ts`
- Source Module: `() => import('@/routes/nuist/cas.ts')`

## Description
| 信息公告 | 新闻快讯 | 科学研究 | 网上公示 | 本科教育 | 研究生教育 |
| -------- | -------- | -------- | -------- | -------- | ---------- |
| xxgg     | xwkx     | kxyj     | wsgs     | bkjy     | yjsjy      |

## Parameters
- `category`: 默认为信息公告


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 信息公告 | 新闻快讯 | 科学研究 | 网上公示 | 本科教育 | 研究生教育 |\n| -------- | -------- | -------- | -------- | -------- | ---------- |\n| xxgg     | xwkx     | kxyj     | wsgs     | bkjy     | yjsjy      |",
  "example": "/nuist/cas/xxgg",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cas.ts",
  "maintainers": [
    "gylidian"
  ],
  "module": "() => import('@/routes/nuist/cas.ts')",
  "name": "NUIST AS（南信大大气科学学院）",
  "parameters": {
    "category": "默认为信息公告"
  },
  "path": "/cas/:category?"
}
```
