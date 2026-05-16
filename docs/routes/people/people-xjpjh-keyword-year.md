# 人民网 - 习近平系列重要讲话

## Coverage
`index-only`

## Route
- Namespace: `people`
- Namespace Name: `人民网`
- Route Path: `/people/xjpjh/:keyword?/:year?`
- Route Name: `习近平系列重要讲话`
- Example: `/people/xjpjh`
- URL: `people.com.cn/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `None`
- Source Location: `xjpjh.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 关键词，默认不填
- `year`: 年份，默认 all


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
  - `people.com.cn/`
- `target`: `/:site?/:category?`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/people/xjpjh",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 17,
  "location": "xjpjh.ts",
  "maintainers": [],
  "name": "习近平系列重要讲话",
  "parameters": {
    "keyword": "关键词，默认不填",
    "year": "年份，默认 all"
  },
  "path": "/xjpjh/:keyword?/:year?",
  "radar": [
    {
      "source": [
        "people.com.cn/"
      ],
      "target": "/:site?/:category?"
    }
  ],
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-06-23T10:14:49.196Z",
      "errorMessage": "[GET] \"http://jhsjk.people.cn/undefined\": 404 Not Found\n[GET] \"http://jhsjk.people.cn/undefined\": 404 Not Found\n",
      "id": "159914682433828881",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://people/xjpjh"
    }
  ],
  "url": "people.com.cn/"
}
```
