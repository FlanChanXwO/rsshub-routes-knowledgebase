# 中国国际航空公司 - 服务公告

## Coverage
`index-only`

## Route
- Namespace: `airchina`
- Namespace Name: `中国国际航空公司`
- Route Path: `/announcement`
- Route Name: `服务公告`
- Example: `/airchina/announcement`
- URL: `www.airchina.com.cn/`
- Language: `zh-CN`
- Categories: `travel`
- Maintainers: `LandonLi`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/airchina/index.ts')`

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
  - `www.airchina.com.cn/`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/airchina/announcement",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "LandonLi"
  ],
  "module": "() => import('@/routes/airchina/index.ts')",
  "name": "服务公告",
  "parameters": {},
  "path": "/announcement",
  "radar": [
    {
      "source": [
        "www.airchina.com.cn/"
      ]
    }
  ],
  "url": "www.airchina.com.cn/"
}
```
