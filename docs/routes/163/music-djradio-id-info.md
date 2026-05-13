# 网易公开课 - 电台节目

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/music/djradio/:id/:info?`
- Route Name: `电台节目`
- Example: `/163/music/djradio/347317067`
- URL: `163.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `magic-akari`
- Source Location: `music/djradio.tsx`
- Source Module: `() => import('@/routes/163/music/djradio.tsx')`

## Description
_None_

## Parameters
- `id`: 节目 id, 可在电台节目页 URL 中找到
- `info`: 默认在正文尾部显示节目相关信息，任意值为不显示


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/163/music/djradio/347317067",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "location": "music/djradio.tsx",
  "maintainers": [
    "magic-akari"
  ],
  "module": "() => import('@/routes/163/music/djradio.tsx')",
  "name": "电台节目",
  "parameters": {
    "id": "节目 id, 可在电台节目页 URL 中找到",
    "info": "默认在正文尾部显示节目相关信息，任意值为不显示"
  },
  "path": "/music/djradio/:id/:info?"
}
```
