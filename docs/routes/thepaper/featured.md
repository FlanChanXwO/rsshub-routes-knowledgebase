# 澎湃新闻 - 首页头条

## Coverage
`index-only`

## Route
- Namespace: `thepaper`
- Namespace Name: `澎湃新闻`
- Route Path: `/featured`
- Route Name: `首页头条`
- Example: `/thepaper/featured`
- URL: `thepaper.cn/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `HenryQW, nczitzk, bigfei`
- Source Location: `featured.ts`
- Source Module: `() => import('@/routes/thepaper/featured.ts')`

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
  - `thepaper.cn/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/thepaper/featured",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "featured.ts",
  "maintainers": [
    "HenryQW",
    "nczitzk",
    "bigfei"
  ],
  "module": "() => import('@/routes/thepaper/featured.ts')",
  "name": "首页头条",
  "parameters": {},
  "path": "/featured",
  "radar": [
    {
      "source": [
        "thepaper.cn/"
      ]
    }
  ],
  "url": "thepaper.cn/"
}
```
