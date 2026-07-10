# 和风天气 - 近三天天气

## Coverage
`index-only`

## Route
- Namespace: `qweather`
- Namespace Name: `和风天气`
- Route Path: `/qweather/3days/:location`
- Route Name: `近三天天气`
- Example: `/qweather/3days/广州`
- URL: `qweather.com`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `Rein-Ou, la3rence`
- Source Location: `3days.ts`
- Source Module: `_None_`

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
  "heat": 1,
  "location": "3days.ts",
  "maintainers": [
    "Rein-Ou",
    "la3rence"
  ],
  "name": "近三天天气",
  "parameters": {
    "location": "N"
  },
  "path": "/3days/:location",
  "topFeeds": [
    {
      "description": "上海未来三天天气情况，使用和风彩云 API (包括空气质量) - Powered by RSSHub",
      "errorAt": "2025-05-21T15:30:27.514Z",
      "errorMessage": "QWeather RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/zh/install/config#%E5%92%8C%E9%A3%8E%E5%A4%A9%E6%B0%94\">relevant config</a>\n",
      "id": "83880188817711104",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.qweather.com/weather/shanghai-101020100.html",
      "title": "上海未来三天天气",
      "type": "feed",
      "url": "rsshub://qweather/3days/%E4%B8%8A%E6%B5%B7"
    }
  ]
}
```
