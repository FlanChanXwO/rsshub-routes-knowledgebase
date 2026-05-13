# 恩山无线论坛 - 板块

## Coverage
`index-only`

## Route
- Namespace: `right`
- Namespace Name: `恩山无线论坛`
- Route Path: `/forum/:id?`
- Route Name: `板块`
- Example: `/right/forum/31`
- URL: `right.com.cn`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `forum.ts`
- Source Module: `() => import('@/routes/right/forum.ts')`

## Description
_None_

## Parameters
- `id`: 板块 id，可在板块页 URL 中找到，默认为新手入门及其它(硬件)


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
    "bbs"
  ],
  "example": "/right/forum/31",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "forum.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/right/forum.ts')",
  "name": "板块",
  "parameters": {
    "id": "板块 id，可在板块页 URL 中找到，默认为新手入门及其它(硬件)"
  },
  "path": "/forum/:id?"
}
```
