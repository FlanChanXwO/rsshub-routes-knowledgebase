# National Cheng Kung University - CSIE News

## Coverage
`index-only`

## Route
- Namespace: `ncku`
- Namespace Name: `National Cheng Kung University`
- Route Path: `/csie/:catagory?`
- Route Name: `CSIE News`
- Example: `/ncku/csie/normal`
- URL: `www.ncku.edu.tw`
- Language: `zh-TW`
- Categories: `university`
- Maintainers: `simbafs`
- Source Location: `csie.ts`
- Source Module: `() => import('@/routes/ncku/csie.ts')`

## Description
Availible catagories：_all, normal, bachelorAdmission, masterAdmission, speeches, awards, scholarship, jobs

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
  - `www.csie.ncku.edu.tw/zh-hant/news/`
- `target`: `/csie/_all`
### Rule 2
- `source`:
  - `www.csie.ncku.edu.tw/zh-hant/news/:catagory`
- `target`: `/csie/:catagory`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "Availible catagories：_all, normal, bachelorAdmission, masterAdmission, speeches, awards, scholarship, jobs",
  "example": "/ncku/csie/normal",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "csie.ts",
  "maintainers": [
    "simbafs"
  ],
  "module": "() => import('@/routes/ncku/csie.ts')",
  "name": "CSIE News",
  "path": "/csie/:catagory?",
  "radar": [
    {
      "source": [
        "www.csie.ncku.edu.tw/zh-hant/news/"
      ],
      "target": "/csie/_all"
    },
    {
      "source": [
        "www.csie.ncku.edu.tw/zh-hant/news/:catagory"
      ],
      "target": "/csie/:catagory"
    }
  ],
  "zh-TW": {
    "description": "可用分類：_all, normal, bachelorAdmission, masterAdmission, speeches, awards, scholarship, jobs",
    "name": "國立成功大學資訊系公告"
  }
}
```
