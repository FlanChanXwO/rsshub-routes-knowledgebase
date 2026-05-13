# 国家能源局 - 分类

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/gov/nrta/news/:category?`
- Route Name: `分类`
- Example: `/gov/nrta/news`
- URL: `www.nea.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `yuxinliu-alex`
- Source Location: `nrta/news.ts`
- Source Module: `_None_`

## Description
| 总局要闻 | 公告公示 | 工作动态 | 其他 |
| -------- | -------- | -------- | ---- |
| 112      | 113      | 114      |      |

## Parameters
- `category`: 资讯类别，可从地址中获取，默认为总局要闻


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
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
  "description": "| 总局要闻 | 公告公示 | 工作动态 | 其他 |\n| -------- | -------- | -------- | ---- |\n| 112      | 113      | 114      |      |",
  "example": "/gov/nrta/news",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "nrta/news.ts",
  "maintainers": [
    "yuxinliu-alex"
  ],
  "name": "分类",
  "parameters": {
    "category": "资讯类别，可从地址中获取，默认为总局要闻"
  },
  "path": "/nrta/news/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "国家广播电视总局 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "198372079645781011",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.nrta.gov.cn/col/col112/index.html",
      "title": "总局要闻",
      "type": "feed",
      "url": "rsshub://gov/nrta/news"
    }
  ]
}
```
