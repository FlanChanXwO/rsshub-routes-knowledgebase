# 虎嗅 - 搜索

## Coverage
`index-only`

## Route
- Namespace: `huxiu`
- Namespace Name: `虎嗅`
- Route Path: `/search/:keyword`
- Route Name: `搜索`
- Example: `/huxiu/search/生活`
- URL: `huxiu.com/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `xyqfer, HenryQW, nczitzk`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/huxiu/search.ts')`

## Description
_None_

## Parameters
- `keyword`: 关键字


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `huxiu.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/huxiu/search/生活",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "location": "search.ts",
  "maintainers": [
    "xyqfer",
    "HenryQW",
    "nczitzk"
  ],
  "module": "() => import('@/routes/huxiu/search.ts')",
  "name": "搜索",
  "parameters": {
    "keyword": "关键字"
  },
  "path": "/search/:keyword",
  "radar": [
    {
      "source": [
        "huxiu.com/"
      ]
    }
  ],
  "url": "huxiu.com/"
}
```
