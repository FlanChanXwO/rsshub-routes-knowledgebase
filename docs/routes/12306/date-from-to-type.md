# 12306 - 售票信息

## Coverage
`index-only`

## Route
- Namespace: `12306`
- Namespace Name: `12306`
- Route Path: `/:date/:from/:to/:type?`
- Route Name: `售票信息`
- Example: `/12306/2022-02-19/重庆/永川东`
- URL: `kyfw.12306.cn`
- Language: `zh-CN`
- Categories: `travel`
- Maintainers: `Fatpandac`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/12306/index.tsx')`

## Description
_None_

## Parameters
- `date`: 时间，格式为（YYYY-MM-DD）
- `from`: 始发站
- `to`: 终点站
- `type`: 售票类型，成人和学生可选，默认为成人


## Features
- `requireConfig`: false
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
    "travel"
  ],
  "example": "/12306/2022-02-19/重庆/永川东",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/12306/index.tsx')",
  "name": "售票信息",
  "parameters": {
    "date": "时间，格式为（YYYY-MM-DD）",
    "from": "始发站",
    "to": "终点站",
    "type": "售票类型，成人和学生可选，默认为成人"
  },
  "path": "/:date/:from/:to/:type?"
}
```
