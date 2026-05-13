# 北京大学 - 生命科学学院通知公告

## Coverage
`index-only`

## Route
- Namespace: `pku`
- Namespace Name: `北京大学`
- Route Path: `/cls/announcement`
- Route Name: `生命科学学院通知公告`
- Example: `/pku/cls/announcement`
- URL: `bio.pku.edu.cn/homes/Index/news/21/21.html`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `william-swl`
- Source Location: `cls/announcement.ts`
- Source Module: `() => import('@/routes/pku/cls/announcement.ts')`

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
  - `bio.pku.edu.cn/homes/Index/news/21/21.html`
  - `bio.pku.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/pku/cls/announcement",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cls/announcement.ts",
  "maintainers": [
    "william-swl"
  ],
  "module": "() => import('@/routes/pku/cls/announcement.ts')",
  "name": "生命科学学院通知公告",
  "parameters": {},
  "path": "/cls/announcement",
  "radar": [
    {
      "source": [
        "bio.pku.edu.cn/homes/Index/news/21/21.html",
        "bio.pku.edu.cn/"
      ]
    }
  ],
  "url": "bio.pku.edu.cn/homes/Index/news/21/21.html"
}
```
