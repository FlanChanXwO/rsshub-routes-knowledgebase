# NT动漫 - 番剧详情

## Coverage
`index-only`

## Route
- Namespace: `ntdm`
- Namespace Name: `NT动漫`
- Route Path: `/video/:id`
- Route Name: `番剧详情`
- Example: `/ntdm/video/4309`
- URL: `www.ntdm9.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `Yamico`
- Source Location: `video.ts`
- Source Module: `() => import('@/routes/ntdm/video.ts')`

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
  - `ntdm9.com/video/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/ntdm/video/4309",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "video.ts",
  "maintainers": [
    "Yamico"
  ],
  "module": "() => import('@/routes/ntdm/video.ts')",
  "name": "番剧详情",
  "parameters": {
    "id": "番剧 id，对应详情 URL 中找到"
  },
  "path": "/video/:id",
  "radar": [
    {
      "source": [
        "ntdm9.com/video/:id"
      ]
    }
  ]
}
```
