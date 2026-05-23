# 創新拿鐵 - 分类

## Coverage
`index-only`

## Route
- Namespace: `startuplatte`
- Namespace Name: `創新拿鐵`
- Route Path: `/startuplatte/:category?`
- Route Name: `分类`
- Example: `/startuplatte`
- URL: `startuplatte.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 首頁 | 大師智慧 | 深度分析 | 新知介紹 |
| ---- | -------- | -------- | -------- |
|      | quote    | analysis | trend    |

## Parameters
- `category`: 分类，见下表，默认为首頁


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
  - `startuplatte.com/category/:category`
  - `startuplatte.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 首頁 | 大師智慧 | 深度分析 | 新知介紹 |\n| ---- | -------- | -------- | -------- |\n|      | quote    | analysis | trend    |",
  "example": "/startuplatte",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 56,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为首頁"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "startuplatte.com/category/:category",
        "startuplatte.com/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "創新拿鐵 - Powered by RSSHub",
      "errorAt": "2026-02-21T11:08:57.570Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "61252688943239172",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://startuplatte.com/",
      "title": "創新拿鐵",
      "type": "feed",
      "url": "rsshub://startuplatte"
    },
    {
      "description": "深度分析 | 創新拿鐵 - Powered by RSSHub",
      "errorAt": "2026-02-21T05:43:39.672Z",
      "errorMessage": "[GET] \"https://startuplatte.com/category/analysis\": 403 Forbidden\n",
      "id": "81622260116168704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://startuplatte.com/category/analysis",
      "title": "深度分析 | 創新拿鐵",
      "type": "feed",
      "url": "rsshub://startuplatte/analysis"
    }
  ]
}
```
