# 本地宝 - 焦点资讯

## Coverage
`index-only`

## Route
- Namespace: `bendibao`
- Namespace Name: `本地宝`
- Route Path: `/bendibao/news/:city`
- Route Name: `焦点资讯`
- Example: `/bendibao/news/bj`
- URL: `bendibao.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 城市名 | 缩写 |
| ------ | ---- |
| 北京   | bj   |
| 上海   | sh   |
| 广州   | gz   |
| 深圳   | sz   |

更多城市请参见 [这里](http://www.bendibao.com/city.htm)

> **香港特别行政区** 和 **澳门特别行政区** 的本地宝城市页面不更新资讯。

## Parameters
- `city`: 城市缩写，可在该城市页面的 URL 中找到


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
  - `bendibao.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 城市名 | 缩写 |\n| ------ | ---- |\n| 北京   | bj   |\n| 上海   | sh   |\n| 广州   | gz   |\n| 深圳   | sz   |\n\n更多城市请参见 [这里](http://www.bendibao.com/city.htm)\n\n> **香港特别行政区** 和 **澳门特别行政区** 的本地宝城市页面不更新资讯。",
  "example": "/bendibao/news/bj",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 378,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "焦点资讯",
  "parameters": {
    "city": "城市缩写，可在该城市页面的 URL 中找到"
  },
  "path": "/news/:city",
  "radar": [
    {
      "source": [
        "bendibao.com/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "上海本地宝焦点资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71225179855962112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://sh.bendibao.com/",
      "title": "上海本地宝焦点资讯",
      "type": "feed",
      "url": "rsshub://bendibao/news/sh"
    },
    {
      "description": "深圳本地宝焦点资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55050469790023681",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://sz.bendibao.com/",
      "title": "深圳本地宝焦点资讯",
      "type": "feed",
      "url": "rsshub://bendibao/news/sz"
    }
  ],
  "url": "bendibao.com/"
}
```
