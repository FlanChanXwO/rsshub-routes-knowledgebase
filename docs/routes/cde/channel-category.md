# 国家药品审评网站 - 首页

## Coverage
`index-only`

## Route
- Namespace: `cde`
- Namespace Name: `国家药品审评网站`
- Route Path: `/:channel/:category`
- Route Name: `首页`
- Example: `/cde/news/gzdt`
- URL: `www.cde.org.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/cde/index.ts')`

## Description
-   频道

| 新闻中心 | 政策法规 |
| :------: | :------: |
|   news   |  policy  |

  -   类别

| 新闻中心 | 政务新闻 | 要闻导读 | 图片新闻 | 工作动态 |
| :------: | :------: | :------: | :------: | :------: |
|          |   zwxw   |   ywdd   |   tpxw   |   gzdt   |

| 政策法规 | 法律法规 | 中心规章 |
| :------: | :------: | :------: |
|          |   flfg   |   zxgz   |

## Parameters
- `channel`: 频道
- `category`: 类别


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
    "government"
  ],
  "description": "-   频道\n\n| 新闻中心 | 政策法规 |\n| :------: | :------: |\n|   news   |  policy  |\n\n  -   类别\n\n| 新闻中心 | 政务新闻 | 要闻导读 | 图片新闻 | 工作动态 |\n| :------: | :------: | :------: | :------: | :------: |\n|          |   zwxw   |   ywdd   |   tpxw   |   gzdt   |\n\n| 政策法规 | 法律法规 | 中心规章 |\n| :------: | :------: | :------: |\n|          |   flfg   |   zxgz   |",
  "example": "/cde/news/gzdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/cde/index.ts')",
  "name": "首页",
  "parameters": {
    "category": "类别",
    "channel": "频道"
  },
  "path": "/:channel/:category"
}
```
