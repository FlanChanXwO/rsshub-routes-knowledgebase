# 西南交通大学 - 体育学院

## Coverage
`index-only`

## Route
- Namespace: `swjtu`
- Namespace Name: `西南交通大学`
- Route Path: `/sports`
- Route Name: `体育学院`
- Example: `/swjtu/sports`
- URL: `www.swjtu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `AzureG03`
- Source Location: `sports.ts`
- Source Module: `() => import('@/routes/swjtu/sports.ts')`

## Description
新闻资讯

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
  - `sports.swjtu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "新闻资讯",
  "example": "/swjtu/sports",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "sports.ts",
  "maintainers": [
    "AzureG03"
  ],
  "module": "() => import('@/routes/swjtu/sports.ts')",
  "name": "体育学院",
  "parameters": {},
  "path": "/sports",
  "radar": [
    {
      "source": [
        "sports.swjtu.edu.cn/"
      ]
    }
  ]
}
```
