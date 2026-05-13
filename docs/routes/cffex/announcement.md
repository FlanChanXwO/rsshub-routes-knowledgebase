# 中国金融期货交易所 - 交易所公告

## Coverage
`index-only`

## Route
- Namespace: `cffex`
- Namespace Name: `中国金融期货交易所`
- Route Path: `/announcement`
- Route Name: `交易所公告`
- Example: `/cffex/announcement`
- URL: `www.cffex.com.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `ChenXiangcheng1`
- Source Location: `announcement.ts`
- Source Module: `() => import('@/routes/cffex/announcement.ts')`

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
  - `cffex.com.cn`
- `target`: `/announcement`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "",
  "example": "/cffex/announcement",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "announcement.ts",
  "maintainers": [
    "ChenXiangcheng1"
  ],
  "module": "() => import('@/routes/cffex/announcement.ts')",
  "name": "交易所公告",
  "parameters": {},
  "path": "/announcement",
  "radar": [
    {
      "source": [
        "cffex.com.cn"
      ],
      "target": "/announcement"
    }
  ],
  "url": "www.cffex.com.cn"
}
```
