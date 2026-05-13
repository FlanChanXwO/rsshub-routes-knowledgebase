# 本地宝 - 焦点资讯

## Coverage
`index-only`

## Route
- Namespace: `bendibao`
- Namespace Name: `本地宝`
- Route Path: `/news/:city`
- Route Name: `焦点资讯`
- Example: `/bendibao/news/bj`
- URL: `bendibao.com/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/bendibao/news.ts')`

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
  "description": "| 城市名 | 缩写 |\n| ------ | ---- |\n| 北京   | bj   |\n| 上海   | sh   |\n| 广州   | gz   |\n| 深圳   | sz   |\n\n  更多城市请参见 [这里](http://www.bendibao.com/city.htm)\n\n  > **香港特别行政区** 和 **澳门特别行政区** 的本地宝城市页面不更新资讯。",
  "example": "/bendibao/news/bj",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/bendibao/news.ts')",
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
  "url": "bendibao.com/"
}
```
