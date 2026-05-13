# 深圳证券交易所 - 上市公告 - 可转换债券

## Coverage
`index-only`

## Route
- Namespace: `szse`
- Namespace Name: `深圳证券交易所`
- Route Path: `/notice`
- Route Name: `上市公告 - 可转换债券`
- Example: `/szse/notice`
- URL: `szse.cn/disclosure/notice/company/index.html`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `Jeason0228, nczitzk`
- Source Location: `notice.ts`
- Source Module: `() => import('@/routes/szse/notice.ts')`

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
  - `szse.cn/disclosure/notice/company/index.html`
  - `szse.cn/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/szse/notice",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "notice.ts",
  "maintainers": [
    "Jeason0228",
    "nczitzk"
  ],
  "module": "() => import('@/routes/szse/notice.ts')",
  "name": "上市公告 - 可转换债券",
  "parameters": {},
  "path": "/notice",
  "radar": [
    {
      "source": [
        "szse.cn/disclosure/notice/company/index.html",
        "szse.cn/"
      ]
    }
  ],
  "url": "szse.cn/disclosure/notice/company/index.html"
}
```
