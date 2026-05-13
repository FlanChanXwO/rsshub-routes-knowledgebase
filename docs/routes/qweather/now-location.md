# 和风天气 - 实时天气

## Coverage
`index-only`

## Route
- Namespace: `qweather`
- Namespace Name: `和风天气`
- Route Path: `/now/:location`
- Route Name: `实时天气`
- Example: `/qweather/now/广州`
- URL: `qweather.com`
- Language: `zh-CN`
- Categories: `forecast`
- Maintainers: `Rein-Ou`
- Source Location: `now.ts`
- Source Module: `() => import('@/routes/qweather/now.ts')`

## Description
_None_

## Parameters
- `location`: N


## Features
- `requireConfig`: [{"description": "访问 `https://www.qweather.com/` 注册开发 API Key。", "name": "HEFENG_KEY"}, {"description": "This is required after 2026/01/01: https://blog.qweather.com/announce/public-api-domain-change-to-api-host/", "name": "HEFENG_API_HOST"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/qweather/now/广州",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "访问 `https://www.qweather.com/` 注册开发 API Key。",
        "name": "HEFENG_KEY"
      },
      {
        "description": "This is required after 2026/01/01: https://blog.qweather.com/announce/public-api-domain-change-to-api-host/",
        "name": "HEFENG_API_HOST"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "now.ts",
  "maintainers": [
    "Rein-Ou"
  ],
  "module": "() => import('@/routes/qweather/now.ts')",
  "name": "实时天气",
  "parameters": {
    "location": "N"
  },
  "path": "/now/:location"
}
```
