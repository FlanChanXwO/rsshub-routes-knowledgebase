# Shaanxi Normal University - 学校官网 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `snnu`
- Namespace Name: `Shaanxi Normal University`
- Route Path: `/`
- Route Name: `学校官网 - 通知公告`
- Example: `/snnu`
- URL: `www.snnu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `alterkeyy`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/snnu/index.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.snnu.edu.cn/tzgg.htm`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/snnu",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "alterkeyy"
  ],
  "module": "() => import('@/routes/snnu/index.ts')",
  "name": "学校官网 - 通知公告",
  "path": "/",
  "radar": [
    {
      "source": [
        "www.snnu.edu.cn/tzgg.htm"
      ],
      "target": "/"
    }
  ],
  "url": "www.snnu.edu.cn"
}
```
