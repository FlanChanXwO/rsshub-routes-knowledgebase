# 汽车召回网 - 汽车召回

## Coverage
`index-only`

## Route
- Namespace: `qiche365`
- Namespace Name: `汽车召回网`
- Route Path: `/recall/:channel`
- Route Name: `汽车召回`
- Example: `/qiche365/recall/1`
- URL: `qiche365.org.cn/index/recall/index.html`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `huanfe1, pseudoyu`
- Source Location: `recall.ts`
- Source Module: `() => import('@/routes/qiche365/recall.ts')`

## Description
| 国内召回新闻 | 国内召回公告 | 国外召回新闻 | 国外召回公告 |
| ------------ | ------------ | ------------ | ------------ |
| 1            | 2            | 3            | 4            |

## Parameters
- `channel`: 频道，见下表


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 国内召回新闻 | 国内召回公告 | 国外召回新闻 | 国外召回公告 |\n| ------------ | ------------ | ------------ | ------------ |\n| 1            | 2            | 3            | 4            |",
  "example": "/qiche365/recall/1",
  "features": {
    "antiCrawler": true
  },
  "location": "recall.ts",
  "maintainers": [
    "huanfe1",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/qiche365/recall.ts')",
  "name": "汽车召回",
  "parameters": {
    "channel": "频道，见下表"
  },
  "path": "/recall/:channel",
  "url": "qiche365.org.cn/index/recall/index.html"
}
```
