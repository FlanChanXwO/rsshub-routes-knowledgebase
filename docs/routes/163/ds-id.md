# 网易公开课 - 用户发帖

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/ds/:id`
- Route Name: `用户发帖`
- Example: `/163/ds/63dfbaf4117741daaf73404601165843`
- URL: `163.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `luyuhuang`
- Source Location: `ds.tsx`
- Source Module: `() => import('@/routes/163/ds.tsx')`

## Description
_None_

## Parameters
- `id`: 用户ID


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
  - `ds.163.com/user/:id`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/163/ds/63dfbaf4117741daaf73404601165843",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "ds.tsx",
  "maintainers": [
    "luyuhuang"
  ],
  "module": "() => import('@/routes/163/ds.tsx')",
  "name": "用户发帖",
  "parameters": {
    "id": "用户ID"
  },
  "path": "/ds/:id",
  "radar": [
    {
      "source": [
        "ds.163.com/user/:id"
      ]
    }
  ]
}
```
