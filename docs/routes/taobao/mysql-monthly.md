# 淘宝网 - 数据库内核月报

## Coverage
`index-only`

## Route
- Namespace: `taobao`
- Namespace Name: `淘宝网`
- Route Path: `/mysql/monthly`
- Route Name: `数据库内核月报`
- Example: `/taobao/mysql/monthly`
- URL: `mysql.taobao.org`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `mysql.ts`
- Source Module: `() => import('@/routes/taobao/mysql.ts')`

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
  - `mysql.taobao.org/monthly/`
- `target`: `/mysql/monthly`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/taobao/mysql/monthly",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "mysql.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/taobao/mysql.ts')",
  "name": "数据库内核月报",
  "path": "/mysql/monthly",
  "radar": [
    {
      "source": [
        "mysql.taobao.org/monthly/"
      ],
      "target": "/mysql/monthly"
    }
  ],
  "url": "mysql.taobao.org",
  "view": 0
}
```
