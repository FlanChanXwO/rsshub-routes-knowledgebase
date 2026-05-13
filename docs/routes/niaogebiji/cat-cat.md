# 鸟哥笔记 - 分类目录

## Coverage
`index-only`

## Route
- Namespace: `niaogebiji`
- Namespace Name: `鸟哥笔记`
- Route Path: `/cat/:cat`
- Route Name: `分类目录`
- Example: `/niaogebiji/cat/103`
- URL: `niaogebiji.com/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `cKotoriKat`
- Source Location: `cat.ts`
- Source Module: `() => import('@/routes/niaogebiji/cat.ts')`

## Description
_None_

## Parameters
- `cat`: 如 https://www.niaogebiji.com/cat/103，最后的数字就是id


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `niaogebiji.com/cat/:cat`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/niaogebiji/cat/103",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cat.ts",
  "maintainers": [
    "cKotoriKat"
  ],
  "module": "() => import('@/routes/niaogebiji/cat.ts')",
  "name": "分类目录",
  "parameters": {
    "cat": "如 https://www.niaogebiji.com/cat/103，最后的数字就是id"
  },
  "path": "/cat/:cat",
  "radar": [
    {
      "source": [
        "niaogebiji.com/cat/:cat"
      ]
    }
  ],
  "url": "niaogebiji.com/"
}
```
