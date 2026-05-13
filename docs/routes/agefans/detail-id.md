# AGE 动漫 - 番剧详情

## Coverage
`index-only`

## Route
- Namespace: `agefans`
- Namespace Name: `AGE 动漫`
- Route Path: `/detail/:id`
- Route Name: `番剧详情`
- Example: `/agefans/detail/20200035`
- URL: `agemys.cc`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `s2marine`
- Source Location: `detail.ts`
- Source Module: `() => import('@/routes/agefans/detail.ts')`

## Description
_None_

## Parameters
- `id`: 番剧 id，对应详情 URL 中找到


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
  - `agemys.org/detail/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/agefans/detail/20200035",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "detail.ts",
  "maintainers": [
    "s2marine"
  ],
  "module": "() => import('@/routes/agefans/detail.ts')",
  "name": "番剧详情",
  "parameters": {
    "id": "番剧 id，对应详情 URL 中找到"
  },
  "path": "/detail/:id",
  "radar": [
    {
      "source": [
        "agemys.org/detail/:id"
      ]
    }
  ]
}
```
