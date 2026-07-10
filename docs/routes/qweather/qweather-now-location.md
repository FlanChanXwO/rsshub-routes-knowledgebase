# 和风天气 - 实时天气

## Coverage
`index-only`

## Route
- Namespace: `qweather`
- Namespace Name: `和风天气`
- Route Path: `/qweather/now/:location`
- Route Name: `实时天气`
- Example: `/qweather/now/广州`
- URL: `qweather.com`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `Rein-Ou`
- Source Location: `now.ts`
- Source Module: `_None_`

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
  "heat": 1,
  "location": "now.ts",
  "maintainers": [
    "Rein-Ou"
  ],
  "name": "实时天气",
  "parameters": {
    "location": "N"
  },
  "path": "/now/:location",
  "topFeeds": [
    {
      "description": "上海实时天气状况 - Powered by RSSHub",
      "errorAt": "2025-05-21T15:40:54.802Z",
      "errorMessage": "QWeather RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/zh/install/config#%E5%92%8C%E9%A3%8E%E5%A4%A9%E6%B0%94\">relevant config</a>\n",
      "id": "83880495163907072",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.qweather.com/weather/shanghai-101020100.html",
      "title": "上海实时天气",
      "type": "feed",
      "url": "rsshub://qweather/now/%E4%B8%8A%E6%B5%B7"
    }
  ]
}
```
