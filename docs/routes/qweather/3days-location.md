# 和风天气 - 近三天天气

## Coverage
`index-only`

## Route
- Namespace: `qweather`
- Namespace Name: `和风天气`
- Route Path: `/3days/:location`
- Route Name: `近三天天气`
- Example: `/qweather/3days/广州`
- URL: `qweather.com`
- Language: `zh-CN`
- Categories: `forecast`
- Maintainers: `Rein-Ou, la3rence`
- Source Location: `3days.ts`
- Source Module: `() => import('@/routes/qweather/3days.ts')`

## Description
获取订阅近三天天气预报

## Parameters
- `location`: N


## Features
- `requireConfig`: [{"description": "QWeather API KEY", "name": "HEFENG_KEY"}, {"description": "This is required after 2026/01/01: https://blog.qweather.com/announce/public-api-domain-change-to-api-host/", "name": "HEFENG_API_HOST"}]
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
  "description": "获取订阅近三天天气预报",
  "example": "/qweather/3days/广州",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "QWeather API KEY",
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
  "location": "3days.ts",
  "maintainers": [
    "Rein-Ou",
    "la3rence"
  ],
  "module": "() => import('@/routes/qweather/3days.ts')",
  "name": "近三天天气",
  "parameters": {
    "location": "N"
  },
  "path": "/3days/:location"
}
```
