# 中国海洋大学 - 后勤公告通知

## Coverage
`index-only`

## Route
- Namespace: `ouc`
- Namespace Name: `中国海洋大学`
- Route Path: `/hqsz`
- Route Name: `后勤公告通知`
- Example: `/ouc/hqsz`
- URL: `hqsz.ouc.edu.cn/news.html?typeId=02`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `ladeng07`
- Source Location: `hqsz.ts`
- Source Module: `() => import('@/routes/ouc/hqsz.ts')`

## Description
_None_

## Parameters
_None_


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
  - `hqsz.ouc.edu.cn/news.html`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/ouc/hqsz",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "hqsz.ts",
  "maintainers": [
    "ladeng07"
  ],
  "module": "() => import('@/routes/ouc/hqsz.ts')",
  "name": "后勤公告通知",
  "parameters": {},
  "path": "/hqsz",
  "radar": [
    {
      "source": [
        "hqsz.ouc.edu.cn/news.html"
      ]
    }
  ],
  "url": "hqsz.ouc.edu.cn/news.html?typeId=02"
}
```
