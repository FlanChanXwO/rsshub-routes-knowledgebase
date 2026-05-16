# 明月中文网 - 榜单

## Coverage
`index-only`

## Route
- Namespace: `56kog`
- Namespace Name: `明月中文网`
- Route Path: `/56kog/top/:category?`
- Route Name: `榜单`
- Example: `/56kog/top/weekvisit`
- URL: `56kog.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `nczitzk`
- Source Location: `top.ts`
- Source Module: `_None_`

## Description
| [周点击榜](https://www.56kog.com/top/weekvisit.html) | [总收藏榜](https://www.56kog.com/top/goodnum.html) | [最新 入库](https://www.56kog.com/top/postdate.html) |
| ---------------------------------------------------- | -------------------------------------------------- | ---------------------------------------------------- |
| weekvisit                                            | goodnum                                            | postdate                                             |

## Parameters
- `category`: 分类，见下表，默认为周点击榜


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
    "reading"
  ],
  "description": "| [周点击榜](https://www.56kog.com/top/weekvisit.html) | [总收藏榜](https://www.56kog.com/top/goodnum.html) | [最新 入库](https://www.56kog.com/top/postdate.html) |\n| ---------------------------------------------------- | -------------------------------------------------- | ---------------------------------------------------- |\n| weekvisit                                            | goodnum                                            | postdate                                             |",
  "example": "/56kog/top/weekvisit",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "top.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "榜单",
  "parameters": {
    "category": "分类，见下表，默认为周点击榜"
  },
  "path": "/top/:category?",
  "topFeeds": []
}
```
