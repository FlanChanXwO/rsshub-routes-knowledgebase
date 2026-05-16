# 中国国家应急广播 - 应急新闻

## Coverage
`index-only`

## Route
- Namespace: `cneb`
- Namespace Name: `中国国家应急广播`
- Route Path: `/cneb/yjxw/:category?`
- Route Name: `应急新闻`
- Example: `/cneb/yjxw`
- URL: `cneb.gov.cn`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `nczitzk`
- Source Location: `yjxw.ts`
- Source Module: `_None_`

## Description
| 全部 | 国内新闻 | 国际新闻 |
| ---- | -------- | -------- |
|      | gnxw     | gjxw     |

## Parameters
- `category`: 分类，见下表，默认为全部


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
  - `cneb.gov.cn/yjxw/:category?`
  - `cneb.gov.cn/`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "description": "| 全部 | 国内新闻 | 国际新闻 |\n| ---- | -------- | -------- |\n|      | gnxw     | gjxw     |",
  "example": "/cneb/yjxw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 18,
  "location": "yjxw.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "应急新闻",
  "parameters": {
    "category": "分类，见下表，默认为全部"
  },
  "path": "/yjxw/:category?",
  "radar": [
    {
      "source": [
        "cneb.gov.cn/yjxw/:category?",
        "cneb.gov.cn/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "国家应急广播 - 新闻 - Powered by RSSHub",
      "errorAt": "2026-05-14T06:03:25.939Z",
      "errorMessage": "Failed to fetch\nFailed to fetch\n",
      "id": "57295548899554304",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.cneb.gov.cn/yjxw",
      "title": "国家应急广播 - 新闻",
      "type": "feed",
      "url": "rsshub://cneb/yjxw"
    },
    {
      "description": "国家应急广播 - 国内新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73292547067243520",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.cneb.gov.cn/yjxw/gnxw",
      "title": "国家应急广播 - 国内新闻",
      "type": "feed",
      "url": "rsshub://cneb/yjxw/gnxw"
    }
  ]
}
```
