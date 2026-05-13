# 人人影视 - 今日播出

## Coverage
`index-only`

## Route
- Namespace: `yyets`
- Namespace Name: `人人影视`
- Route Path: `/today`
- Route Name: `今日播出`
- Example: `/yyets/today`
- URL: `yysub.net/tv/schedule`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `bao1991213`
- Source Location: `today.ts`
- Source Module: `() => import('@/routes/yyets/today.ts')`

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
  - `yysub.net/tv/schedule`
  - `yysub.net/`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/yyets/today",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "today.ts",
  "maintainers": [
    "bao1991213"
  ],
  "module": "() => import('@/routes/yyets/today.ts')",
  "name": "今日播出",
  "parameters": {},
  "path": "/today",
  "radar": [
    {
      "source": [
        "yysub.net/tv/schedule",
        "yysub.net/"
      ]
    }
  ],
  "url": "yysub.net/tv/schedule",
  "view": 5
}
```
