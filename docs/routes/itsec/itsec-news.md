# 中国信息安全测评中心 - 新闻发布

## Coverage
`index-only`

## Route
- Namespace: `itsec`
- Namespace Name: `中国信息安全测评中心`
- Route Path: `/itsec/news`
- Route Name: `新闻发布`
- Example: `/itsec/news`
- URL: `www.itsec.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `ch3n4y`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `www.itsec.gov.cn/zxxw/index.html`
  - `www.itsec.gov.cn/zxxw/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/itsec/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "ch3n4y"
  ],
  "name": "新闻发布",
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.itsec.gov.cn/zxxw/index.html",
        "www.itsec.gov.cn/zxxw/"
      ],
      "target": "/news"
    }
  ],
  "topFeeds": []
}
```
