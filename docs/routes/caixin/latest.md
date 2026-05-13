# 财新博客 - 最新文章

## Coverage
`index-only`

## Route
- Namespace: `caixin`
- Namespace Name: `财新博客`
- Route Path: `/latest`
- Route Name: `最新文章`
- Example: `/caixin/latest`
- URL: `caixin.com/`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `tpnonthealps`
- Source Location: `latest.ts`
- Source Module: `() => import('@/routes/caixin/latest.ts')`

## Description
说明：此 RSS feed 会自动抓取财新网的最新文章，但不包含 FM 及视频内容。订阅用户可根据文档设置环境变量后，在url传入`fulltext=`以解锁全文。

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
  - `caixin.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "说明：此 RSS feed 会自动抓取财新网的最新文章，但不包含 FM 及视频内容。订阅用户可根据文档设置环境变量后，在url传入`fulltext=`以解锁全文。",
  "example": "/caixin/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "latest.ts",
  "maintainers": [
    "tpnonthealps"
  ],
  "module": "() => import('@/routes/caixin/latest.ts')",
  "name": "最新文章",
  "parameters": {},
  "path": "/latest",
  "radar": [
    {
      "source": [
        "caixin.com/"
      ]
    }
  ],
  "url": "caixin.com/",
  "view": 0
}
```
