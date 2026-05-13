# 鸟哥笔记 - 今日事

## Coverage
`index-only`

## Route
- Namespace: `niaogebiji`
- Namespace Name: `鸟哥笔记`
- Route Path: `/today`
- Route Name: `今日事`
- Example: `/niaogebiji/today`
- URL: `niaogebiji.com/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `KotoriK`
- Source Location: `today.ts`
- Source Module: `() => import('@/routes/niaogebiji/today.ts')`

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
  - `niaogebiji.com/`
  - `niaogebiji.com/bulletin`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/niaogebiji/today",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "today.ts",
  "maintainers": [
    "KotoriK"
  ],
  "module": "() => import('@/routes/niaogebiji/today.ts')",
  "name": "今日事",
  "parameters": {},
  "path": "/today",
  "radar": [
    {
      "source": [
        "niaogebiji.com/",
        "niaogebiji.com/bulletin"
      ],
      "target": ""
    }
  ],
  "url": "niaogebiji.com/"
}
```
