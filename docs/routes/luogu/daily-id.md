# 洛谷 - 日报

## Coverage
`index-only`

## Route
- Namespace: `luogu`
- Namespace Name: `洛谷`
- Route Path: `/daily/:id?`
- Route Name: `日报`
- Example: `/luogu/daily`
- URL: `luogu.com.cn/discuss/47327`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `LogicJake, prnake, nczitzk`
- Source Location: `daily.ts`
- Source Module: `() => import('@/routes/luogu/daily.ts')`

## Description
_None_

## Parameters
- `id`: 年度日报所在帖子 id，可在 URL 中找到，不填默认为 `47327`


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
  - `luogu.com.cn/discuss/47327`
  - `luogu.com.cn/`
- `target`: `/daily`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/luogu/daily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "daily.ts",
  "maintainers": [
    "LogicJake",
    "prnake",
    "nczitzk"
  ],
  "module": "() => import('@/routes/luogu/daily.ts')",
  "name": "日报",
  "parameters": {
    "id": "年度日报所在帖子 id，可在 URL 中找到，不填默认为 `47327`"
  },
  "path": "/daily/:id?",
  "radar": [
    {
      "source": [
        "luogu.com.cn/discuss/47327",
        "luogu.com.cn/"
      ],
      "target": "/daily"
    }
  ],
  "url": "luogu.com.cn/discuss/47327"
}
```
