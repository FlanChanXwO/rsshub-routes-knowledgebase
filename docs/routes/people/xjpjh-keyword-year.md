# 人民网 - 习近平系列重要讲话

## Coverage
`index-only`

## Route
- Namespace: `people`
- Namespace Name: `人民网`
- Route Path: `/xjpjh/:keyword?/:year?`
- Route Name: `习近平系列重要讲话`
- Example: `/people/xjpjh`
- URL: `people.com.cn/`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `None`
- Source Location: `xjpjh.ts`
- Source Module: `() => import('@/routes/people/xjpjh.ts')`

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
  "location": "xjpjh.ts",
  "maintainers": [],
  "module": "() => import('@/routes/people/xjpjh.ts')",
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
  "url": "people.com.cn/"
}
```
