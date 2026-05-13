# 中央气象台 - 全国气象预警

## Coverage
`index-only`

## Route
- Namespace: `nmc`
- Namespace Name: `中央气象台`
- Route Path: `/weatheralarm/:province?`
- Route Name: `全国气象预警`
- Example: `/nmc/weatheralarm/广东省`
- URL: `nmc.cn/publish/alarm.html`
- Language: `zh-CN`
- Categories: `forecast`
- Maintainers: `ylc395`
- Source Location: `weatheralarm.ts`
- Source Module: `() => import('@/routes/nmc/weatheralarm.ts')`

## Description
_None_

## Parameters
- `province`: 省份


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
  - `nmc.cn/publish/alarm.html`
  - `nmc.cn/`
- `target`: `/weatheralarm`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/nmc/weatheralarm/广东省",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "weatheralarm.ts",
  "maintainers": [
    "ylc395"
  ],
  "module": "() => import('@/routes/nmc/weatheralarm.ts')",
  "name": "全国气象预警",
  "parameters": {
    "province": "省份"
  },
  "path": "/weatheralarm/:province?",
  "radar": [
    {
      "source": [
        "nmc.cn/publish/alarm.html",
        "nmc.cn/"
      ],
      "target": "/weatheralarm"
    }
  ],
  "url": "nmc.cn/publish/alarm.html"
}
```
