# 国家市场监督管理总局缺陷产品管理中心 - 召回信息

## Coverage
`index-only`

## Route
- Namespace: `samrdprc`
- Namespace Name: `国家市场监督管理总局缺陷产品管理中心`
- Route Path: `/samrdprc/news/:type1/:type2`
- Route Name: `召回信息`
- Example: `/samrdprc/news/xfpzh/xfpgnzh`
- URL: `www.samrdprc.org.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `a180285`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 类型中文   | 召回类型 ID1 | 召回类型 ID2 |
| ---------- | ------------ | ------------ |
| 消费品召回 | xfpzh        | xfpgnzh      |
| 汽车召回   | qczh         | gnzhqc       |

## Parameters
- `type1`: 召回类型ID1，见下表
- `type2`: 召回类型ID2，见下表


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
  - `www.samrdprc.org.cn/:type1/:type2`
- `target`: `/news/:type1/:type2`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 类型中文   | 召回类型 ID1 | 召回类型 ID2 |\n| ---------- | ------------ | ------------ |\n| 消费品召回 | xfpzh        | xfpgnzh      |\n| 汽车召回   | qczh         | gnzhqc       |",
  "example": "/samrdprc/news/xfpzh/xfpgnzh",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "news.ts",
  "maintainers": [
    "a180285"
  ],
  "name": "召回信息",
  "parameters": {
    "type1": "召回类型ID1，见下表",
    "type2": "召回类型ID2，见下表"
  },
  "path": "/news/:type1/:type2",
  "radar": [
    {
      "source": [
        "www.samrdprc.org.cn/:type1/:type2"
      ],
      "target": "/news/:type1/:type2"
    }
  ],
  "topFeeds": [
    {
      "description": "国内消费品召回新闻 - 国家市场监督管理总局 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "160626513899715584",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.samrdprc.org.cn/xfpzh/xfpgnzh",
      "title": "国内消费品召回新闻 - 国家市场监督管理总局",
      "type": "feed",
      "url": "rsshub://samrdprc/news/xfpzh/xfpgnzh"
    }
  ]
}
```
