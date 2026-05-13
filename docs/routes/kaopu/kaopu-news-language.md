# 靠谱新闻 - 全部

## Coverage
`index-only`

## Route
- Namespace: `kaopu`
- Namespace Name: `靠谱新闻`
- Route Path: `/kaopu/news/:language?`
- Route Name: `全部`
- Example: `/kaopu/news/zh-hans`
- URL: `kaopu.news`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `fashioncj`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 简体中文 | 繁体中文 |
| -------- | -------- |
| zh-hans  | zh-hant  |

## Parameters
- `language`: 语言


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `kaopu.news/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 简体中文 | 繁体中文 |\n| -------- | -------- |\n| zh-hans  | zh-hant  |",
  "example": "/kaopu/news/zh-hans",
  "heat": 41,
  "location": "news.ts",
  "maintainers": [
    "fashioncj"
  ],
  "name": "全部",
  "parameters": {
    "language": "语言"
  },
  "path": "/news/:language?",
  "radar": [
    {
      "source": [
        "kaopu.news/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "靠谱新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70765921687286784",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://kaopu.news/index.html",
      "title": "靠谱新闻",
      "type": "feed",
      "url": "rsshub://kaopu/news"
    },
    {
      "description": "靠谱新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60732733478199296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://kaopu.news/index.html",
      "title": "靠谱新闻",
      "type": "feed",
      "url": "rsshub://kaopu/news/zh-hans"
    }
  ]
}
```
