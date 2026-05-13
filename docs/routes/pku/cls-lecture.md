# 北京大学 - 生命科学学院近期讲座

## Coverage
`index-only`

## Route
- Namespace: `pku`
- Namespace Name: `北京大学`
- Route Path: `/cls/lecture`
- Route Name: `生命科学学院近期讲座`
- Example: `/pku/cls/lecture`
- URL: `bio.pku.edu.cn/homes/Index/news_jz/7/7.html`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `TPOB`
- Source Location: `cls/lecture.ts`
- Source Module: `() => import('@/routes/pku/cls/lecture.ts')`

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
  - `bio.pku.edu.cn/homes/Index/news_jz/7/7.html`
  - `bio.pku.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/pku/cls/lecture",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cls/lecture.ts",
  "maintainers": [
    "TPOB"
  ],
  "module": "() => import('@/routes/pku/cls/lecture.ts')",
  "name": "生命科学学院近期讲座",
  "parameters": {},
  "path": "/cls/lecture",
  "radar": [
    {
      "source": [
        "bio.pku.edu.cn/homes/Index/news_jz/7/7.html",
        "bio.pku.edu.cn/"
      ]
    }
  ],
  "url": "bio.pku.edu.cn/homes/Index/news_jz/7/7.html"
}
```
