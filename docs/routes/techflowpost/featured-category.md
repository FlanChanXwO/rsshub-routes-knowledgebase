# 深潮 TechFlow - 精选

## Coverage
`index-only`

## Route
- Namespace: `techflowpost`
- Namespace Name: `深潮 TechFlow`
- Route Path: `/featured/:category?`
- Route Name: `精选`
- Example: `/techflowpost/featured`
- URL: `techflowpost.com/article/index.html`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `zhenlohuang`
- Source Location: `featured.ts`
- Source Module: `() => import('@/routes/techflowpost/featured.ts')`

## Description
| 全部 | 行业 & 项目观察 | 项目简介 | 项目动态 | 赛道解读 | 播客笔记 | 交易观察 | VC洞察 | 实用教程 | 人物故事 & 访谈 | 法律 & 监管动态 | 活动动态 | 交易所动态 |
  | ---- | --------------- | -------- | -------- | -------- | -------- | -------- | ------ | -------- | --------------- | --------------- | -------- | ---------- |
  |      | 2040            | 2046     | 2047     | 2045     | 2044     | 2043     | 2042   | 2041     | 2039            | 2033            | 2032     | 2031       |

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
  - `techflowpost.com/article/index.html`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 全部 | 行业 & 项目观察 | 项目简介 | 项目动态 | 赛道解读 | 播客笔记 | 交易观察 | VC洞察 | 实用教程 | 人物故事 & 访谈 | 法律 & 监管动态 | 活动动态 | 交易所动态 |\n  | ---- | --------------- | -------- | -------- | -------- | -------- | -------- | ------ | -------- | --------------- | --------------- | -------- | ---------- |\n  |      | 2040            | 2046     | 2047     | 2045     | 2044     | 2043     | 2042   | 2041     | 2039            | 2033            | 2032     | 2031       |",
  "example": "/techflowpost/featured",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "featured.ts",
  "maintainers": [
    "zhenlohuang"
  ],
  "module": "() => import('@/routes/techflowpost/featured.ts')",
  "name": "精选",
  "parameters": {
    "category": "分类，见下表，默认为全部"
  },
  "path": "/featured/:category?",
  "radar": [
    {
      "source": [
        "techflowpost.com/article/index.html"
      ]
    }
  ],
  "url": "techflowpost.com/article/index.html",
  "view": 0
}
```
