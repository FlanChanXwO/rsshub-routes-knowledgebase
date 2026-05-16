# 南京信息工程大学 - NUIST CS（南信大计软院）

## Coverage
`index-only`

## Route
- Namespace: `nuist`
- Namespace Name: `南京信息工程大学`
- Route Path: `/nuist/scs/:category?`
- Route Name: `NUIST CS（南信大计软院）`
- Example: `/nuist/scs/xwkx`
- URL: `bulletin.nuist.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `gylidian`
- Source Location: `scs.ts`
- Source Module: `_None_`

## Description
| 新闻快讯 | 通知公告 | 教务信息 | 科研动态 | 学子风采 |
| -------- | -------- | -------- | -------- | -------- |
| xwkx     | tzgg     | jwxx     | kydt     | xzfc     |

## Parameters
- `category`: 默认为新闻快讯


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
  - `scs.nuist.edu.cn/:category/list.htm`
- `target`: `/scs/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 新闻快讯 | 通知公告 | 教务信息 | 科研动态 | 学子风采 |\n| -------- | -------- | -------- | -------- | -------- |\n| xwkx     | tzgg     | jwxx     | kydt     | xzfc     |",
  "example": "/nuist/scs/xwkx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "scs.ts",
  "maintainers": [
    "gylidian"
  ],
  "name": "NUIST CS（南信大计软院）",
  "parameters": {
    "category": "默认为新闻快讯"
  },
  "path": "/scs/:category?",
  "radar": [
    {
      "source": [
        "scs.nuist.edu.cn/:category/list.htm"
      ],
      "target": "/scs/:category"
    }
  ],
  "topFeeds": []
}
```
