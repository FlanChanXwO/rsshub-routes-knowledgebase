# 四川农业大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `sicau`
- Namespace Name: `四川农业大学`
- Route Path: `/sicau/yan/:category?`
- Route Name: `研究生院`
- Example: `/sicau/yan/xwgg`
- URL: `yan.sicau.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `yan.ts`
- Source Module: `_None_`

## Description
| 新闻公告 | 学术报告 |
| -------- | -------- |
| xwgg     | xsbg     |

## Parameters
- `category`: 分类，见下表，默认为新闻公告


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
  - `yan.sicau.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 新闻公告 | 学术报告 |\n| -------- | -------- |\n| xwgg     | xsbg     |",
  "example": "/sicau/yan/xwgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "yan.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "研究生院",
  "parameters": {
    "category": "分类，见下表，默认为新闻公告"
  },
  "path": "/yan/:category?",
  "radar": [
    {
      "source": [
        "yan.sicau.edu.cn/"
      ]
    }
  ],
  "topFeeds": [],
  "url": "yan.sicau.edu.cn/"
}
```
