# Hacking8 - 搜索

## Coverage
`index-only`

## Route
- Namespace: `hacking8`
- Namespace Name: `Hacking8`
- Route Path: `/search/:keyword?`
- Route Name: `搜索`
- Example: `/hacking8/search/rsshub`
- URL: `hacking8.com`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/hacking8/search.ts')`

## Description
_None_

## Parameters
- `keyword`: 关键字，默认为空


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
  - `hacking8.com/index/:category`
  - `hacking8.com/`
- `target`: `/:category?`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/hacking8/search/rsshub",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/hacking8/search.ts')",
  "name": "搜索",
  "parameters": {
    "keyword": "关键字，默认为空"
  },
  "path": "/search/:keyword?",
  "radar": [
    {
      "source": [
        "hacking8.com/index/:category",
        "hacking8.com/"
      ],
      "target": "/:category?"
    }
  ]
}
```
