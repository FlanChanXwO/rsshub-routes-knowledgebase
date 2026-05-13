# 深潮 TechFlow - 精选

## Coverage
`index-only`

## Route
- Namespace: `techflowpost`
- Namespace Name: `深潮 TechFlow`
- Route Path: `/techflowpost/featured/:category?`
- Route Name: `精选`
- Example: `/techflowpost/featured`
- URL: `techflowpost.com/zh-CN/article`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `zhenlohuang`
- Source Location: `featured.ts`
- Source Module: `_None_`

## Description
| 全部 | 行业 & 项目观察 | 项目简介 | 项目动态 | 赛道解读 | 播客笔记 | 交易观察 | VC 洞察 | 实用教程 | 人物故事 & 访谈 | 法律 & 监管动态 | 活动动态 | 交易所动态 |
| ---- | --------------- | -------- | -------- | -------- | -------- | -------- | ------- | -------- | --------------- | --------------- | -------- | ---------- |
|      | 2040            | 2046     | 2047     | 2045     | 2044     | 2043     | 2042    | 2041     | 2039            | 2033            | 2032     | 2031       |

## Parameters
- `category`: 分类，见下表，默认为全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `techflowpost.com/zh-CN/article`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 全部 | 行业 & 项目观察 | 项目简介 | 项目动态 | 赛道解读 | 播客笔记 | 交易观察 | VC 洞察 | 实用教程 | 人物故事 & 访谈 | 法律 & 监管动态 | 活动动态 | 交易所动态 |\n| ---- | --------------- | -------- | -------- | -------- | -------- | -------- | ------- | -------- | --------------- | --------------- | -------- | ---------- |\n|      | 2040            | 2046     | 2047     | 2045     | 2044     | 2043     | 2042    | 2041     | 2039            | 2033            | 2032     | 2031       |",
  "example": "/techflowpost/featured",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "featured.ts",
  "maintainers": [
    "zhenlohuang"
  ],
  "name": "精选",
  "parameters": {
    "category": "分类，见下表，默认为全部"
  },
  "path": "/featured/:category?",
  "radar": [
    {
      "source": [
        "techflowpost.com/zh-CN/article"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "techflowpost.com/zh-CN/article",
  "view": 0
}
```
