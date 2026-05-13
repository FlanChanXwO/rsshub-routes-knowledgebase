# 新华社 - 新华社新闻

## Coverage
`index-only`

## Route
- Namespace: `news`
- Namespace Name: `新华社`
- Route Path: `/whxw`
- Route Name: `新华社新闻`
- Example: `/news/xhsxw`
- URL: `news.cn/xhsxw.htm`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `xhsxw.ts`
- Source Module: `() => import('@/routes/news/xhsxw.ts')`

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
  - `news.cn/xhsxw.htm`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/news/xhsxw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "xhsxw.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/news/xhsxw.ts')",
  "name": "新华社新闻",
  "parameters": {},
  "path": [
    "/xhsxw",
    "/whxw"
  ],
  "radar": [
    {
      "source": [
        "news.cn/xhsxw.htm"
      ]
    }
  ],
  "url": "news.cn/xhsxw.htm"
}
```
