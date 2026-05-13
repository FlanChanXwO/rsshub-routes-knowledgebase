# HKEPC - HKEPC 电脑领域

## Coverage
`index-only`

## Route
- Namespace: `hkepc`
- Namespace Name: `HKEPC`
- Route Path: `/:category?`
- Route Name: `HKEPC 电脑领域`
- Example: `/hkepc/news`
- URL: `hkepc.com/`
- Language: `zh-HK`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/hkepc/index.ts')`

## Description
| 专题报导   | 新闻中心 | 新品快递 | 超频领域 | 流动数码 | 生活娱乐      | 会员消息 | 脑场新闻 | 业界资讯 | 最新消息 |
| ---------- | -------- | -------- | -------- | -------- | ------------- | -------- | -------- | -------- | -------- |
| coverStory | news     | review   | ocLab    | digital  | entertainment | member   | price    | press    | latest   |

## Parameters
- `category`: 分类，见下表，默认为最新消息


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
  - `hkepc.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 专题报导   | 新闻中心 | 新品快递 | 超频领域 | 流动数码 | 生活娱乐      | 会员消息 | 脑场新闻 | 业界资讯 | 最新消息 |\n| ---------- | -------- | -------- | -------- | -------- | ------------- | -------- | -------- | -------- | -------- |\n| coverStory | news     | review   | ocLab    | digital  | entertainment | member   | price    | press    | latest   |",
  "example": "/hkepc/news",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/hkepc/index.ts')",
  "name": "HKEPC 电脑领域",
  "parameters": {
    "category": "分类，见下表，默认为最新消息"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "hkepc.com/"
      ],
      "target": ""
    }
  ],
  "url": "hkepc.com/"
}
```
