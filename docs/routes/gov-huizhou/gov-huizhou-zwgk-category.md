# 惠州市人民政府 - 政务公开

## Coverage
`index-only`

## Route
- Namespace: `gov/huizhou`
- Namespace Name: `惠州市人民政府`
- Route Path: `/gov/huizhou/zwgk/:category?`
- Route Name: `政务公开`
- Example: `/gov/huizhou/zwgk/jgdt`
- URL: `www.huizhou.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `Fatpandac`
- Source Location: `zwgk/index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: 资讯类别，可以从网址中得到，默认为政务要闻


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `政务公开 - 政务要闻`
- `source`:
  - `www.huizhou.gov.cn/zwgk/hzsz/zwyw`
- `target`: `/zwgk/zwyw`
### Rule 2
- `title`: `政务公开 - 机关动态`
- `source`:
  - `www.huizhou.gov.cn/zwgk/hzsz/jgdt`
- `target`: `/zwgk/jgdt`
### Rule 3
- `title`: `政务公开 - 县区要闻`
- `source`:
  - `www.huizhou.gov.cn/zwgk/hzsz/xqyw`
- `target`: `/zwgk/xqyw`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/huizhou/zwgk/jgdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "zwgk/index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "政务公开",
  "parameters": {
    "category": "资讯类别，可以从网址中得到，默认为政务要闻"
  },
  "path": "/zwgk/:category?",
  "radar": [
    {
      "source": [
        "www.huizhou.gov.cn/zwgk/hzsz/zwyw"
      ],
      "target": "/zwgk/zwyw",
      "title": "政务公开 - 政务要闻"
    },
    {
      "source": [
        "www.huizhou.gov.cn/zwgk/hzsz/jgdt"
      ],
      "target": "/zwgk/jgdt",
      "title": "政务公开 - 机关动态"
    },
    {
      "source": [
        "www.huizhou.gov.cn/zwgk/hzsz/xqyw"
      ],
      "target": "/zwgk/xqyw",
      "title": "政务公开 - 县区要闻"
    }
  ],
  "topFeeds": []
}
```
