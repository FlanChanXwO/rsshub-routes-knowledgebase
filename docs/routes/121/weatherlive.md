# 深圳台风网 - 深圳天气直播

## Coverage
`index-only`

## Route
- Namespace: `121`
- Namespace Name: `深圳台风网`
- Route Path: `/weatherLive`
- Route Name: `深圳天气直播`
- Example: `/121/weatherLive`
- URL: `tf.121.com.cn`
- Language: `zh-CN`
- Categories: `forecast`
- Maintainers: `nczitzk`
- Source Location: `weather-live.tsx`
- Source Module: `() => import('@/routes/121/weather-live.tsx')`

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
  - `tf.121.com.cn`
  - `tf.121.com.cn/web/weatherLive`
- `target`: `/weatherLive`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/121/weatherLive",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "weather-live.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/121/weather-live.tsx')",
  "name": "深圳天气直播",
  "path": "/weatherLive",
  "radar": [
    {
      "source": [
        "tf.121.com.cn",
        "tf.121.com.cn/web/weatherLive"
      ],
      "target": "/weatherLive"
    }
  ],
  "url": "tf.121.com.cn",
  "view": 5
}
```
