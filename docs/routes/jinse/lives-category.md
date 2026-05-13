# 金色财经 - 快讯

## Coverage
`index-only`

## Route
- Namespace: `jinse`
- Namespace Name: `金色财经`
- Route Path: `/lives/:category?`
- Route Name: `快讯`
- Example: `/jinse/lives`
- URL: `jinse.com.cn`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `lives.ts`
- Source Module: `() => import('@/routes/jinse/lives.ts')`

## Description
| 全部 | 精选 | 政策 | 数据 | NFT | 项目 |
| ---- | ---- | ---- | ---- | --- | ---- |
| 0    | 1    | 2    | 3    | 4   | 5    |

## Parameters
- `category`: {"default": "0", "description": "分类", "options": [{"label": "全部", "value": "0"}, {"label": "精选", "value": "1"}, {"label": "政策", "value": "2"}, {"label": "数据", "value": "3"}, {"label": "NFT", "value": "4"}, {"label": "项目", "value": "5"}]}


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
    "finance"
  ],
  "description": "| 全部 | 精选 | 政策 | 数据 | NFT | 项目 |\n| ---- | ---- | ---- | ---- | --- | ---- |\n| 0    | 1    | 2    | 3    | 4   | 5    |",
  "example": "/jinse/lives",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "lives.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/jinse/lives.ts')",
  "name": "快讯",
  "parameters": {
    "category": {
      "default": "0",
      "description": "分类",
      "options": [
        {
          "label": "全部",
          "value": "0"
        },
        {
          "label": "精选",
          "value": "1"
        },
        {
          "label": "政策",
          "value": "2"
        },
        {
          "label": "数据",
          "value": "3"
        },
        {
          "label": "NFT",
          "value": "4"
        },
        {
          "label": "项目",
          "value": "5"
        }
      ]
    }
  },
  "path": "/lives/:category?",
  "view": 5
}
```
